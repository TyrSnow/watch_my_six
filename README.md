# watch_my_six
简单的爬虫监控，会每隔一段时间看下某个列表是不是有新的内容出现
# 功能
## 1. 配置目标URL
配置一个目标URL用于定时访问
## 2. 配置访问后进行的操作
比如我们可以定义一个数组，将数组中的值依次填入某个input中点击某个button
## 3. 爬取页面上的内容
操作完成后，自动执行爬取操作，将结果入库
## 4. 结果比对
与上一次的结果进行比对，找出新增或被编辑过的内容
