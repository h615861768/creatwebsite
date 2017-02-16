### 其他的本次创建网站遇到的问题:

传老师的像素鸟到服务器上测试,结果json文件 读取404了,蛋疼,然后运行不了.各种调路径名没用.

![](/assets/Snip20170216_1.png)

结果百度到原因是json格式在IIs服务器上无法读取.不被识别.

需要设置.

设置方法,后台也有.

在自定义mime属性里面

![](/assets/Snip20170216_2.png)

拓展名填写.json

mime类填写: application/json

![](/assets/Snip20170216_3.png)

解决

