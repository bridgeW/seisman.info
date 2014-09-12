Hi-net走时和震源机制数据
########################

:date: 2014-09-02 02:20
:author: SeisMan
:category: 地震学基础
:tags: Hinet, 走时, 地震目录, Python
:slug: hinet-arrival-time-and-focal-mechanism-catalog

Hi-net基于JMA Unified Hypocenter Catalog，提供了到时数据以及震源机制解目录。

数据下载地址：http://www.hinet.bosai.go.jp/REGS/JMA/?LANG=en

数据格式官方文档：http://www.hinet.bosai.go.jp/REGS/manual/dlDialogue.php?r=jmaformat&LANG=en

本文不谈数据格式，只讨论数据的下载问题。

走时和震源机制数据不需要申请可以直接下载。因为省略了申请的步骤，实现下载也更简单一些。

HinetJMADownload
================

数据下载Python脚本位于\ `HinetJMADownload.py <https://github.com/seisman/HinetScripts/blob/master/HinetJMADownload.py>`_

用法
----

::

    Download arrival time data or focal mechanism catalog from Hi-net.

    Usage:
        HinetJMADownload.py (--measure | --mecha) <yyyymmdd> <span> [--os=OS]
        HinetJMADownload.py -h

    Options:
        -h --help     Show this help.
        --measure     Request arrival time data.
        --mecha       Request focal mechanism catalog.
        --os=OS       Line break format, choose from DOS or UNIX. [default: DOS]

示例
----

下载走时数据::

    HinetJMADownload.py --measure 20120101 5

下载震源机制数据::

    HinetJMADownload.py --mecha 20120101 1
