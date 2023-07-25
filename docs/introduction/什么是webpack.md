# 什么是webpack

这里引用下官网的定义和标志性的一张图

> 本质上，webpack 是一个用于现代 JavaScript 应用程序的 静态模块打包工具。当 webpack 处理应用程序时，它会在内部从一个或多个入口点构建一个依赖图(dependency graph)，然后将你项目中所需的每一个模块组合成一个或多个 bundles，它们均为静态资源，用于展示你的内容。- webpack官网

![image-20230725171410612](https://raw.githubusercontent.com/nalantianyi/my-pics-base/master/202307251714805.png)

我们知道，浏览器本身能够运行的资源本质上无外乎是html，css，js，还有些图片、音频和视频文件等，那么在最近十年前端技术栈爆炸式发展的历史中，不光是React，Vue，Angular等框架技术体系下,css预编译器等等，诞生了很多新的“资源”，.jsx，.vue，.ts，.tsx,.less,.sass等等，那么这些资源如何能够运行在浏览器中，于是乎我们的主角webpack登场了。

这张图的寓意好比一个发生立方体多维机器，任何东西经历webpack的洗礼，发生畸变，输出统一的标准资源。[有一个东西能够把扔进去的东西都变成钱就好了 🐶]

## 历史

当然在webpack出现之前，也有很多工具在一定程度上扮演了webpack的部分角色，grunt，gulp等，但是还是有不少本质的区别

这里简单介绍下gulp的场景

### gulp



