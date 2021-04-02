### MySQL截取字符串

1、从左边第index开始截取

```sql
left(str,index)
```

2、从右边第index开始截取

```sql
right(str,index)
```

3、当index>0从左边开始截取直到结束  当index<0从右边开始截取直到结束 当index=0返回空

```sql
substring(str,index)
```

4、 截取str,从index开始，截取len长度

```sql
substring(str,index,len)
```

5、str是要截取的字符串，delim是截取的字段（根据此字段进行截取） ，count是从哪里开始截取(为0则是左边第0个开始，1从左边开始第一个选取左边的，-1从右边第一个开始选取右边的。特殊情况，字符串中没有指定的字符，则返回原字符串(index=0时候例外)

```sql
substring_index(str,delim,count)
```

6、截取时间，时间（天）减去后面的day

```sql
subdate(date,day)
```

7、时分秒expr1-expr2

```sql
subtime(expr1,expr2)
```







