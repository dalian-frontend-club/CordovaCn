翻译自cordova官方文档（如果需要链接，请自行对照原文链接进行查看）： <br>
https://cordova.apache.org/#getstarted<br>

### 1. 安装Cordova
Cordova是通过运行在Nodejs的NPM工具安装的,通过后面的添加平台相关内容安装对应的平台依赖.
打开命令行窗口输入命令:
```sh
$ npm install -g cordova
```

### 2 创建Cordova工程
通过Cordova的命令行工具创建一个Cordova空工程,进入到你希望的工程文件夹根目录输入如下命令:
```sh
$ cordova create MyApp
```
获取更多帮助信息可以输入 [cordova help create] 指令<br>

### 3 添加平台(指创建对应的手机环境)
在创建完Cordova项目以后,进入到项目根目录,在此通过下面的指令添加你需要生成对应的app的平台.
输入 [cordova platform add <platform name>]添加对应的app平台,而后通过[cordova run <platform name>]运行你的app.
```sh
$ cd MyApp

$ cordova platform add browser // 在后面Command cli章节会详细介绍常用指令的使用
```
