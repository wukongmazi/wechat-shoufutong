# 微信电商收付通系统

https://mp.weixin.qq.com/s/nv6eOxufbe3PW8ZNDJDb5w


![Image text](https://img-blog.csdnimg.cn/4dcad2dece454029b1f588c1deee4468.png)

#### 介绍
说正题前还是要再介绍一下电商收付通，微信电商收付通可谓是电商行业场景的一把利器，是微信专门为电商平台打造的一站式支付解决方案。

二级商户进件成功签约效果

![Image text](https://img-blog.csdnimg.cn/img_convert/da58f5fbb7dc3f304b653064a57edc59.png)

传统的电商平台都是在用户确认收货后再在一定的周期内结算给商户，就是采取平台先收款的方式，但这样不仅给电商平台带来税务的问题，还影响商户的资金安全。有了电商收付通，就不存在这样的问题了。

电商平台通过电商收付通提供的接口将商户进件为微信的二级商户，不仅支持个体工商户、企业等主体类型进件，还支持小微商户即无营业执照的个人商家进件。

有了商户号，平台就可以发起合单支付，就是将多商户（1- 50个二级商户）商品同时支付的场景（如电商购物车中的多笔订单合并支付），方便快捷。更绝的是交易资金是分别直接进入到各二级商户账户中并处于冻结状态，系统默认冻结180天。电商平台在满足业务流程条件下（如确认收货等），可将二级商户的冻结状态的资金解冻，并收取平台佣金。

![Image text](https://img-blog.csdnimg.cn/img_convert/19b557261dfaec58b89346eafe8598d0.png)
图片来自微信开发文档

你以为只有合单支付就没了吗，还有更高大上的分账功能。许多场景可以使用到，比如平台抽成，供应商分润，主播佣金，导购激励等都适用。传统的一般是采用汇总记账然后手动转账给对方，分账功能可以说解放了转账到手软的财务小姐姐的双手，哦，也可能是财务小哥哥，非常灵活。目前默认最高分账比例30%，如果场景需求大，可以申请提高比例。

![Image text](https://img-blog.csdnimg.cn/img_convert/a28508ec7083ac0f9f366ff1686648b4.png)
图片来自微信开发文档

现在来瞧瞧做好的进件二级商户的功能。

#### 二级商户进件

提交商户信息进件二级商户，可支持的主体类型丰富，满足大部分人的需求。

![Image text](https://img-blog.csdnimg.cn/img_convert/240a49634f4335f11d136f0f610a7891.png)

提交资料到微信审核通过后，是待签约的状态，扫码签约即可。

![Image text](https://img-blog.csdnimg.cn/img_convert/d0a6b47c2088ae6733fecb8c211ef4b2.png)

提交资料到微信审核失败后，是已驳回的状态，查看原因，按描述修改再次提交即可。

![Image text](https://img-blog.csdnimg.cn/img_convert/c4f7cefdac60084bf41f03f0d251aeb0.png)

签约通过后的状态是完成，完成状态意味着二级商户的商户号即可使用了。

![Image text](https://img-blog.csdnimg.cn/img_convert/04c4aa8d3502531be8a0b11aafb91ddf.png)

#### 合单支付

选择商户，然后点击合单支付，因为是pc端，所以做了扫码支付的体验，其他类型(APP、JSAPI、小程序、H5)支付都一样的。

![Image text](https://img-blog.csdnimg.cn/img_convert/e895d97aad08141120140eec3b31066d.png)

![Image text](https://img-blog.csdnimg.cn/img_convert/d6e2c309235011abd9dd86770f651db3.png)

微信电商收付通支付一站式解决方案其实还是给广大商户带来了很多的便捷，最明显的就是资金不再需要先结算到微信支付服务商那边，而是直接付给自己的商户号，还有分账等功能。

收付通在手，生意你有。

公众号后台回复【收付通】获取账号密码。

![Image text](https://img-blog.csdnimg.cn/101a73ed0228494786544af811382ace.png)

山水有相逢，来日皆可期，谢谢阅读，我们再会

我手中的金箍棒，上能通天，下能探海