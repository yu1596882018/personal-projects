# 个人项目与开源工具

这里汇总了我的技术实践，涵盖前端工具、全栈应用、自动化脚本及逆向研究等方向。

## 📦 NPM 开源工具

### [react-code-extractor](https://github.com/yu1596882018/react-code-extractor)
**React 项目代码迁移/提取工具**

智能解析 React 项目结构与文件依赖，快速提取页面或功能代码，支持自动识别组件依赖关系。

- 🔍 自动解析项目结构与文件依赖
- 🚀 快速提取页面或功能代码
- 📊 可视化依赖关系分析
- **技术栈**: Node.js, Babel, AST

---

### [unreferenced-files-webpack-plugin](https://github.com/yu1596882018/unreferenced-files-webpack-plugin)
**Webpack 未引用文件检测与清理工具**

一键检测并清理项目中未被引用的文件，支持 Webpack 插件与 CLI 两种使用方式，帮助项目瘦身。

- 🧹 自动检测未引用文件
- ⚡ 支持 Webpack 插件与 CLI 模式
- 📋 生成详细的清理报告
- **技术栈**: Webpack, Node.js

---

### [surround-contents](https://github.com/yu1596882018/surround-contents)
**增强版 Range.surroundContents()**

支持跨节点包裹的 DOM 操作工具，专为富文本编辑器选中操作场景设计，解决原生 API 的跨节点限制。

- 🎯 支持跨节点包裹
- 📝 适用于富文本编辑器
- 🔧 兼容性良好
- **技术栈**: JavaScript, DOM API

---

### [universal-code-extractor](https://github.com/yu1596882018/universal-code-extractor)
**通用代码提取工具**

适用于多种框架（React、Vue 等）的通用代码提取解决方案，支持智能依赖分析。

- 🌐 支持多框架
- 🔗 智能依赖分析
- **技术栈**: Node.js

---

### [broad-sdk](https://github.com/yu1596882018/broad-sdk)
**全栈开发工具集 (Monorepo)**

一套面向生产环境的全栈开发工具集，基于 Lerna 管理的 Monorepo 架构，包含 web-sdk 和 server-sdk 两个包，提供前后端统一的日志监控、性能分析、错误追踪等能力。

**技术栈**: JavaScript, Lerna, Elasticsearch, Kibana

---

## 🚀 全栈应用项目

### [楼市查询平台](https://github.com/yu1596882018/changsha-house-mobile) (2021.2)
**前后端一体化的楼盘销售状态查询平台**

针对住建局官网查询界面简陋的痛点，独立开发的移动端查询平台，接入微信公众号对外开放使用，持续运行近一年。

**项目亮点**:
- 📱 前端使用 Vue + Vant 构建移动端界面
- 🔧 后端基于 Koa + MySQL2 + Redis 提供查询服务
- 🕷️ 使用 request-promise + cheerio 编写数据爬虫，同步住建局官网房源数据
- ☁️ 部署于阿里云服务器，使用 PM2 守护后端服务，Nginx 代理并配置 HTTP 缓存
- 📊 利用 Lerna + father-build 管理自研前/后端 SDK
- 🔍 引入自研 MonitorJS 工具，结合 Kibana + Elasticsearch 构建监控平台

**技术栈**: Vue, Vant, Koa, MySQL2, Sequelize, Redis, request-promise, cheerio, Elasticsearch, Kibana, Lerna

**项目地址**:
- 前端: [changsha-house-mobile](https://github.com/yu1596882018/changsha-house-mobile)
- 后端: [changsha-house-backend](https://github.com/yu1596882018/changsha-house-backend)

---

## 🤖 自动化脚本

### [12306 抢票爬虫](https://github.com/yu1596882018/12306-ticket-sniper) (2019.12)
**春运购票自动化解决方案**

应对春运购票难，自编抢票爬虫，成功抢到自己及同事/朋友的高铁票，避免收费抢票软件的优先级问题。

**项目亮点**:
- 🎫 使用 Node.js + superagent 模拟抢票请求
- 📋 Redis 管理任务队列
- 📧 Nodemailer 邮件提醒中签结果
- 🔄 PM2 守护进程保障稳定运行

**技术栈**: Node.js, superagent, Redis, Nodemailer, PM2

**项目地址**: [12306-ticket-sniper](https://github.com/yu1596882018/12306-ticket-sniper)

---

## 🔬 其他

### [storage-transfer-chrome-extension](https://github.com/yu1596882018/storage-transfer-chrome-extension)
**Chrome 扩展 - 存储数据迁移工具**

一键迁移浏览器存储数据的 Chrome 扩展，支持 Cookie、LocalStorage、SessionStorage 的导出/导入/清除操作。

**技术栈**: Chrome Extension API, JavaScript

---

### [frontend-learning-notes](https://github.com/yu1596882018/frontend-learning-notes)
**前端学习笔记**

个人前端学习笔记与技术总结，包含知识图谱的可视化整理。

---

### [qiankun-demo](https://github.com/yu1596882018/qiankun-demo)
**微前端 qiankun 实践 Demo**

基于 qiankun 整合 Angular 与 Vue 的微前端架构 Demo，包含主应用和多个子应用的完整实践。

**技术栈**: qiankun, Vue, Angular

---

### [Flexmonster License 破解（技术研究）](https://github.com/yu1596882018/flexmonster) (2025.5)
**逆向工程技术研究**

因公司 21 年采购的 License 不支持升级到最新版本，业务落地时受限于功能缺失。出于极客精神，通过调试压缩源码，逆向分析并移除 License 校验逻辑。

**说明**: 出于版权考虑，该方案未投入生产，仅作为个人技术研究积累保留（仓库私有）。

---

## 📫 联系方式

- GitHub: [@yu1596882018](https://github.com/yu1596882018)
- Email: 1596882018@qq.com

---

## 📊 技术栈总览

**前端**: Vue, React, Vant, Webpack  
**后端**: Node.js, Koa
**数据库**: MySQL, Redis, Elasticsearch  
**工具链**: Babel, AST, Lerna, father-build  
**运维**: PM2, Nginx, 阿里云  
**其他**: Chrome Extension, 爬虫技术, 逆向工程
