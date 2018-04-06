# 快应用
这个项目是学习快应用的笔记。
1、创建项目：
hap init <ProjectName>
2、安装依赖
在项目目录下，执行
npm install
3、编译项目
进入项目目录下，执行这个命令：
npm run build
如果报下面的错误：
报错：Error: Cannot find module 'F:\spaceforkuaiapp\QuickApp\node_modules\hap-tools\webpack.config.js'

在项目目录下，执行hap update --force ，再执行npm run build

4、自动编译项目：希望每次修改源代码文件后，都自动编译项目
npm run watch

5、扫码安装
启动HTTP服务器
npm run server
6、手机下载调试器app
https://statres.quickapp.cn/quickapp/quickapp/201803/file/quickapp_debugger.apk
7、打开调试器，扫码安装