# 安装

## 直接下载 / CDN

https://unpkg.com/vue-tinder/dist/vue-tinder.js

Unpkg.com 提供了基于 NPM 的 CDN 链接。上面的链接会一直指向在 NPM 发布的最新版本。你也可以像 https://unpkg.com/vue-tinder@1.0.0/dist/vue-tinder.js 这样指定 版本号 或者 Tag。

在 Vue 后面加载 vue-tinder，它会自动安装的：

```html
<script src="/path/to/vue.js"></script>
<script src="/path/to/vue-tinder.js"></script>
```

## NPM / Yarn

```shell
npm install vue-tinder --save
# or
yarn add vue-tinder
```

## 构建开发版

如果你想使用最新的开发版，就得从 GitHub 上直接 clone，然后自己 build 一个 vue-tinder。

```shell
git clone https://github.com/shanlh/vue-tinder.git node_modules/vue-tinder
cd node_modules/vue-tinder
npm install
npm run build
```
