# AppStart
一行代码实现App启动页加载(包括网络视频, 本地视频, 网络图片, 本地图片)


使用方法 > 

导入写好的类ZHMoviePlayerController, 创建一个对象, 然后根据项目需求调用demo中的两个对象方法(分加载视频跟加载图片,可以是网络的也可以是本地的)

这里展示的demo没加缓存, 我自己做的项目中加了缓存了,提供下思路在这里:
加缓存的话, 写入沙盒, 设置一个userdefault, 启动的时候先去沙盒找, 如果沙盒有的话就加载沙盒的, 沙盒没有的话就加载网络的, 然后把需要加载的启动页写入沙盒就行



