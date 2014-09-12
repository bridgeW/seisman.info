SAC参考手册中文版
#################

:date: 2013-07-06 18:21
:modified: 
:author: SeisMan
:category: SAC
:tags: 书籍, PDF
:slug: sac-manual

.. contents::

3.1 dev版
=========

此文档使用Git进行版本控制，我会不定期更新或修正文档内容，读者可以下载已定稿的3.0版或正在修订中的3.1-dev版。待更新积累到一定程度的时候，我会正式发布3.1版。

- 重新整理了大部分命令的语法说明；
- 对“SAC图像”一章进行了修订；  

下载地址：`3.1-dev版 <https://github.com/seisman/SAC_Docs_zh/blob/master/SAC_Docs.pdf?raw=true>`_

2014-04-18   3.0版
==================

- 重新设计了整个文档的结构
- 重写了教程部分的大多数内容
- 教程部分根据SAC v101.6a进行修正
- Bug修订

下载地址: `SAC参考手册v3.0.pdf <http://pan.baidu.com/s/1kTiGTb5>`_

2014-02-22   2.3版
==================

- 使用Git管理源码
- 整理结构和布局的修改
- 新的小节: ”SAC IO升级版“、”暂存块变量的读写“、”SAC保存图像“
- Bug修订

下载地址: `SAC帮助文档中文版v2.3.pdf <http://pan.baidu.com/s/1o6kBdnO>`_

2013-04-12   2.2版
==================

命令已经整理完毕，排版上基本已经没有问题了，重新设计了封面，在接下来很长一段时间应该都不会有大的改动了。如果有时间，会加一些SAC其他方面的东西。如果有读者反馈，命令方面也可能会有更新。

下载地址： `SAC帮助文档中文版v2.2.pdf <http://pan.baidu.com/share/link?shareid=718423145&uk=19892171>`_  

2013-04-06   2.1版
==================

重新细致整理了手册的第一章，基本达到了我认为可以打印的地步。命令部分还没有整，200多个，需要很长一段时间才能出来。

下载地址： `SAC帮助文档中文版v2.1.pdf <http://pan.baidu.com/share/link?shareid=707884920&uk=19892171>`_   

2013-03-29   2.0版
==================

花了两天的时间重新制作了整个文档，内容及排版部分有很多bug，草草结束是因为接下来的一段时间要好好干活了，先把v2.0的细节总结如下：

-  操作系统：CentOS 6.4 (Final)
-  编译环境：TeX Live 2012
-  编译命令：xeLaTeX
-  中文实现：CTEX宏包
-  中文字体：宋体+黑体
-  英文主字体：Liberation Sans
-  代码字体：Courier 10 Pitch

下载地址：\ `SAC帮助文档中文版v2.0.pdf <http://pan.baidu.com/share/link?shareid=692702403&uk=19892171>`_

2012-09-18   1.2版
==================

-  增加了封面配图。

下载地址：\ `SAC帮助文档中文版v1.2.pdf <http://pan.baidu.com/share/link?shareid=678805242&uk=19892171>`_

2012-09-03   1.1版
==================

-  重新格式化整个文档，使得其看上去更规范，也易于以后的修改；
-  文档中的所有C或Fortran代码从notepad++中直接导出，代码支持语法高亮；
-  代码及正文英文字体采用Consolas字体。
-  增加了”在脚本中调用SAC“一节；
-  新增了transfer、traveltime、saveimg、datagen命令（依赖于SAC v101.5c）；
-  公式用公式编辑器编辑

下载地址：\ `SAC帮助文档中文版v1.1.pdf <http://pan.baidu.com/share/link?shareid=665878684&uk=19892171>`_

2012-01-08   1.0版
==================

自学SAC是在2010年的寒假，看的是1995年出版的《数字地震波形分析》的电子版以及SAC自带的英文文档。《数字地震波形分析》大概是当时唯一一本介绍SAC的中文书，电子版很不清晰而且有些命令已经过时了。我一直希望能有一个新版本出现。

这个SAC中文手册最初翻译于2011年暑假，用了20天左右的时间，完成了大部分的翻译工作。这个版本主要参考了《数字地震波形分析》一书。包含了大部分的用户指南以及几乎全部的命令。这个版本的优点在于：

-  结合了SAC101.4版本，增加、删除和修改了一些命令；
-  更清晰；
-  增加了书签，方便定位，支持全文搜索。

这个版本的缺点在于：

-  与matlab引擎相关的几个命令未加入；
-  SAC的两个子程序部分暂时还没有翻译；
-  由于没有时间和心思检查，中间可能会出现一些错误；
-  关于命令的简写还有一些细节没有做；
-  在某些linux版本下，pdf打开后看到的是完全颠倒的字（比如悲摧的CentOS...）希望这些可以在以后的版本中得到改善和加强。

下载地址：\ `SAC帮助文档中文版v1.0.pdf <http://pan.baidu.com/share/link?shareid=663854091&uk=19892171>`_