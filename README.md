# 生成订单



{% embed url="http://xxx.com/bank\_cashier?mchid=商户号&total\_fee=金额&out\_trade\_no=订单号&notify\_url=异步通知url。" %}

同步请求

请求方式:get

| 字段名称 | 字段类型 | 必填参数 | 说明 |
| :--- | :--- | :--- | :--- |
| mchid | string | Y | 商户号 |
| total\_fee | int | Y | 金额。单位：分 |
| out\_trade\_no | string | Y | 用户端自主生成的订单号 |
| notify\_url | string | Y | 异步通知url |



