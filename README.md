#### 0x01. 描述

现在抓鸡越来越没有门槛，肉鸡随处可见。

本篇文章是针对目前linux下比较常见的两款ddos木马，进行脚本查杀
1. gates
2. xorddos马

该脚本良好支持这些马的删除。脚本直接执行就ok


#### 0x02. 自查

如果发现宽带流量被打满，那排查下是否有异常端口，如果有，那应该是被肉鸡了。
如果脚本没清理干净的，根据`top`、`netstat -anop`、`ps -ef`进行自查也很简单

有任何问题，欢迎指正。



