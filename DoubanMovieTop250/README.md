
# Python爬取豆瓣电影top250
- [教程地址](http://www.jianshu.com/p/826f8566a7c7)
- 基于python3
- 所需类库Requests，BeautifulSoup
- 代码总共30多行
- [豆瓣电影top250](https://movie.douban.com/top250)
- 抓取结果存为txt

记录一下：lxml在python2.7.3版本之前兼容性不好，可以用html5lib. 
还需加入
import sys 
reload(sys) 
sys.setdefaultencoding('utf8')
解决unicode编码冲突.