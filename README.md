# 基于SpringBoot+Vue3的智能健康饮食管理系统

![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) ![Vue3](https://img.shields.io/badge/-Vue3-grey?style=flat-square) ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Pinia](https://img.shields.io/badge/-Pinia-grey?style=flat-square) 

## 项目介绍

本项目是个特别好用的健康饮食管理系统，能帮助大家规划每天吃什么，而且系统本身还结合了AI大模型，可以给用户定制食谱。说到这个，系统的功能真的挺多的，它能根据你的健康档案来分析你需要的营养，然后帮你自动搭配合理的餐食，同时你也可以自己查各种食材的信息，要是觉得食谱比较合适，就可以直接添加进每天的饮食清单里面记录下来。同样，管理员可以在后台看到所有的用户情况，可以发布一些系统公告让大家看见，还能对系统里的食材、食谱分类这些信息进行修改和删除，整个操作过程还是挺简单直观的。

主要的功能模块大概有这么几个：
- **用户登录和权限管理**：也就是支持管理员和普通用户分别登录，然后不同的角色会跳到不同的页面，管理员能管后台，普通用户只能用客户端，而且用到了JWT技术来保护接口，如果没有登录的话是进不去的。
- **个人健康档案**：普通用户能在系统里填上自己的身高、体重、性别、还有平时运动量多不多这些信息，系统就会把这些数据保存下来，当作后面推荐食谱的根据。
- **AI 智能推荐**：这个主要是调用了阿里的千问AI接口，根据大家前面填写的身体数据和想吃的东西，直接生成一个一天三餐的合理方案。
- **食材和食谱分类管理**：管理员能在后台增加、修改、还有删除各种各样的食材分类，还能把具体的食材营养数据记录下来，普通用户平时可以去浏览这些食材，找自己想吃的。
- **饮食清单记录**：大家看到满意的食谱之后可以一键放进自己的饮食清单里，这样就能方便地监督自己今天到底吃了什么。
- **系统通知公告**：管理员在后台发的新公告会直接在普通用户的主页显示，大家一打开系统就能看到，非常省事。
- **后台系统管理**：能够管理注册的用户，分发不同角色，而且可以看系统的操作日志什么的。

技术架构
- **后端**：Spring Boot 2.6.13 + MyBatis-Plus 3.5.3.1 + Spring Security + JWT 认证
- **前端**：Vue 3.5.32 + Element Plus 2.13.7 + Vite 8.0.9 + ECharts 6.0.0 + Pinia 3.0.4
- **数据库**：MySQL 8.0

<!-- screenshots-start -->
## 系统截图

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/ff40600453ed4374bd3f3aa8b88c8dd2.png" alt="系统截图1" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/f6a349bf979f45068232419d7d279429.png" alt="系统截图2" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/9e3c0c996c3a4afeb00de110c895b1c4.png" alt="系统截图3" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/28559f7d22d64222966278fbc509dda7.png" alt="系统截图4" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/9404c80cbb4f447d8ff55d4d77b0f130.png" alt="系统截图5" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/b00bc2b2f5664b22a0573fecaa277603.png" alt="系统截图6" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/a1b70996b5b54edcb3145ad617afe2e7.png" alt="系统截图7" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/6bf6ac9310a240d7b9194dd866715b2a.png" alt="系统截图8" width="600" />

<!-- screenshots-end -->

---

**软件版本：** JDK 8.0 | MySQL 8 | Vue 3 | Node 20.19.0 | Navicat 16

**需要软件和PPT + 微信：vvsgxmn**
二维码：

<div align="left">
<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/753b7d4a2ede90f531338ee5549c2695.jpg" alt="二维码" width="300" />
</div>


1. 免费赠送以上所有软件都有，包括IDEA、WebStorm的压缩包和破解文件
2. 帮忙好评或者star截图发我，免费赠送PPT+答辩问答20题！！！谢谢谢谢老板！！！

⚠️ Bug添加微信**免费修复**，免费修复。其他平台的私信一律不管（微信方便发送文件）

承接商业项目、课设、毕设和论文，包括但不限于Web、APP、小程序等，课设、毕设提供远程部署和不限次数代码解答！

