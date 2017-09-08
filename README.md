## 一、前言
vue-cli-easy 是在 vue-cli 的基础上，添加了 vue-router、vuex、ElementUI依赖。同样的也对异步请求进行了封装处理，大大简化的请求的代码量（使用github 上 elm 项目对于接口 api 请求的代码思路）。

## 二、使用步骤
```
1、clone 仓库到本地。
2、npm install 安装依赖。
3、npm run dev 启动项目。
4、npm run build 压缩打包。
```

## 三、打包上线
当你项目完成后，你想要打包部署到服务器上时，你只需要在 npm run build 之前，对 config 文件夹中的 index.js 进行简单的修改: assetsPublicPath: './', productionSourceMap: false。然后进行打包，目录中会生成一个 dist 的文件夹。只需要将 dist 文件夹扔到服务器中就可以了。

# vue-cli-easy
this is a vue development environment。
