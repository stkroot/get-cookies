配合私有签到框架使用，一键获取cookies

推荐使用平台：https://hub.docker.com/r/a76yyyy/qiandao

# 简介

稍微瞎修改并改进下了。
针对源代码会漏掉某些cookie抓不到的问题进行了补足

# 使用注意
整个代码打包下载回去，使用chrome扩展 加载已解压的扩展程序来使用

或者去Releases下载打包好的crx文件。（然而还是无法直接使用，因为付不起5刀），将crx扩展名改为zip。解压、同上使用

注意！使用前请打开扩展详情里打开扩展设置“扩展程序选项”，根据提示填入ip或域名

# Tip
插件目前无法获取在隐私模式下访问的网站的cookies，虽然理论上是可以的。不过我没有那个精力去改后台代码来实现这个我不咋用的方式

但是，可以使用chrome的多用户模式来达到隐私模式一样的效果。

只需要新建一个用户，重新安装本插件（无非是重新导入文件夹一次），在这个用户下同时访问签到平台和需要隐私访问的网站

同时在该用户的chrome设置里-隐私设置和安全性-cookie及其他网站数据-关闭所有窗口时清除cookie及网站数据 处打勾即可。


# 更新
v1.0.0 修改匹配及注入方式，添加设定选项方便自行添加需要启用的网站

# 鸣谢
原作者 https://github.com/acgotaku/GetCookies
