## 98.css

一套兼顾情怀&还原度&可爱的经典UI复刻方案

<img alt="window" src="https://cdn.jsdelivr.net/gh/meorionel/98-pink.css@0.0.2/docs/window.png" height="133">

### 这是什么

这是98.css的分支版本<strong style="color: purple">✨ 98-pink.css ✨</strong>

在原来的基础上将色调修改为粉红色和蓝色。

### 如何开始

通过cdn导入!

```bash
https://cdn.jsdelivr.net/gh/meorionel/98-pink.css/dist/98-pink.css
```

### 开发

首先你需要进行`npm install`.

`style.css`这是你需要关注的地方.

原文作者让我们使用`npm start`去启动一个开发环境, 但是我试了一下, 浏览器会报错.

所以我自己琢磨了一下, 我们可以运行`node server.js`启动开发环境, 该环境将监视文件更改并重建 98.css, 在此过程中重新加载浏览器.

当你做完一切之后可以运行`node build.js`或者`npm run build`打包css文件, css会生成在`dist`目录下.

### Issues, Contributing, etc.

Refer to [the GitHub issues page](https://github.com/jdan/98.css/issues) to see bugs in my CSS or report new ones. I'd really like to see your pull requests (especially those new to open-source!) and will happily provide code review. 98.css is a fun, silly project and I'd like to make it a fun place to build your open-source muscle.

Thank you for checking my little project out, I hope it brought you some joy today. Consider [starring/following along on GitHub](https://github.com/jdan/98.css/stargazers) and maybe subscribing to more fun things on [my twitter](https://twitter.com/jdan). 👋

### Publishing

Building the docs site: `npm run deploy:docs`

Publishing to npm: `npm run release`

### License

[MIT](https://github.com/jdan/98.css/blob/main/LICENSE)