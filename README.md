本脚手架参考大神的方案：https://github.com/airyland/vux/issues/1796

1.主要是根据淘宝的高清解决方案lib-flexible和vux组件结合，按照这个脚手架，设计出750px稿子（这个可以商量，webpack里面有配置可以改的），你在布局中直接使用px，webpack会自动转化rem，再根据淘宝的自适应方案达到自适应的效果。

2.vux组件使用的是px在很多情况下显示效果不好，此方案也是一种解决办法
