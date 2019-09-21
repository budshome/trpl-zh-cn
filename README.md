# 前言

> [foreword.md](https://github.com/rust-lang/book/blob/master/second-edition/src/foreword.md)
> <br>
> commit 5e085bd1add34aec03416e891751552b439dde52

虽然不是那么明显，但 Rust 程序设计语言的本质在于 **赋能**（*empowerment*）：无论你现在编写的是何种代码，Rust 能让你在更为广泛的编程领域走得更远，写出自信。

比如，“系统层面”（“systems-level”）的工作，涉及内存管理、数据表示和并发等底层细节。从传统角度来看，这是一个神秘的编程领域，只为浸淫多年的极少数人所触及，也只有他们能避开那些臭名昭著的陷阱。即使谨慎的实践者，亦唯恐代码出现漏洞、崩溃或损坏。

Rust 破除了这些障碍，其消除了旧的陷阱并提供了伴你一路同行的友好、精良的工具。想要 “深入” 底层控制的程序员可以使用 Rust，无需冒着常见的崩溃或安全漏洞的风险，也无需学习时常改变的工具链的最新知识。其语言本身更是被设计为自然而然的引导你编写出在运行速度和内存使用上都十分高效的可靠代码。

已经在从事编写底层代码的程序员可以使用 Rust 来提升抱负。例如，在 Rust 中引入并行是相对低风险的操作：编译器会为你捕获经典的错误。同时你可以自信的采取更为积极的优化，而不会意外引入崩溃或漏洞。

但 Rust 并不局限于底层系统编程。其表现力和工效足以令人愉悦的编写出 CLI 应用、web server 和很多其他类型的代码 —— 在本书中你会看到两个简单示例。使用 Rust 能将你在一个领域中学习的技能延伸到另一个领域；你可以学习 Rust 来编写 web 应用，接着将同样的技能应用到你的 Raspberry Pi（树莓派）上。

本书全面介绍了 Rust 为用户赋予的能力。其内容平易近人，致力于帮助你提升 Rust 的知识，并且提升你作为程序员整体的理解与自信。那么让我们准备深入学习 Rust 吧（打开新世界的大门 :)） —— 欢迎加入 Rust 社区！

— Nicholas Matsakis 和 Aaron Turon

## 声明

`Rust 程序设计语言（第二版 & 2018 edition）`由 [KaiserY](https://github.com/KaiserY) 翻译，源码仓库在 [GitHub](https://github.com/KaiserY/trpl-zh-cn)，翻译自`Rust`官方书籍 [*The Rust Programming Language*](https://github.com/rust-lang/book/tree/master/src)。

感谢`KaiserY`和`Rust团队`的无私奉献。

**本站点仅为方便学习和查阅等相关用途，书籍和译本的所有内容和相关权利属于书籍编写者和翻译者。**

若有任何不当，请联系`linshi@budshome.com`删除。

💥 **更新时间：2019-09-21**
