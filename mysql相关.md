## MySql

#### mysql引擎：
   1. MyIsam  MyIsam为MySQL默认存储引擎，不支持行级锁，不支持事务，读取速度很快，写入较慢。
   2. InnoDB  InnoDB是一个事务型的存储引擎，锁粒度比较小，有行级锁定和外键约束；支持事务（ACID）。
   3. Memory
   4. Blackhole
   5. CSV
   6. Performance_Schema
   7. Archive
   8. Federated
   9 Mrg_Myisam
#### mysql中innodb事务隔离级别:
隔离级别|脏读|不可重复读|幻读
--|:--:|--:|--:
未提交读|可能|可能|可能
已提交读|不可能|可能|可能
可重复读|不可能|不可能|可能
序列化|不可能|不可能|不可能

#### mysql索引：
  - 单一索引：
  
  - 聚合索引：
  
  - 主键索引：
  
  索引底层实现：
    - hash
    - B+树
    - 红黑树
    - 二叉树
#### mysql防止sql注入：


#### mysql sql优化


