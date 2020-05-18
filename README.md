Github

### 创建远程仓库

### 创建本地仓库

`git init`

`git add .`

`git commit -m "first commit"`

`git remote add origin https://github.com/kanonair/gitdemo.git`

`git push origin master`

### 创建 dev 分支并切换分支

`git checkout -b dev`

`git push origin dev`

### 克隆

`git clone https://github.com/kanonair/gitdemo.git`

### 查看分支

`git branch`

### 克隆后创建分支

`git checkout -b dev origin/dev`

### 得到后面新增的远程分支

`git pull`

`git checkout -b dev origin/dev`
