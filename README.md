# 基于SpringBoot+Vue3的智能健康饮食管理系统

![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) ![Vue3](https://img.shields.io/badge/-Vue3-grey?style=flat-square) ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Pinia](https://img.shields.io/badge/-Pinia-grey?style=flat-square) 

## 项目介绍

健康饮食管理系统是一个前后端分离的全栈项目，面向日常饮食规划与健康管理场景，提供用户端与管理后台两套界面。系统结合 AI 大模型，可根据用户健康档案进行营养分析并生成定制化食谱；用户可查询食材信息、将合适食谱加入每日饮食清单；管理员可管理用户、食材与食谱分类，并发布系统公告。

## 功能模块

- **用户登录与权限管理**：支持管理员与普通用户分角色登录，按角色跳转至管理后台或用户端，基于 JWT 进行接口鉴权
- **个人健康档案**：记录身高、体重、性别、运动量等基础信息，作为食谱推荐依据
- **AI 智能推荐**：对接阿里千问 AI 接口，结合身体数据与饮食偏好，生成一日三餐方案
- **食材与食谱分类管理**：管理员维护食材分类及营养数据，支持增删改；用户可浏览查询食材信息
- **饮食清单记录**：将满意食谱一键加入个人饮食清单，便于记录与监督每日饮食
- **系统通知公告**：管理员发布公告，用户端首页即时展示
- **后台系统管理**：用户与角色管理、系统操作日志查看

## 技术架构

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
