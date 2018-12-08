## Mysql相关知识学习整理

+ 存储引擎
+ 索引
+ 配置文件
+ 逻辑架构

---
##### 1.Mysql常用存储引擎有哪些？
    MyISAM和InnoDB
##### 2.Mysql逻辑架构？
    连接层、服务层、引擎层、存储层
##### 3.Mysql索引分类？
    单值索引、唯一索引、复合索引
##### 4.Mysql索引结构？
    BTree、Hash、full-text、R-Tree
##### 5.你对Mysql索引的认识？
    索引是一个数据结构，可以帮助mysql高效获取数据。
##### 6.创建索引sql的语句？
    CREATE [UNIQUE] INDEX indexName ON tableName (columnName*)
##### 7.mysql的explain有啥用？
    使用EXPLAIN关键字可以模拟优化器执行SQL语句，查看MySQL是如何处理你的SQL语句的，分析你的查询语句或是结构的性能瓶颈。
##### 8.什么是覆盖索引？
    索引和查询的select字段重叠
##### 9.Mysql索引失效的情况有哪些？
    
##### 10.Mysql索引优化?

