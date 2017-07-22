## stulogin.js
1. url: /login/student
2. 请求方法: post
3. 数据类型: json
4. 客户端->服务端（CS）
```json
	{
		"userName": "何干事",
		"passWord": "123456"
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

## register.js
1. url: /register/student
2. 请求方法: post
3. 数据类型: json
4. CS
```json
	{   
		"userName": "何干事",
		"password1": "123456"，
		"email": "666666666@qq.com",
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

## admregist.js
1. url: /register/admin
2. 请求方法: post
3. 数据类型: json
4. CS
```json
	{   
		"userName": "admin",
		"password": "123456"，
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
## admlogin.js
1. url: /login/admin
2. 请求方法: post
3. 数据类型: json
4. CS
```json
	{   
		"userName": "admin",
		"password": "123456"，
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
## comlogin.js
1. url: /login/enterprise
2. 请求方法: post
3. 数据类型: json
4. CS
```json
	{   
		"userName": "tencent123",
		"password": "123456"，
		"email": "666666666@qq.com",
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
## comregist.js
1. url: /register/enterprise
2. 请求方法: post
3. 数据类型: json
4. CS
```json
	{   
		userName: "tencent123",
                password: "123456",
                name: "腾讯公司"
                mailbox: "tencent@qq.com",
                phoneNum: "400-123-123-456",
                enterpriseIntroduction: "腾讯公司是中国的伟大公司",
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
