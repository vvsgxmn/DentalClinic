# 基于SpringBoot+Vue的口腔诊所系统

![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) ![Vue3](https://img.shields.io/badge/-Vue3-grey?style=flat-square) ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MyBatis](https://img.shields.io/badge/-MyBatis-000000?style=flat-square&logo=mybatis&logoColor=white) 

## 项目介绍

本系统是一款面向民营口腔诊所与连锁门诊的数字化诊疗与运营平台，针对预约撞期靠微信表格、医生排班与科室项目难统一、病历账单分散、耗材库存难预警、患者评价与科普内容难沉淀等问题，把在线预约挂号、诊疗项目浏览、医生团队展示、电子病历与账单、耗材库存、健康科普与评价反馈，以及管理端科室医生维护、预约审核、耗材盘点与经营看板整合到同一套前后端分离工程中。

系统采用 SpringBoot + Vue 架构，区分患者与系统管理员：患者端完成找科室/项目、选医生预约、查看病历账单、阅读科普与提交评价；管理端维护专科科室、医生与诊疗项目、处理预约与病历账单、管理耗材库存与用户启停，并在 ECharts 看板查看预约与营收趋势。适合作为毕设、课设与口腔门诊数字化学习参考。

## 主要功能模块

- **用户认证与角色分流**：患者与管理员统一登录注册，JWT 鉴权；登录后按角色进入患者门户或管理看板，/admin 路由与接口双重隔离
- **患者首页大厅**：轮播推荐、精选诊疗项目与口腔专家速览，导流至预约与科普
- **诊疗项目浏览**：按科室筛选项目，查看价格时长与图文介绍后发起预约
- **口腔专家团队**：浏览医生职称专长与出诊信息，支持按科室筛选
- **在线预约挂号**：选择医生、项目与时段提交预约，个人中心跟踪状态与取消
- **电子病历与账单**：查看就诊记录与费用明细，支持支付状态查询
- **健康科普与评价**：阅读口腔健康文章，对就诊体验提交评分与文字评价
- **个人中心**：资料密码维护，我的预约、病历、账单与评价集中管理
- **经营数据看板**：预约量、营收与科室占比等 KPI，ECharts 趋势图辅助运营
- **主数据中台**：专科科室、医生档案、诊疗项目上下架与耗材库存预警维护
- **履约与内容审核**：预约审核、病历账单录入、评价审核、科普发布与用户启停
- **论文与 UML 概览**：配套 UML 图列表，便于答辩材料对照

## 技术架构

- **后端**：Spring Boot 2.7 + MyBatis-Plus + JWT + Lombok
- **前端**：Vue 3 + TypeScript + Vue Router + Pinia + Element Plus + Vite + ECharts
- **数据库**：MySQL 8.0

<!-- screenshots-start -->
## 系统截图

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/dentalclinic/%E7%99%BB%E5%BD%95%E9%A1%B5%E9%9D%A2.png" alt="登录页面" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/dentalclinic/%E6%82%A3%E8%80%85%E9%A6%96%E9%A1%B5.png" alt="患者首页" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/dentalclinic/%E8%AF%8A%E7%96%97%E9%A1%B9%E7%9B%AE.png" alt="诊疗项目" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/dentalclinic/%E5%8F%A3%E8%85%94%E4%B8%93%E5%AE%B6.png" alt="口腔专家" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/dentalclinic/%E5%81%A5%E5%BA%B7%E7%A7%91%E6%99%AE.png" alt="健康科普" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/dentalclinic/%E7%AE%A1%E7%90%86%E5%91%98%E6%95%B0%E6%8D%AE%E7%9C%8B%E6%9D%BF.png" alt="管理员数据看板" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/dentalclinic/%E4%B8%93%E7%A7%91%E7%A7%91%E5%AE%A4%E7%AE%A1%E7%90%86.png" alt="专科科室管理" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/dentalclinic/%E8%80%97%E6%9D%90%E5%BA%93%E5%AD%98%E7%AE%A1%E7%90%86.png" alt="耗材库存管理" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/dentalclinic/UML%E5%9B%BE%E5%88%97%E8%A1%A8.png" alt="UML图列表" width="600" />

<!-- screenshots-end -->

---

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
