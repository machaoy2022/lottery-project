# lottery-project

抽奖请求进来，经过网关用户鉴权后，解析用户请求后转发到抽奖服务，完成抽奖逻辑实现。使用Redis做抽奖资格过滤、奖品预扣，进一步减轻数据库压力。

![1712883110200](assets/lottery_framework.png)
