# Mesos 简介

Mesos 论文于 2010 年 9 月在著名的加州大学伯克利分校发表，
该论文中描述了一种能够更好的共享计算资源的技术，特别是在大规模集群计算场景中。

论文中详细讨论了为什么 Mesos 能够提高集群资源综合利用率，
建立了详细的数学模型，编写代码实现了 5 个可以运行在 Mesos 上的计算框架，
并且获得了实验数据，可谓有理有据。5 个框架中，有 3
个是对当时已有的计算框架的移植，以便证明移植到 Mesos 上的成本并不高，
而且用户程序完全不用修改；另外两个框架之一便是 Spark，目前已经是 Apache
软件基金会下属顶级开源项目，炙手可热。

在 Mesos 论文发布后两个多月，就开放了源代码，成为 Apache 软件基金会孵化器中的一员，
并且迅速成长于 2013 年 7 月从孵化器中毕业，正式成为 Apapche 软件基金会的顶级项目。