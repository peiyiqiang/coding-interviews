### 笔试（0910）

##### 1、

> **题目描述**
>
> 小B是公司的Java工程师，现有一个有关应用程序部署的任务如下：  
> (1)一台服务器的磁盘空间、内存是固定的，现在有M个应用程序需要部署；  
> (2)每个应用程序所需要的磁盘、内存不同，每个应用程序允许访问的用户数也不同，且同一个应用程序不能在一台服务器上部署多个。  
> 请设计算法协助小B决策，对于一台服务器而言，如何组合部署应用程序能够使得单台服务器允许访问的用户数最多？
>
> **输入描述**
>
> 输入包括三个参数，以空格分隔，分别表示服务器的磁盘大小、内存大小，以及应用程序列表；  
> 其中第三个参数即应用程序列表，表达方式为：  
> 多个应用程序信息之间用'#'分隔，每个应用程序的信息包括','分隔的部署所需磁盘空间、内存、允许访问的用户量三个数字；比如10, 10, 5000表示部署该应用程序需要10G磁盘空间，10G内存，允许访问的用户数是5000
>
> **输出描述**
>
> 单台服务器能承载的最大用户数和承载最大用户数时的内存利用率和磁盘利用率，多个结果之间用英文的逗号分隔。
>
> **方法签名定义**
>
> public static String calLoad(String param)
>
> **示例输入**
>
> 15 10 5,1,1000#2,3,3000#5,2,15000#10,4,16000
>
> **示例输出**
>
> 31000,100%,60%

##### 2、

> **题目描述**
>
> 请用Java泛型实现快速排序算法，能对输入实现逆序的排序效果。
>
> 要求：  
> a.自行定义方法签名，需用Java泛型来支持不同类型的数据排序。  
> b.代码中不允许使用JDK自带的排序功能，如Arrays.sort(), Collections.sort()等方法和排序类数据结构（如TreeSet）。

##### 3、

> **题目描述**
>
> 现有一个n行n列的字符矩阵，我们将其放置于直角坐标系的第二象限中。假设x, y坐标轴均为镜面，请输出镜面反射后的结果。
>
> **方法签名**
>
> List\<List\<String\>\> mirror (List\<List\<String\>\> data) {}
>



### 一面（60min）

##### 1、输入网址得到页面展示的流程

##### 2、DNS解析具体过程

##### 3、TCP四次挥手

##### 4、TCP怎么保证可靠性

##### 5、拥塞控制和流量控制怎么保证TCP可靠性的

##### 6、TCP/IP网络分层

##### 7、怎么区分内网IP和外网IP

##### 8、进程和线程的区别

##### 9、什么情况下会发生死锁

##### 10、出现死锁时怎么检测

##### 11、数据库三范式

##### 12、MySQL数据库索引的实现方式

##### 13、Hash索引和B+树索引的区别

##### 14、数据库索引为什么用B+树不用其他的二叉树

##### 15、为什么B+树可以进行范围检索

##### 16、Java基本数据结构及占用的字节数

##### 17、Java创建线程的方式

##### 18、不同的创建方式有什么区别

##### 19、介绍一下反射机制

##### 20、JVM的内存回收过程

##### 21、Full GC时会发生什么

##### 22、逻辑题

> 怎么用一个9升的桶和一个4升的桶量出6升的水

##### 23、算法题

> 单向链表节点两两交换，1->2->3->4->5 变成 2->1->4->3->5



### 二面（60min）

##### 1、MySQL加索引时一般会加哪些类型的索引，会对哪些字段加

##### 2、Redis做缓存时常见的问题

##### 3、Redis主从结构，主服务器挂了怎么切换

##### 4、消息队列写和读的具体流程

##### 5、生产者发送消息时超时了

##### 6、线程安全和非线程安全的集合分别有什么

##### 7、HashMap怎么保证线程安全

##### 8、操作int类型实现计数器，怎么保证线程安全

##### 9、TCP和UDP的区别

##### 10、TCP粘包和拆包问题的原因和解决方案

##### 11、HTTP是怎么解决粘包的

##### 12、cookie和session的区别和联系

##### 13、第三方通过盗取cookie冒充身份去操作，怎么办

##### 14、算法题

> 把字符串中非数值类型的去点，反转这个数值并输出
>
> a1b.23 --> 32.1  
> 1.2.3 --> 报错  
> 100 --> 1



