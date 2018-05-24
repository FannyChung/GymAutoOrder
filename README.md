# GymAutoOrder
Order gym automatically in SEU.

-----------------------
## 简介 ##
* 由于学校羽毛球馆晚上的时段比较抢手，需要早起卡时间点“抢票”，所以制作了这款软件。
* 当天运行程序后，程序会在第二天早8点自动预约1天后的羽毛球场，时间段自定义。大家可以晚上把程序挂在实验室电脑上，然后就回去睡觉吧。
* **但是不宜过多人同时使用**。

----------------------
## 需求环境 ##
1. [python2.7](https://www.python.org/downloads/)
2. [PIL](http://www.pythonware.com/products/pil/)

---
## 使用方法 ##
1. 转到文件目录下，运行 `python WebLogin_V1.0.py`
2. 设置信息文件`info.txt`
3. 程序在午夜12点前启动，离开时不要关闭程序进程和电脑

### 设置方法 ###
`info.txt`下有多行设置，
```
username:一卡通号
password:登陆门户网站的密码
phone:自己的手机号
friendid:朋友的id
weekdayTime:工作日打球起始时间
weekendTime:周末打球起始时间
```
添加常用联系人，然后在常用联系人中右击对应人名，点击“检查”，可以看到查看朋友的id，为五位数的数字。
工作日打球起始时间可选择：6,7,8
周末可选:5,6,7,8
