### 安装 `npm`
`npm` 全称为 `Node Package Manager`，是一个基于`Node.js`的包管理器，也是整个`Node.js`社区最流行、支持的第三方模块最多的包管理器。
```
npm -v
```

### 由于网络原因 安装 `cnpm`
```
npm install -g cnpm --registry=https://registry.npm.taobao.org
```

###安装完成，如下图
C:\Users\User>npm install -g cnpm --registry=https://registry.npm.taobao.org
npm WARN deprecated request@2.88.2: request has been deprecated, see https://github.com/request/request/issues/3142
npm WARN deprecated har-validator@5.1.5: this
D:\Program\cnpm -> D:\Program\node_modules\cnpm\bin\cnpm
+ cnpm@6.1.1
updated 1 package in 15.553s

其中D:\Program为cnpm安装路径,将应路径添加系统环境变量path中即可


### 安装 `vue-cli`
```
cnpm install -g @vue/cli
```

### 安装 `webpack`
`webpack` 是  `JavaScript` 打包器(module bundler)
```
cnpm install -g webpack
```

