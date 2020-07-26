### 搜索引擎的构成

一个搜索引擎由搜索器、索引器、检索器和用户接口四个部分组成

~~~markdown
	搜索器，通俗来讲就是我们常提到的爬虫（scrawler），它能在互联网上大量爬取各类网站的内容，送给索引器。索引器拿到网页和内容后，会对内容进行处理，形成索引（index），存储于内部的数据库等待检索。
~~~

~~~markdown
	最后的用户接口很好理解，是指网页和 App 前端界面，例如百度和谷歌的搜索页面。用户通过用户接口，向搜索引擎发出询问（query），询问解析后送达检索器；检索器高效检索后，再将结果返回给用户。
~~~

