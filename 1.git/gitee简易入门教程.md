gitee

#### 简易的命令行入门教程:

Git 全局设置:

```
git config --global user.name "androidwhm"
git config --global user.email "1746699469@qq.com"
```

创建 git 仓库:

```
mkdir my-study
cd my-study
git init 
touch README.md
git add README.md
git commit -m "first commit"
git remote add origin git@gitee.com:androidwhm/my-study.git
git push -u origin "master"
```

已有仓库?

```
cd existing_git_repo
git remote add origin git@gitee.com:androidwhm/my-study.git
git push -u origin "master"
```