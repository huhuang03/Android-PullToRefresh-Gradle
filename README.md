Android上拉加载，下拉刷新的一个好的解决方案是：<https://github.com/chrisbanes/Android-PullToRefresh>

虽然项目作者已经不维护了，但是还是很实用

但是有一点麻烦的就是，原工程是Eclipse工程，想要集成它太麻烦了，拷类，拷资源文件，拷各种资源xml内容，修改拷贝引起的错误。

将其转为gradle 的lib就很好了，只要在dependency中引用一下就搞定了，而且不污染原工程

本工程就是做了这个事情。

