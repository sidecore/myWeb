# vuehtml

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
项目文件描述

├── README.md  项目说明文档
├── node_modules  项目依赖包
├── build  编译配置文件，可忽略
│   ├── build.js
│   ├── check-versions.js
│   ├── dev-client.js
│   ├── dev-server.js
│   ├── utils.js
│   ├── vue-loader.conf.js
│   ├── webpack.base.conf.js 
│   ├── webpack.dev.conf.js
│   └── webpack.prod.conf.js
├── config  项目基本设置文件夹
│   ├── dev.env.js  开发配置文件
│   ├── index.js  配置主文件
│   └── prod.env.js  编译配置文件
├── index.html   项目入口文件
├── package-lock.json   npm5 新增文件，优化性能
├── package.json   项目依赖包配置文件
├── src   项目文件【开发】
│   ├── App.vue   APP入口文件
│   ├── assets   初始项目资源目录
│   │   └── logo.png
│   ├── components  公共组件目录
│   │   └── HelloWorld.vue    测试组件
│   ├── main.js   主配置文件
│   └── router  路由配置文件夹
│      └── index.js  路由配置文件
└── static   静态资源目录
