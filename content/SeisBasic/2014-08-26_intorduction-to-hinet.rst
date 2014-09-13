Hi-net简介
##########

:date: 2014-08-26 17:20
:author: SeisMan
:category: 地震学基础
:tags: Hinet, 数据, 台网
:slug: introduction-to-hinet

Hi-net，全称为High Sensitivity Seismograph Network，是NIED下的一个覆盖日本全境的高密度地震台网。

网址
====

以前的网站只有日文版，从2012年左右建立了英文版网站，目前英文版网站尚为beta版。

- 官网网址：http://www.hinet.bosai.go.jp/
- 台站分布图下载：http://www.hinet.bosai.go.jp/st_info/detail/dataset.php?LANG=en
- 用户注册：https://hinetwww11.bosai.go.jp/nied/registration/?LANG=en


基本情况
========

- 2000年10月开始部署Hi-net台网；
- Hi-net台站均匀分布于整个日本境内，台站间距约为20km，预计约1000个台站（目前共计近800个台站）；
- 每个Hi-net台站都包含了一个用于安装地震仪的钻孔（borehole）以及一个用于放置数据记录器和其他数据传输设备的观测小屋；
- 在每个钻孔的底部（深度大于100m），安装了短周期三分量速度地震仪、三分量强震加速度仪。同时在每个台站的地表也安装了三分量强震加速度仪；其中Hi-net只收集短周期三分量速度地震仪的数据，两对强震加速度仪的数据则由KiK-net收集；
- 位于钻孔底部的传感器没有用水泥覆盖，因而当传感器出现问题时很容易将传感器取出，进行维修或更换；
- 钻孔的深度不一，最浅的位于地表，最深的深度超过3.5km，大多数钻孔的深度在100-300m之间；
- 地震仪的运动首先被转化成弱电信号，经过模数转换器转换成每秒1000个采样点的数字信号，经过减采样后，得到采样率为100Hz、27位精度的数字信号，再将数据以一秒为最小单位打包传送给数据中心；

数据
====

数据使用的注意事项：

- 在文章、会议摘要中使用了NIED的数据，应将数据使用情况报告给NIED；
- NIED拥有数据的版权，严禁用户自行分发数据；
- 发表文章时要致谢数据来源；

数据种类：

- JMA Unified earthquake catalog（日本境内及附近区域的地震目录）
- Arrival-time data（基于JMA unified catalog）
- Focal mechanism catalog（基于JMA unified catalog）
- Event waveform data（仅JMA unified catalog中的事件）
- Continuous waveform data（2004年4月1日至今的连续波形数据）
- Old waveform data（2004年4月之前的数据）
