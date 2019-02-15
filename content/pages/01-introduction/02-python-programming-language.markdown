title: Python 编程语言
category: page
slug: python-programming-language
sortorder: 0102
toc: False
sidebartitle: 核心语言
meta: 核心Python编程语言包含许多其他语言中没有的功能组合。


# Python 编程语言

Python编程语言是一种
[开源](https://www.python.org/downloads/source/)，
[广泛使用](/why-use-python.html)的工具，用于创建软件应用程序。

## Python用来做什么？

Python 经常用于[构建](/web-frameworks.html)和[部署](/deployment.html)[网络应用](/web-development.html)和[网络 API](/application-programming-interfaces.html)。Python 也可以分析和可视化[数据](/data.html)，即使被测试的软件不是用 Python 编写的，Python 也可以[测试软件](/testing.html)。

## 语言概念

Python有一些有用的编程语言概念，在其他语言中不常见。 这些概念包括：

* 生成器
* 推导表达式
* [应用依赖](/application-dependencies.html)通过内置 
  [venv](https://www.python.org/dev/peps/pep-0405/)（[从 Python 3.3 开始](https://docs.python.org/3/whatsnew/3.3.html)） 
  和 [pip](https://www.python.org/dev/peps/pep-0453/)（[从 Python 3.4 开始](https://docs.python.org/3/whatsnew/3.4.html)）
  命令管理

## 生成器

生成器是一种Python核心语言结构，它允许函数的返回值表现为迭代器。
通过在大量迭代的上下文期间分配和释放内存，生成器可以允许更有效的内存使用。
生成器在[PEP255](https://www.python.org/dev/peps/pep-0255/) 中定义，
并在2001年的 Python 2.2 中包含在语言中。

## 推导表达式

推导表达式是一种Python语言结构，用于在列表，字典和集合中简明地创建数据。列表推导包含在 Python 2 中，
而字典和集合推导在 Python 3 中引入。

## 为什么推导表达式很重要？

推导表达式是在核心Python数据结构中填充条件数据的更清晰的语法。在没有推导表达式的情况下
创建数据通常涉及具有条件的嵌套循环，这些条件对于代码阅读器来说难以正确评估。

## 推导表达式示例

列表推导：

    >>> double_digit_evens = [e*2 for e in range(5, 50)]
    >>> double_digit_evens
    [10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48, 50, 52, 54, 56, 58, 60, 62, 64, 66, 68, 70, 72, 74, 76, 78, 80, 82, 84, 86, 88, 90, 92, 94, 96, 98]

集合推导：

    >>> double_digit_odds = {e*2+1 for e in range(5, 50)}
    {11, 13, 15, 17, 19, 21, 23, 25, 27, 29, 31, 33, 35, 37, 39, 41, 43, 45, 47, 49, 51, 53, 55, 57, 59, 61, 63, 65, 67, 69, 71, 73, 75, 77, 79, 81, 83, 85, 87, 89, 91, 93, 95, 97, 99}

字典推导：

    >>> {e: e*10 for e in range(1, 11)}
    {1: 10, 2: 20, 3: 30, 4: 40, 5: 50, 6: 60, 7: 70, 8: 80, 9: 90, 10: 100}

### 通用 Python 语言资源

* [在线 Python 导师](http://www.pythontutor.com/) 直观地浏览代码并显示它在 Python 解释器上的执行方式。

* [本周的 Python 模块](http://pymotw.com/2/index.html) 是一个Python标准库之旅。

* [用 Python 编写的 Python 解释器](http://aosabook.org/en/500L/a-python-interpreter-written-in-python.html)
  是一个令人难以置信的元，但真的很有用的包围在语言中的一些较低级别的东西。

* [在 Python 中编码时要记住的一些事项](http://satyajit.ranjeev.in/2012/05/17/python-a-few-things-to-remember.html)
  是在使用该语言构建程序时使用的一组很好的实践。

* [Python 内部：向Python添加一个新语句](http://eli.thegreenplace.net/2010/06/30/python-internals-adding-a-new-statement-to-python/)

* [你不能没有的 Python 技巧](http://www.slideshare.net/audreyr/python-tricks-that-you-cant-live-without)
  是 Audrey Roy 的幻灯片，介绍了代码可读性，linting，依赖性隔离和其他优秀的 Python 实践。

* [Python 内部原理介绍](http://tech.blog.aknin.name/2010/04/02/pythons-innards-introduction/)
  解释了Python的一些内部执行是如何发生的。

* [什么是 Python 中的元类](http://stackoverflow.com/questions/100003/what-is-a-metaclass-in-python)
  是关于 Python 的最佳 Stack Overflow 答案之一。

* Armin Roacher 在2012年的南非 PyCon 介绍的[你不了解 Python 的事情](https://speakerdeck.com/mitsuhiko/didntknow)。

* [编写惯用的 Python](http://www.jeffknupp.com/blog/2012/10/04/writing-idiomatic-python/)
  是编写Pythonic代码的指南。

* [运行 Python 的东西](http://ashfall.github.io/blog/2012/10/23/the-thing-that-runs-your-python/)
  是一个开发人员在研究 PyPy 时所学到的内容的摘要。

### Python 生态系统资源

[最佳 Python 资源](/best-python-resources.html)上有一个完整的页面，其中包含链接，
但是当您超越初学者主题时，以下资源更适合你。

* [reddit 的 Python 子版块](http://www.reddit.com/r/python) 汇总了很棒的Python链接，
  并有一个活跃的社区准备好回答初学者和高级Python开发人员的问题。

* 博客 [免费 Python 技巧](http://freepythontips.wordpress.com/) 
  提供有关 Python 主题的帖子以及Python生态系统的新闻。

* [Python Books](http://pythonbooks.revolunet.com/) 是一系列免费提供的关于 
  Python，Django 和数据分析的书籍。

* [Python IAQ：不经常问的问题](http://norvig.com/python-iaq.html)
  是一个关于稀有 Python 功能的古怪查询列表，以及为什么某些语法已经或没有内置到该语言中。

* [Python 函数式编程的实用介绍](https://codesachin.wordpress.com/2016/04/03/a-practical-introduction-to-functional-programming-for-python-coders/)
  对于希望学习该语言的函数式编程范式的开发人员来说，它是一个很好的入门者。

* [Python 内部入门](http://akaptur.com/blog/2014/08/03/getting-started-with-python-internals/)
  从庞大的CPython代码库中获取一部分并解构其中的一部分，以了解我们可以了解Python本身的构建方式。

### 推导表达式资源

* [理解 Python 的推导表达式](https://dbader.org/blog/list-dict-set-comprehensions-in-python#intro)
  Dan Bader是一篇很棒的文章，其中有一些例子可以解释如何使用列表，字典和集合推导表达式。

* [Python列表推导：视觉解释](http://treyhunner.com/2015/12/python-list-comprehensions-now-in-color/)
  解释了迭代的常用习语如何成为语言本身的语法糖，以及如何在自己的程序中使用它。

* Python 3 模式和习语网站概述了
  [推导表达式](http://python-3-patterns-idioms-test.readthedocs.org/en/latest/Comprehensions.html)
  包括代码示例和图表，以解释它们如何工作。

* [绝地的方式使用 Python 推导表达式](https://gist.github.com/bearfrieze/a746c6f12d8bada03589)
  展示了以星球大战为主题的推导表达式，以便穿过细节。所有示例都使用 Python 3.5。

* [Python 惯用语：推导表达式](https://blogs.msdn.microsoft.com/pythonengineering/2016/03/14/idiomatic-python-comprehensions/)
  解释了 Python 的推导是如何受到 Haskell 列表推导的启发。它还提供了清晰的示例，
  显示了常见迭代代码的简要概括，例如在对包含的元素执行某些操作时将一个列表复制到另一个列表。

* [通过示例学习 Python：列表推导](http://blog.cdleary.com/2010/04/learning-python-by-example-list-comprehensions/)
  给出了一个不正确的列表理解的例子，然后展示了如何纠正它的问题。

* [Python 列表推导](http://www.pythonforbeginners.com/basics/list-comprehensions-in-python)
  涵盖列表推导的代码，并给出一些示例代码来说明它们是如何工作的。

* [Python 列表简介](http://effbot.org/zone/python-list.htm)
  是一般的 Python 列表的实用概述，覆盖到了列表推导。

### Python 生成器资源

* 博客 [Python 生成器](http://rdrewd.blogspot.com/2014/02/python-generators.html)
  特别注重生成字典。它为 Python 新手提供了很好的介绍。

* [Python中的Generator表达式：简介](https://dbader.org/blog/python-generator-expressions#intro)
  是有关如何使用生成器的最佳全面介绍，并提供了大量代码示例供您学习。

* [Python 201：生成器简介](http://www.blog.pythonlibrary.org/2014/01/27/python-201-an-intro-to-generators/)
  是另一个简短但信息丰富的，包含生成器示例代码的文章。

* [迭代器和生成器](http://anandology.com/python-practice-book/iterators.html)
  提供了这两个结构的代码示例以及每个结构的一些简单解释。

* [Python：生成器 - 如何使用它们以及您获得的好处](https://www.youtube.com/watch?v=bD05uGo_sVI)
  是一个视频，用于讲解 Python 中的生成器。

* Stack Overflow 上[理解Python中的生成器？](http://stackoverflow.com/questions/1756096/understanding-generators-in-python)
  的问题有一个令人印象深刻的答案，清楚地列出了 Python 生成器涉及的代码和概念。

* [系统程序员的生成器技巧](http://www.dabeaz.com/generators/)
  提供了使用生成器的代码示例。该材料最初是在系统程序员的 PyCon 研讨会上提出的，
  但与所有致力于理解使用生成器的适当方法的 Python 开发人员相关。
