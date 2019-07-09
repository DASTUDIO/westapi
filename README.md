# 西部数码业务接口

### 配置

username和password

PS:注意这个password是api的password而不是登录密码,这个API密码需要用户是代理级别才有,如果没有[官网](http://west.cn)可以申请.

example:

```python
username = 'xiaoming'
passowrd = 'myPassword'
```

### 使用

示例：

查询余额

```python
check_balance()
```
注册域名

```python
register_domain('iamreallyrich.com',1,712)
```


更多功能移步[注释](https://github.com/DASTUDIO/westapi/blob/master/westapi.py)
