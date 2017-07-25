# wxapi

#### 相关接口及收费价格如下：付费方式详情见 pay.md

##### 0) 公众号文章，阅读数，点赞数更新接口

```
接口描述：详情见 api0.md

支持订阅号与服务号，当公众号更新文章后，在一天左右通知，且会更新文章在第一天，第三天的阅读点赞数。

目前支持两种通知方式：
1.主动回调客户提供的接口
2.客户主动调用接口查询最近有更新的文章数据

建议使用第一种方式，第二种可作为辅助使用。

须知：
第二次更新文章阅读数与点赞数时，由于随机延时，实际更新间隔可能在第3-4天左右
```

##### 1) 公众号即时更新接口， 一个公众号 0.02¥／天

```
接口描述：详情见 api1.md

仅支持订阅号，当公众号更新图文消息时，半小时内通知客户。

目前支持两种通知方式：
1.主动回调客户提供的接口
2.客户主动调用接口查询最近有更新的公众号列表

建议使用第一种方式，第二种可作为辅助使用。

须知：
对于个别公众号延时偶尔超过半小时属于正常现象。
```

##### 2) 文章临时链接转永久链接／短链接转长链接，一次0.005¥，详情见 api2.md

##### 3) 获取公众账号信息，如根据account获取账号信息， 一次0.03¥，详情见 api3.md

##### 4) 实时获取文章阅读点赞数， 一次0.05¥，详情见 api4.md

##### 5) 批量获取公众号历史文章以及点赞阅读数据，单公众号价格：20＋文章数＊0.15

///////////////////////////////////////////////////////////

所有接口均可先免费试用，满意后再付费使用。

如有其它接口需求，可定制开发。

#### 联系QQ：1628121385，添加好友时请注明：wxapi
