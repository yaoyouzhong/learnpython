# Python Spider

* 贵有恒，何必三更起五更睡；最无益，只怕一日暴十寒。
* [我的博客](http://blog.csdn.net/c406495762 "悬停显示")
* Python3爬虫实战：实战源码+博客讲解
* 欢迎关注我的[[CSDN爬虫专栏](http://blog.csdn.net/column/details/15321.html "悬停显示")]<br>
* 学习交流群【328127489】<a target="_blank" href="//shang.qq.com/wpa/qunwpa?idkey=e70f3fcff3761450fda9b43eadc1910dac308a962ef9e3e87941cd2c681c4bb4"><img border="0" src="https://github.com/Jack-Cherish/Pictures/blob/master/qqgroup.png" alt="Coder" title="Coder"></a><br>

## 声明

* 软件均仅用于学习交流，请勿用于任何商业用途！

## 爬虫小工具

* downloader.py:文件下载小助手

	一个可以用于下载图片、视频、文件的小工具，有下载进度显示功能。稍加修改即可添加到自己的爬虫中。
	
	动态示意图：
	
	![image](https://raw.githubusercontent.com/Jack-Cherish/Pictures/master/9.gif)

## 爬虫实战
 
 * biqukan.py:《笔趣看》盗版小说网站，爬取小说工具

	第三方依赖库安装：

		pip3 install beautifulsoup4

	使用方法：

		python biqukan.py

 * video_downloader：爱奇艺等主流视频网站的VIP视频破解助手(暂只支持PC和手机在线观看VIP视频！)

	感谢Python3二维码生成器作者：https://github.com/sylnsfar/qrcode
	
	编译好的软件下载连接：http://pan.baidu.com/s/1eR4Y7aM  解压密码：`c406495762`
	
	无需Python3环境，在Windows下，解压即用！[软件使用方法](http://blog.csdn.net/c406495762/article/details/71334633 "悬停显示")
	
	源码可查看`video_downloader`，运行源码需要搭建Python3环境，并安装相应第三方依赖库：
	
	在`video_downloader`文件夹下，安装第三方依赖库：

		pip3 install -r requirements.txt

	使用方法：
	
		python movie_downloader.py

	运行环境：
	
		Windows, Python3
		
		Linux, Python3
		
		Mac, Python3

 * baiduwenku.py: 百度文库word文章爬取
	
	原理说明：http://blog.csdn.net/c406495762/article/details/72331737
	
	代码不完善，没有进行打包，不具通用性，纯属娱乐，以后有时间会完善。
	
 * shuaia.py: 爬取《帅啊》网，帅哥图片

	《帅啊》网URL：http://www.shuaia.net/index.html

	原理说明：http://blog.csdn.net/c406495762/article/details/72597755
	
	第三方依赖库安装：
	
		pip3 install requests beautifulsoup4
		
 * daili.py: 构建代理IP池

	原理说明：http://blog.csdn.net/c406495762/article/details/72793480
	
	
 * carton: 使用Scrapy爬取《火影忍者》漫画

	代码可以爬取整个《火影忍者》漫画所有章节的内容，保存到本地。更改地址，可以爬取其他漫画。保存地址可以在settings.py中修改。
	
	动漫网站：http://comic.kukudm.com/
	
	原理说明：http://blog.csdn.net/c406495762/article/details/72858983
	
 * hero.py: 《王者荣耀》推荐出装查询小助手

	网页爬取已经会了，想过爬取手机APP里的内容吗？
	
	原理说明：http://blog.csdn.net/c406495762/article/details/76850843
	
 * financical.py: 财务报表下载小助手

	爬取的数据存入数据库会吗？《跟股神巴菲特学习炒股之财务报表入库(MySQL)》也许能给你一些思路。
	
	原理说明：http://blog.csdn.net/c406495762/article/details/77801899
	
	动态示意图：
	
	![image](https://raw.githubusercontent.com/Jack-Cherish/Pictures/master/10.gif)
	
 * one_hour_spider:一小时入门Python3网络爬虫。

	原理说明:
	
	 * 知乎：https://zhuanlan.zhihu.com/p/29809609
	 * CSDN：http://blog.csdn.net/c406495762/article/details/78123502
	
	本次实战内容有：
	
	 * 网络小说下载(静态网站)-biqukan
	 * 优美壁纸下载(动态网站)-unsplash
	 * 爱奇艺VIP视频下载
	 
 * douyin.py:抖音App视频下载
 
	抖音App的视频下载，就是普通的App爬取，没有原理说明。
	
  	


	
	
	

	


