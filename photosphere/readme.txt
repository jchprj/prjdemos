说明：
压缩包里包含了整个客户端的所有文件，可直接打开PhotoSphere.html进行测试，在做到正式版服务器上的时候请根据下面各文件的用途进行配置。

具体的文件用途是： 
PhotoSphere.html，运行客户端的页面文件，里面有各个js接口的调用方式，和主swf文件的参数设置方式，正式版只需要其中的写法，不需要原文件。
注1：客户端请求的服务器接口通过html里flash的flashVars参数传入，比如客户端请求所有格子和点击单个格子的接口分别为grids.jsp和box.jsp，在flashVars里就设置为：gridsurl=grids.jsp&boxurl=boxes.jsp
注2：所有格子的接口提交的参数（当前请求次数，每次请求总数）分别为：currentload和loadnum。其中第二个始终为50个不变。

PhotoSphere.swf，主文件，正式版必须用。
popup.png，泡泡框图片，正式版必须用。

mask.png，遮罩图片，正式版必须用。
framework_3.5.0.12683.swf，运行库文件，正式版必须用。

framework_3.5.0.12683.swz，运行库文件，正式版必须用。

以上是正式版要用到的文件，其他的：

playerProductInstall.swf，AC_OETags.js，history文件夹：判断flash player版本的文件，根据需要使用，使用方法见PhotoSphere.html里的用法。

img文件夹，测试用的一系列图片。正式版不需要。

grids.xml，测试用的所有格子的请求数据，可用来做格式参考，正式版不需要。

boxes.xml，测试用的点击格子的请求数据，可用来做格式参考，正式版不需要。


------------------
陈珏