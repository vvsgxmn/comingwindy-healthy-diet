## 接毕业设计和论文

### 作者微信：vvsgxmn  (支持修改、 部署调试、 支持代做毕设)

### 接网站建设、小程序

### 选题+开题报告+任务书+程序定制+安装调试+论文+答辩ppt 都可以做

### 购买地址：[https://www.vvxx.love](https://www.vvxx.love)（vv毕设网）

### 支持 **一键生成 UML 图**：上传项目压缩包即可自动产出功能模块图、用例图、流程图、E-R 图、时序图等全套毕设图表。

### 提供 **免费配套软件下载 + 安装说明 + 部署教程**

![vv毕设网 - 一键画图](https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/uml-draw.png)

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/image-20260825133349317.png" alt="image-20260825133349317" />

⚠️ Bug添加微信**免费修复**，免费修复。其他平台的私信一律不管（微信方便发送文件）

---

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

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/comingwindy-healthy-diet/01-%E7%99%BB%E5%BD%95%E9%A1%B5%E9%9D%A2.png" alt="01-登录页面" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/comingwindy-healthy-diet/02-%E7%AE%A1%E7%90%86%E5%90%8E%E5%8F%B0-%E4%B8%BB%E9%A1%B5.png" alt="02-管理后台-主页" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/comingwindy-healthy-diet/03-%E7%AE%A1%E7%90%86%E5%90%8E%E5%8F%B0-%E9%A3%9F%E6%9D%90%E4%BF%A1%E6%81%AF.png" alt="03-管理后台-食材信息" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/comingwindy-healthy-diet/04-%E7%AE%A1%E7%90%86%E5%90%8E%E5%8F%B0-%E9%A3%9F%E8%B0%B1%E7%AE%A1%E7%90%86.png" alt="04-管理后台-食谱管理" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/comingwindy-healthy-diet/05-%E7%AE%A1%E7%90%86%E5%90%8E%E5%8F%B0-%E7%B3%BB%E7%BB%9F%E5%85%AC%E5%91%8A.png" alt="05-管理后台-系统公告" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/comingwindy-healthy-diet/06-%E7%94%A8%E6%88%B7%E7%AB%AF-%E7%B3%BB%E7%BB%9F%E9%A6%96%E9%A1%B5.png" alt="06-用户端-系统首页" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/comingwindy-healthy-diet/07-%E7%94%A8%E6%88%B7%E7%AB%AF-%E5%81%A5%E5%BA%B7%E6%A1%A3%E6%A1%88.png" alt="07-用户端-健康档案" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/comingwindy-healthy-diet/08-%E7%94%A8%E6%88%B7%E7%AB%AF-%E6%99%BA%E8%83%BD%E6%8E%A8%E8%8D%90.png" alt="08-用户端-智能推荐" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/comingwindy-healthy-diet/UML%E5%9B%BE%E5%88%97%E8%A1%A8.png" alt="UML图列表" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/comingwindy-healthy-diet/%E8%AE%BA%E6%96%87%E5%9B%BE1.png" alt="论文图1" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/comingwindy-healthy-diet/%E8%AE%BA%E6%96%87%E5%9B%BE2.png" alt="论文图2" width="600" />

<!-- screenshots-end -->
