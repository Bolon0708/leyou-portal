门户系统面向的是用户，安全性很重要，而且搜索引擎对于单页应用并不友好。因此门户系统不再采用与后台系统类似的SPA（单页应用）。依然是前后端分离，不过前端的页面会使用独立的html，在每个页面中使用vue来做页面渲染。
采用live-server热部署方式：

安装指令：npm install -g live-server

运行指令：live-server --port=9002

访问http://www.leyou.com/，在虚拟机采用nginx跳转回本地9002端口