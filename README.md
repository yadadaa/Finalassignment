# Finalassignment
1.在github上创建项目

2.导入网上找到的源代码

3.连接数据库 mongorestore -d douban /home/ubuntu/公共的/期末大作业案例/douban_Website-master/doubanDatabase/douban

4.路由修改10133

5.源代码获取验证码模块失效，使用Math.random()函数重新生成验证码

6.完善新生成的验证码，验证码模块能正常检验输入是否正确 ，运行成功

7.调试录入电影功能出错  2021.12.24/14：37

8.在数据库中删除失效的电影

9.找到原代码中海报失效的原因

10.修改在首页上gallery上突破无法显示图片的错误

11.解决首页上gallery连接无响应问题 2021.12.24/21：57

12.对movie的index界面重新布局和图片的更新

13.通过配置文件路径解决页面图片出错问题 

14.无法解决 电影分类问题 mongodb push方法失效导致电影分类功能无效 12.25/12：13

15.使用addToSet方法替代push方法实现电影分类数据的同步 12.25/17.43

16.当已经存在的电影修改电影分类时会导致categary内的movie.id重新生成而 movie数据库中的id未发生变化

17.解决movie数据库中的id未发生变化 并对index首页的信息进行更新和无效内容的矫正与填充

18.对系统的框架进行更改

19.对页面进行删改

20.解决由于adobe flash player不支持问题

21.数据库 的导入 和导出  https://www.cnblogs.com/jingsupo/p/14111593.html

22.在首页点击四个电影分类按钮无反应

23.movie_index.js中 关于fliterMovies.class-top 按钮切换 的ajax不起作用