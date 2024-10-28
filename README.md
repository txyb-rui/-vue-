# -vue-
配置vue环境

一、前端环境

1.vscode

	直接在https://code.visualstudio.com/中下载
2.nodejs

 	在https://nodejs.org/zh-cn中下载，安装时出现custom setup时，点击add to path就会自动加到环境变量中
	
	然后windows+r cmd打开控制台，输入node -v若出现版本号则视为成功
 3.设置淘宝源
 	淘宝npm源是一个常用的第三方npm镜像源，它可以提高npm包在中国大陆地区的下载速度。
	
	（1）打开cmd窗口,查看当前仓库

输入：npm config get registry

查看当前仓库。



(2) 设置淘宝源

输入：npm config set registry https://registry.npmmirror.com/

(3) 查看源

npm config get registry



(4)其他的源

阿里源：

npm config set registry https://npm.aliyun.com
腾讯源：

npm config set registry https://mirrors.cloud.tencent.com/npm/
华为源：

npm config set registry https://mirrors.huaweicloud.com/repository/npm/
网易源：

npm config set registry https://mirrors.163.com/npm/

  

