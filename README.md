### 基于SpringBoot + Vue的中药店管理系统.

中药饮片进销存、中医处方流转、中医馆管理系统

###### 管理员：
公告管理 、药材管理 、库存统计 、物流信息 、订单详情 、订单评价 、订单信息 、缴费记录 、药店管理 、药店库存 、员工管理 、用户管理 、数据统计 、管理员管理 、供应商管理 、电子处方 、药材采购 、库房预警 、销售统计 、病症处方 、采购物流。

###### 用户：
账户注册登录、密码修改、个人信息 、我的订单 、缴费记录 、订单评价 、药材购买 、在线支付。

###### 医生：
账户注册登录、密码修改、病症处方 、库存统计 、订单物流 、订单管理 、订单评价 、店内库存 、员工管理。

##### 药材资源与供应链管理
###### 药材管理/采购： 标准化管理中药饮片信息，实现药材采购入库与供应商档案的全程追踪。

###### 供应商/物流信息： 维护药材供应渠道，实时监控采购与订单物流状态，保障药材供应链路。

###### 库房/库存预警： 实时监控药柜与库房存量，针对低库存自动告警，确保常用药材不缺货。

##### 处方诊断与配药体系
###### 电子处方/病症： 医生根据病症在线开具电子处方，系统关联后台药材库实现自动核价。

###### 药材购买/支付： 用户通过线上选购或处方下单，支持多种在线支付方式并记录缴费流水。

###### 病症处方模板： 管理员维护典型病症的参考方剂，辅助医生快速开方，提升临床诊疗效率。

##### 订单流转与售后保障
###### 订单信息/详情： 记录从抓药、复核到配送的全流程状态，支持多方实时查询订单进度。

###### 订单评价管理： 收集用户对药材品质及医生服务的反馈，通过评价数据驱动药店口碑提升。

###### 订单物流追踪： 医生与管理员可实时掌握药品配送动态，确保中药配送过程安全、准时。

##### 人力行政与药店运维
###### 用户/员工管理： 统一管控医生、店员及客户档案，按角色分配权限，确保系统安全运行。

###### 药店/管理员管理： 实现多门店信息维护与系统管理员配置，支撑中药店连锁化经营管理。

###### 公告管理： 实时发布药店动态、养生知识或停诊公告，确保关键信息有效触达用户。

##### 经营决策与财务统计
###### 数据/销售统计： 自动汇总药材销量、门诊收入等核心指标，通过报表分析辅助药店经营。

#### 安装环境

JAVA 环境 

Node.js环境 [https://nodejs.org/en/] 选择14.17

Yarn 打开cmd， 输入npm install -g yarn !!!必须安装完毕nodejs

Mysql 数据库 [https://blog.csdn.net/qq_40303031/article/details/88935262] 一定要把账户和密码记住

redis

Idea 编译器 [https://blog.csdn.net/weixin_44505194/article/details/104452880]

WebStorm OR VScode 编译器 [https://www.jianshu.com/p/d63b5bae9dff]

#### 采用技术及功能

后端：SpringBoot、MybatisPlus、MySQL、Redis、
前端：Vue、Apex、Antd、Axios

平台前端：vue(框架) + vuex(全局缓存) + rue-router(路由) + axios(请求插件) + apex(图表)  + antd-ui(ui组件)

平台后台：springboot(框架) + redis(缓存中间件) + shiro(权限中间件) + mybatisplus(orm) + restful风格接口 + mysql(数据库)

开发环境：windows10 or windows7 ， vscode or webstorm ， idea + lambok


#### 前台启动方式
安装所需文件 yarn install 
运行 yarn run dev

#### 默认后台账户密码
[管理员]
admin
1234qwer

#### 项目截图
暂无

|  |  |
|---------------------|---------------------|
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/7a77d1cf-cbf7-4704-9d6c-7497bfa9f167.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/4318deb5-d0e7-44c1-9444-047c27addf7f.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/7a34e0b3-c4b2-4878-822f-dba68382f17a.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/816f4336-da22-43ab-9cdd-60f4387319d9.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/2ae57348-857a-48e4-996f-ecf761014da9.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/704dd654-3b4c-41bc-b881-f646ea7b5d06.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/2ad61557-2a42-4f18-b060-03bbf4461594.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/700c8e0e-9ba1-4634-bb71-474f6fbac9db.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/fa7d5267-0cd8-455e-9be8-56663ead16bd.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/329d7f4d-6c28-40be-8f24-111d6065cc0d.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/e67a3eff-2c13-4a34-a616-28fceed92775.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/141ccbd3-978d-4cb0-8475-abb4134f7908.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/d17974b0-f8aa-469f-be62-1ddce396efe4.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/75d0abdd-b6d7-4f9f-bbdd-5cfe8c4c46df.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/c39c87f7-0d2d-4617-9ce8-d9291bc993f2.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/55deb49a-1c40-44cf-94bf-6f2224a29607.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/bf16d595-0336-4b27-8989-b5f808b16f17.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/53b93eec-7f44-4d4f-ae4a-e38172b8f753.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/b682df7a-8be4-4356-9d0d-924c0a61448b.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/30bca179-aeeb-41d2-84f5-4fc59ad8d8d3.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/ad4767b3-0171-494f-87d0-c2403e8465ef.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/17d710cb-12f5-44d2-92ba-76fb46a27be5.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/9669d791-a2a2-47b1-83cd-8640cc5758b4.png) |  |

![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/work/936e9baf53eb9a217af4f89c616dc19.png)

#### 演示视频

暂无

#### 获取方式

Email: fan1ke2ke@gmail.com

WeChat: `Storm_Berserker`

`附带部署与讲解服务，因为要恰饭资源非免费，伸手党勿扰，谢谢理解😭`

> 1.项目纯原创，不做二手贩子 2.一次购买终身有效 3.项目讲解持续到答辩结束 4.非常负责的答辩指导 5.**黑奴价格**

> 项目部署调试不好包退！功能逻辑没讲明白包退！

#### 其它资源

[2025年-答辩顺利通过-客户评价🍜](https://berserker287.github.io/2025/06/18/2025%E5%B9%B4%E7%AD%94%E8%BE%A9%E9%A1%BA%E5%88%A9%E9%80%9A%E8%BF%87/)

[2024年-答辩顺利通过-客户评价👻](https://berserker287.github.io/2024/06/06/2024%E5%B9%B4%E7%AD%94%E8%BE%A9%E9%A1%BA%E5%88%A9%E9%80%9A%E8%BF%87/)

[2023年-答辩顺利通过-客户评价🐢](https://berserker287.github.io/2023/06/14/2023%E5%B9%B4%E7%AD%94%E8%BE%A9%E9%A1%BA%E5%88%A9%E9%80%9A%E8%BF%87/)

[2022年-答辩通过率100%-客户评价🐣](https://berserker287.github.io/2022/05/25/%E9%A1%B9%E7%9B%AE%E4%BA%A4%E6%98%93%E8%AE%B0%E5%BD%95/)

[毕业答辩导师提问的高频问题](https://berserker287.github.io/2023/06/13/%E6%AF%95%E4%B8%9A%E7%AD%94%E8%BE%A9%E5%AF%BC%E5%B8%88%E6%8F%90%E9%97%AE%E7%9A%84%E9%AB%98%E9%A2%91%E9%97%AE%E9%A2%98/)

[50个高频答辩问题-技术篇](https://berserker287.github.io/2023/06/13/50%E4%B8%AA%E9%AB%98%E9%A2%91%E7%AD%94%E8%BE%A9%E9%97%AE%E9%A2%98-%E6%8A%80%E6%9C%AF%E7%AF%87/)

[计算机毕设答辩时都会问到哪些问题？](https://www.zhihu.com/question/31020988)

[计算机专业毕业答辩小tips](https://zhuanlan.zhihu.com/p/145911029)

#### 接JAVAWEB毕设，纯原创，价格公道，诚信第一

`网站建设、小程序、H5、APP、各种系统 选题+开题报告+任务书+程序定制+安装调试+项目讲解+论文+答辩PPT`

More info: [悲伤的橘子树](https://berserker287.github.io/)

<p><img align="center" src="https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/%E5%90%88%E4%BD%9C%E7%89%A9%E6%96%99%E6%A0%B7%E5%BC%8F%20(3).png" alt="fankekeke" /></p>
