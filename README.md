## 经纬恒润面试

### 个人介绍

各位面试官你们好，很高兴得到这次面试机会。我叫岳翔宇，毕业于辽宁大学，所学专业为软件工程。我应聘的岗位是软件测试实习生。我了解软件测试的基本理论，熟悉软件测试的流程，并使用Golang语言仿做过的两个小项目，开发过程中我使用 Apipost 对部分功能模块进行接口测试，保证该模块能够正常运行。并通过写一些简单的测试用例对这些模块进行测试，并记录到测试报告文档中。同时，我还熟练掌握SQL语句，能够使用SQL语句对数据库进行增删查改等操作。我有在软件测试行业进行长期发展的意愿，也渴望在实习中学习更多的实践知识，希望贵公司能给我一个进入公司实习工作的机会，我的个人介绍完毕了，谢谢!


#### 1.软件测试是什么？
软件测试是为了发现程序中存在的代码或者业务逻辑错误，它检验软件产品是否符合用户需求，提高用户体验。
- 禅道里面缺陷处理的基本流程是：测试提交bug => 开发解决bug => 测试验证bug => 测试关闭bug
- 软件开发的生命周期：需求分析——开发计划——设计——编码——测试——运行维护  
- 软件测试的生命周期（软件开发的流程）：需求分析——测试计划——测试设计/开发——测试执行——报告评估

#### 2.软件测试的流程
1.分析测试需求
2.制定测试计划
3.设计测试用例
4.执行测试
5.编写测试报告

#### 3.软件测试的分类
按开发阶段分：单元测试、集成测试、系统测试、验收测试（正式验收测试、Alpha测试、Beta测试）
按测试技术分：白盒测试、黑盒测试、灰盒测试
按测试对象是否运行划分：动态测试、静态测试
按测试手段分：手工测试、自动化测试
按测试包含的内容划分：功能测试、安全测试、兼容性测试、易用性测试、性能测试、压力测试、负载测试、回复测试

#### 4.测试用例怎么写？
1、明确需求文档，根据需求文档来编写测试用例
2、根据项目模块特点，选择合适的用例设计方法。常用设计方法有等价类划分法、边界值法、因果图、判定表、正交表、错误推断法、场景法等。

####  5.测试用例包括哪些元素？
包括用例id、项目/模块、前置条件、测试项、测试环境、操作步骤、数据、预期输出、实际输出、重要程度、是否通过、备注等。

#### 6.什么是压力测试？它的流程是什么样的？
压力测试也叫性能测试，是针对系统的性能指标建立性能测试模型，制定性能测试方案，在场景条件执行执行性能场景，分析判断性能瓶颈并调优，最终得出性能结果来评估系统的性能指标是否满足既定值。
流程：1.对他压力测试的场景及用户行为进行收集；2.制定测试方案，根据需求确定测试场景、测试点和估算相关指标；3.制定测试计划；4.执行测试；5.性能调优；6.编写测试报告

#### 接口测试的请求方式
1.`get`：向特定资源发出请求（请求指定页面信息，并返回实体主体）
2.`post`：向指定资源提交数据进行处理请求（提交表单，上传文件），又可能导致新的资源资源的建立或原有资源的修改
3.`put`：向指定资源位置上上传其最新内容（从客户端向服务器传送的数据取代指定文档的内容）
4.`head`：与服务器索与get请求一致的响应，响应体不回返回，获取包含在小信息头中的原有信息（与get请求类似，返回的响应中没有具体内容，用于获取报头）
5.`delete`：请求服务器删除request-url所表示的资源（如：请求服务器删除页面）

#### 0.什么是索引？

索引是一种单独的、物理的对数据库表中一列或多列的值进行排序的一种存储结构,它是一种特殊的数据结构，通过提供指向存储在表指定列中的数据的指针，加快查询数据的效率。

#### 0.什么是事务？事务的特征？

事务：是数据库中一个单独的执行单元，它可以由一条语句组成，也可以由多条语句组成。它是一个整体，要么全部执行，要么全部不执行，是不可分割的工作单元。事务的四大特性：原子性（不可分割）、一致性（数据完整性保持一致）、隔离性（彼此独立）、持续性（永久改变）

#### 9.什么是sql注入？如何防止sql注入？

sql注入：通过把SQL命令插入到Web表单提交或输入域名或页面请求的查询字符串，最终达到欺骗服务器
执行恶意的SQL命令。
防止sql注入的措施：
1.C# 的MVC框架使用Filter过滤Action参数防止sql注入
2.严格区分用户权限
3.过滤参数中含有的一些数据库关键词(关键词过滤、敏感词过滤)
4.确认每种数据的类型，比如是数字，数据库则必须使用int类型来存储
5.强化参数化语句

#### 1.面向对象的三大特征？
`封装`：封装就是把对象的属性和方法封装到一个类中，对外隐藏内部细节，只给外界暴漏它的访问方法。
`继承`：继承是从已有的类中派生出新的类，新的类能吸收已有类的数据属性和行为，并能扩展新的能力。
`多态`：多态就是对同一个父类或接口，使用不同的实例而执行不同操作。

#### 2.SQL语句中增删查改都用什么命令？
增加- insert       insert into table value ( )
删除-delete
查询-select
修改-update

DDL 数据定义语言 CREATE DROP ALTER
DML 数据操作语言 INSERT UPDATE DELETE
DQL 数据查询语言 SELECT
DCL 数据控制语言 GRANT REVOKE COMMIT ROLLBACK

#### 3.C 语言的关键字 static 和 C++ 的关键字 static 有什么区别  ？
在 C 中 static 用来修饰局部静态变量和外部静态变量、函数。
C++中除了上述功能外，还用来定义类的成员变量和函数。即静态成员和静态成员函数。

#### 4.Ｃ中的 malloc 和Ｃ＋＋中的 new 有什么区别
malloc 和 new 有以下不同：
（1） new是操作符，可以重载，只能在 C++中使用。
（2） malloc是函数，可以覆盖，C、C++中都可以使用。
（3） new返回的是某种数据类型指针，malloc返回的是空指针。
（5） new 可以调用对象的构造函数，对应的 delete 调用相应的析构函数。
（4） malloc 仅仅分配内存，free 仅仅回收内存，并不执行构造和析构函数
注意：malloc 申请的内存空间要用 free 释放，而 new 申请的内存空间要用 delete 释放。因为两者实现的机理不同。

#### 5.如何避免“野指针”
“野指针”产生原因及解决办法如下：
（1） 指针变量声明时没有被初始化。解决办法：指针声明时初始化，可以是具体的地址值，也可让它指向 NULL。
（2） 指针 p 被 释放(free) 或者 删除(delete) 之后，没有置为 NULL。解决办法：指针指向的内存空间被释放后指针应该指向 NULL。
（3） 指针操作超越了变量的作用范围。解决办法：在变量的作用域结束前释放掉变量的地址空间并且让指针指向 NULL。

#### 6.常引用有什么作用
常引用的引入主要是为了避免使用变量的引用时，在不知情的情况下改变变量的值。


#### 7.计算机网络模型
`OSI七层模型`：物理层、数据链路层、网络层、传输层、会话层、表示层、应用层
`TCP/IP四层模型`：网络接口层、网际层、传输层、应用层
（其中网络接口层包括物理层和数据链路层）

#### 8.TCP和UDP的区别
-   TCP 面向连接提供可靠的服务，UDP 是无连接的，即发送数据之前不需要建立连接.UDP 尽最大努力交付，即不保证可靠交付。   
-   UDP 工作效率比 TCP 高，具有较好的实时性，   
-   每一条 TCP 连接只能是一对一的，UDP 支持一对一，一对多，多对一和多对多的交互通信。    
-   UDP 分组首部开销小，TCP 首部开销 20 字节，UDP 的首部开销小，只有 8 个字节。   
-   TCP 面向字节流，实际上是 TCP 把数据看成一连串无结构的字节流，UDP 是面向报文的一次交付一个完整的报文，报文不可分割，报文是 UDP 数据报处理的最小单位。    
-   UDP 适合一次性传输较小数据的网络应用，如 DNS，SNMP 等。

#### 9.HTTP和HTTPS的基本概念

HTTP：是从万维网服务器传输超文本到本地浏览器的一种网络传输协议，是客户端和服务器端请求和应答的标准（TCP），它可以使浏览器更加高效，使网络传输减少。

HTTPS：在HTTP协议的基础上下加入SSL层，因此加密的详细内容就需要SSL，是HTTP的安全版，。

#### 9.操作系统（大概率线程、进程、协程）
进程和线程的区别？
①首先，对于操作系统而言，线程是最小的执行单元，进程是最小的资源管理单元。
②每个进程都有独立的地址空间，一个进程崩溃不影响其它进程。一个进程中的多个线程共享该进程的地址空间，一个线程的非法操作会使整个进程崩溃。
③进程之间的切换开销较大，线程之间的切换开销较小。

`进程`：进程是一个具有一定独立功能的程序.关于某个数据集合上的一次运行活动，是系统资源分配和独立运行的最小单位.
`线程`：线程是进程的一个执行单元，是任务调度和系统执行的最小单位；
`协程`：协程是一种用户态的轻量级线程，协程的调度完全由用户控制。

#### 10.三次握手和四次挥手
1、第一次握手：客户端给服务器发送一个 SYN 报文。    
2、第二次握手：服务器收到 SYN 报文之后，会应答一个 SYN+ACK 报文。  
3、第三次握手：客户端收到 SYN+ACK 报文之后，会回应一个 ACK 报文。    
4、服务器收到 ACK 报文之后，三次握手建立完成。

1、第一次挥手：客户端发送一个 FIN 报文，报文中会指定一个序列号。此时客户端处于FIN_WAIT1状态。  
2、第二次握手：服务端收到 FIN 之后，会发送 ACK 报文，且把客户端的序列号值 + 1 作为 ACK 报文的序列号值，表明已经收到客户端的报文了，此时服务端处于 CLOSE_WAIT状态。    
3、第三次挥手：如果服务端也想断开连接了，和客户端的第一次挥手一样，发给 FIN 报文，且指定一个序列号。此时服务端处于 LAST_ACK 的状态。    
4、第四次挥手：客户端收到 FIN 之后，一样发送一个 ACK 报文作为应答，且把服务端的序列号值 + 1 作为自己 ACK 报文的序列号值，此时客户端处于 TIME_WAIT 状态。需要过一阵子以确保服务端收到自己的 ACK 报文之后才会进入 CLOSED 状态  
5、服务端收到 ACK 报文之后，就处于关闭连接了，处于 CLOSED 状态。
