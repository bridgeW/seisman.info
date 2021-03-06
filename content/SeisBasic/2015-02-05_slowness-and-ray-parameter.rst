慢度与射线参数
##############

:author: SeisMan
:date: 2015-02-05
:category: 地震学基础
:tags: 射线, 名词解释
:slug: slowness-and-ray-parameter
:depends: mathjax

.. contents::

本文介绍几个专业名词：

- 慢度
- 水平慢度/垂直慢度
- 射线参数
- 视速度/视慢度

这些名词其实很简单，但是在大三一直到研一的几年间，这几个名词在我脑中的概念是有些混乱的，我把混乱的原因归结于不同课本对同一个专业名词乱用了不同的词汇。故而在这里总结一下。

慢度
====

速度\ :math:`v`\ 是用于衡量波在介质中传播的快慢的物理量，单位一般是km/s。

慢度是速度的倒数，单位为s/km:

.. math::

   s = \frac{1}{v}

所以慢度是一个用于描述介质的物理量。

慢度矢量
========

对于一个在介质中传播的射线来说，取射线中的任何一段，射线都有一个方向，同时该\ **段**\ 射线所在的介质都有一个慢度值。

介质的慢度值以及射线的方向构成了该\ **段**\ 射线的一个属性，即慢度矢量。

.. math::

   \mathbf{s} = \frac{1}{v} \mathbf{e_s}

根据慢度矢量的定义可知，慢度矢量是与射线相关的量，且慢度矢量是一个局部量，一条射线中的不同段，其慢度矢量是不同的。

水平慢度和垂直慢度
==================

既然是一个矢量，就可以将其分解到水平方向和垂直方向。

在\ **水平分层模型**\ 下，定义射线方向与垂直方向的夹角为\ :math:`\theta`\ ，则水平慢度为：

.. math::

   p = s\sin \theta = \frac{\sin \theta}{v}

垂直慢度为：

.. math::

   \eta = s \cos \theta = \frac{\cos \theta}{v}

所以实际上水平慢度和垂直慢度，也是一个局部量，同一条射线，不同段的水平慢度和垂直慢度是不同的。

射线参数
========

射线在经过两种介质的分界面时，满足Snell定律:

.. math::

   \frac{\sin \theta_1}{v_1} = \frac{\sin \theta_2}{v_2}

关于Snell定律，有两点需要注意：

#. Snell定律不要求介质分界面是水平的，可以是水平分层的、球状分层或任意曲率；
#. 此处\ :math:`\theta`\ 是射线与界面法向的夹角。

因此，对于水平分层介质来说，界面法向与垂直方向是重合的。因而根据Snell定律，有：

.. math::

   p_1 = \frac{\sin \theta_1}{v_1} = \frac{\sin \theta_2}{v_2} = p_2

即在水平分层模型下，射线在不同层里的水平慢度是不变的，每条射线都有唯一的水平慢度，因而定义水平慢度为射线参数：

.. math::

   p = \frac{\sin \theta}{v}

需要注意的是，“射线参数不变”这个准则仅在水平分层等特殊的情况下成立，若存在倾斜界面，则该准则不再成立。

视速度/视慢度
=============

在水平分层模型下，每条射线对应了唯一的射线参数，因而射线参数是很重要的一个量。

经过一些简单的推导，可知：

.. math::

   \frac{dT}{dX} = p

其中\ :math:`X`\ 为射线传播的水平距离，\ :math:`T`\ 为射线传播的时间。

:math:`\frac{dT}{dX}`\ 即波前在经过不同震中距的台站的到时差，即所谓的视慢度，所以平常说的视慢度其实就是射线参数。

球状分层介质
============

上面的一些概念大都是在水平分层模型下解释的，更常见的模型是球状分层模型。

在球状分层模型下，射线参数的定义变成：

.. math::

   p = \frac{r \sin \theta}{v}

其中\ :math:`r`\ 是计算射线参数时所使用的半径，\ :math:`\theta`\ 为射线与径向方向的夹角。

做了这样的定义之后，在水平分层模型下推导的公式基本都可以直接推广到球状分层模型中了。


