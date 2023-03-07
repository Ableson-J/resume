 <center>
     <h1>姜来明简历</h1>
     <div>
         <span>
             <img src="assets/phone-solid.svg" width="18px">
             18290272187
         </span>
         ·
         <span>
             <img src="assets/envelope-solid.svg" width="18px">
             846405397@qq.com
         </span>
     </div>
</center>
 ## <img src="assets/info-circle-solid.svg" width="30px"> 个人信息 

 - 性别：男
 - 微信：18290272187
 - 求职意向：c++ 后端开发工程师

## <img src="assets/graduation-cap-solid.svg" width="30px"> 教育经历

- 重庆大学             2021.9 ~ 至今           软件工程             硕士研究生
- 重庆交通大学      2015.9 ~ 2019.6       机械电子工程      本科

## <img src="assets/project-diagram-solid.svg" width="30px"> 项目经历

- **Web Server项目**  基于 C++ 开发的支持 GET 和 POST 请求的 web 服务器
  * 使用 **线程池 + 非阻塞 socket + epoll + 事件处理( Reactor 和模拟 Proactor 均实现)** 的并发模型；
  * 使用**状态机**解析HTTP请求报文，支持解析 **GET 和 POST **请求；
  * 实现 web 端用户**注册、登录**功能，使用**数据库连接池**实现数据库访问，可以请求服务器**图片和视频文件**；
  * 实现**同步/异步**日志系统，记录服务器运行状态；
  * 使用 Webbench 压力测试可以实现**上万并发连接 **数据交换。
- **CMU15-445**   基于 C++ 开发的支持简单 SQL 操作的单机数据库
  * 底层基于 **LRU** 设计了 BufferPool，所有 page 操作在 BufferPool 上进行。同时在 BufferPool 实现了**可扩展哈希表**；
  * 语句执行采用**火山模型**，支持 SELECT，DELETE，UPDATE，JOIN，AGGREGATION，LIMIT，DISTINCT 操作。Join 有 Nested Loop Join 和 Hash Join 两种实现；
  * 并发控制采用 **2PL** 设计，实现 RU, RC, RR 3种隔离级别；
  * 实现全局的 Lock Manager 管理 R/W 锁，死锁处理是基于死锁预防中的 **wound-wait** 算法。
- **MIT 6.824**   基于Go开发的分布式 KV 数据库
  * 开发了**Raft** 模块，支持 **Leader 选举，日志复制，Snapshot **等基础功能；
  * 在实现Raft模块的基础上，实现一个 KV 数据库。采用 **Multi-Raft 架构，支持数据分片**，每一个分片属于一个 Raft Group，支持分片迁移。数据库分为两部分：
    * shardctrler Raft Group：负责集群配置管理服务。
    * shardkv Raft Groups：负责数据的读、写和持久化以及分片的迁移。

## <img src="assets/tools-solid.svg" width="30px"> 技能清单

- 熟悉**C++**编程语言，熟悉STL下常见容器，了解Python、SQL等；
- 熟悉Linux下**I/O复用技术**，能够利用Socket套接字进行网络编程；
- 熟悉网络分层模型，熟悉HTTP、TCP/UDP、IP等常见协议；
- 通过了英语六级(CET-6)，具备良好英语能力。

## <img src="assets/briefcase-solid.svg" width="30px"> 个人荣誉

  - 重庆大学优秀研究生
  - 重庆大学A类学业奖学金
  - 重庆交通大学优秀毕业生