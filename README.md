# umi-subapp-template

> umi 子应用工程模板，基于 umi 3

本仓库是脚手架 [umi-subapp-cli](https://github.com/blueju/umi-subapp-cli) 的工程模板仓库。

搭建步骤：
1. 使用 yarn create @umijs/umi-app 创建工程
2. 添加 umi 插件 [@umijs/plugin-qiankun](https://umijs.org/zh-CN/plugins/plugin-qiankun) 及其 [相关配置](https://umijs.org/zh-CN/plugins/plugin-qiankun#第一步：插件注册（configjs）)
3. 修改 package.json 的 name 属性，添加工程名，后续仍需视情况修改，必须与主应用注册配置中的应用名 name 保持一致
