# SpringBoot
SpringBoot快速入门——siki学院笔记


SpringBoot + Gradle + thymeleaf + h2快速入门

		项目管理工具 + 代替jsp + 内存数据库
		
1）安装SpringBoot
	https://spring.io/tools/sts/all
2）安装Gradle
	https://services.gradle.org/distributions/
	新建环境变量GRADLE_HOME	，配置为你安装GRADLE的目录
	修改环境变量Path，在后面+上 %GRADLE_HOME%\bin
3）使用Gradle编译项目
	创建：https://start.spring.io/
	来到解压的目录
		gradle build
4）将编译好的项目导入到eclipse中（eclipse会自动安装Gradle）
	时间会比较久，大家请耐心等待（20分钟）
	
	1）对SpringBoot说你好~~

5）	
	spring Boot + spring Data JPA + hiernamte的集成 h2
	1）用户登录案例实现
	
	2）分析用户注册
		导入thymeleaf
		<html xmlns:th="http://www.thymeleaf.org" xmlns:layout="http://www.ultraq.net.nz/thymeleaf/layout">
	3）添加thymeleaf插件
		http://www.thymeleaf.org/eclipse-plugin-update-site/
	4）实体的规则
		什么是实体：
			就是与数据库对应的表
				1）有Entity注解
				2）要有public 或者 protected无参构造函数
				3）要有主键（唯一标识）
		
	5）	crudRepository
		sava		
		savaAll
		findById
		existsById
		findAll
		findAllById
		count
		deleteById
		delete
		deleteAll
		
		//用户登录
		通过用户名和密码查询对象
		
		
	6） 使用mysql
		三层   web   service    dao
		
		简单的用户注册和登录
		
		用户的查询
			查询所有用户
		用户的修改
		

		
		
		
		
