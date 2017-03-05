---
layout:     post
title:      "The development of my first ReactJs App"
subtitle:   " \"Dev tool: debug ES6 in chrome\""
date:       2017-03-03
author:     "Xin"
header-img: "img/post-bg-js-module.jpg"
tags:
    - ReactJs
    - Dev Tool
    - Code or Die
---

### ReactJs Debug

- [ ] TODO： 不能直接 Debug 的原因.

开发软件的重要步骤就是Debug， 使用高效的Debug工具能达到事半功倍的效果。

ES6 的代码无法直接在 chrome 中 Debug， 为了解决这个问题，提高我们的开发效率。

- 安装chrome插件：　**React Developer Tools**

- 在代码构建的时候， 在 webpack config 加上 `devtool: 'source-map'`

然后就能愉快的在 chrome 中 Debug 了。

-- Xin 2017年03月03日23:27:10
