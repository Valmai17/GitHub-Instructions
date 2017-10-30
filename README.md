## git 常用命令
- 进入github平台，点击new repositories ，新建一个新项目（你也可以加入到一个已有的项目）
- 输入项目名，选择遵从开源协议

### 安装完git后，设置用户名与邮箱
- 设置邮箱
```html
   $ git config --global user.email "Your email"
```
- 设置用户名
```html
   $ git config --global user.name "Your Name"
```

### 上传或修改项目
- 右键启动Git Bash命令行，输入git  clone  接着将先前记录下来的地址复制到后面，回车
```html
   $ git  clone https://github.com/Valmai17/InspectForm.git
```
- 输入 git add .    （注意有个“ . ”）将改动的地方添加到版本管理器
```html
   $ git add .
```
- 输入 git  commit -m "changes log"  提交到本地的版本控制库里，引号里面是你对本次提交的说明信息。
```html
   $ git  commit -m "changes log"
```
- 最后输入 git push -u origin master  将你本地的仓库提交到你的github账号里，此时会要求你输入你的github的账号和密码。
```html
   $ git push -u origin master
```

- 最后输入 git push -u origin master  将你本地的仓库提交到你的github账号里，此时会要求你输入你的github的账号和密码。
```html
   $ git push -u origin master
```

### 把仓库代码同步到本地（更新代码到本地）
- 最后输入 git push -u origin master  将你本地的仓库提交到你的github账号里，此时会要求你输入你的github的账号和密码。
```html
   $ git pull
```
- 或者更新分支
```html
   $ git pull origin "分支名"
```

[百度教程链接](https://jingyan.baidu.com/article/f7ff0bfc7181492e27bb1360.html)
