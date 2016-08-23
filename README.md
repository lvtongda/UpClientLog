### UpClientLog

又拍云后台日志下载列表拉取工具

#### 功能

**2016-08-22**

* 支持某天某个服务名下某个域名日志列表拉取
* 支持多天某个服务名下某个域名日志列表拉取

#### 使用

运行 `getlog.py` 程序

```
$ python getlog.py access_token date bucket_name domain
```

参数说明

```
access_token    必填，验证信息，需要联系又拍云获取，如：4edfeeb3-97b9-4330-b44f-83e2492b66e3
date            必填，要拉取哪些天的日志列表，多天或单天，如：2016-08-20~2016-08-22 或 2016-08-20
bucket_name     必填，要拉取日志的服务名，如：testbucket
domain          选填，要拉取日志的域名，不填，拉取默认域名的日志列表。
```

#### Todo

* 支持账号下所有日志下载列表拉取
* 支持某个服务名下所有日志列表拉取