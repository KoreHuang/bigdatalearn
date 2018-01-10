### Hive的组成以及各功能部件

***

#### 1.什么是Hive
    
     * Hive是一个数据仓库基础工具，在Hadoop中用来处理结构化数据。提供简单的sql查询功能，
    可以将sql语句转换为MapReduce任务进行运行
    
#### 2.Hive特点

* 存储架构在一个数据库当中，并处理数据到HDFS
* 为OLAP(联机扥洗处理)而设计  <参见笔记OLAP>
* 提供SQL类型的语言查询称为HQL或HiveQL
* 熟知、快速、可扩展性高

#### 3.Hive的架构组件
    
    

    单元名称 | 操作
        ---|---
    用户接口界面 | Hive是一个数据仓库基础工具软件，可以创建用户和HDFS之间互动。用户界面，Hive支持是Hive的Web UI，Hive命令行，HiveHD洞察
    元存储| Hive是一个数据仓库基础工具软件，可以创建用户和HDFS之间互动。用户界面，Hive支持是Hive的Web UI，Hive命令行，HiveHD洞察
    HiveQL处理引擎 | HiveQL类似于SQL的查询上Metastore模式信息。这是传统的方式进行MapReduce程序的替代品之一。相反，使用Java编写的MapReduce程序，可以编写为MapReduce工作，并处理它的查询。
    执行引擎 | HiveQL处理引擎和MapReduce的结合部分是由Hive执行引擎。执行引擎处理查询并产生结果和MapReduce的结果一样。它采用MapReduce方法。
    HDFS或HBASE | Hadoop的分布式文件系统或者HBASE数据存储技术是用于将数据存储到文件系统。


