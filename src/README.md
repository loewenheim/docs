# 简介

## 什么是 Yew ？

**Yew** 是一个设计先进的 [Rust](https://www.rust-lang.org/) 框架，目的是使用 [WebAssembly](https://webassembly.org/) 来创建多线程的前端web应用。

* **基于组件的框架**，可以轻松的创建交互式UI。拥有 [React](https://reactjs.org/) 或 [Elm](https://elm-lang.org/) 等框架经验的开发人员在使用Yew时会感到得心应手。
* **高性能** ，前端开发者可以轻易的将工作分流至后端来减少 DOM API 的调用，从而达到异常出色的性能。
* **支持与Javascript交互** ，允许开发者使用NPM包，并与现有的Javascript应用程序结合。

### 加入我们 😊

* 你可以在这里 [GitHub issues page](https://github.com/yewstack/yew/issues) 报告Bugs 或者是提出新的想法。
* 我们欢迎 pull requests 。 如果你想要帮助我们，先参考下 [good first issues](https://github.com/yewstack/yew/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+issue%22) 吧！
* 我们的 [Gitter chatroom](https://gitter.im/yewframework/Lobby) 非常的热闹，也是一个问问题和解决问题的好地方！

![&#x6211;&#x4EEC;&#x7684;&#x793E;&#x533A;&#x6B63;&#x5728;&#x8301;&#x58EE;&#x6210;&#x957F;&#xFF01;](https://img.shields.io/github/stars/yewstack/yew?color=009A5B&label=Github%20stars)

### 准备好开始了吗？

点击下面的链接，来学习并编写你的第一个 Yew 前端App ， 并通过丰富的社区示例项目来学习。

{% page-ref page="getting-started/getting-started.md" %}

### **还没有完全信服？**

Yew 项目基于划时代的新技术，非常适合那些希望开发未来基础项目的开发者。接下来是一些我们相信Yew这样的框架将为成为未来Web开发的主流。

#### **等等，为什么选用 WebAssembly?**

WebAssembly _\(Wasm\)_ 是一种可移植的底层语言，并且可以由Rust编译而来。它在浏览器中可以以原生速度运行，还同时支持和JavaScript交互。这些在所有的主流浏览器中都已经提供。希望了解更多关于 WebAssembly 是如何为前端应用提速的，可以查看官方说明 [Use Cases](https://webassembly.org/docs/use-cases/).

值得注意的是，Wasm **（目前还）**并不是提高Web应用性能的**万金油（原文：A Silver Bullet）**就目前来说，在WebAssembly中使用DOM API 仍然比从 JavaScript 中调用要慢。但只是暂时性问题的， [WebAssembly Interface Types](https://github.com/WebAssembly/interface-types/blob/master/proposals/interface-types/Explainer.md) 计划将解决这个问题。如果你想要了解更多关于这方面的信息，可以查看 Mozilla 的这篇 [佳作](https://hacks.mozilla.org/2019/08/webassembly-interface-types/) 。

#### 好的，那为什么选用 Rust 呢？

Rust 是一门运行速度超快，并且以他丰富的类型系统和可信赖的所有权模型而闻名的语言。尽管它的学习曲线非常的陡峭，但是带来的回报完全成正比！Rust 连续在 [2018](https://insights.stackoverflow.com/survey/2018#technology-_-most-loved-dreaded-and-wanted-languages) 和 [2019](https://insights.stackoverflow.com/survey/2019#technology-_-most-loved-dreaded-and-wanted-languages) 年在 Stack Overflow's Developer Surveys 中被评选为 **最受喜爱的编程语言** 。

Rust 同样可以用它丰富的类型系统和可信赖的所有权模型来帮助开发者编写出更加安全的代码。和那些在JavaScript中难以定位的竞争条件Bug们说再见吧！ 事实上，通过 Rust ，大部分的 Bugs 都将在项目上线之前的编写阶段被编译器发现。同时不用担心，当你的应用出现错误的时候，你仍然可以在浏览器的调试控制台中获得你 Rust 代码的完整的错误栈追踪。

#### 同类的项目？

我们非常愿意和其他的类似项目交流想法，并且相信通过这种方式，我们可以互相扶持进步来发挥出这个新技术的潜力。如果你对Yew没有兴趣，你可能会喜欢这些项目（按照字母顺序排列）

* [Draco](https://github.com/utkarshkukreti/draco) - _"A Rust library for building client side web applications with Web Assembly"_
* [Percy](https://github.com/chinedufn/percy) - _"A modular toolkit for building isomorphic web apps with Rust + WebAssembly"_
* [Seed](https://github.com/seed-rs/seed) - _"A Rust framework for creating web apps"_
* [Smithy](https://github.com/rbalicki2/smithy) - _"A framework for building WebAssembly apps in Rust"_