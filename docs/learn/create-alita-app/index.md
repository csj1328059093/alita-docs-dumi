---
nav:
  title: 学习
  order: 3
toc: menu
order: 1
firstPost: true
nextText: '环境配置及基础详解'
nextUrl: '/learn/create-alita-app/setup'
---

# 创建 alita 应用程序

要从头开始使用 React 构建一个完整的移动端 Web 应用程序(H5)，需要考虑许多重要的细节:

- 必须使用打包程序（例如 webpack）打包代码，并使用 Babel 等编译器进行代码转换。
- 你需要针对生产环境进行优化，例如代码拆分。
- 考虑页面在不同设备上的适配情况。
- 多个项目公用的全局的布局和组件。
- 在什么时机请求数据才是合适合理的。

## alita: 一个基于 umi 的 React 框架

赶紧试试 **alita** 框架吧。alita 为上述所有问题提供了解决方案。但更重要的是，它能确保你和你的团队轻松的构建一个混合的应用程序。

alita 面向场景化的设计思路，以插件化、零配置的方式构建。使得你在使用时能有较好的开发体验和享受许多内置的功能。列举其中一些如下:

- 文件即路由，约定式的项目文件结构，自动将 pages 目录下的文件映射成路由配置。（并支持动态路由）
- 自动代码拆分，提升页面加载速度，在某些场景提供自动生成骨架屏的功能
- 内置 Less 支持，内置 antd 和 antd-mobile 组件库。
- 开发环境支持热更新，开发时你无需频繁的重启你的开发服务，只要你修改项目代码，alita 会自动重新渲染页面。
- 友好地移动端 app 开发模式，你可以在真机上预览你的开发效果，并使用 web 的日志系统来快速定位问题。
- 专注与某些真实的应用场景
- 可拔插的插件设计，你可以完全的自定义你自己的 alita

## 关于本教程

这个免费的课程将指导你完成 alita 入门的学习。我们将会通过手动新建项目的方式，来一步一步引导你完成学习。其中会涉及到部分前端工程化的一些简单概念，如果你已经掌握了，那你可以选择性的跳过部分的内容。

在本教程中，你将通过创建一个非常简单的**移动端应用程序**来学习 alita 基础。这是最终结果的示例:

**[alita-init-demo](https://alitajs.com/demos/alita-init-demo/index.html#/)** ([源码](https://github.com/alitajs/next-alita-app))

让我们开始吧!

> 本教程假定你具有 JavaScript 和 React 的基础知识。如果你从未编写过 React 代码，则应首先阅读[官方的 React 教程](https://reactjs.org/tutorial/tutorial.html)。
