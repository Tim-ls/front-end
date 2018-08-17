# front end

## last week(7.24~7.30)

- add ab test
- add hint when lock tote
  -  确认下单的提醒
- fix some bugs

## current week(7.31~8.3)

- add closet report statistics
  - 各种需要筛选条件、router 信息
- add ab test
  -  新用户是否走芝麻信用，支付成功的流程。
- refactoring pay
  -  重构购买支付，待付款的支付
- 购买衣服提示
- 当衣服购买之后，会有已购买的提示
- fix some bugs

## 想法

- 上线一个星期两次是不是太频繁了
- ci => docker

## ---------------------------------------------------

## 8.7 ~ 8.13

- 评价有礼

```
 在活动期内，评价衣箱送5元奖励金
```

- 统计的一些 bug

- 删除了一些无用的 restful api

- 衣箱个状态的 UI 优化

## 8.14 ~ 8.21

- 实现 499 A/B 测试 50 元红包

```
  原始版本：现状
  试验版本：验证芝麻成功后送50元红包（如果用户已有优惠券， 就不展示红包
```

+ 去除已经无用的AB测试的代码
