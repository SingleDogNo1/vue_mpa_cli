# mpa-demo

> vue多入口文件脚手架
### 集成axios/vue-router/vuex/jquery并且使用jquery时无需引用。
### 集成babel/sass
### 项目结构
```
├─build
├─config
├─src
│  ├─modules  存放所有网页公用组件
│  └─pages  存放每张网页，首页默认index
│      ├─index  首页
│      │  ├─assets  存放专属于首页的资源
│      │  │  ├─css  首页样式文件(css/scss/sass)
│      │  │  ├─font 首页字体文件
│      │  │  ├─images 首页图片
│      │  │  ├─js 首页js文件
│      │  │  └─media  首页媒体文件
│      │  ├─components  首页组件
│      │  ├─router  首页路由文件
│      │  ├─App.vue  首页vue
│      │  ├─index.html  首页html
│      │  └─index.js  首页入口js
│      └─test **注意**
│          ├─assets  存放专属于test的资源
│          │  ├─css  test样式文件(css/scss/sass)
│          │  ├─font test字体文件
│          │  ├─images test图片
│          │  ├─js testjs文件
│          │  └─media  test媒体文件
│          ├─components  test组件
│          ├─router  test路由文件
│          ├─App.vue  testvue
│          ├─test.html  testhtml **<font>注意</font>**
│          └─test.js  test入口js **注意**
├─static
│  ├─css  所有网页公用字体文件
│  ├─font
│  ├─images
│  ├─js
│  └─media
└─test
```
### 注意
每张网页的结构可以copy首页，上面创建了一个test文件，结构可以完全copy首页，调试时打开[这里](http://localhost:8080/test.html)。注意：上面标示注意的位置命名必须相同。
