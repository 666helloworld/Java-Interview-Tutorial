> 全是干货的技术号：
> 本文已收录在github，欢迎 star/fork：
> https://github.com/Wasabi1234/Java-Interview-Tutorial


关系键是关系数据库的重要组成部分。关系键是一个表中的一个或几个属性，用来标识该表的每一行或与另一个表产生联系。 其中就包括外键
# 1 主键（primary key或unique key）
又称主码，数据库表中对储存数据对象予以唯一和完整标识的数据列或属性的组合。一个数据列只能有一个主键，且主键的取值不能缺失，即不能为null。

技术角度看，primary key和unique key有相似之处。但还是有差异：
- 作为primary key的域／域组不能为null；而unique key可以
- 在一个表中只能有一个primary key，而多个unique key可以同时存在
- 更大的区别在逻辑设计上。primary key一般在逻辑设计中用作记录标识，这也是设置primary key的本来用意。而unique key只是为了保证域／域组的唯一性

# 2 外键（foreign key）
又称外部键。在关系数据库中，每个数据表都是由关系来连系彼此的关系，父数据表（Parent Entity）的主键（primary key）会放在另一个数据表，当做属性以创建彼此的关系，而这个属性就是外键。

比如，学生跟老师之间是教学关系，学生数据表会有个属性叫指导老师（FK），而这个值就是对应到老师数据表的老师代号（PK），学生的指导老师就是外键。

注意 : 外键不一定要与相应主键同名，只是在应用中为便于识别，当主键与相应外键属于不同关系时，往往取同名

## 作用
保持数据一致性，完整性，主要目的是控制存储在外键表中的数据。 使两张表形成关联，外键只能引用外表中的列的值或使用空值。

## 案例

如果不使用外键，表2的学号字段插了一个值（比如20140999999），但该值在表1中并没有。这时，数据库允许插入，并不会对插入的数据做关系检查。
然而在设置外键时，你插入表2学号字段的值必须要求在表1的学号字段能找到。 同时，如果你要删除表1的某个学号字段，必须保证表2中没有引用该字段值的列，否则就没法删除。这就是所谓的保持数据的一致性和完整性。
如果表2还引用表1的某个学号，你却把表1中的这个学号删了，表2就不知道这个学号对应的学生是哪个学生。

![](https://img-service.csdnimg.cn/img_convert/e73f0068e9903357fa4b22791bb3ae19.png)

![](https://img-blog.csdnimg.cn/20200825235213822.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzMzNTg5NTEw,size_1,color_FFFFFF,t_70#pic_center)