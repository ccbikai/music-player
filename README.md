##HTML5 网页音乐播放器

基于 Flask 框架搭建的一个播放器，音乐源来自虾米、网易云音乐。

程序可以直接运行在 JAE ，其他环境需要自行修改配置。

###演示
虾米播放器（推荐）：  
http://miantiao.jd-app.com/xiamiplayer/63608  
网易云音乐播放器（备用）：  
http://miantiao.jd-app.com/m163player/28815250

###使用
**推荐使用虾米源，没有防盗链。如果歌曲在虾米找不到，再使用网易云音乐。**

虾米播放器（推荐）：  
`<iframe src="http://miantiao.jd-app.com/xiamiplayer/63608" frameborder="0" scrolling="0" width="430" height="200" allowtransparency></iframe>`

网易云音乐播放器（备用）：  
`<iframe src="http://miantiao.jd-app.com/m163player/28815250" frameborder="0" scrolling="0" width="430" height="200" allowtransparency></iframe>`

###搭建方法

1. 所依赖的模块在 requirements.txt 里。可以直接使用 `pip -r install requirements.txt`;
2. 运行`python wsgi.py`即可。

