# Webpack+TypeScript Demo

集成了`ts-loader`的webpack

## 目录结构

```
├── src
│   ├── index.html 入口模板，使用html-webpack-plugin
│   └── index.ts ts入口文件
├── tsconfig.json ts设置
└── webpack.config.js webpack配置
```

## dev

使用`webpack-dev-server`，有热更新。

```sh
npm run dev
```

启动后，访问 [http://localhost:9000/](http://localhost:9000/)

## build

```sh
npm run build
```