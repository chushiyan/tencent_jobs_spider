"# tencent_jobs_spider" 
## 爬取腾讯的招聘职位的scrapy爬虫
+ the start url : https://hr.tencent.com/position.php?keywords=%E8%AF%B7%E8%BE%93%E5%85%A5%E5%85%B3%E9%94%AE%E8%AF%8D&lid=0&tid=0&start=0#a
+ [腾讯招聘](https://hr.tencent.com/position.php?keywords=%E8%AF%B7%E8%BE%93%E5%85%A5%E5%85%B3%E9%94%AE%E8%AF%8D&lid=0&tid=0&start=0#a)

+ This spider is base on Scrapy.
+ This spider is build for crawling the jobs of the tencent company. 
+ This scrapy spider can crawl the jobs's information,contain the job title,the job category,the job duties,the job requirement,the number of hiring,the work location and so on.
+ The data was save as a json file.

## 用法usage
+ make sure your machine is already installed Scrapy.
+ execute the command: scarpy crawl TencentSpider
+ wait,check the 'tencent_jobs.json' file,ok,done.



