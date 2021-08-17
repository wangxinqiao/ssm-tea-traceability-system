# ssm茶叶溯源系统

## 项目介绍
````
茶叶溯源系统，分为前台与后台。普通用户可在前台通过18位的编码查询茶叶的出售历史。

后台分为两种角色，管理员与经销商；
管理员主要功能包括：
主界面；
管理员管理：管理员列表、添加管理员；
分类管理：茶叶类型的添加、删除、修改；
茶叶管理：茶叶列表、添加、删除、修改茶叶；
大包装管理：大包装列表、添加、删除、修改大包装；
单品管理：售出统计、单品信息修改；
经销商主要功能包括：
主界面；
售出单品：确认售出单品；
````

源码获取：[ **点此获取** ](http://www.shuyue.fun/index.php?type=productinfo&id=228)

## 环境需要
````
1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。
2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS；
5.是否Maven项目: 否；查看源码目录中是否包含pom.xml；若包含，则为maven项目，否则为非maven项目
6.数据库：MySql 5.7版本；
````
## 技术栈
````
1. 后端：Spring SpringMVC MyBatis
2. 前端：JSP+bootstrap+jQuery+layUI
````

## 使用说明
````
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；
2. 将项目中jdbc.properties配置文件中的数据库配置改为自己的配置;
3. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;
若为maven项目，导入成功后请执行maven clean;maven install命令，配置tomcat，然后运行；
4. 运行项目，输入localhost:8080/tea-web/ 登录
````

## 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/220337_cb2a6180_9600016.jpeg "WechatIMG2106.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/220345_2254daa1_9600016.jpeg "WechatIMG2107.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/220353_d8b9a100_9600016.jpeg "WechatIMG2109.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/220402_4a06a7e8_9600016.jpeg "WechatIMG2110.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/220412_73c5acf3_9600016.jpeg "WechatIMG2111.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/220419_bc24c042_9600016.jpeg "WechatIMG2112.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/220427_377015b0_9600016.jpeg "WechatIMG2113.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/220434_18a3e766_9600016.jpeg "WechatIMG2114.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/220444_97c9ad50_9600016.jpeg "WechatIMG2115.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/220452_3a6fd5be_9600016.jpeg "WechatIMG2118.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/220500_ab10a6e0_9600016.jpeg "WechatIMG2119.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/220508_c766eaac_9600016.jpeg "WechatIMG2120.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/220518_4402ad0c_9600016.jpeg "WechatIMG2121.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/220530_26b7cc0b_9600016.jpeg "WechatIMG2122.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/220538_e0f722a9_9600016.jpeg "WechatIMG2123.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/220545_72996c9f_9600016.jpeg "WechatIMG2125.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/220553_1a224046_9600016.jpeg "WechatIMG2126.jpeg")
