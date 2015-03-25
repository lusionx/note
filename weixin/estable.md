# 微信公众号关注者

## 原始数据[doc](http://mp.weixin.qq.com/wiki/14/bb5031008f1494a59c6f71fa0f319c66.html)
* subscribe: int
* openid:  string
* nickname string
* sex: int {1:男, 2:女, 0:未知}
* city: string
* country: string
* province: string
* language: string
* headimgurl: string
* subcribe_time: datatime?int
* unionid: string 可选字段


----------


## 追加字段
* appid: string 公众号id
* groupid: [分组情况](http://mp.weixin.qq.com/wiki/0/56d992c605a97245eb7e617854b169fc.html)
* * id: int 
* * name: string
* idate: datatime 入库时间

x