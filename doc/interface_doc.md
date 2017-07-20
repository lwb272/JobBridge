## login.html
1. url: /login.do
2. 请求方法: get
3. 数据类型: json
4. 客户端->服务端（CS）
```json
	{
	    "type":"stu",
		"userName": "何干事",
		"password": "123456"
	}
```
5. 服务端->客户端（SC）
```json
    {
        "ok": true
    }
```
```json
    {
        "ok": false,
        "reason": "email/userName"
    }
```


----

## register.html
1. url: /register.do
2. 请求方法: get
3. 数据类型: json
4. CS
```json
	{   "type":"enterprise",
		"userName": "何干事",
		"email": "666666666@qq.com",
		"password": "123456"
	}
```
5. SC
```json
    {
        "ok": true
    }
```

```json
    {
        "ok": false,
        "reason": "email/userName" 
    }
    
```
