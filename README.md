# 科大二手工坊


**写在前面：**

感谢各位小伙伴们的支持，最近比较忙，后续有更新一定告知大家（2020.12.09）

## 项目介绍

基于SSM的校园二手物品交易平台
（项目包括前台和后台）

## 运行环境

开发工具 IDEA

安装运行环境：jdk1.8   Tomact8  maven3.3 

数据库：MySQL 

## 项目说明

**端口号暂时固定为8088，不要更改其它的tomact端口号**

访问网址：localhost:8088/goods/index

学生用户登录 15232103749/123456

管理页面登录：localhost:8088/admin/toLogin

系统管理员用户登录  17611056916/aaa

### 项目中可能遇到的问题

#### 关于上传的图片无法显示的问题

方案一：最直接最有效的解决办法：换成`Tomcat7.0`版本

方案二：如果你使用的是`Tomcat8.0`及以上版本解决方案如下：

1. 编辑Tomcat配置

![](https://gitee.com/lvr1997/PicGioRepository/raw/master/img/PKT(~Y~@W3{T4GLV$NN)IK5.png)

2. 点击Deployment，点击加号

![](https://gitee.com/lvr1997/PicGioRepository/raw/master/img/U2XACY}J8FJ56JLUXGE}8CB.png)

3. 选择External Source

![](https://gitee.com/lvr1997/PicGioRepository/raw/master/img/NXRP]UE3GQI81YQFYS$B1VB.png)

4. 选择项目下的 images目录，点击ok

![](https://gitee.com/lvr1997/PicGioRepository/raw/master/img/WPZ6O}J3V[1_1F70GNO9{DA.png)

5. 重启`Tomcat`

## 更新情况

2020.04.14 
1. 项目部分调整，保证能启动
2. 添加数据库`sql`文件，在`src/main/java/resources`目录下

2020.12.09

1. 更新pom依赖
2. 添加git忽略文件

2020.12.10

1. 更新至Spring5.x版本 

2020.12.11

1. 修复项目启动访问页面报404问题
2. 修改项目名 **kd-second-hand-workshop**

2021.01.05

1. 统一项目根路径


## 功能模块

前台部分：
- [x] 首页
    - [x] 分类展示
    - [x] 闲置检索
    - [x] 发布商品
- [x] 学生用户登录
    - [x] 找回密码
    - [x] 注册
- [x] 发布/想要
    - [x] 管理我发布的商品
    - [x] 管理我想要的商品    
- [x] 用户留言（收到的留言，发布的留言）
- [x] 个人信息管理
- [x] 订单管理
- [x] 意见反馈
- [x] 累计收入，累计支出
- [x] 支付
- [x] 收货地址管理
- [x] 商品收藏

后台管理系统部分：

- [x] 首页轮播图管理
- [x] 闲置管理
- [x] 分类管理
- [x] 举报管理
- [x] 留言管理
- [x] 订单管理

**PS: 如果感兴趣的话可以添加qq群 696224249 一起讨论哦^v^**
