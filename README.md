# blog_plus
> 这次是在原有博客上进行了响应式二次开发，将页面缩小到一定的宽度，你会发现，菜单栏等的变化。
1. 媒体查询的用法新发现：
 ###### link media="(max-width:768px)" rel="stylesheet" href="css/mobile.css"
(当设备宽度小于768px时，移动版样式适用)

2. 另外菜单的展示和不展示是纯html写的，是加一个checkbox当点击时产生一个伪类，给这个伪类下面的导航类设置样式display:blck使导航展现出来，详情参照代码。
