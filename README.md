smartlayout
===========

后面的sliders，会跟随浏览器大小而“智能”填充内容。sliders的个数也相应变化。
如果图片大小不能预先知道，页面的初始化很慢。(这里没有做图片预加载，你懂的)
所以这里的图片都设置了width,hegiht
这里尽量避免了低效的算法（不用递归，和节点重复利用）
