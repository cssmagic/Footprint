# Footprint · 日拱一卒

***

> ### 背景
> 
> 2022 难得闲暇，决定把自己做过的架构方案、开源项目、技术分享都整理出来！这里不仅会有过去的积累，还会不断添加新的收获。
> 
> © 经验分享 · 日拱一卒 &nbsp; | &nbsp; **Star** = 收藏 &nbsp; | &nbsp; **Watch** = 订阅

***

&nbsp;

## 职业履历

### 2023 · 上海 · 百姓 AI

职位：研发工程师

百姓 AI 是一家专注于 “AI 应用” 赛道的创业公司。主导或参与多个核心项目和孵化项目。

### 2019～2022 · 上海 · OC 公司

职位：资深架构师(前端) / 技术委员会委员

“OC” 公司是一家中型互联网公司，技术团队数百人，产品覆盖 PC 端和移动端。公司虽有十余年历史，但技术积累薄弱。入职后从零开始搭建前端研发体系、完善基础设施、营造技术氛围、推动团队知识管理和梯队建设。

### 2013～2018 · 上海 · 百姓网

职位：前端架构负责人 / 技管委委员

百姓网是国内知名互联网企业，工程师氛围深厚。这段时期是步入职业正轨、成长最快的一个阶段。

### 2008～2013 · 上海 · 电商与广告行业

这段时间经历了三家公司，不断学习和磨练前端技能，也在社区中不断积累影响力。

### 2008 之前 · 老家 · 传统行业

在个人志向的驱动下，通过自学，由传统行业转到互联网行业，从老家来到上海。


## 公司项目

### 2023.02～2023.04 · Chato 企业知识库 AI 机器人（一期）

* 所在公司：百姓 AI
* 角色：项目负责人 / 前端开发
* 项目线上地址：<https://chato.cn/>
* 项目概述：一款基于大语言模型的 To B 的 AIGC 应用，系公司主打产品。用户在此平台可基于 “知识库” 或 “身份设定” 轻松创建 AI 机器人，实现文本或语音形式的自然语言对话，并可接入微信群、公众号、企业官网等应用场景。
* 职责与业绩：
	* 作为项目负责人，完成从零到一的产品设计、项目管理、架构设计。带领另两名研发同事，如期交付，为公司开拓新业务。
	* 完成前端开发工作。

### 2021.03～2021.05 · 开放平台（为整合子系统而生的微前端方案）

* 所在公司：OC
* 角色：项目负责人 / 架构师
* 项目概述：
	* 为解决以下问题：
		* 公司内部各个技术平台（子系统）散落在各处 / 查找和使用不便 / 使用体验不统一；
		* 子系统开发基础功能时重复劳动 / 开发标准不统一 / 成本高；
		* 开发者围绕应用维度的工作流程没有打通等问题；
	* 决定：
		* 基于研发中台 v2 打造 “开放平台”，把子系统以标准化的方式接入平台。
		* 把研发中台的基础数据和基础能力能过 OpenAPI 开放出来，提升各个子系统的功能和体验。
		* 把各个子系统围绕应用维度的功能集合进平台，打通应用维度的工作流程。
* 职责与业绩：
	* 向 CTO 提议发起此项目，担任项目负责人。
	* 作为架构师，主导设计平台核心机制、流程、界面、后端接口 OpenAPI、前端 SDK；指导工程效率组和前端架构组完成研发。
	* 此项目探索出了符合公司现状的内部系统整合方案，上线后接入公司内部管理系统和研发平台共 30 余项。此方案以较低的接入成本和良好的使用体验赢得了各系统研发人员和用户的一致好评，CTO 评价：“可满足公司未来 5 年的技术基建需求”。
	* 此项目成功申报软件著作权一项。
* 项目回顾：[cssmagic/Footprint#9](https://github.com/cssmagic/Footprint/issues/9)

### 2020.11～2020.12 · 研发中台（持续交付平台）v2

* 所在公司：OC
* 角色：产品经理 / 架构师
* 项目概述：“研发中台” 是 OC 公司自研的持续交付 PaaS 平台，具备应用管理、构建部署、资产管理等功能，具备虚拟机与容器两种部署能力，底层对接 GitLab、Jenkins、K8s 等系统，上层为用户提供管理界面。v1 已实现底层对接能力，但功能体验欠佳，落地受阻；v2 由本人发起，着重改善用户端的易用性。
* 职责与业绩：
	* 向 CTO 主动请缨担任 v2 产品经理，以挽救 v1 推广不利的局面。
	* 主导流程、界面、权限、路由的全局设计，提升综合体验；发起“快速部署”和“环境总览”两项新功能，完成相关的界面设计和接口设计，满足日常研发场景下的核心需求；指导工程效率组和前端架构组完成研发。
	* 项目如期交付，CTO 评价：“功能体验和使用效率较 v1 有明显提升，批准在全公司推广落地”。
* 项目回顾：[cssmagic/Footprint#8](https://github.com/cssmagic/Footprint/issues/8)

### 2017.03～2017.06 · 百姓网主站性能优化

* 所在公司：百姓网
* 角色：项目负责人 / 前端架构师
* 项目概述：百姓网在 2017 年春季发起的全站性能优化项目。CTO 只给出最终目标——在年中时间点，桌面和移动两个网站的 “四大核心页面” 的两大指标（首屏渲染、完全加载）分别 ≤1s 和 ≤4s。这是一个非常激进的目标，而具体达成路径需要自行探索和实践。
* 职责与业绩：
	* 作为项目负责人，完成目标拆解，确定优化思路。
	* 优化性能指标监控工具，开发 A/B 测试功能，实现精细化的性能评估。
	* 组织近十人的虚拟团队（横跨架构组+业务开发+商业化等多个技术团队），涵盖前端与后端，与常规工作并行，推进项目整体目标。
	* 项目通过 CTO 验收。
* 项目回顾：[cssmagic/Footprint#2](https://github.com/cssmagic/Footprint/issues/2)

### [更多公司项目 >>](https://github.com/cssmagic/Footprint/issues/10)

&nbsp;

## 架构方案

### 2022 · 业务项目基于 Monorepo 的前端研发工作流

* 所在公司：RJ
* 方案介绍：[cssmagic/Footprint#14](https://github.com/cssmagic/Footprint/issues/14)

### 2020 · 通过 SDK 助力前端项目高效接入 Sentry 和 ARMS

* 所在公司：OC
* 方案概述：（待更新）

### 2019 · 提升 H5 性能的 WebView 缓存方案（Android + iOS）

* 所在公司：OC
* 方案介绍：（待更新）

&nbsp;

## 个人作品

### 出版物

* **2016 · 《CSS 揭秘》** <br>
	https://github.com/cssmagic/CSS-Secrets

	[![封面](https://user-images.githubusercontent.com/1231359/204426759-1e446b8d-2b74-434e-b4b9-53be44298000.png)](https://github.com/cssmagic/CSS-Secrets)
	
	原书《CSS Secrets》是 2015 前端领域最重要的图书之一，堪称 CSS 进阶必读书目。本人翻译的中文版于 2016 年出版，畅销两万册；为这本书编写的万余字注解也在 GitHub 开源。


### 技术分享

* **2024 · B 站直播 《一次看懂 GPTs：如何使用、如何开发、如何赚钱》** <br>
	[第一段](https://www.bilibili.com/video/BV1MN4y1H7aR/) | [第二段](https://www.bilibili.com/video/BV1tV411Q7Jd/) | [第三段](https://www.bilibili.com/video/BV1GC4y1k7KK/) | [第四段](https://www.bilibili.com/video/BV1rT4y147y2/)
	
	[![幻灯片封面](https://github.com/cssmagic/Footprint/assets/1231359/dff97541-b8a3-490a-a884-936d54ef75a9)](https://www.bilibili.com/video/BV1MN4y1H7aR/)

	这是我的 B 站直播回放剪辑。这是一部关于 GPTs 的完整指南，帮助大家快速玩转 GPTs，抓住新机遇。

* **2023 · K+Talk 《AI 编程助手会给程序员带来哪些收益和影响（节选）》** <br>
	https://www.bilibili.com/video/BV1BC4y1U7JZ/
	
	[![视频封面](https://github.com/cssmagic/Footprint/assets/1231359/ebb6e4c8-b1e6-4dd1-ba9f-4d8bea52032f)](https://www.bilibili.com/video/BV1BC4y1U7JZ/)

	这是我受邀参与 “K+Talk” 第 57 期直播对话节目的回放剪辑。本期节目探讨程序员在 AI 时代的机遇和挑战。直播全长 90 分钟，本视频节选部分片断，完整内容参见 “中智凯灵” 视频号。鸣谢另两位嘉宾老师：步绍鹏（微软中国高级研发经理）、李明宇（中科院计算所高级工程师），鸣谢主办方：AIDD（AI+软件研发数字峰会）。

* **2023 · VE 开发者社区 《GitHub Copilot 值不值每月十刀》** <br>
	[第一段](https://www.bilibili.com/video/BV1rF411o7D4/) | [第二段](https://www.bilibili.com/video/BV1Zj411z7Mq/) | [第三段](https://www.bilibili.com/video/BV1qh4y1Q7gC/) | [第四段](https://www.bilibili.com/video/BV1Fc411f79G/)
	
	[![幻灯片封面](https://github.com/cssmagic/Footprint/assets/1231359/a1b49035-6b3b-47dd-9175-7c37204dbb75)](https://www.bilibili.com/video/BV1rF411o7D4/)

	以大量实例讲解了 GitHub Copilot 的原理、用法、技巧，令听众直观感受 AI 辅助编程的魅力，并快速进阶为 AI 时代的高效程序员。

* **2018 · QCon 上海站 《为什么前端工程师更应该掌握区块链 DApp 开发》** <br>
	http://www.cssmagic.net/blog/new/97
	
	[![幻灯片封面](https://user-images.githubusercontent.com/1231359/204426791-6bbf29c8-e52b-49bf-b6ba-c470f1b073bb.png)](http://www.cssmagic.net/blog/new/97)
	
	以讲故事的方式向听众讲解区块链应用的独特魅力、技术原理和开发流程。听众在听完本次分享之后，将对 DApp 的组成和构建具备整体概念，可以立刻着手开发自己 DApp 并上线运行。现场听众满意率极高。

* **2015 · CSS Conf 《重拾 CSS 的乐趣》** <br>
	http://www.cssmagic.net/blog/new/52

	[![幻灯片封面](https://user-images.githubusercontent.com/1231359/204426780-fe125d42-e951-4cc7-aa5c-8e570665799f.png)](http://www.cssmagic.net/blog/new/52)
	
	通过一系列精巧的案例，为听众讲解 CSS 解题思路，分享鲜为人知的 CSS 技巧，广受好评。演讲视频在慕课网发布后，十天播放破万。
	
* [更多技术分享 >>](https://github.com/cssmagic/Footprint/issues/3)


### 开源项目

* **2012～2016 · CMUI** <br>
	http://cmui.net/

	一款专攻 Mobile Web 的 UI 框架。它提供了丰富的组件和简洁的接口，开箱即用；帮助开发者摆脱样式细节和兼容性困扰，从而腾出更多精力投入到业务开发中。CMUI 被百姓网、薇姿官方商城等网站采纳为 UI 层解决方案，每日承受数千万 PV 的考验。

* **2018 · Nasa.js** <br>
	https://github.com/NasaTeam/Nasa.js

	Nasa.js 是星云链 DApp 客户端开发框架，轻量，易用。追求 “体积” 与 “功能” 之间的最佳平衡，满足网页性能的极致追求；专为 Web 前端工程师设计，符合直觉；帮助开发者快速搭建自己的区块链应用。

* [更多开源项目 >>](https://github.com/cssmagic/Footprint/issues/4)


### 博客

* https://github.com/cssmagic/blog/issues <br>
	2014～2019 累计发表百余篇原创文章；在 GitHub 获得两千多 Star，同步更新的微信公众号获得万余名订阅用户。

&nbsp;

## 其它资源

> 包括技术规范、经验分享、教程、杂谈、文档模板等。

* [如何让 Charles 抓取 Node.js 应用发出的 HTTPS 请求](https://github.com/cssmagic/Footprint/issues/7)
* [业务项目 Monorepo 操作指南](https://github.com/cssmagic/Footprint/issues/13)

&nbsp;

（新增内容以 issue 形式发布，持续更新中……）

***

© 经验分享 · 日拱一卒 &nbsp; | &nbsp; **Star** = 收藏 &nbsp; | &nbsp; **Watch** = 订阅
