
使用教程:
1.下载工具:https://mp.weixin.qq.com/debug/wxadoc/dev/devtools/download.html
2.安装后,进入程序.
3.扫二维码登录(微信)--->选择小程序开发---> 新建(图标+)一个项目---->填写以下信息:
		a.AppId:(暂无,不影响工具预览,无法手机微信预览,需要注册微信公众平台的应用号,才可具有(与开发者微信有关联,不是随便别人给一个就行)))
		b.项目名:随意
		c.目录,选择解压后的sl目录(sl下有image,pages,util等目录)
	然后确定即可进入预览页面!
	

在手机微信上预览:
1.去微信公众号注册一个应用号,具体百度,无须认证(要钱的300一次)即可.
2.进入应用号首页--->选择设置-->基本设置--->然后可以看到你的appId
3.工具里新建一个项目,appid填写刚刚获取的
4.工具左侧的3个导航(编辑,调试,项目)--->选择项目---->点击预览按钮-->等待上传--->手机扫描预览


AppId:wx4b7e3ff383c215b1(我的,说了你们不能用,不信试试)

欲使用服务端,请解压 Wxmini.zip 后导入到eclipse,修改环境BuildPath和一些jdk版本属性以及tomcat环境!然后放在8080端口运行即可!
(同时记得在工具中对项目属性修改为调试模式不检查域名,且只能在工具调试时可连接服务端,手机扫描预览是万万不能滴!)