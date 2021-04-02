### 保留两位小数

**1、format格式化**

```sql
 SELECT FORMAT(11541515.1156565,2)
```

结果 -> 11,541,515.12 

用format格式化的缺点就是超过1000的会自动加“，”，在函数或者代码中二次处理是使用数据容易出错（类型转换错误）

**2、四舍五入法** 

```sql
select round(4545.1366,2);
```

结果 ->4545.14

**3、截取** 

```sql
select truncate(4545.1366,2)
```

结果 ->4545.13

### 取整

**1、CONVERT转型**

```sql
SELECT CONVERT(41515.1156565,DECIMAL)
```

结果-> 41515

**2、CEILING 取整**

```sql
select CEILING(4545.1366)
```

结果->4546

**3、floor 截取**

```sql
select floor(5.6);
```

结果->5



**cast()用法**

```sql
 select cast(55.55555 as decimal(10,2)) 
```

结果->55.56

```sql
Cast(字段名 as 转换的类型 )，其中类型可以为：
CHAR[(N)] 字符型 
DATE  日期型
DATETIME  日期和时间型
DECIMAL  float型
SIGNED  int
TIME  时间型
```













