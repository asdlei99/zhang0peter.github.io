---
layout: page
title: About
description: 张思淡的个人博客
keywords: Zhang Peter
comments: true
menu: 关于
permalink: /about/
---

浙大2016级信安学生，喜欢使用Python。  
联系我：zhang@zhangsidan.com 


## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
