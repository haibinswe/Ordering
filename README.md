# Ordering
基于maven+SSM框架编写的订餐管理系统

## 1、项目介绍：
订餐管理系统是为商家和用户开发的一套在线订餐平台，旨在合理化安排餐厅的工作，提高商家的经营管理效率以及方便用户的用餐，在传统商家与订餐者之间架起了一道绿色通道。通过这个平台，商家可以更加方便以及合理地经营自己的餐馆，提交日常销售量；用户可以更加方便的浏览餐馆与选择自己合适的菜式下单，更加方便快捷，实现用户与商家的双赢。

## 2、使用技术与开发环境：
（1）该系统主要使用SpringMVC+Spring+Mybatis+JSP+Oracle搭建。<br/>
（2）该系统的开发环境是：Ecplise+JDK1.8+Tomcat9+SpringMVC4.3.9+Spring+4.3.9+Mybatis3.4.4+Oracle11g<br/>
（3）系统主要分成四层：视图层+web层+service层+Dao层：<br/>
&ensp; &ensp; 视图层主要使用JSP编写;<br/>
&ensp; &ensp; SpringMVC主要负责web层的管理;<br/>
&ensp; &ensp; Spring主要负责service层的管理;<br/>
&ensp; &ensp; Mybatis主要负责Dao层的管理;<br/>

## 3、主要功能：
### 商家功能：
（1）商家信息模块：商家的注册登陆、基本信息完善功能。<br/>
（2）菜单管理模块：菜式图片的管理、菜单的查看、添加、菜式信息的更新、删除。<br/>
（3）订单管理模块：查看用户订单、订单详情、订单统计。<br/>
（4）评价管理模块：查看用户对菜品的评价。<br/
### 用户功能：
（1）用户信息模块：用户的注册登陆、基本信息完成功能。<br/>
（2）订餐管理功能：查看所有商家信息、菜品信息。查看商家以及商家商品详情。<br/>
（3）购物车模块：商品加入购物车、购物车查看、购物车商品的删除、在购物车下单。<br/>
（4）订单管理模块：查看订单、添加订单、修改订单、删除订单、查看订单详情与订单商品详情，微信或支付宝付款，可使用优惠券。<br/>
（5）评价管理模块：订单评价、查看订单评价、查看商家评论。
### 管理员功能：
（1）管理用户功能。<br/>
（2）管理商家功能。<br/>
