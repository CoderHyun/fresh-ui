## 简介

[Fresh-ui] (基于 [Vue3.0](https://github.com/vuejs/vue-next)、[Vite](https://github.com/vitejs/vite)、[TypeScript](https://www.typescriptlang.org/)
的UI框架，它使用了最新的前端技术栈。

## 使用

- 获取项目代码

```bash
git clone https://github.com/CoderHyun/fresh-ui.git
```

- 安装依赖

```bash
cd fresh-ui

npm install

# 建议不要直接使用 cnpm 安装依赖，会有各种诡异的 bug。可以通过如下操作解决 npm 下载速度慢的问题
npm install --registry=https://registry.npm.taobao.org
```

- 运行

```bash
npm run dev
```

- 打包

```bash
npm run build
```

## 浏览器支持

本地开发推荐使用`Chrome 80+` 浏览器

支持现代浏览器, 不支持 IE


## 发布

```bash
# 构建生产环境
npm run build:prod
```

