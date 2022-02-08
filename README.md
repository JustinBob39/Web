# Web前端
## 学习的原因
前几天终于把个人博客网站搭建好了，准备用来分享有意思的计算机知识  
搭建网站的流程  

* 购买云服务器，我选择的是阿里云，买了低配的一年才38块钱
* 购买域名，我买的域名是justinbob.site
* ICP工信部备案，只花了三天，速度挺快的。阿里云也很良心，补偿了备案花的时间
* 网安部门备案，这个很快，拿到ICP备案号之后再去，一天时间就通过了
* 备案期间可以并行搭建网站，Linux, Nginx, MySQL, PHP, 配合Typecho，Tyecho支持Markdowm语法，非常方便
* 在个人网站底部悬挂两个备案的号以及超链接
* 打开域名的DNS解析
* 部署STL服务，阿里云可以免费提供证书
* 部署CDN加速图片的加载速度，可以用免费的七牛云，七牛云还可以用来做typora的图床，美滋滋

## 学习路线
现在我想学习Web前端，来优化我的个人网站 
寒假打算咸学完HTML和CSS吧  
数据库MySQL和PHP放到学期内去学，反正下学期也挺闲的
感觉还是很有意思的！反正在家也是闲着，不如找点有意义的事做。

## 服务器小毛病
突然发现，chrome上cdn的图片加载不出来  
应该是因为https协议嵌套了http协议，安全性原因，浏览器不接收图片 
七牛云的http流量是免费的，但是https收费，万一被恶意攻击流量跑几个G那我岂不亏死了
我怀疑是强制https的原因，让我一会连上服务器修改一下  
还有用户头像url异常，导致浏览器会在后台加载到30s才放弃，耗费资源

## 每日打卡
b站有尚硅谷的网课，大概每天看十集吧，总共148集  
老师讲的挺不错的  
[链接 here](https://www.bilibili.com/video/BV1XJ411X7Ud?spm_id_from=333.1007.top_right_bar_window_default_collection.content.click)

* [x] Day01 看完第十六集
* [x] Day02 看完了第三十二集，最后的那个CSS听的我有点懵逼啊 得多看点文档温习一下
* [x] Day03 今天除夕，没看了，中断了一天！
* [x] Day04 绝绝子，<https://flukeout.github.io> 练习CSS选择器的网站 今天看完第四十八集了，奥力给
* [x] Day05 太难了，今天做了三个练习，margin，padding给我整懵了，还得多巩固，看完第五十八集了，明天继续
* [x] Day06 今天看完了第七十二集，学习了float和position，这两个挺重要的，得好好复习一下。说实话，感觉现在的主题好丑啊！
* [x] Day07 有小伙伴已经把下学期的课程学完了，好牛啊！今天看完了第83集，有点不在状态，明天继续吧！
* [x] Day08 蚌埠住了，今天又是下午才起床，学了一点点，看到第九十集了，背景部分有点乱，得看看文档。
* [x] Day09 今天又没啥进度，有点纠结是不是该开始复习操作系统和计组了。今天看完了第九十三集，主要是了解了Sprite雪碧图。明天早起打卡！
* [x] Day10 今天看完了第98集，学习了表格，还做了个小的练习，明天是讲表单。每天可以少看一点，但是一定要坚持看！！！明天一定要早起啊。
* [x] Day11 刚才看完第100集了，后面开始做项目练习。今天起的比较早，九点就醒了！看完第103集了，现在在模仿做mi.com，挺有意思的。