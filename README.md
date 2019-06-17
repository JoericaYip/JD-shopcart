# 京东购物车结算界面demo

主要功能
-------
div+css3实现网页布局，用vue-resource发送请求至PHP文件以获取本地JSON文件数据，使用Vue和原生JavaScript实现商品的增删、全选和反选以及核算总金额逻辑功能。该项目须通过本地服务器打开。

关于WAMP集成环境
-------------
* 因为需要用到vue-resource请求数据，涉及到PHP文件，开发过程中我使用的是wampserver软件。WAMP是Windows下的Apache+Mysql/MariaDB+Perl/PHP/Python，一组常用来搭建动态网站或者服务器的开源软件，本身都是各自独立的程序，但是因为常被放在一起使用，拥有了越来越高的兼容度，共同组成了一个强大的Web应用程序平台。
* 具体使用方法：软件安装成功后，找到安装位置的wamp文件夹，进入到www文件夹里，将index.php文件名修改为index1.php（或任意其他名字），再将该项目文件夹添加进www文件夹下，通过浏览器进入http://127.0.0.1/，选中页面显示的项目文件夹下的html文件即可打开。

无须本地服务器打开版本
----------------
无须本地服务器打开的版本亦可展示同样效果，请移步至https://github.com/JoericaYip/JD-shopcart2
