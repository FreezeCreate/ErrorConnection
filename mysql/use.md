# MySQL使用坑 || 其他问题 #

----------


- not in || in 使用时若存在为空的数据，则查询不出任何数据，如：id not in (12,190,654,NULL,109)则查询的数据为空
>解决方法：where id is not null即可解决

- 其他