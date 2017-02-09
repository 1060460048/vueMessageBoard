##这是复制别人的一个项目源项目的地址是：https://github.com/chenkie/vue-events-bulletin
之所以复制出来，是因为，如果是新手可能运行的时候可能遇到跟我类似的一些问题，所以把它单独提出来给予相应的说明，让你更容易在本地的把项目跑起来！

项目是需要有服务器环境来支行的，这就是你为什么后来要使用node server.js才能把项目跑起来的原因.

除了让vue.js项目有服务器运行环境，还要让bootstrap，vue,vue-resource可以正常的使用npm进行安装，安装成功相应的bootstrap样式文件，相应的vue运行时依赖的js文件才可以找到.

所使用的命令是：npm install vue vue-resource bootstrap

node是项目可以跑起来依赖的核心，它安装的时候建议下载.exe文件，然后复制到某个目录下面（针对windows用户）然后加到环境变量里面；

安装的时候node_modules目录中的内容npm成功安装之后，它的包管理工具的作用使相应的package都安装到node_modules内，这样写项目时候引入js,css文件时路径好定义，如果是全局安装，在c盘用户盘符下不好引入，所以建议在项目目录下使用npm进行包安装及管理；

##下面这是原来的安装说明
## Vue Events Bulletin Board

This is the code for the Vue.js [tutorial on Scotch.io](https://scotch.io/tutorials/build-a-single-page-time-tracking-app-with-vue-js-introduction). In the tutorial we build a events bulletin board application and cover the basics of [Vue](http://vuejs.org/).

## Installation

1. Run `npm install`.
2. Run `node server.js`.
3. Visit [http://localhost:8080](http://localhost:8080).

## RESTful API (contributed by Jason Lam)

1. **Use Node.js & Express for backend server and router.**
2. **RESTful requests towards the server to simulate CRUD on *events* model, instead of local hardcoded ones.**
3. Translated into Traditional Chinese.

## RESTful API written in Go 

If you would like to use a backend written in Go, [thewhitetulip](http://github.com/thewhitetulip) has written on. See [the source code](https://github.com/thewhitetulip/go-vue-events).
 
