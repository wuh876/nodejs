# nodejs
## 一、sublime text3 安装 node 插件

选择菜单：preferences/Package Control，或快捷键ctrl+shift+p，调出package control。
输入install Package，按回车等待，再输入nodejs。单击nodejs选项，编辑器左下角会有安装进度显示。

注意：
1、在sublime text中，install Package控制安装插件，remove Package控制删除插件。
2、如果提示的插件里面没有nodejs，说明装过了，可通过preferences/Package Settings查看已安装的插件。

## 二、配置
```
选择菜单：preferences/Browse Packages...，进入插件所在的文件夹。

打开Nodejs/Nodejs.sublime-build
修改encoding

"encoding": "utf8"

打开Nodejs/Nodejs.sublime-settings，修改（红色部分为修改后的内容）

"node_command": "D:\\Program Files\\nodejs\\node.exe", 
"npm_command": "D:\\Program Files\\nodejs\\npm.cmd",
```

