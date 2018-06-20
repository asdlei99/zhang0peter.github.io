---
layout: post
title:  "爬取B站我关注的人关注的人关注的人关注的人"
date:   2018-05-22 14:35:18 +0800
categories: Python
description: ""
keywords: Python
---
# bilibili-following-spider
## 本文最后更新于2018-6-20，可能会因为没有更新而失效。如已失效或需要修正，请联系我！
项目地址：https://github.com/zhang0peter/bilibili-following-spider
我突发奇想，想爬取我关注的人，我关注的人关注的人，我关注的人关注的人关注的人等。  
代码很简单，在 [bilibili-following-spider.py](https://github.com/zhang0peter/bilibili-following-spider/blob/master/bilibili-following-spider.py)  
我使用sqlite存储数据，在数据库中放2个表，一个表示用户与关注者的关系，一个表存用户的mid，uname和sign。
我花了一天的时间从我开始，爬了10万用户，数据压缩后在[data.zip](https://github.com/zhang0peter/bilibili-following-spider/blob/master/data.zip)里  
然后我写了词云生成，代码在[bilibili-wordcloud.py](https://github.com/zhang0peter/bilibili-following-spider/blob/master/bilibili-wordcloud.py)  
最后生成的图片为  
![wordcloud.png](https://github.com/zhang0peter/bilibili-following-spider/blob/master/wordcloud.png)  
可以看出蕾丝，暴走漫画，木鱼水心等都是热门关注。    
我觉得这张图可以从一个方面反映这些UP主的粉丝量。