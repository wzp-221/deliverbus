
# 校园快递Bus项目简介

校园快递Bus是一款基于大学校园的代领快递服务的微信小程序，是为了解决校园快递最后的几百米路程，使在校大学生在寝室就能够拿到自己的快递。通过使用这款微信小程序，在校大学生可以做到无需出寝室门，无需等待，即可快速，安全地拿到自己的快递。在使用中，在校大学生能够自由的选择领取快递的时间和地点，并且可以收到系统的实时派件通知。除此之外，代领快递的学生,能够获得一定的报酬，使得人力资源得到更好地利用。
## 扫如下二维码进行体验

![](https://user-gold-cdn.xitu.io/2020/7/10/17338fcf1adc8768?w=1074&h=1084&f=png&s=549835)
## 其他进入方式
进入微信 -> 点击“发现”菜单栏  ->   选择“小程序”选项  ->    点击右上角搜索     -> 输入关键字“快递Bus”进行搜索  ->    选择第一个微信小程序

## 用到的技术
- Laravel5.6
- easywechat
- 微信小程序
## 程序部分截图

![](https://user-gold-cdn.xitu.io/2020/7/10/17339287218f716a?w=356&h=616&f=png&s=67463)

![](https://user-gold-cdn.xitu.io/2020/7/10/1733928970c4b50e?w=360&h=608&f=png&s=38053)

![](https://user-gold-cdn.xitu.io/2020/7/10/1733928b1b1ffa1f?w=364&h=606&f=png&s=34926)

![](https://user-gold-cdn.xitu.io/2020/7/10/1733928c7229e015?w=374&h=586&f=png&s=72159)




## 应用简介
校园快递Bus是一款基于大学校园的代领快递服务的微信小程序，是为了解决校园快递最后的几百米路程，使在校大学生在寝室就能够拿到自己的快递。通过使用这款微信小程序，在校大学生可以做到无需出寝室门，无需等待，即可快速，安全地拿到自己的快递。在使用中，在校大学生能够自由的选择领取快递的时间和地点，并且可以收到系统的实时派件通知。除此之外，代领快递的学生,能够获得一定的报酬，使得人力资源得到更好地利用。
## 我们的优势 <br>
我们通过小程序搜索发现了有竞品，下面我们将介绍我们对比竞品的优势
- 我们运行速度更加快，用户体验程度好。
- 我们可以让用户自己赚取利润，实现了共享经济。
- bus制使我们的设计更加合理，更加节约时间和力气。

## 业务流程
我们便确定将系统分为用户模块、司机模块以及后台管理模块。其中用户模块的使用流程如下：开始->登录获取授权->进入首页->选票上车->填写信息->确认金额->支付->获取发车状态至结束->确认收货->完成。老司机的使用流程如下：开始->申请老司机->认证通过->填写发车信息->发布成功->确认发车->根据派件转态更改发车状态(更改时用户收到微信下发的模板消息)->派件成功->等待所有用户确认收货->完成订单。其中，司机发车状态与用户快递状态一一对应，他们之间的交互会派发微信模板消息，以此增加小程序的即时通讯。后台模块则是有学校管理、站点管理、老司机管理。
![](https://user-gold-cdn.xitu.io/2020/7/10/1733926f473a9fff?w=720&h=442&f=png&s=51057)
- 用户模块说明
![](https://user-gold-cdn.xitu.io/2020/7/10/1733929cdc146b00?w=840&h=1026&f=png&s=352588)

## 其他
本项目在操作数据并未过多使用laravel Eloquent ORM 模型，导致 controller 里面逻辑代码过多，这是也作者使用 laravel 熟练度不高的表现。因为开发这个应用已经过于久远，仅供参考，不再做更新。
<br>
觉得对您有用的话，我表示很高兴。

