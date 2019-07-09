# Git

## 官网地址:

## 下载地址:

## 命令

### 设置签名

- `git config user.name maobo`

- `git config user.email 2464899506@qq.com`
  设置姓名和邮箱,以后提交代码的备注签名

### 远程克隆项目

- `git clone https://github.com/WustMao/help.git ./help`

  第一参数为git地址,第二个参数为放置目录.克隆完成后会获取git项目

### 查看git状态

- `git status`

### 修改文件后提交代码

- `git commit -m "提交代码" README.md`
  提交代码,指定文件

### 提交到远程

- `git push origin master`
  提交代码到远程