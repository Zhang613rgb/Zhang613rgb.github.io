## Hello 
同学们大家好!

该blog用于分享学习资料, 只需要做几步, 就能创建一个静态blog网站.

1. 大家可以将Typora编写的markdown文件拷贝到blog文件夹中,
2. 将自己的图片拷贝进imgs并修改正确路径。类似 `![我是图片](./imgs/xxxxx.png)`
   - 需要保证markdown中的图片地址引入路径正确。
3. 在_navbar.md 或者 _sidebar.md 中配置正确的md文件路径.
    ```md
    <!-- _navbar.md -->
    * good good study
    * [Home](/)
    * [1.01-web-api](blog/01-webApis.md)
    * [2.项目开发流程](blog/项目开发流程.md)
    * [3.怎么提高](blog/怎么提高.md)
    <!-- * [TypeScript]() -->
    <!-- * [Webpack]() -->
    <!-- * [Node]() -->
    <!-- * [LeetCode]() -->
    ```
4. 安装docsify, `npm i docsify-cli -g`
5. 终端中,进入docs目录, 执行 `docsify serve`, 启动本地服务器
6. enjoy!

<!-- ## see see
看看学学官方怎么配置文件的.
https://github.com/docsifyjs/docsify/tree/develop/docs

## docsify

> 一个神奇的文档网站生成器。

## 概述

docsify 可以快速帮你生成文档网站。不同于 GitBook、Hexo 的地方是它不会生成静态的 `.html` 文件，所有转换工作都是在运行时。如果你想要开始使用它，只需要创建一个 `index.html` 就可以开始编写文档并直接部署在 GitHub Pages。 -->


