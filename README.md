# project
移动端豆瓣电影

技术栈：移动端/jQuery/CSS3/响应式

项目功能介绍：

1.经测试可在手机端展现

2.有三块内容分别展示豆瓣高分电影，最新的北美票房榜单电影，和与搜索相关的电

3.详细展示了电影的相关信息如评分，导演，主演，年限，分类，被收藏数，并可点击跳转到对应页面，浏览详细信息；

4.点击底部相应图标，迅速切换相应内容，几乎无任何卡顿；

5.当请求数据时，显示加载图标，数据到来后隐藏

项目技术细节介绍：

1.设置meta，解决页面适配，与300 毫秒点击延迟；

2.设置动态 rem，媒体查询，实现响应式；

3.整体只设计一个页面，切换相应内容，减少卡顿；

4.通过封装函数，初始化，绑定事件，增加功能，减少变量污染与简化代码。

4.通过Jonsp的方法请求数据，解决了同源策略的问题。

5.将10条数据拼装成DOM展示在页面上，当滚动条底部时再次发送请求，并通过加锁与函数节流来优化功能；

6.判断是否滚动到底部，结束请求数据；




