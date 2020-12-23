# doubanMovieApi
doubanMovieApi
author：home

adress：https://gpnu.edu.cn/ 计算机科学学院

数据来源
数据是豆瓣电影top250，用java爬取，数据库为SQL server

api说明
获取所有列表电影
eg:http://http://8.129.125.200:8080/files/MovieListServlet

获取所有类型电影
eg:http://8.129.125.200:8080/files/MovieGetAllType

根据id获取对应的moive信息
eg:http://8.129.125.200:8080/files/MovieGetOne?id=5

根据类型获取对应类型电影列表
eg:http://8.129.125.200:8080/files/MovieGetByType?type=剧情

根据国家或地区获取榜单电影列表
eg:http://8.129.125.200:8080/files/MovieGetByCountry?country=中国大陆

根据电影名称获取
eg:http://8.129.125.200:8080/files/MovieGetByTitle?title=霸王别姬

分页查询，每次获取10条
eg:http://8.129.125.200:8080/files/MovieGetTen?num=5

部署说明：
1.git clone

2.在myeclipse导入file工程，修改src下util包类的连接数据库的用户名和密码

3.用本地tomcat打开调试

此接口已经部署在云服务器上。

通过http://http://8.129.125.200:8080/files可以访问接口首页。

里面有对应的访问信息
