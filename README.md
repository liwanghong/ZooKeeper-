# ZooKeeper源码分析

业余时间学习了一下ZooKeeper : Distributed process coordination这本书的内容，对ZooKeeper实现的细节很好奇，所以顺便把ZooKeeper源码看了一遍。看完之后想写点内容做个笔记，确发现不好开始。由于ZooKeeper一个完整的逻辑的代码可能在多个线程，多个文件以及多个节点上互相作用，所以如果只讲原理，就很难把原理同源代码对应上；相反，只讲源代码就很难理解原理的全貌。本人尝试解释服务器从开始启动到正常提供的服务的代码逻辑，由于表述能力欠佳，且源码中逻辑分支很多，所以文档中避免不了出现错误。如发现错误请提Issue或者私发wanghong.li1029@163.com。

[ZooKeeper架构](架构.md)

[ZooKeeper服务器节点启动以及选举](服务器启动以及选举.md)

[ZooKeeper服务器状态同步](服务器状态同步.md)

[ZooKeeper客户端连接管理](客户端连接管理.md)

[ZooKeeper响应客户端请求](响应客户端请求.md)

[ZooKeeper数据库以及日志文件](数据库以及日志文件.md)

