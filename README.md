
**weixin_rebot** 用Python实现的一个web微信机器人。

## web微信Api
```
1. api: https://login.weixin.qq.com/jslogin
2. method: post
3. params: appid: //应用ID, 值为wxeb7ec651dd0aefa9,表示"微信网页版"
           fun: new //应用类型, 固定为new
           lang: zh_CN //语言, 表示中文
           _:  //时间戳
4. 返回值: window.QRLogin.code = 200; window.QRLogin.uuid = "xxx"
```
