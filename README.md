fullstackpython.qiwihui.com
===

本项目是网站[全栈 Python](https://fullstackpython.qiwihui.com/) 的源代码。
本项目作为 [Full Stack Python](https://github.com/mattmakai/fullstackpython.com) 的
简体中文翻译项目进行维护，在对原项目中的文章内容进行同步翻译的同时，
还使文件样式和网站结构也尽可以与原项目保持同步。

## 如何贡献翻译

1. [新建一个 issue](https://github.com/qiwihui/fullstackpython.com/issues/new)，说明要贡献哪篇文档，注意翻译之前先看看 issues 里面有没有人已经认领了；
2. fork 之后，修改 `/content/` 中的对应文档进行翻译，并在本地预览，如果不知道如何在本地启动，可以参考[如何在本地启动](https://github.com/qiwihui/fullstackpython.com#如何在本地启动)
3. 注意在 File metadata 中将自己加入到 `translators` 字段，若无此字段，则添加一个；
4. 注意在 File metadata 中更新 `updated`，若无此字段，则添加一个；
5. 提交一个 pull-request，等待审核。

## 如何在本地启动

1. 安装 [Pelican](http://docs.getpelican.com/en/3.6.3/install.html) 运行环境 `make init`
2. 重新生成网页 `make run`
3. 启动 Pelican HTTP 服务器 `cd generated/updated_site && python -m pelican.server`
4. 在浏览器中访问 `http://127.0.0.1:8000/`

## 如何查看成果

更新内容一旦合并后，可以在 [https://fullstackpython.qiwihui.com](https://fullstackpython.qiwihui.com) 上看到成果。