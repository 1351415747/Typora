1、修改本地hosts文件，目标路径

```
C:\Windows\System32\drivers\etc
```

2、访问网址，获取IP地址

```
http://github.com.ipaddress.com/
```

3、分别输入

```
github.com
github.global.ssl.fastly.net
```

4、获取对应的IP地址

```
140.82.113.4
199.232.69.194
```

5、修改hosts文件,增加两行即可

```
github.com 140.82.113.4
github.global.ssl.fastly.net 199.232.69.194
```

