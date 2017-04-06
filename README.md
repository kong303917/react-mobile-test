# react-mobile-test

react-mobile-test是一个全新的基于webpack2、react15、react-router4、antd-mobile的前端架构实现方案例子（h5）

# 项目依赖

* webpack^2.3.2
* antd-mobile^1.0.7
* react^15.4.2
* react-router-dom^4.0.0


# 运行

```
npm install --registry https://registry.npm.taobao.org info underscore 
npm run start
```

# 编译

```
npm run build
```

编译后的文件会生成到`output`目录下，直接将这个目录下的文件部署到服务器上即可。



# 目录结构

```
.
├── src
│   ├── app
│   │   ├── index.jsx
│   │   └── list.jsx
│   ├── home
│   │   ├── index.jsx
│   │   └── list.jsx
│   ├── home.jsx
│   ├── app.jsx
│   └── template.ejs
├── output
│   ├── css
│   ├── image
│   └── js
├── .babelrc
├── package.json
└── webpack.config.js
```

