# KardoFlow：Open TapNow & Lovart & Flowith

[English](README_EN.md) | 简体中文

KardoFlow 开源版的 TapNow & Lovart，这俩个都是非常优秀和值得使用的产品，但是有点贵，数据还不在本地，很多隐私信息会暴露，业余时间做了这个项目，欢迎技术交流。

#### 不是假开源！
#### 不是假开源！
#### 不是假开源！
#### 代码太垃圾了，拿不出手，大家提提问题反馈，优化好一点再开，二开也舒服。


## 功能介绍

#### 1.0.1231-pre版
- ✅ 1、工作流：支持批量生成营销图片、营销视频、AI漫剧、AI短剧 
- ✅ 2、图片卡片：支持Nano Banana/MJ/等多个优秀模型 
- ✅ 3、视频卡片：支持Sora2，Veo3，可灵等多个优秀模型 
- ✅ 4、文本卡片：支持Gemini3 Pro，GPT-5.2等多个优秀模型
- ✅ 5、表格卡片：支持数据收集和更新，支持数据分析
- ✅ 6、支持云端托管版 kardo.1mx.cn 和 本地安装版
- ✅ 7、支持多卡片链接，形成各种丰富创意内容，相比N8N更简单，比Coze更直接

#### 1.1.2026 - 预计2026.01.31 发布
- ⌛️ 1、增加多个模型供应商选比，用户可以选择便宜及稳定的模型供应商，降低成本
- ⌛️ 2、增加海螺，字节的几个优秀模型支持
- ⌛️ 3、增加多图编辑和视频编辑的能力
- ⌛️ 4、增加专业镜头设置，分镜能力，脚本能力
- ⌛️ 5、增加声音卡片：支持音乐，人声，素材声生成
- ✅ 6、增加多语言支持，增加浅色主题及跟随系统
- ✅ 7、增加软件升级更新能力
- ✅ 8、增加工具能力，支持网络搜索，定向采集，视频拆片等自定义工具能力
- ⌛️ 9、增加数字人功能，支持流式API调用及定时调用
- ⌛️ 10、开发自定义批量短剧，漫剧等默认工作流能力
- ⌛️ 11、增加优秀提示词能力，快速生成各种类型吸粉视频


## 产品展示

通过卡片的链接实现 高质量AI短剧，高质量AI电影，电商营销图，带货视频，直播方案，智能体卡片包括：文本卡，图片卡，表格卡，音频卡，视频卡，分析卡
![alt text](4d60e2c420997e44f8ff94e2243de508.png)

### AI短剧 & AI电影（创作时长：15 分钟）
![alt text](64cbaed552938f934a114cf098786d84.jpg)
<video controls src="https://github.com/user-attachments/assets/a7499fd3-0a50-4b7b-b1a7-6067284697da" title="Title"></video>

### 电商商品图（创作时长：1 分钟）
![alt text](0ea40210ad30d8f26778bf2d43b0d379.png)
### 营销带货图（创作时长：1.5分钟）
![alt text](9e96a4de0123a949240b893b377d5af8.png)
### 带货视频（创作时长：1 分钟）
![alt text](1a08885c5db841f120ce431a5fd5d4f2.png)
<video controls src="https://github.com/user-attachments/assets/4d2b42dc-b640-44d8-84f6-de224c766abf" title="Title"></video>

- 还有更多 等你探索～
- 抖音低粉高赞转场视频等...
- 性感美女自然跳舞视频等...
- be water my friend 场景等...


## 我们怎么赚钱的
- 稳定供应商模型部分有一定的收入，支持一部分开发和运营成本
- 云端托管版，支持授权贴牌和运维，贴牌用户可以提开发诉求
- 自己也会生成优秀的AI短剧、AI漫剧、营销视频，发布到平台，有对应的奖励
- 企业客户的定制集成和研发

## 上线7天大概积累了1000多用户，好多用户还打赏了，非常感谢
## 项目目前还能够维持研发和运营成本，谁的钱都不容易，在这里感谢大家



### 技术栈
- 后端：Python FastAPI（事件流用 WebSocket）
- 流程引擎：LangGraph（Agent 循环 / 串并行 / 检查点）
- 本地数据库：SQLite + sqlite-vss（轻量 RAG）
- 前端：React + Vite + React Flow（画布 / DAG）

### 工程架构
- desktop
  - backend：桌面端后端（FastAPI）与应用启动器（pywebview）
    - app.py：REST/WS + 静态托管 + SQLite 持久化（workflows/nodes/edges）
    - launch_desktop.py：一键启动（dev/production），子线程运行后端
    - pyproject.toml：uv 项目配置（提供 desktop-backend/desktop-app/desktop-dev 脚本）
    - data/supra.db：本地 SQLite 数据库（运行自动创建）
  - frontend：桌面端前端（React + Vite + React Flow）
    - src/App.tsx：画布 + 运行事件 + 右侧属性面板
    - src/Canvas.tsx：三类节点、连线剪断/重连、工具条、尺寸调整
    - src/Inspector.tsx：节点属性编辑
    - vite.config.ts：开发代理与构建输出到 `../dist`

不是假开源！
不是假开源！
不是假开源！
代码太垃圾了，拿不出手，大家提提问题反馈，优化好一点再放出来，二开也舒服。


请登录世界级同性交友网站自行领取：
https://github.com/libn-net/open_tapnow_lovart/releases/tag/pre-1.0.0



## 交流群：备注（KardoFlow 技术交流）
## 仅作使用和技术交流，请勿发送广告和营销。

![alt text](503eb1ce5a373112b3461debf9052d16.png)
![alt text](8a1714ab2395ac4b5cc8e5756663289a.jpg)

