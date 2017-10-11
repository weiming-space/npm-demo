npm 常用基本命令总结

一、构建篇

	1、npm init 
	初始化项目、引导生成一个package.json文件
	npm init -y 快速生成package.json
	
	2、npm install 
	安装包
	-g 全局包安装
	
	3、npm uninstall 
	删除包
	-g 全局包删除
	
	4、npm search 
	查找包
	
	5、npm view 
	打印相应包的package.json文件信息
	
	6、npm update 
	更新包
	* 可更新全局的或当前项目的所有包，
	* 也可更新单个包
	
二、配置篇

	1、npm root 
	包的安装位置
	-g 查看全局包的位置
	
	2、npm config list 
	打印配置信息
	
	3、npm config set 
	设置配置项

三、发布篇

	1、npm adduser 
	注册npmjs.org官网账号
	
	2、npm login
	登录账号
	
	3、npm version patch
	自增v0.0.0最后一位（修复版本号）
	
	4、npm version minor
	自增v0.0.0中间一位（功能版本号）
	
	5、npm version major
	自增v0.0.0第一位（主版本号）
	
	6、npm publish
	发布自己的包
	
	7、npm unpublish --force
	删除自己发布的包
	
