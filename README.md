# eleme-single-seller
之前基于vue1.0开发的一个饿了么单个商家页面

***
快速预览

npm install || cnpm install    
npm run dev || cnmp run dev

在浏览器地址栏中打开 localhost:8080 （为了达到更好的体验效果，建议使用chrome浏览器）

目录介绍<br>

     .    
     ├── build    
     ├── config    
     ├── src                      // 生产目录   
     │   ├── common               // 公用方法样式
     │   │   ├── fonts            // icon字体图标
     │   │   ├── js           
     │   │   │   ├── date.js      // 格式化时间戳
     │   │   │   ├── store.js     // localstorage存取用户信息
     │   │   │   ├── utils.js     // 截取url中data   
     │   │   ├── stylus    
     │   ├── components           // 各种组件
     │   │   ├── cartcontrol      // 控制购买数量
     │   │   ├── food             // 单个商品详情
     │   │   ├── goods            // 首页商品列表
     │   │   ├── header           // 头部信息
     │   │   ├── ratings          // 评价页
     │   │   ├── ratingselect     // 评价详情列表
     │   │   ├── seller           // 商家信息
     │   │   ├── shopcart         // 底部购物车
     │   │   ├── split            // 模块之间分割线
     │   │   ├── star             // 星星可数
     │   └── App.vue              // 根组件
     │   └── main.js              // Webpack 预编译入口      
     ├── static                   // 存放静态文件
     │   ├── css
     │   │   ├── reset.css        // 清楚默认样式
     ├── .babelrc
     ├── .editorconfig
     ├── .eslintignore
     ├── .eslintrc.js
     ├── .gitignore
     ├── data.json                // 开发中用到的静态数据文件
     ├── index.html               // 项目入口文件
     ├── package.json             // 项目依赖
     ├── README.md


技术栈   
  webpack 1.0    
  vue 1.0    
  vue-router    
  vue-resource    
  [better-scroll](https://github.com/ustbhuangyi/better-scroll)  实现页面中的滚动效果   

