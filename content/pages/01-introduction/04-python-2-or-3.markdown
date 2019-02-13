title: Python 2 还是 3?
category: page
slug: python-2-or-3
sortorder: 0104
toc: False
sidebartitle: Python 2 还是 3?
meta: 了解是否应使用Python版本2或3来构建应用程序。


# Python 2 还是 3?

Python 编程语言几乎完成了从版本 2 升级到版本 3 的长期过渡。初学者通常会有到底该学哪个版本的问题。
Python 3 最初是在 2008 年发布的，但目前仍不是作为默认版本安装在很多操作系统，比如 macOS 上，
听到这些很令人困惑。然而，随着最终的第 2 版 Python 2.7 正在接近其定于[2020年1月1日](https://mail.python.org/pipermail/python-dev/2018-March/152348.html)的生命周期结束，这种情况正在迅速发生变化。

现在简单的答案是：学习Python 3，特别是截至2018年5月的最新版本是 [Python 3.6.5](https://www.python.org/downloads/)。 
如果由于某种原因你绝对必须学习 Python 2，例如因为你的雇主正在研究一堆遗留代码，
你将能够将你的大部分知识从 Python 2 转移到 Python 3 中。同样，你如果从 Python 3 开始，
你仍然能够阅读和编写 Python 2 代码。

有足够的[很棒的资源](/best-python-resources.html)可以教你在没有任何先前版本2经验的版本3中编写代码。
Python 3 是未来，你不会后悔从最新版本的[编程语言](/learning-programming.html)开始。

关于完全使用 Python 3 的建议的一个警告。如果您对使用[配置管理工具](/configuration-management.html)的 DevOps 类型工作感兴趣，
例如 [Fabric](http://www.fabfile.org/) 或 [Ansible](/ansible.html)，
那么你可能不得不同时使用 Python 2 和 3，因为这些库的部分落后于完整的Python 3支持。

## 可视化和项目

由于从 Python 2 升级到3在社区内是如此巨大的事业，许多项目如雨后春笋般涌现，使转换更加容易。

* [six](https://pythonhosted.org/six/) 是一个2/3兼容性库，它是许多流行的 Python 项目
  的依赖项，可以更容易同时支持 Python 2 和 3。

* [Python 3 Readiness](http://py3readiness.org/) 是一个可视化库，
  其中最流行的360个库（通过下载）已准备好与 Python 3 一起使用。

* [Python 时钟](https://pythonclock.org/) 倒计时直到P ython 2.x 不再维护。
  虽然 Python 2 的退役可能还需要很长时间，但是将现有应用程序迁移到 3.x 中的修改语法
  可能需要花费大量的时间和精力。

### 转到 3 的相关资源

将现有的代码库从2移动到Python 3可能是一项艰巨的任务。这些资源是由以前经历过这个过程的开发人员
创建的，并且提供了减少痛苦的建议。

* [Python 3 迁移](http://python3porting.com/) 是一本完整的书，其中详细介绍了如何
  将现有项目和库升级到Python 3.x。
  
* [从 Python 2 转到 Python 3](http://ptgmedia.pearsoncmg.com/imprint_downloads/informit/promotions/python/python2python3.pdf)
  是一份如何移植 Python 代码的 PDF 小抄

* 官方[将代码移植到 Python 3](https://wiki.python.org/moin/PortingToPy3k/) 页面
  包含有关移植 Python 代码以及底层 C 实现的资源。还有一个[使用Python 2和3兼容性编写代码的快速参考](https://wiki.python.org/moin/PortingToPy3k/BilingualQuickRef)。

* [Django 和 Python 3 如何设置 pyenv 来支持多个 Python 版本](https://godjango.com/96-django-and-python-3-how-to-setup-pyenv-for-multiple-pythons/)，
  是一部讲述如何用 pyenv 来实现同时运行 Python 2 和 3 以支持不同的项目的视频。

* [通过零停机升级到 Python 3](https://tech.yplanapp.com/2016/08/24/upgrading-to-python-3-with-zero-downtime/) 
  提供有关将大型 Web 应用程序从现有 Python 2 转移到 Python 3 的建议。
  他们的过程涉及升级依赖关系，测试和部署新版本，然后返回清理过渡创建的不必要的代码。

* [愉快地迁移到 Python 3](https://github.com/arogozhnikov/python3_with_pleasure) 
  是一个移植指南，侧重于数据科学家通常在其程序中使用的代码。

* [Instagram 顺利移植到 Python 3](https://thenewstack.io/instagram-makes-smooth-move-python-3/) 
  解释了他们在大约一年内将所有代码转换为 Python 3 的升级过程。

* [转移到 Python 3 的实践步骤](https://talkpython.fm/episodes/show/155/practical-steps-for-moving-to-python-3) 
  是一个播客，它将迁移大型现有应用程序代码库从 Python 2 到 Python 3。

* [迁移到 Python 3 的经验教训](https://able.bio/rhett/lessons-learned-from-migrating-to-python-3--27jsj82) 
  介绍了开发团队如何升级基于 [Django](/django.html) 的大型电子商务网站。

### 从 Python 2 转到 3 的相关资源

以下资源将为您提供有关社区如何感受从 Python 2 到 3 的过渡的更多背景信息，以及您应该尽快升级的原因。

* [我为什么要使用 Python 3？](https://eev.ee/blog/2016/07/31/python-faq-why-should-i-use-python-3/) 
  是关于重要主题的详细常见问题解答，例如 3.x 提供的 unicode 支持，迭代改进和异步升级。
  作者还有一篇很棒的后续帖子，题为[针对 Python 3 的反驳](https://eev.ee/blog/2016/11/23/a-rebuttal-for-python-3/) ，
  反驳其他社区成员对 Python 3 中的各种功能感到不满的论点。

* 想知道 Python 3 与 Python 2 相比都有什么改动以及 Python 3 的所有优势吗？你需要看下 
  [Python 3 修改情况的官方文档](https://docs.python.org/3/whatsnew/index.html)。

* [Python 3 是赢家](https://blogs.msdn.microsoft.com/pythonengineering/2016/03/08/python-3-is-winning/) 
  上的数据和图表来自 PyPI，可以看出如果以当前速度发展，到 2016 年中期，支持 Python 3 的库总量将超过 支持 Python 2 的库。

* [来自仁慈的独裁者的 Python 3 回顾](https://www.youtube.com/watch?v=Oiw23yfqQy8) 
  是 Guido van Rossum 关于什么可行，什么不可行以及仍需要在转变被认为完成前需要做的视频。

* [Python 3 过渡的各个阶段](http://www.snarky.ca/the-stages-of-the-python-3-transition) 
  提供了一个核心 Python 开发人员关于截止到2015年底从 Python 2 到 3 的过渡进展。

* [Dropbox 如何推进有史以来最大的 Python 3 迁移之一](https://blogs.dropbox.com/tech/2018/09/how-we-rolled-out-one-of-the-largest-python-3-migrations-ever/) 
  解释了他们的转型是如何在2015年开始的，并在2018年成功完成。

* [为什么使用Python 3？](http://whypy3.com/) 随机输出使用 Python 3 而不是 2.x 的合理理由。

* [激进的规则：在 Facebook 改变 Python 文化](https://www.youtube.com/watch?v=nRtp9NgtXiA) 
  是一个引人入胜的关于 Facebook 如何在公司内部一群热情的开发人员的努力下从主要用 Python 2 转移到 Python 3。
  关于如何在大公司中迁移已建立的代码库这篇绝对值得阅读。

* [移植到 Python 3 就像要求你吃蔬菜](http://nothingbutsnark.svbtle.com/porting-to-python-3-is-like-eating-your-vegetables)，
  阐述了 Python 3 有些特性值得我们将代码移植过去，同时还提供了一些怎样移植更省力的小建议。

* [Scrapy 的 Python 3 支持之路](http://blog.scrapinghub.com/2015/08/19/scrapy-on-the-road-to-python-3-support/)，
  以一个广为使用的 Python 项目的角度阐述了它的 Python 3 支持计划，以及为何实施起来花了这么长时间的原因。

* 所有主要的科研型 Python 类库都承诺不晚于 2020 年，即当 Python 2 维护期结束时，
  [放弃支持 Python 2](https://python3statement.github.io/)。
  该承诺通过公开声明它们的意图来大力鼓励对 Python 3 的使用。

* [10个很棒的 Python 功能，因为你拒绝升级到 Python 3 而无法使用](http://www.asmeurer.com/python3-presentation/slides.html)，
  是一个很棒的幻灯片，带有 Python 3 有的，2.x 中没有的新功能的有用代码片段，
  例如仅关键字参数，链式异常和 `yield from` 关键字。
