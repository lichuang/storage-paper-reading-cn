# 存储（分布式、存储引擎等）领域论文阅读笔记索引

本人当前工作方向集中在分布式、存储引擎等领域，在这个项目中将记录这个方向自己已经阅读的论文解析博客文章索引，以及记录待阅读论文（Todo是程序员说过最大的谎言：）。



# 分布式



## 一致性模型

* [《Time, Clocks, and the Ordering of Events in a Distributed System》](./pdf/distributed/consistencymodel/time-clocks.pdf)：[周刊（第21期）：Lamport时钟介绍 - codedump的网络日志](https://www.codedump.info/post/20220703-weekly-21/)
* 顺序一致性论文《[How to Make a Multiprocessor Computer That Correctly Executes Multiprocess Progranm](./pdf/distributed/consistencymodel/How-to-Make-a-Multiprocessor-Computer-That-Correctly-Executes-Multiprocess-Programs.pdf)》：[周刊（第22期）：图解一致性模型 - codedump的网络日志](https://www.codedump.info/post/20220710-weekly-22/)
* 线性一致性论文[Linearizability: A Correctness Condition for Concurrent Objects](./pdf/distributed/consistencymodel/p463-herlihy.pdf)：[周刊（第22期）：图解一致性模型 - codedump的网络日志](https://www.codedump.info/post/20220710-weekly-22/)



## 一致性算法

### Raft

* [《Consensus: Bridging Theory and Practice》](./pdf/distributed/raft/OngaroPhD.pdf)
  * [Raft算法原理 - codedump的网络日志](https://www.codedump.info/post/20180921-raft/)
  * [为什么Raft协议不能提交之前任期的日志？ - codedump的网络日志](https://www.codedump.info/post/20211011-raft-propose-prev-term/)
  * [周刊（第13期）：重读Raft论文中的集群成员变更算法（一）：理论篇 - codedump的网络日志](https://www.codedump.info/post/20220417-weekly-13/)



# 存储引擎

### 错误恢复

* [《ARIES: A Transaction Recovery Method Supporting Fine-Franularity Locking and Partial Rollbacks Using Write-Ahead Logging》](./pdf/storageengine/misc/aries.pdf)
  * [周刊（第15期）：图解ARIES论文（上） - codedump的网络日志](https://www.codedump.info/post/20220514-weekly-15/)
  * [周刊（第16期）：图解ARIES论文（下） - codedump的网络日志](https://www.codedump.info/post/20220521-weekly-16/)

### Blink-Tree

* [《Efficient Locking for Concurrent Operations on B-Trees 》](./pdf/storageengine/blinktree/Efficient Locking for Concurrent Operations on B-Trees.pdf):[周刊（第23期）：图解Blink-Tree：B+Tree的一种并发优化结构和算法 - codedump的网络日志](https://www.codedump.info/post/20220807-weekly-23/)

# Todo

* [Amazon DynamoDB: A Scalable, Predictably Performant, and Fully Managed NoSQL Database Service](https://assets.amazon.science/33/9d/b77f13fe49a798ece85cf3f9be6d/amazon-dynamodb-a-scalable-predictably-performant-and-fully-managed-nosql-database-service.pdf)
* [Building a Bw-Tree Takes More Than Just Buzz Words](http://www.cs.cmu.edu/~huanche1/publications/open_bwtree.pdf)





