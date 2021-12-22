# 基于web的大数据可视化管理系统
##系统包括前台和后台，支持数据（视图）自定义，字段自定义，字段类型自定义，数据集选择，可视化图表自定义，echarts图表类型选择，图表任意选择，包括公告管理，数据视图管理，用户管理，权限管理，管理员管理，数据随意定义添加。

# 如果需要源码和数据库，请加我 **QQ1516993194** 获取，不会运行可以提供远程调试帮助。

基于web的图表可视化系统 的设计与实现
基于基于web的图表可视化系统,后台实现技术springboot，系统包括前台和后台，支持数据（视图）自定义，字段自定义，字段类型自定义，数据集选择，可视化图表自定义，echarts图表类型选择。
功能使用说明：系统包括前台和后台，支持数据（视图）自定义，字段自定义，字段类型自定义，数据集选择，可视化图表自定义，
   echarts图表类型选择，图表任意选择，包括公告管理，数据视图管理，用户管理，权限管理，管理员管理，数据随意定义添加。


![输入图片说明](https://images.gitee.com/uploads/images/2021/1222/115024_93e2a7d0_865419.png "222.png")


![输入图片说明](https://images.gitee.com/uploads/images/2021/1222/115034_0697f33f_865419.png "个人中心.png")


![输入图片说明](https://images.gitee.com/uploads/images/2021/1222/115227_02a060aa_865419.png "商品销售数据柱状图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/1222/115236_2c547f45_865419.png "学生成绩饼图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/1222/115246_c1148aaf_865419.png "用户数据集选择.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/1222/115324_7c30e35b_865419.png "视图数据在线修改.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/1222/115332_2243c264_865419.png "公告信息查看.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/1222/115339_7be61341_865419.png "管理员登陆.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/1222/115352_281f88d9_865419.png "管理员-个人信息修改.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/1222/115400_529d11e8_865419.png "管理员-公告信息管理.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/1222/115411_dfd67b77_865419.png "管理员-视图结构修改.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/1222/115418_e76016b8_865419.png "管理员用户管理.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/1222/115426_bd53ba21_865419.png "管理员-用户权限管理.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/1222/115434_ec4ed0bc_865419.png "商品销售数据折线图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/1222/115446_98a27b45_865419.png "视图数据详情查看.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/1222/115454_41f5008e_865419.png "添加可视化视图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/1222/115503_eb54515c_865419.png "图标类型选择.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/1222/115510_e0800475_865419.png "用户登陆.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/1222/115517_8ea3013a_865419.png "用户数据集选择.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/1222/115525_e5d42c4a_865419.png "用户注册.png")

<p>
	<br />
http://localhost:8080/myproject/index<br />
【系统测试账号】<br />
管理员 admin 123456<br />
后台技术 Springboot框架<br />
数据库 Mysql+navciat<br />
开发工具：IDEA<br />
【如果不会运行，可以找我们远程帮助调试运行】<br />
数据库每个表都有详细注释<br />
代码也有详细注释（详细说明）<br />
前段使用技术：html+JavaScript+css+layui+jQuery<br />
网站前端：http://localhost:8080/myproject/index<br />
网站后台:http://localhost:8080/myproject/manage/login<br />
4.系统实现（基础代码，业务功能代码的编写）<br />
<br />
com&nbsp; &nbsp;项目包结构说明<br />
└─module<br />
&nbsp; &nbsp; ├─controller&nbsp; 控制层，负责请求的处理，数据库的操作调用<br />
&nbsp; &nbsp; ├─mapper&nbsp; &nbsp; &nbsp; 数据库操作接口，sql文件在xml中的配置<br />
&nbsp; &nbsp; ├─pojo&nbsp; &nbsp; &nbsp; &nbsp; 数据库对应实体类，用来和数据库表实现映射关系<br />
&nbsp; &nbsp; └─util&nbsp; &nbsp; &nbsp; &nbsp; java中常见工具类的存放<br />
</p>
