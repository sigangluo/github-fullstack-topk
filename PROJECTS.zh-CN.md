# Full-Stack Top-K 项目清单

> 本文件由 `scripts/build.py` 自动生成，请勿手动修改。
> GitHub 全站 star 排名前 2000 的仓库中，与全栈开发相关的 **977** 个项目，按「大类 / 小类」整理。排名快照 2026-09-30，star 数更新于 2026-09-30。
> English version: [PROJECTS.md](PROJECTS.md)

## 目录

- [全栈框架与应用骨架](#全栈框架与应用骨架)（77）
  - [全栈与元框架](#全栈与元框架)（14）
  - [静态站点与文档站生成器](#静态站点与文档站生成器)（12）
  - [脚手架与项目模板](#脚手架与项目模板)（24）
  - [管理后台与低代码](#管理后台与低代码)（19）
  - [CMS 与电商平台](#cms-与电商平台)（8）
- [客户端与应用框架](#客户端与应用框架)（53）
  - [前端视图框架](#前端视图框架)（16）
  - [状态、路由与数据请求](#状态路由与数据请求)（16）
  - [移动与跨端应用框架](#移动与跨端应用框架)（9）
  - [桌面应用框架](#桌面应用框架)（12）
- [界面组件与视觉](#界面组件与视觉)（119）
  - [组件库与 CSS 框架](#组件库与-css-框架)（31）
  - [图标、字体与主题](#图标字体与主题)（13）
  - [交互小组件](#交互小组件)（20）
  - [动画与动效](#动画与动效)（13）
  - [编辑器与富文本](#编辑器与富文本)（10）
  - [图表与地图](#图表与地图)（9）
  - [3D、Canvas 与白板绘图](#3dcanvas-与白板绘图)（13）
  - [媒体、文档与演示](#媒体文档与演示)（10）
- [工程化工具链](#工程化工具链)（75）
  - [构建、打包与编译](#构建打包与编译)（16）
  - [代码规范与格式化](#代码规范与格式化)（8）
  - [测试与性能](#测试与性能)（13）
  - [包管理与版本管理](#包管理与版本管理)（18）
  - [开发者体验与 Monorepo](#开发者体验与-monorepo)（20）
- [编程语言与开发环境](#编程语言与开发环境)（124）
  - [编程语言、运行时与编译器](#编程语言运行时与编译器)（25）
  - [代码编辑器与 IDE](#代码编辑器与-ide)（23）
  - [Shell 与终端](#shell-与终端)（29）
  - [Git 与版本控制工具](#git-与版本控制工具)（9）
  - [命令行工具](#命令行工具)（27）
  - [CLI 与 TUI 框架](#cli-与-tui-框架)（11）
- [后端与服务框架](#后端与服务框架)（78）
  - [后端框架](#后端框架)（25）
  - [微服务与服务治理](#微服务与服务治理)（14）
  - [API 与网关](#api-与网关)（25）
  - [认证、身份与密钥](#认证身份与密钥)（10）
  - [后端即服务](#后端即服务)（4）
- [数据与中间件](#数据与中间件)（64）
  - [数据库引擎](#数据库引擎)（18）
  - [ORM 与数据库工具](#orm-与数据库工具)（13）
  - [缓存、搜索与对象存储](#缓存搜索与对象存储)（9）
  - [消息与任务队列](#消息与任务队列)（6）
  - [数据处理与工作流编排](#数据处理与工作流编排)（10）
  - [数据分析、BI 与产品分析](#数据分析bi-与产品分析)（8）
- [通用库与 SDK](#通用库与-sdk)（84）
  - [JS / TS 通用库](#js--ts-通用库)（36）
  - [JVM / Android 通用库](#jvm--android-通用库)（16）
  - [Python / Go / Swift / PHP 通用库](#python--go--swift--php-通用库)（21）
  - [C / C++ 通用库](#c--c-通用库)（11）
- [部署与运维](#部署与运维)（77）
  - [容器与运行时](#容器与运行时)（13）
  - [Kubernetes 与集群管理](#kubernetes-与集群管理)（10）
  - [基础设施即代码](#基础设施即代码)（5）
  - [部署与自托管平台](#部署与自托管平台)（12）
  - [反向代理、证书与隧道](#反向代理证书与隧道)（14）
  - [CI/CD 与自动化](#cicd-与自动化)（10）
  - [监控与可观测](#监控与可观测)（13）
- [学习与教程](#学习与教程)（115）
  - [路线图与综合课程](#路线图与综合课程)（26）
  - [前端、JavaScript 与移动教程](#前端javascript-与移动教程)（19）
  - [编程语言教程](#编程语言教程)（23）
  - [命令行、Git 与运维实践](#命令行git-与运维实践)（17）
  - [操作系统与编译原理](#操作系统与编译原理)（6）
  - [算法与数据结构](#算法与数据结构)（24）
- [面试、规范与清单](#面试规范与清单)（111）
  - [系统设计与面试](#系统设计与面试)（32）
  - [最佳实践与规范](#最佳实践与规范)（22）
  - [前端与移动精选清单](#前端与移动精选清单)（18）
  - [语言、后端与通用精选清单](#语言后端与通用精选清单)（39）

## 全栈框架与应用骨架

一个项目里同时覆盖客户端与服务端的框架、站点生成器、脚手架和现成的应用底座

### 全栈与元框架

自带路由、渲染、数据加载与服务端能力的全栈框架（Next.js、Nuxt、Remix、Rails、Laravel、Django、Phoenix 一类） · 14 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [vercel/next.js](https://github.com/vercel/next.js) | 142.9k | #66 | 官方 · Vercel | 基于 React 的全栈框架，支持服务端渲染、静态生成、App Router 与 React Server Components，内置 Rust 编写的构建工具链。 |
| [django/django](https://github.com/django/django) | 91.2k | #157 | 社区 | Python 的全功能 Web 框架，内置 ORM、管理后台、认证、模板和迁移，遵循「电池全包」的设计理念。 |
| [laravel/laravel](https://github.com/laravel/laravel) | 85k | #181 | 官方 · Laravel | Laravel 应用骨架仓库：PHP 全栈 Web 框架，提供路由、Eloquent ORM、队列、认证和 Blade 模板，以优雅的语法和完整生态著称。 |
| [withastro/astro](https://github.com/withastro/astro) | 62.9k | #338 | 官方 · Astro | 面向内容型网站的 Web 框架，采用「群岛架构」默认输出零 JavaScript，可在同一项目里混用 React、Vue、Svelte 等组件。 |
| [nuxt/nuxt](https://github.com/nuxt/nuxt) | 60.9k | #364 | 社区 | 基于 Vue 的全栈框架，提供文件路由、服务端渲染、自动导入、模块生态和 Nitro 服务引擎，类型安全。 |
| [rails/rails](https://github.com/rails/rails) | 58.8k | #387 | 社区 | Ruby 全栈 Web 框架，遵循 MVC 与「约定优于配置」，内置 Active Record、路由、邮件、任务队列和前端集成。 |
| [streamlit/streamlit](https://github.com/streamlit/streamlit) | 45.9k | #584 | 社区 | 把 Python 脚本快速变成交互式 Web 应用的框架，用几行代码搭建数据看板和原型，无需前端知识。 |
| [meteor/meteor](https://github.com/meteor/meteor) | 44.8k | #609 | 社区 | JavaScript 全栈应用平台，前后端共用一套代码，内置实时数据同步和构建系统，默认搭配 MongoDB。 |
| [DioxusLabs/dioxus](https://github.com/DioxusLabs/dioxus) | 39.3k | #759 | 社区 | Rust 全栈应用框架，用一套代码构建 Web、桌面和移动应用，提供热重载、服务端函数与类似 React 的组件模型。 |
| [laravel/framework](https://github.com/laravel/framework) | 34.9k | #937 | 官方 · Laravel | Laravel 框架核心代码仓库，包含路由、Eloquent ORM、队列、缓存、验证等核心组件，用于开发 Laravel 本身。 |
| [remix-run/remix](https://github.com/remix-run/remix) | 33.4k | #1026 | 社区 | Remix 3 的源码仓库，主打「全栈」的 Web 框架，基于 Web 标准构建，正在积极开发中。 |
| [reflex-dev/reflex](https://github.com/reflex-dev/reflex) | 28.9k | #1327 | 官方 · Reflex | 用纯 Python 构建全栈 Web 应用的框架，前端界面与后端逻辑都用 Python 编写，编译为 React 前端。 |
| [phoenixframework/phoenix](https://github.com/phoenixframework/phoenix) | 23.2k | #1873 | 社区 | Elixir 的 Web 框架，基于 Erlang 虚拟机，提供 LiveView 实时交互、Channels 与高并发能力。 |
| [balderdashy/sails](https://github.com/balderdashy/sails) | 22.8k | #1915 | 社区 | 面向 Node.js 的实时 MVC 框架，借鉴 Rails，提供 Waterline ORM、自动生成 REST API 与 WebSocket 支持。 |

### 静态站点与文档站生成器

Hugo、Jekyll、Gatsby、Hexo 等静态站点生成器，以及 Docusaurus、VuePress、MkDocs 一类的文档站工具 · 12 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [gohugoio/hugo](https://github.com/gohugoio/hugo) | 90k | #171 | 社区 | Go 编写的静态站点生成器，以构建速度极快著称，支持主题、短代码、多语言和 Markdown 内容，常用于博客与文档站。 |
| [facebook/docusaurus](https://github.com/facebook/docusaurus) | 66.4k | #302 | 官方 · Meta | Meta 开源的文档站点生成器，基于 React，支持 Markdown / MDX、版本管理、多语言和搜索，很多开源项目文档站使用它。 |
| [gatsbyjs/gatsby](https://github.com/gatsbyjs/gatsby) | 55.9k | #417 | 社区 | 基于 React 和 GraphQL 的静态站点框架，构建时聚合各类数据源生成高性能站点，曾是 JAMstack 代表。 |
| [jekyll/jekyll](https://github.com/jekyll/jekyll) | 51.7k | #476 | 社区 | Ruby 编写的静态站点生成器，把 Markdown 和 Liquid 模板转成静态网站，是 GitHub Pages 的原生引擎。 |
| [hexojs/hexo](https://github.com/hexojs/hexo) | 41.8k | #679 | 社区 | 基于 Node.js 的快速博客框架，把 Markdown 生成静态网站，支持主题和插件，并可一键部署到 GitHub Pages 等。 |
| [docsifyjs/docsify](https://github.com/docsifyjs/docsify) | 31.5k | #1134 | 社区 | 文档站点生成器，运行时把 Markdown 渲染成网站，无需构建，适合快速搭建项目文档。 |
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 29.1k | #1311 | 官方 · GitBook | GitBook 用于渲染已发布内容的开源前端代码，GitBook 是面向团队的技术知识管理平台，仓库也说明了本地运行方式与贡献流程。 |
| [squidfunk/mkdocs-material](https://github.com/squidfunk/mkdocs-material) | 27.5k | #1434 | 社区 | 基于 MkDocs 的 Material Design 文档主题，用 Markdown 快速生成美观、可搜索、响应式的项目文档站。 |
| [pedronauck/docz](https://github.com/pedronauck/docz) 🗄️已归档 | 23.6k | #1825 | 社区 | 用 MDX 为代码编写并发布交互式文档的工具，把 MDX 文件变成支持热重载、对 SEO 友好的生产级文档站，并可自定义外观；仓库已归档。 |
| [vuejs/vuepress](https://github.com/vuejs/vuepress) | 22.7k | #1921 | 社区 | Vue 驱动的极简静态站点生成器，v1 已进入维护模式，官方推荐改用 VitePress。 |
| [mkdocs/mkdocs](https://github.com/mkdocs/mkdocs) | 22.5k | #1959 | 社区 | 用 Markdown 编写项目文档的静态站点生成器，配置只需一个 YAML 文件，Material 主题是常用搭配。 |
| [rust-lang/mdBook](https://github.com/rust-lang/mdBook) | 22.2k | #1997 | 社区 | 用 Markdown 文件创建在线书籍的工具，类似 GitBook 但用 Rust 实现，用户指南本身即是成书效果的示范。 |

### 脚手架与项目模板

SaaS 模板、全栈起步项目、示例应用和最佳实践参考实现，以及 .gitignore 等项目配置模板 · 24 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [github/gitignore](https://github.com/github/gitignore) | 176k | #47 | 官方 · GitHub | GitHub 官方维护的 .gitignore 模板集合，用于填充 GitHub 网页上创建仓库和文件时的 .gitignore 模板选择器，覆盖各类语言、框架与编辑器。 |
| [react/create-react-app](https://github.com/react/create-react-app) | 103.2k | #122 | 社区 | 一条命令创建 React 单页应用的脚手架，基于 webpack，曾是官方推荐的起步方式，现已弃用，官方建议改用 React 框架。 |
| [macrozheng/mall](https://github.com/macrozheng/mall) | 84.9k | #182 | 社区 | 基于 Spring Boot 和 MyBatis 的电商系统示例，包含前台商城与后台管理，配套完整教程，并以 Docker 容器化部署，是国内常见的 Java 全栈学习项目。 |
| [realworld-apps/realworld](https://github.com/realworld-apps/realworld) | 84.2k | #188 | 社区 | 「RealWorld」全栈示例：同一个 Medium 克隆应用，用不同前端（React、Angular 等）和后端（Node、Django 等）实现，共享统一 API 规范，可任意组合。 |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 57.6k | #399 | 社区 | 前端模板项目，汇集十多年社区经验的合理默认值（重置样式、缓存与安全配置等），作为构建快速健壮网站的起点。 |
| [golang-standards/project-layout](https://github.com/golang-standards/project-layout) | 56.7k | #409 | 社区 | Go 项目的常见目录结构约定（cmd、internal、pkg 等），社区总结的布局参考，并非官方标准。 |
| [android/architecture-samples](https://github.com/android/architecture-samples) | 45.8k | #585 | 官方 · Google | Google 官方的 Android 架构示例，用同一个 TODO 应用演示不同架构模式与工具的实现差异。 |
| [fastapi/full-stack-fastapi-template](https://github.com/fastapi/full-stack-fastapi-template) | 45.8k | #586 | 社区 | FastAPI 官方全栈模板，整合 FastAPI、SQLModel、PostgreSQL、React、Tailwind 与 Docker Compose，含认证、邮件和 CI 配置。 |
| [bailicangdu/vue2-elm](https://github.com/bailicangdu/vue2-elm) | 41k | #699 | 社区 | 基于 Vue 2 与 Vuex 的 45 页大型单页应用，仿饿了么外卖，含购物车、登录注册等复杂交互，用作 Vue 实战示例。 |
| [alan2207/bulletproof-react](https://github.com/alan2207/bulletproof-react) | 35.9k | #901 | 社区 | 面向生产的 React 应用架构示例，展示项目结构、状态管理、测试、性能和安全等方面的最佳实践。 |
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 35.3k | #925 | 社区 | Node.js Web 应用样板，预置 Express、多种 OAuth 登录、MongoDB 和常见第三方 API 示例，为黑客松缩短起步时间。 |
| [xkcoding/spring-boot-demo](https://github.com/xkcoding/spring-boot-demo) | 34.1k | #980 | 社区 | 深入学习 Spring Boot 的实战项目，包含六十多个集成示例，涵盖监控、日志、缓存、消息队列、权限与第三方登录等。 |
| [ityouknow/spring-boot-examples](https://github.com/ityouknow/spring-boot-examples) | 30.5k | #1188 | 社区 | Spring Boot 学习示例集，每个示例依赖最少、力求简单实用，覆盖 Web、数据访问、缓存、消息等常见集成。 |
| [react-boilerplate/react-boilerplate](https://github.com/react-boilerplate/react-boilerplate) | 29.5k | #1275 | 社区 | 可扩展、离线优先的 React 项目起点，预置 Redux、Redux-Saga、Reselect 和测试配置，强调性能与最佳实践。 |
| [t3-oss/create-t3-app](https://github.com/t3-oss/create-t3-app) | 29.1k | #1305 | 社区 | 交互式命令行工具，生成全栈、类型安全的 Next.js 应用（T3 Stack：Next.js、TypeScript、tRPC、Tailwind、Prisma 等）。 |
| [tastejs/todomvc](https://github.com/tastejs/todomvc) | 29k | #1323 | 社区 | 用同一个 Todo 应用在 React、Angular、Vue 等众多 JavaScript 框架中的实现，帮助比较和选择框架。 |
| [lenve/vhr](https://github.com/lenve/vhr) | 28.1k | #1404 | 社区 | 基于 Spring Boot 与 Vue 的前后端分离人力资源管理系统「微人事」，可作为中后台全栈实战参考。 |
| [cookiecutter/cookiecutter](https://github.com/cookiecutter/cookiecutter) | 25.1k | #1657 | 社区 | 跨平台命令行工具，根据项目模板（cookiecutter）快速生成项目骨架，支持变量替换。 |
| [dotnet-architecture/eShopOnContainers](https://github.com/dotnet-architecture/eShopOnContainers) 🗄️已归档 | 24.3k | #1746 | 社区 | 基于 .NET 与容器的跨平台微服务示例应用，演示 Docker 和 Kubernetes 部署，已迁移到新的 eShop 仓库。 |
| [electron-react-boilerplate/electron-react-boilerplate](https://github.com/electron-react-boilerplate/electron-react-boilerplate) | 24.3k | #1752 | 社区 | Electron 加 React 的桌面应用样板，整合 React Router、electron-vite 和热更新，作为可扩展跨平台应用的起点。 |
| [kriasoft/react-starter-kit](https://github.com/kriasoft/react-starter-kit) | 23.7k | #1811 | 社区 | 现代 React 全栈 Monorepo 模板，整合 Bun、TypeScript、Tailwind、tRPC、Stripe 和 Cloudflare Workers，用于搭建 SaaS 应用。 |
| [android/compose-samples](https://github.com/android/compose-samples) | 23.5k | #1834 | 官方 · Google | Google 官方 Jetpack Compose 示例合集，包含多个独立 Android Studio 项目，演示不同的 Compose 用法。 |
| [mitesh77/Best-Flutter-UI-Templates](https://github.com/mitesh77/Best-Flutter-UI-Templates) | 22.8k | #1910 | 社区 | 免费的 Flutter UI 模板合集，提供酒店预订、健身、设计课程等完整界面示例。 |
| [jhipster/generator-jhipster](https://github.com/jhipster/generator-jhipster) | 22.5k | #1961 | 社区 | 快速生成、开发并部署现代 Web 应用与微服务的开发平台，结合 Spring Boot 后端和 Angular、React、Vue 前端。 |

### 管理后台与低代码

后台管理模板、内部工具、低代码 / 无代码应用构建平台与工作流搭建工具 · 19 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [PanJiaChen/vue-element-admin](https://github.com/PanJiaChen/vue-element-admin) | 90.2k | #169 | 社区 | 基于 Vue 与 Element UI 的后台管理前端方案，内置权限验证、动态路由、多环境构建和典型业务模板，是国内流行的 Vue 后台脚手架。 |
| [nocodb/nocodb](https://github.com/nocodb/nocodb) | 65.1k | #317 | 官方 · NocoDB | 可自托管的 Airtable 开源替代品，把 MySQL、Postgres、SQLite 等数据库变成带表格视图的界面，并自动生成 API。 |
| [Zie619/n8n-workflows](https://github.com/Zie619/n8n-workflows) | 56.9k | #406 | 社区 | 收集的 n8n 自动化工作流模板合集，可通过基于 SQLite FTS5 的在线搜索界面浏览，也提供 Docker 镜像本地运行。 |
| [huginn/huginn](https://github.com/huginn/huginn) | 50k | #500 | 社区 | 用于构建自动执行任务的代理系统，代理读取网页、监听事件并采取行动，事件沿有向图传播，可看作自托管、可深度定制的 IFTTT 或 Zapier。 |
| [jeecgboot/JeecgBoot](https://github.com/jeecgboot/JeecgBoot) | 48k | #537 | 社区 | 企业级低代码平台，可在线配置并一键生成前后端代码、表单、报表与流程，基于 Spring Boot 与 Vue，并集成 AI 应用能力。 |
| [ColorlibHQ/AdminLTE](https://github.com/ColorlibHQ/AdminLTE) | 45.6k | #591 | 社区 | 基于 Bootstrap 5 的免费后台管理面板模板，纯原生 JavaScript，响应式并高度可定制。 |
| [tabler/tabler](https://github.com/tabler/tabler) | 41.8k | #677 | 社区 | 基于 Bootstrap 5 的免费开源 HTML 仪表盘 UI 套件，提供丰富的页面模板和组件，含多个框架版本。 |
| [ToolJet/ToolJet](https://github.com/ToolJet/ToolJet) | 41k | #697 | 官方 · ToolJet | 开源内部工具与应用生成平台，可视化搭建管理后台、仪表盘、业务应用与工作流，连接数据库和 API。 |
| [appsmithorg/appsmith](https://github.com/appsmithorg/appsmith) | 41k | #701 | 官方 · Appsmith | 开源低代码平台，用来搭建管理后台、内部工具和仪表盘，可连接二十多种数据库和任意 API，可自托管。 |
| [YunaiV/ruoyi-vue-pro](https://github.com/YunaiV/ruoyi-vue-pro) | 39.5k | #756 | 社区 | 基于 Spring Boot、MyBatis Plus 与 Vue 的后台管理系统（RuoYi-Vue 的 Pro 版），含 RBAC 权限、多租户、工作流、支付、商城等模块，全部开源。 |
| [ant-design/ant-design-pro](https://github.com/ant-design/ant-design-pro) | 38.8k | #775 | 官方 · Ant Group | 基于 Ant Design 的企业级中后台 React 脚手架，内置布局、路由、权限和数据流方案与常见业务页面。 |
| [refinedev/refine](https://github.com/refinedev/refine) | 35.7k | #905 | 官方 · Refine | 面向 CRUD 密集型应用的 React 元框架，用来构建内部工具、管理后台和 B2B 应用，介于低代码与从零开发之间。 |
| [vbenjs/vue-vben-admin](https://github.com/vbenjs/vue-vben-admin) | 33.5k | #1016 | 社区 | 基于 Vue 3、Vite、TypeScript 与 Shadcn UI 的开源中后台模板，采用 Monorepo 结构，提供多套 UI 适配。 |
| [filamentphp/filament](https://github.com/filamentphp/filament) | 32.2k | #1089 | 社区 | 面向 Laravel 的 UI 框架，基于 Livewire，可快速搭建管理后台、表单、表格和应用界面。 |
| [marmelab/react-admin](https://github.com/marmelab/react-admin) | 26.9k | #1489 | 官方 · Marmelab | 在 REST / GraphQL API 之上构建单页管理应用的 React 前端框架，基于 Material Design，提供列表、表单和数据提供者抽象。 |
| [GrapesJS/grapesjs](https://github.com/GrapesJS/grapesjs) | 26.3k | #1543 | 社区 | 开源的网页构建器框架，可视化拖拽设计页面与邮件模板，可嵌入到自己的产品中。 |
| [akveo/ngx-admin](https://github.com/akveo/ngx-admin) | 25.7k | #1600 | 官方 · Akveo | 基于 Angular 的可定制后台管理面板模板，含多套主题和大量页面示例。 |
| [flipped-aurora/gin-vue-admin](https://github.com/flipped-aurora/gin-vue-admin) | 25.1k | #1661 | 社区 | 基于 Vite、Vue 3 与 Gin 的后台管理开发平台，内置 JWT 认证、权限管理、代码生成器、表单生成器和导入导出等企业常用功能。 |
| [node-red/node-red](https://github.com/node-red/node-red) | 23.7k | #1809 | 社区 | 面向事件驱动应用的低代码编程工具，用浏览器中的可视化流程把设备、API 和服务连接起来，基于 Node.js。 |

### CMS 与电商平台

无头 CMS、博客 / 建站系统与无头电商平台（Strapi、Ghost、Payload、Directus、Medusa、Saleor 一类） · 8 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [strapi/strapi](https://github.com/strapi/strapi) | 73.3k | #260 | 官方 · Strapi | 开源无头 CMS，用 JavaScript / TypeScript 编写，提供可视化内容类型建模、自动生成的 REST 与 GraphQL API、管理面板和权限系统，可自托管。 |
| [TryGhost/Ghost](https://github.com/TryGhost/Ghost) | 55.5k | #422 | 社区 | 开源出版与会员订阅平台，用 Node.js 编写，提供写作编辑器、邮件通讯、付费会员和无头 API，可自托管。 |
| [payloadcms/payload](https://github.com/payloadcms/payload) | 45k | #605 | 官方 · Payload | 基于 Next.js 的全栈框架和无头 CMS，用 TypeScript 配置生成后端、管理面板和 API，可嵌入现有 Next.js 项目。 |
| [halo-dev/halo](https://github.com/halo-dev/halo) | 39.9k | #735 | 社区 | Java 编写的开源建站工具，可搭建博客、知识库、企业官网和商城，提供插件与主题体系，可用 Docker 快速部署。 |
| [directus/directus](https://github.com/directus/directus) | 38k | #809 | 官方 · Directus | 把任意 SQL 数据库变成无头 CMS 和管理后台，即时生成 REST 与 GraphQL API，提供可视化工作室与权限管理。 |
| [medusajs/medusa](https://github.com/medusajs/medusa) | 36.5k | #872 | 官方 · Medusa | 开源的电商平台与内置定制框架，以模块化构件构建自定义商业应用，涵盖商品、订单、支付、库存与管理后台，可自托管或使用云服务。 |
| [bagisto/bagisto](https://github.com/bagisto/bagisto) | 28.2k | #1392 | 社区 | 基于 Laravel 和 Vue.js 的开源电商与多商户市场平台，用于搭建单商户店铺、B2B 电商与多商户市场。 |
| [saleor/saleor](https://github.com/saleor/saleor) | 23.4k | #1844 | 官方 · Saleor | 基于 GraphQL 的无头电商 API 平台，采用纯 API 架构与技术栈无关的设计，提供商品、订单、结账与仪表盘等能力。 |

## 客户端与应用框架

用户直接接触的一层：网页、移动端、桌面端与小程序的应用框架

### 前端视图框架

React、Vue、Angular、Svelte、Solid 等视图框架，以及 jQuery、htmx、Alpine 一类的轻量方案 · 16 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [react/react](https://github.com/react/react) | 250.8k | #17 | 社区 | Meta 主导的声明式 UI 库，以组件和虚拟 DOM 为核心，同时支持 Web 与原生应用，是当前最主流的前端视图框架之一。 |
| [vuejs/vue](https://github.com/vuejs/vue) | 212.8k | #24 | 社区 | Vue 2 的代码仓库，渐进式 JavaScript 前端框架，已于 2023 年底结束维护，Vue 3 迁至 vuejs/core。 |
| [angular/angular](https://github.com/angular/angular) | 101k | #126 | 社区 | Google 主导的 TypeScript 前端平台，提供组件、依赖注入、路由、表单、HTTP 等完整能力，面向大型应用。 |
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 88.2k | #177 | 社区 | 以编译器方式工作的前端框架，在构建阶段把声明式组件转成直接更新 DOM 的 JavaScript，没有虚拟 DOM，运行时体积小。 |
| [jquery/jquery](https://github.com/jquery/jquery) | 59.8k | #377 | 社区 | 经典 JavaScript 库，简化 DOM 操作、事件处理、Ajax 和动画，抹平早期浏览器差异，仍存在于大量存量网站中。 |
| [angular/angular.js](https://github.com/angular/angular.js) 🗄️已归档 | 58.5k | #389 | 社区 | AngularJS（Angular 1.x），早期的 MVC 前端框架，用指令扩展 HTML 并提供双向数据绑定，已停止维护。 |
| [vuejs/core](https://github.com/vuejs/core) | 54.5k | #435 | 社区 | Vue 3 的核心仓库，渐进式 JavaScript 前端框架，采用组合式 API 与响应式系统，可从简单页面逐步扩展到大型应用。 |
| [bigskysoftware/htmx](https://github.com/bigskysoftware/htmx) | 49.5k | #512 | 社区 | 让 HTML 直接通过属性发起 AJAX、WebSocket 和 SSE 请求并做 CSS 过渡，无需写 JavaScript 就能做出现代交互，倾向于服务端渲染。 |
| [preactjs/preact](https://github.com/preactjs/preact) | 38.9k | #771 | 社区 | 仅几 KB 的 React 轻量替代，保持相同的现代 API（hooks、组件、虚拟 DOM），可通过兼容层使用 React 生态。 |
| [solidjs/solid](https://github.com/solidjs/solid) | 36.1k | #891 | 社区 | 声明式 JavaScript UI 库，不用虚拟 DOM，把模板编译为真实 DOM 节点并用细粒度响应式更新，性能突出。 |
| [yewstack/yew](https://github.com/yewstack/yew) | 32.8k | #1059 | 社区 | Rust / WebAssembly 前端框架，用类似 React 的组件与 JSX 风格宏构建客户端 Web 应用。 |
| [alpinejs/alpine](https://github.com/alpinejs/alpine) | 32k | #1102 | 社区 | 轻量的 JavaScript 框架，直接在 HTML 标记里用属性声明交互行为，语法类似 Vue，适合给服务端渲染页面添加交互。 |
| [jashkenas/backbone](https://github.com/jashkenas/backbone) | 28.1k | #1400 | 社区 | 早期的 JavaScript MVC 库，提供模型、视图、集合和事件，为前端应用提供基本结构。 |
| [quasarframework/quasar](https://github.com/quasarframework/quasar) | 27.2k | #1466 | 社区 | 基于 Vue.js 的跨平台框架，用一套代码构建 SPA、SSR、PWA、移动应用和 Electron 桌面应用，自带组件库。 |
| [livewire/livewire](https://github.com/livewire/livewire) | 23.6k | #1823 | 社区 | Laravel 的全栈框架，用 PHP 编写动态 UI 组件，无需手写 JavaScript 就能获得类似单页应用的交互。 |
| [emberjs/ember.js](https://github.com/emberjs/ember.js) | 22.6k | #1942 | 社区 | 面向「雄心勃勃」Web 应用的 JavaScript 框架，强调约定优于配置、稳定升级和完整的路由与数据层。 |

### 状态、路由与数据请求

状态管理、路由、数据请求与缓存、表单和 Hooks 工具库（Redux、Zustand、React Router、TanStack Query、Axios 一类） · 16 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [axios/axios](https://github.com/axios/axios) | 109.2k | #112 | 社区 | 基于 Promise 的 HTTP 客户端，同时支持浏览器和 Node.js，提供拦截器、请求取消、自动 JSON 转换等功能。 |
| [reduxjs/redux](https://github.com/reduxjs/redux) | 61.5k | #355 | 社区 | JavaScript 应用的可预测全局状态容器，通过单向数据流、纯函数 reducer 和中间件管理状态，常与 React 配合。 |
| [pmndrs/zustand](https://github.com/pmndrs/zustand) | 58.8k | #388 | 社区 | 小巧、快速的 React 状态管理库，基于 hooks，API 极简、无需 Provider 和样板代码。 |
| [remix-run/react-router](https://github.com/remix-run/react-router) | 56.6k | #410 | 社区 | React 的声明式路由库，支持嵌套路由、数据加载与提交，并可作为框架模式使用，已与 Remix 合并发展。 |
| [TanStack/query](https://github.com/TanStack/query) | 50.4k | #492 | 社区 | 异步状态管理库，负责服务端数据的请求、缓存、同步与更新，提供 React、Vue、Solid、Svelte 等适配。 |
| [react-hook-form/react-hook-form](https://github.com/react-hook-form/react-hook-form) | 44.9k | #607 | 社区 | 高性能的 React 表单状态管理与校验库，基于 hooks 和非受控组件，重渲染少、体积小，也支持 React Native。 |
| [streamich/react-use](https://github.com/streamich/react-use) | 44k | #628 | 社区 | React Hooks 合集，提供传感器、UI、动画、状态等数十种常用 hook。 |
| [jaredpalmer/formik](https://github.com/jaredpalmer/formik) | 34.3k | #965 | 社区 | React 表单库，处理表单状态、校验、提交和错误提示，减少样板代码。 |
| [vercel/swr](https://github.com/vercel/swr) | 32.5k | #1069 | 官方 · Vercel | React 数据请求 hooks 库，采用「先返回缓存再重新验证」（stale-while-revalidate）策略，自动缓存、重试与聚焦刷新。 |
| [statelyai/xstate](https://github.com/statelyai/xstate) | 30.2k | #1207 | 官方 · Stately | 基于状态机和 actor 模型的 JavaScript / TypeScript 状态管理与编排库，适合复杂业务逻辑，并提供可视化工具。 |
| [vuejs/vuex](https://github.com/vuejs/vuex) | 28.3k | #1376 | 社区 | Vue 的集中式状态管理库，官方推荐现已改用 Pinia，Vuex 处于维护状态。 |
| [mobxjs/mobx](https://github.com/mobxjs/mobx) | 28.2k | #1386 | 社区 | 简单可扩展的状态管理库，基于透明的函数式响应式编程，状态变化自动驱动 UI 更新，常与 React 搭配。 |
| [react-navigation/react-navigation](https://github.com/react-navigation/react-navigation) | 24.5k | #1719 | 社区 | React Native 与 Web 应用的路由和导航库，提供栈、标签页、抽屉等导航模式。 |
| [reduxjs/react-redux](https://github.com/reduxjs/react-redux) | 23.4k | #1840 | 社区 | Redux 官方的 React 绑定，提供 Provider 与 hooks，让组件高效读取 store 并派发 action。 |
| [redux-saga/redux-saga](https://github.com/redux-saga/redux-saga) | 22.4k | #1970 | 社区 | Redux 的副作用管理库，用 Generator 函数以同步风格编排异步流程，便于测试。 |
| [vueuse/vueuse](https://github.com/vueuse/vueuse) | 22.4k | #1977 | 社区 | 面向 Vue 3 的组合式工具函数集合，提供数百个覆盖浏览器、传感器、状态等的常用 composable，也兼容 Vue 2。 |

### 移动与跨端应用框架

Android / iOS 开发框架、Flutter、React Native、Expo、Ionic 与小程序跨端框架 · 9 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [flutter/flutter](https://github.com/flutter/flutter) | 179.2k | #45 | 社区 | Google 的跨平台 UI 工具包，使用 Dart 语言，一套代码构建移动、Web 和桌面应用，自带渲染引擎和丰富的 Material / Cupertino 组件。 |
| [react/react-native](https://github.com/react/react-native) | 126.8k | #86 | 社区 | 用 React 构建原生 Android / iOS 应用的框架，JavaScript 编写业务逻辑并渲染为真正的原生组件。 |
| [ionic-team/ionic-framework](https://github.com/ionic-team/ionic-framework) | 52.7k | #460 | 官方 · Ionic | 基于 Web Components 的跨平台 UI 工具包，用 HTML、CSS、JavaScript 一套代码构建 iOS、Android 与 PWA 应用，可搭配 Angular、React、Vue。 |
| [expo/expo](https://github.com/expo/expo) | 52.5k | #461 | 官方 · Expo | 构建 React 原生通用应用的开源框架与平台，提供 SDK、开发工具和云构建服务，覆盖 Android、iOS 和 Web。 |
| [dcloudio/uni-app](https://github.com/dcloudio/uni-app) | 41.6k | #683 | 官方 · DCloud | 用 Vue.js 开发所有前端应用的跨平台框架，一套代码可发布到 iOS、Android、Web 以及微信、支付宝等各类小程序。 |
| [NervJS/taro](https://github.com/NervJS/taro) | 37.7k | #818 | 社区 | 开放式跨端跨框架方案，用 React、Vue 等开发，可编译为微信、支付宝、京东等小程序以及 H5 和 React Native 应用。 |
| [NativeScript/NativeScript](https://github.com/NativeScript/NativeScript) | 25.7k | #1603 | 社区 | 用 TypeScript 直接调用 iOS 和 Android 原生 API 的跨平台框架，可搭配 Angular、React、Vue、Svelte 等。 |
| [dotnet/maui](https://github.com/dotnet/maui) | 23.3k | #1854 | 社区 | .NET 多平台应用 UI（.NET MAUI），用 C# 一套代码构建 Android、iOS、macOS 和 Windows 的原生应用。 |
| [Tencent/wepy](https://github.com/Tencent/wepy) 🗄️已归档 | 22.5k | #1949 | 官方 · Tencent | 腾讯的小程序组件化开发框架，支持组件化和 Vue 风格语法，项目已归档。 |

### 桌面应用框架

Electron、Tauri、Wails 一类的桌面应用框架，以及 Rust / Go / C# 的原生 GUI 工具包 · 12 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [electron/electron](https://github.com/electron/electron) | 123.3k | #89 | 社区 | 用 JavaScript、HTML 和 CSS 构建跨平台桌面应用的框架，内嵌 Chromium 与 Node.js，VS Code 等众多桌面应用基于它开发。 |
| [tauri-apps/tauri](https://github.com/tauri-apps/tauri) | 111.5k | #104 | 社区 | 用 Web 前端加 Rust 后端构建体积小、安全的桌面与移动应用的框架，使用系统 WebView 而非内嵌浏览器，可搭配任意前端框架。 |
| [ocornut/imgui](https://github.com/ocornut/imgui) | 76.4k | #232 | 社区 | Dear ImGui：面向 C++ 的轻量图形用户界面库，依赖极少，采用即时模式设计。 |
| [tw93/Pake](https://github.com/tw93/Pake) | 61.8k | #351 | 社区 | 一条命令把任意网页打成轻量桌面应用，基于 Tauri 与 Rust，支持 macOS、Windows 和 Linux，体积远小于 Electron 方案。 |
| [nwjs/nw.js](https://github.com/nwjs/nw.js) | 41.2k | #691 | 社区 | 基于 Chromium 与 Node.js 的应用运行时（原名 node-webkit），可用 HTML 和 JavaScript 编写桌面应用并直接调用 Node 模块。 |
| [wailsapp/wails](https://github.com/wailsapp/wails) | 36.4k | #878 | 社区 | 用 Go 与 Web 技术构建桌面应用的框架，前端用任意 Web 框架，后端 Go 方法可直接被前端调用。 |
| [nativefier/nativefier](https://github.com/nativefier/nativefier) 🗄️已归档 | 35.3k | #924 | 社区 | 一条命令把任意网页打包成桌面应用（基于 Electron），已不再维护。 |
| [iced-rs/iced](https://github.com/iced-rs/iced) | 31.6k | #1129 | 社区 | 受 Elm 启发的 Rust 跨平台 GUI 库，强调简洁与类型安全，采用消息驱动的架构。 |
| [AvaloniaUI/Avalonia](https://github.com/AvaloniaUI/Avalonia) | 31.6k | #1130 | 官方 · Avalonia | .NET 跨平台 UI 框架，用 C# 与 XAML 开发桌面、嵌入式、移动和 WebAssembly 应用，自绘控件、样式系统灵活。 |
| [emilk/egui](https://github.com/emilk/egui) | 30.8k | #1176 | 社区 | 纯 Rust 的即时模式（immediate mode）GUI 库，可同时运行在原生桌面和浏览器（WebAssembly）中。 |
| [fyne-io/fyne](https://github.com/fyne-io/fyne) | 28.7k | #1339 | 社区 | 受 Material Design 启发的 Go 跨平台 GUI 工具包，用 Go 写一份代码即可构建桌面和移动应用。 |
| [slint-ui/slint](https://github.com/slint-ui/slint) | 24k | #1770 | 官方 · Slint | 声明式 GUI 工具包，用 .slint 描述界面，可为 Rust、C++、JavaScript、Python 应用构建嵌入式与桌面原生界面。 |

## 界面组件与视觉

搭建界面用的现成组件与图形库：组件库、动效、图表与图形、编辑器、交互小组件和媒体组件

### 组件库与 CSS 框架

组件库、设计系统和 CSS / 样式框架（shadcn/ui、Ant Design、Bootstrap、Tailwind 一类） · 31 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [twbs/bootstrap](https://github.com/twbs/bootstrap) | 174.9k | #48 | 社区 | 最流行的 HTML / CSS / JS 前端框架之一，提供响应式栅格、预置组件和 Sass 变量，主打移动优先的快速开发。 |
| [shadcn-ui/ui](https://github.com/shadcn-ui/ui) | 124.9k | #87 | 社区 | 一套可访问、可定制的 React 组件，以「复制代码到自己项目」的方式分发而非 npm 依赖，基于 Radix UI 与 Tailwind CSS，提供 CLI 安装。 |
| [ant-design/ant-design](https://github.com/ant-design/ant-design) | 99.6k | #129 | 官方 · Ant Group | 蚂蚁集团的企业级 React UI 组件库与设计语言，提供数据密集型后台常用的表格、表单、布局等丰富组件，中文生态成熟。 |
| [mui/material-ui](https://github.com/mui/material-ui) | 99.1k | #130 | 官方 · MUI | 实现 Google Material Design 的 React 组件库，提供样式系统与主题定制，另有数据表格、图表等进阶组件。 |
| [tailwindlabs/tailwindcss](https://github.com/tailwindlabs/tailwindcss) | 97.7k | #134 | 官方 · Tailwind Labs | 原子化（utility-first）CSS 框架，直接在标记里组合类名构建界面，通过构建时扫描按需生成样式，体积小且易定制。 |
| [ElemeFE/element](https://github.com/ElemeFE/element) | 54k | #441 | 官方 · Eleme | 饿了么开源的 Vue 2 桌面端 UI 组件库（Element UI），Vue 3 版本请使用社区维护的 Element Plus。 |
| [necolas/normalize.css](https://github.com/necolas/normalize.css) | 53.5k | #449 | 社区 | CSS 重置的现代替代方案，保留有用的浏览器默认样式并抹平跨浏览器差异。 |
| [Semantic-Org/Semantic-UI](https://github.com/Semantic-Org/Semantic-UI) | 51k | #484 | 社区 | 以自然语言命名理念设计的 UI 组件框架，提供五十多个组件、可主题化的 CSS 变量，类名读起来像句子。 |
| [jgthms/bulma](https://github.com/jgthms/bulma) | 50.1k | #497 | 社区 | 基于 Flexbox 的现代 CSS 框架，纯 CSS 无 JavaScript，通过类名组合出响应式布局与常见组件。 |
| [DavidHDev/react-bits](https://github.com/DavidHDev/react-bits) | 48.3k | #534 | 社区 | 大型 React 动效组件合集，提供二百多个可自由定制的文字、背景、UI 与微交互动画，复制即用。 |
| [saadeghi/daisyui](https://github.com/saadeghi/daisyui) | 42.5k | #660 | 社区 | Tailwind CSS 组件库，用语义类名（如 btn、card）提供预设样式和主题，减少冗长的原子类。 |
| [styled-components/styled-components](https://github.com/styled-components/styled-components) | 41.1k | #694 | 社区 | React 的 CSS-in-JS 库，用带样式的标签模板创建组件，支持主题、服务端渲染和 React Native。 |
| [vuetifyjs/vuetify](https://github.com/vuetifyjs/vuetify) | 41k | #696 | 社区 | Vue 的 Material Design 组件框架，提供丰富的预制组件、主题系统和栅格。 |
| [chakra-ui/chakra-ui](https://github.com/chakra-ui/chakra-ui) | 40.7k | #709 | 社区 | 面向 SaaS 产品的 React 组件系统，组件可访问、可组合，支持主题和样式属性，兼容 Next.js RSC。 |
| [Dogfalo/materialize](https://github.com/Dogfalo/materialize) | 38.8k | #776 | 社区 | 基于 Material Design 的 CSS 框架，提供组件、栅格和动效，现已停止活跃维护。 |
| [google/material-design-lite](https://github.com/google/material-design-lite) | 32.2k | #1083 | 官方 · Google | Google 的 Material Design 组件库（纯 HTML / CSS / JS 实现），已停止开发，被 Material Components 取代。 |
| [mantinedev/mantine](https://github.com/mantinedev/mantine) | 31.8k | #1112 | 社区 | 功能齐全的 React 组件库，提供上百个组件和 hooks，含表单、日期、通知等模块，样式基于 CSS Modules。 |
| [heroui-inc/heroui](https://github.com/heroui-inc/heroui) | 30.8k | #1172 | 官方 · HeroUI | 现代 React 组件库（前身 NextUI），基于 Tailwind CSS 与 React Aria，视觉精致、可访问性好。 |
| [layui/layui](https://github.com/layui/layui) | 30.6k | #1185 | 社区 | 遵循浏览器原生开发模式的 Web UI 组件库，用原生 HTML / CSS / JS 开发，国内后台管理系统中较常见。 |
| [foundation/yeti](https://github.com/foundation/yeti) | 29.8k | #1240 | 社区 | 以 CSS 为先、原生且无需构建的布局与样式框架，面向网页设计师，由 Foundation 团队出品。 |
| [tailwindlabs/headlessui](https://github.com/tailwindlabs/headlessui) | 28.8k | #1336 | 官方 · Tailwind Labs | 完全无样式、可访问的 UI 组件（下拉、对话框、标签页等），与 Tailwind CSS 搭配，提供 React 与 Vue 版本。 |
| [element-plus/element-plus](https://github.com/element-plus/element-plus) | 27.8k | #1416 | 社区 | 基于 Vue 3 组合式 API 与 TypeScript 的 UI 组件库，由 Element 团队打造，是 Element UI 的 Vue 3 继任者。 |
| [Tencent/weui](https://github.com/Tencent/weui) | 27.4k | #1445 | 官方 · Tencent | 微信官方设计团队的移动 Web UI 库，提供贴近微信原生风格的组件，适用于公众号网页和小程序。 |
| [react-native-elements/react-native-elements](https://github.com/react-native-elements/react-native-elements) | 25.9k | #1582 | 社区 | React Native 跨平台 UI 工具包，提供按钮、输入框、列表等常用组件并支持主题。 |
| [angular/components](https://github.com/angular/components) | 25k | #1665 | 社区 | Angular 官方组件库，含 Material Design 组件和组件开发工具包（CDK）。 |
| [youzan/vant](https://github.com/youzan/vant) | 24.4k | #1735 | 官方 · Youzan | 有赞的轻量、可定制的 Vue 移动端组件库，覆盖电商和移动 Web 常见组件。 |
| [mdbootstrap/mdb-ui-kit](https://github.com/mdbootstrap/mdb-ui-kit) | 24.3k | #1753 | 官方 · MDBootstrap | Bootstrap 5 与 Material Design UI 套件，提供七百多个原生 JavaScript 组件，安装简单。 |
| [iview/iview](https://github.com/iview/iview) | 23.8k | #1802 | 社区 | 基于 Vue.js 的高质量 UI 组件库（现更名为 View UI），提供大量实用组件。 |
| [pure-css/pure](https://github.com/pure-css/pure) | 23.7k | #1806 | 社区 | 一组小巧的响应式 CSS 模块，可用于任何 Web 项目，出自 Yahoo。 |
| [react-bootstrap/react-bootstrap](https://github.com/react-bootstrap/react-bootstrap) | 22.6k | #1936 | 社区 | 用 React 重写的 Bootstrap 5 组件，不依赖 jQuery，以 React 组件方式使用 Bootstrap。 |
| [magicuidesign/magicui](https://github.com/magicuidesign/magicui) | 22.4k | #1964 | 社区 | 面向设计工程师的动画 React 组件库，复制粘贴即可使用，基于 Tailwind CSS 与 Framer Motion，免费开源。 |

### 图标、字体与主题

图标集与图标字体（Font Awesome、Lucide 一类）、编程字体（Fira Code、Nerd Fonts、Iosevka 一类），以及 Dracula 这类跨应用的配色主题 · 13 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [tonsky/FiraCode](https://github.com/tonsky/FiraCode) | 82.1k | #201 | 社区 | 带编程连字的免费等宽字体，把常见的多字符符号序列（如箭头、比较运算符）渲染为更易读的单个字形，并附安装与排错说明。 |
| [FortAwesome/Font-Awesome](https://github.com/FortAwesome/Font-Awesome) | 76.9k | #226 | 官方 · Fonticons | 使用最广的图标库，以 SVG、字体和 CSS 形式提供数千个图标，免费版与 Pro 版并行。 |
| [ryanoasis/nerd-fonts](https://github.com/ryanoasis/nerd-fonts) | 64.8k | #319 | 社区 | 为开发者字体打补丁的项目，把 3600 多个图标和字形集合（Font Awesome、Material Design Icons、Octicons 等）合并进 50 多款常用编程字体，并提供字体补丁工具。 |
| [google/material-design-icons](https://github.com/google/material-design-icons) | 54.1k | #440 | 官方 · Google | Google 官方的 Material 图标集，包含现行的 Material Symbols（可变字体）和经典的 Material Icons。 |
| [subframe7536/maple-font](https://github.com/subframe7536/maple-font) | 29.1k | #1308 | 社区 | Maple Mono：带连字与 Nerd Font 图标、圆角设计的开源等宽字体，适合 IDE 与终端，中英文宽度为 2:1，提供细粒度的自定义选项。 |
| [microsoft/cascadia-code](https://github.com/microsoft/cascadia-code) | 27.9k | #1410 | 官方 · Microsoft | 随 Windows Terminal 一同发布的编程字体，包含连字，现已是 Visual Studio 的默认字体，并提供带 Powerline 与 Nerd Font 符号的变体。 |
| [powerline/fonts](https://github.com/powerline/fonts) | 26.3k | #1537 | 社区 | 为 Powerline 状态栏插件预先打过补丁并调整过的字体集合，提供安装脚本，Debian 与 Ubuntu 系统也有对应软件包。 |
| [feathericons/feather](https://github.com/feathericons/feather) | 26k | #1566 | 社区 | 简洁美观的开源 SVG 图标集，每个图标都为 24×24 网格设计，风格统一。 |
| [simple-icons/simple-icons](https://github.com/simple-icons/simple-icons) | 25.9k | #1575 | 社区 | 热门品牌的 SVG 图标集合，提供数千个品牌矢量图标，可用于社交链接、技术栈展示等。 |
| [lucide-icons/lucide](https://github.com/lucide-icons/lucide) | 24.8k | #1691 | 社区 | 社区维护的图标集，风格统一，是 Feather 的分支，提供 React、Vue、Svelte 等框架的组件包。 |
| [tailwindlabs/heroicons](https://github.com/tailwindlabs/heroicons) | 23.8k | #1789 | 官方 · Tailwind Labs | Tailwind CSS 团队手工制作的免费 SVG 图标集，提供多种风格，有 React、Vue 组件包。 |
| [dracula/dracula-theme](https://github.com/dracula/dracula-theme) | 23.6k | #1821 | 社区 | Dracula 主题：一个配色方案覆盖 VS Code、iTerm、Vim、JetBrains、Windows Terminal、Zsh 等 400 多个应用，附完整调色板。 |
| [be5invis/Iosevka](https://github.com/be5invis/Iosevka) | 22.8k | #1916 | 社区 | 为编写代码、终端使用和技术文档设计的开源无衬线加板状衬线等宽字体族。 |

### 交互小组件

轮播、拖拽、上传、表格、虚拟列表、引导提示、弹层与下拉等单点交互组件 · 20 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [nolimits4web/swiper](https://github.com/nolimits4web/swiper) | 41.9k | #672 | 社区 | 现代移动触摸滑块（轮播）库，硬件加速动画，可用于网站、Web 应用与移动端，并提供 React、Vue 等组件。 |
| [alvarotrigo/fullPage.js](https://github.com/alvarotrigo/fullPage.js) | 35.4k | #920 | 社区 | 创建全屏滚动网页的插件，支持分区滚动、导航点和响应式，有 Vue、React、Angular 封装。 |
| [atlassian/react-beautiful-dnd](https://github.com/atlassian/react-beautiful-dnd) 🗄️已归档 | 33.9k | #989 | 官方 · Atlassian | 面向 React 列表的美观、无障碍拖拽库，已归档并在 npm 上弃用，Atlassian 推荐迁移到新方案。 |
| [floating-ui/floating-ui](https://github.com/floating-ui/floating-ui) | 32.8k | #1060 | 社区 | 定位浮层元素（提示框、下拉、弹出层）的 JavaScript 库，前身为 Popper，提供 React、Vue 等绑定。 |
| [SortableJS/Sortable](https://github.com/SortableJS/Sortable) | 31.2k | #1155 | 社区 | 可重新排序的拖拽列表库，兼容现代浏览器和触摸设备，不依赖 jQuery，并有 Vue、React 等封装。 |
| [transloadit/uppy](https://github.com/transloadit/uppy) | 31k | #1166 | 官方 · Transloadit | 精致的模块化 JavaScript 文件上传器，支持拖拽、断点续传、多来源导入（网盘、摄像头）和多种后端。 |
| [blueimp/jQuery-File-Upload](https://github.com/blueimp/jQuery-File-Upload) 🗄️已归档 | 30.7k | #1179 | 社区 | jQuery 文件上传组件，支持多文件选择、拖拽、进度条、校验、分块与断点续传，并带图片和音视频预览；仓库已归档。 |
| [kenwheeler/slick](https://github.com/kenwheeler/slick) | 28.5k | #1356 | 社区 | 广受欢迎的 jQuery 轮播插件，支持响应式、触摸、自动播放与多种配置。 |
| [TanStack/table](https://github.com/TanStack/table) | 28.5k | #1363 | 社区 | 无头（headless）表格与数据网格库，提供排序、过滤、分页、分组等逻辑，样式自定义，适配 React、Vue、Solid、Svelte。 |
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 28k | #1406 | 社区 | React 的选择控件，支持搜索、多选、异步加载和自定义样式，最初为 KeystoneJS 开发。 |
| [bvaughn/react-virtualized](https://github.com/bvaughn/react-virtualized) | 27.1k | #1476 | 社区 | 高效渲染大型列表与表格的 React 组件，通过虚拟化只渲染可见区域，提升长列表性能。 |
| [nilbuild/driver.js](https://github.com/nilbuild/driver.js) | 26.9k | #1494 | 社区 | 轻量无依赖的 JavaScript 库，用于产品导览和功能引导，可高亮页面元素并逐步说明。 |
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 26.4k | #1532 | 社区 | 轻量的顶部细进度条库，类似 YouTube、Medium 的页面加载进度提示。 |
| [select2/select2](https://github.com/select2/select2) | 25.9k | #1577 | 社区 | 基于 jQuery 的下拉选择框增强组件，支持搜索、远程数据和无限滚动。 |
| [scwang90/SmartRefreshLayout](https://github.com/scwang90/SmartRefreshLayout) | 25.1k | #1658 | 社区 | Android 智能下拉刷新框架，支持下拉刷新、上拉加载、二级刷新和越界回弹，内置多种 Header / Footer 样式。 |
| [CymChad/BaseRecyclerViewAdapterHelper](https://github.com/CymChad/BaseRecyclerViewAdapterHelper) | 24.6k | #1711 | 社区 | Android RecyclerView 适配器封装库（BRVAH），简化列表适配、多类型布局、加载更多和动画。 |
| [hammerjs/hammer.js](https://github.com/hammerjs/hammer.js) | 24.3k | #1740 | 社区 | 多点触控手势 JavaScript 库，识别点按、滑动、缩放、旋转等手势。 |
| [usablica/intro.js](https://github.com/usablica/intro.js) | 23.5k | #1837 | 社区 | 轻量的用户引导库，用分步高亮的方式做产品导览和新功能介绍。 |
| [react-grid-layout/react-grid-layout](https://github.com/react-grid-layout/react-grid-layout) | 22.4k | #1963 | 社区 | React 可拖拽、可缩放的栅格布局组件，支持响应式断点，常用于仪表盘。 |
| [t4t5/sweetalert](https://github.com/t4t5/sweetalert) | 22.3k | #1987 | 社区 | JavaScript 原生 alert 的美观替代品，提供样式精致、可定制的弹窗。 |

### 动画与动效

CSS / JS 动画库、滚动动效、Lottie 一类的矢量动画渲染 · 13 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [animate-css/animate.css](https://github.com/animate-css/animate.css) | 82.8k | #196 | 社区 | 纯 CSS 动画库，提供淡入、弹跳、滑动等即用型动画类，加上类名即可使用。 |
| [juliangarnier/anime](https://github.com/juliangarnier/anime) | 73.2k | #261 | 社区 | 轻量的 JavaScript 动画引擎（Anime.js），可对 CSS 属性、SVG、DOM 属性和 JS 对象做补间动画，API 简洁。 |
| [airbnb/lottie-android](https://github.com/airbnb/lottie-android) | 35.7k | #906 | 官方 · Airbnb | Airbnb 的动画库，解析 After Effects 通过 Bodymovin 导出的 JSON 动画并原生渲染，覆盖 Android、iOS、Web 和 React Native。 |
| [motiondivision/motion](https://github.com/motiondivision/motion) | 33.8k | #1003 | 官方 · Motion | 面向 JavaScript、React 和 Vue 的现代动画库（原 Framer Motion），声明式 API，支持手势、布局与滚动动画。 |
| [airbnb/lottie-web](https://github.com/airbnb/lottie-web) | 32.1k | #1090 | 官方 · Airbnb | Airbnb 的 Lottie 网页版，把 After Effects 通过 Bodymovin 导出的动画在网页里以 SVG / Canvas 渲染。 |
| [VincentGarreau/particles.js](https://github.com/VincentGarreau/particles.js) | 30.2k | #1206 | 社区 | 轻量的粒子效果 JavaScript 库，用于在网页背景生成可交互的粒子动画。 |
| [IanLunn/Hover](https://github.com/IanLunn/Hover) | 29.4k | #1285 | 社区 | 基于 CSS3 的悬停效果集合，可直接应用到链接、按钮、图片和 SVG 等元素上。 |
| [pmndrs/react-spring](https://github.com/pmndrs/react-spring) | 29.2k | #1303 | 社区 | 基于弹簧物理的 React 动画库，用声明式 hooks 制作自然流畅的交互动画，也支持 React Native 和 Three.js。 |
| [greensock/GSAP](https://github.com/greensock/GSAP) | 28.7k | #1338 | 官方 · GreenSock | GreenSock 动画平台，与框架无关的高性能 JavaScript 动画库，提供时间轴、滚动触发和丰富插件。 |
| [michalsnik/aos](https://github.com/michalsnik/aos) | 28.1k | #1403 | 社区 | 滚动触发动画库（Animate On Scroll），元素进入视口时自动播放动画。 |
| [airbnb/lottie-ios](https://github.com/airbnb/lottie-ios) | 26.9k | #1492 | 官方 · Airbnb | Airbnb 的 iOS 动画库，原生渲染 After Effects 导出的矢量动画，无需手写动画代码。 |
| [HeroTransitions/Hero](https://github.com/HeroTransitions/Hero) | 22.5k | #1955 | 社区 | 为 iOS 与 tvOS 构建视图控制器转场的库，在 UIKit 繁琐的转场 API 之上提供声明式接口，类似 Keynote 的 Magic Move，通过 heroID 自动匹配视图。 |
| [jlmakes/scrollreveal](https://github.com/jlmakes/scrollreveal) | 22.5k | #1960 | 社区 | 滚动进入视口时触发元素动画的 JavaScript 库，配置简单，无需依赖。 |

### 编辑器与富文本

嵌入网页 / 应用的代码编辑器组件、富文本编辑框架和语法高亮（独立的编辑器与 IDE 归「编程语言与开发环境」） · 10 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [slab/quill](https://github.com/slab/quill) | 47.4k | #553 | 社区 | 现代所见即所得富文本编辑器，强调兼容性和可扩展性，用 Delta 格式表示内容，支持自定义模块与主题。 |
| [microsoft/monaco-editor](https://github.com/microsoft/monaco-editor) | 46.8k | #567 | 官方 · Microsoft | VS Code 同款的浏览器代码编辑器组件，支持语法高亮、智能提示和多语言，可嵌入网页。 |
| [ueberdosis/tiptap](https://github.com/ueberdosis/tiptap) | 38.6k | #787 | 官方 · überdosis | 无头（headless）富文本编辑框架，基于 ProseMirror，自身不带界面，通过扩展定制，支持 React、Vue 等。 |
| [codex-team/editor.js](https://github.com/codex-team/editor.js) | 32k | #1100 | 社区 | 块状（block-style）富文本编辑器，输出干净的 JSON 数据，通过插件扩展块类型。 |
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 31.8k | #1116 | 社区 | 完全可定制的富文本编辑器框架，基于 React，用数据模型与插件构建自定义编辑体验，仍处于 beta。 |
| [codemirror/codemirror5](https://github.com/codemirror/codemirror5) 🗄️已归档 | 27.2k | #1464 | 社区 | CodeMirror 5，浏览器内的代码编辑器（旧版），仓库已迁移，新项目应使用 CodeMirror 6。 |
| [ajaxorg/ace](https://github.com/ajaxorg/ace) | 27.1k | #1472 | 社区 | Ace，浏览器内的高性能代码编辑器（前身 Cloud9 编辑器），支持语法高亮、主题和多语言模式。 |
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 25k | #1668 | 社区 | JavaScript 语法高亮库，零依赖，可自动识别语言，同时适用于浏览器和 Node.js。 |
| [facebook/lexical](https://github.com/facebook/lexical) | 23.9k | #1781 | 官方 · Meta | Meta 开源的可扩展文本编辑器框架，强调可靠性、无障碍和性能，提供 React 等绑定。 |
| [facebookarchive/draft-js](https://github.com/facebookarchive/draft-js) 🗄️已归档 | 22.6k | #1940 | 官方 · Meta | Meta 的 React 富文本编辑器框架，项目已进入维护模式，不再新增功能，官方后续推荐 Lexical。 |

### 图表与地图

图表、地图和数据可视化库（D3、ECharts、Chart.js、Leaflet、Matplotlib、Dash 一类） · 9 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [d3/d3](https://github.com/d3/d3) | 113.8k | #103 | 社区 | 用 SVG、Canvas 和 HTML 驱动数据可视化的 JavaScript 库，以数据绑定和丰富的比例尺、布局模块著称，是众多图表库的底层。 |
| [chartjs/Chart.js](https://github.com/chartjs/Chart.js) | 67.7k | #291 | 社区 | 基于 HTML5 Canvas 的简单灵活的 JavaScript 图表库，内置折线、柱状、饼图等常见图表，支持响应式与动画。 |
| [apache/echarts](https://github.com/apache/echarts) | 67.4k | #294 | 社区 | Apache 基金会的交互式图表与数据可视化库，功能丰富、图表类型多，支持大数据量渲染与主题定制，在国内使用广泛。 |
| [Leaflet/Leaflet](https://github.com/Leaflet/Leaflet) | 45.7k | #589 | 社区 | 轻量的移动友好交互式地图 JavaScript 库，核心小巧、插件丰富，是开源 Web 地图的常用选择。 |
| [PhilJay/MPAndroidChart](https://github.com/PhilJay/MPAndroidChart) | 38.2k | #802 | 社区 | Android 图表库，支持折线、柱状、饼图、雷达图与 K 线，提供缩放、拖动和动画，现已用 Kotlin 重写并提供 Compose 模块。 |
| [ChartsOrg/Charts](https://github.com/ChartsOrg/Charts) | 28k | #1407 | 社区 | iOS / tvOS / macOS 图表库，是 MPAndroidChart 的 Apple 平台版本，支持折线、柱状、饼图等。 |
| [recharts/recharts](https://github.com/recharts/recharts) | 27.6k | #1428 | 社区 | 基于 React 与 D3 的图表库，以声明式组件组合折线、柱状、饼图等图表。 |
| [plotly/dash](https://github.com/plotly/dash) | 24.4k | #1725 | 官方 · Plotly | 用纯 Python 构建数据应用与仪表盘的框架，基于 Plotly.js、React 和 Flask，把下拉框、滑块、图表与分析代码直接绑定。 |
| [matplotlib/matplotlib](https://github.com/matplotlib/matplotlib) | 23.3k | #1858 | 社区 | Python 的综合绘图库，可创建静态、动画和交互式图表，输出多种出版级格式，并可嵌入脚本、Web 应用和 GUI 工具包。 |

### 3D、Canvas 与白板绘图

3D 与 2D 渲染引擎、Canvas 库、创意编程，以及白板与图表绘制工具（three.js、PixiJS、p5.js、tldraw、Excalidraw、Mermaid 一类） · 13 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [excalidraw/excalidraw](https://github.com/excalidraw/excalidraw) | 133.3k | #78 | 官方 · Excalidraw | 开源的手绘风虚拟白板，可协作、端到端加密，用于绘制图表与线框图，编辑器也以 npm 包形式提供，可嵌入其他应用。 |
| [mrdoob/three.js](https://github.com/mrdoob/three.js) | 116.1k | #100 | 社区 | 在浏览器中渲染 3D 图形的 JavaScript 库，封装 WebGL / WebGPU，提供场景、相机、材质、动画等抽象。 |
| [mermaid-js/mermaid](https://github.com/mermaid-js/mermaid) | 90.5k | #165 | 社区 | 用类 Markdown 的文本生成流程图、时序图、甘特图等图表的 JavaScript 库，可在文档与网页中直接渲染，并提供在线编辑器。 |
| [tldraw/tldraw](https://github.com/tldraw/tldraw) | 50.7k | #488 | 官方 · tldraw | 在 React 中构建无限画布应用的 SDK，提供白板、绘图与协作能力，可嵌入自己的产品。 |
| [pixijs/pixijs](https://github.com/pixijs/pixijs) | 48.2k | #535 | 社区 | 面向网页的 2D 渲染库，支持 WebGL 与 WebGPU，提供资源加载、触控交互、文本、矢量绘制、滤镜与混合模式。 |
| [AykutSarac/jsoncrack.com](https://github.com/AykutSarac/jsoncrack.com) | 44.5k | #617 | 社区 | 把 JSON、YAML、XML、CSV 转成可交互图形的开源可视化工具，可格式化、校验、转换格式、生成 Schema 并导出图片。 |
| [mingrammer/diagrams](https://github.com/mingrammer/diagrams) | 42.6k | #656 | 社区 | 用 Python 代码绘制云系统架构图的「图即代码」工具，支持 AWS、Azure、GCP、Kubernetes 等主要云厂商、本地节点与常见编程框架，便于对架构图做版本管理。 |
| [xyflow/xyflow](https://github.com/xyflow/xyflow) | 38.6k | #789 | 官方 · xyflow | 构建节点式界面的库，包含 React Flow 和 Svelte Flow，用于流程图、工作流编辑器和可视化编排，开箱即用且高度可定制。 |
| [pmndrs/react-three-fiber](https://github.com/pmndrs/react-three-fiber) | 32.6k | #1064 | 社区 | Three.js 的 React 渲染器，用声明式组件和 hooks 搭建 3D 场景，与 React 生态无缝配合。 |
| [fabricjs/fabric.js](https://github.com/fabricjs/fabric.js) | 31.5k | #1137 | 社区 | 简单强大的 HTML5 Canvas 库，提供对象模型、交互与 SVG 互转，常用于图形编辑器和在线设计工具。 |
| [BabylonJS/Babylon.js](https://github.com/BabylonJS/Babylon.js) | 26.1k | #1555 | 社区 | 基于 JavaScript / TypeScript 的 3D 渲染与游戏引擎，支持 WebGL 与 WebGPU，提供场景、材质、物理、XR 与配套的 Playground。 |
| [d2lang/d2](https://github.com/d2lang/d2) | 25.5k | #1620 | 社区 | 现代化的图表脚本语言，把文本转换为图表，提供多种主题、字体、布局引擎和导出格式，也可作为库使用并附在线 Playground。 |
| [processing/p5.js](https://github.com/processing/p5.js) | 24.1k | #1765 | 社区 | 面向创意编程的客户端 JavaScript 库，基于 Processing 的理念，提供画布绘制、交互、声音与 DOM 操作，适合设计师与初学者。 |

### 媒体、文档与演示

视频与音频播放、图片浏览、PDF 渲染、演示幻灯片和程序化视频生成（video.js、Howler.js、pdf.js、reveal.js、Remotion 一类） · 10 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [hakimel/reveal.js](https://github.com/hakimel/reveal.js) | 72.4k | #267 | 社区 | 基于 HTML 的演示文稿框架，支持嵌套幻灯片、Markdown、自动动画、PDF 导出、演讲者备注、LaTeX 与代码高亮。 |
| [remotion-dev/remotion](https://github.com/remotion-dev/remotion) | 61.2k | #361 | 官方 · Remotion | 用 React 以编程方式制作视频的框架，以代码为视频的唯一来源，支持数据驱动、批量渲染和服务器端渲染。 |
| [mozilla/pdf.js](https://github.com/mozilla/pdf.js) | 54k | #443 | 社区 | 用 HTML5 构建的 PDF 阅读器，目标是提供基于 Web 标准的通用 PDF 解析与渲染平台，由社区驱动、Mozilla 支持，也用于 Firefox 内置阅读器。 |
| [slidevjs/slidev](https://github.com/slidevjs/slidev) | 48.9k | #525 | 社区 | 面向开发者的演示文稿工具，用 Markdown 编写，内置代码高亮与现场编码，可嵌入 Vue 组件，基于 Vite 并支持主题与演讲者模式。 |
| [videojs/video.js](https://github.com/videojs/video.js) | 39.9k | #736 | 社区 | 开源 HTML5 视频播放器与框架，支持 HLS / DASH、字幕、插件和主题，可跨浏览器播放。 |
| [impress/impress.js](https://github.com/impress/impress.js) | 38.2k | #803 | 社区 | 基于 CSS3 变换与过渡的演示文稿框架，灵感来自 prezi.com，可在浏览器中制作带空间移动与缩放效果的演示，并附入门指南。 |
| [sampotts/plyr](https://github.com/sampotts/plyr) | 30k | #1221 | 社区 | 简洁的 HTML5、YouTube 和 Vimeo 播放器，界面可定制、无障碍友好；项目提示可迁移到 Video.js。 |
| [goldfire/howler.js](https://github.com/goldfire/howler.js) | 25.4k | #1637 | 社区 | 面向现代网页的 JavaScript 音频库，默认使用 Web Audio API 并回退到 HTML5 Audio，提供跨平台的音频播放、空间音效与音频精灵。 |
| [dimsemenov/PhotoSwipe](https://github.com/dimsemenov/PhotoSwipe) | 25.3k | #1645 | 社区 | 模块化、不依赖框架的 JavaScript 图片画廊，支持桌面和移动端的手势缩放与滑动。 |
| [bilibili/flv.js](https://github.com/bilibili/flv.js) | 23.2k | #1871 | 官方 · Bilibili | 用纯 JavaScript 编写、不依赖 Flash 的 HTML5 FLV 播放器，借助 Media Source Extensions 把 FLV 转封装为 MP4 分片；README 说明项目将很少维护。 |

## 工程化工具链

项目层面的构建、检查、测试与依赖管理工具

### 构建、打包与编译

打包器、转译器、编译器与构建工具（Vite、webpack、Babel、esbuild、SWC、Rollup 一类） · 16 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [vitejs/vite](https://github.com/vitejs/vite) | 83.1k | #194 | 社区 | 新一代前端构建工具，开发时利用浏览器原生 ES 模块实现秒级启动与热更新，生产构建基于 Rollup，插件生态丰富。 |
| [webpack/webpack](https://github.com/webpack/webpack) | 66k | #308 | 社区 | JavaScript 模块打包器，通过 loader 处理各类资源，支持代码分割、按需加载和丰富的插件体系，是长期主流的前端构建工具。 |
| [babel/babel](https://github.com/babel/babel) | 44k | #626 | 社区 | JavaScript 编译器，把新语法转成旧环境可运行的代码，并支持 JSX、TypeScript 等转换，是前端构建链的基础组件。 |
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 44k | #627 | 社区 | 零配置的 Web 应用打包工具，开箱即用支持多种资源类型和热更新，并可扩展到大型项目。 |
| [evanw/esbuild](https://github.com/evanw/esbuild) | 40.1k | #727 | 社区 | 用 Go 写的极速 JavaScript / TypeScript 打包器和压缩器，比传统工具快一到两个数量级，是 Vite 等工具的底层组件。 |
| [swc-project/swc](https://github.com/swc-project/swc) | 34.2k | #973 | 社区 | 用 Rust 编写的极速 TypeScript / JavaScript 编译器，可作 Babel 替代，被 Next.js 等框架内置使用。 |
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 32.9k | #1052 | 社区 | 基于流的前端自动化构建工具，用 JavaScript 代码定义任务，处理编译、压缩、监听等工作流。 |
| [vuejs/vue-cli](https://github.com/vuejs/vue-cli) | 29.5k | #1270 | 社区 | 基于 webpack 的 Vue 项目脚手架工具，已进入维护模式，新项目建议使用 create-vue。 |
| [postcss/postcss](https://github.com/postcss/postcss) | 29k | #1321 | 社区 | 用 JavaScript 插件转换样式的工具，可做 lint、变量、嵌套、自动前缀等，Tailwind、Autoprefixer 等都构建其上。 |
| [emscripten-core/emscripten](https://github.com/emscripten-core/emscripten) | 27.6k | #1426 | 社区 | 基于 LLVM 的 C / C++ 到 WebAssembly 编译器，可把原生代码移植到浏览器和 Node.js 中运行。 |
| [angular/angular-cli](https://github.com/angular/angular-cli) | 27k | #1480 | 社区 | Angular 官方命令行工具，用于创建项目、生成代码、构建、测试和部署 Angular 应用。 |
| [rollup/rollup](https://github.com/rollup/rollup) | 26.3k | #1540 | 社区 | 面向 ES 模块的 JavaScript 打包器，擅长 tree-shaking，适合打包库，也是 Vite 生产构建的底层。 |
| [vercel/pkg](https://github.com/vercel/pkg) 🗄️已归档 | 24.3k | #1741 | 官方 · Vercel | 把 Node.js 项目打包成可执行文件的工具，已弃用（5.8.1 为最后版本），官方给出了替代方案。 |
| [oxc-project/oxc](https://github.com/oxc-project/oxc) | 22.9k | #1899 | 社区 | 高性能 JavaScript 工具集合，包含解析器、Linter、格式化、压缩和转换器，用 Rust 编写。 |
| [svg/svgo](https://github.com/svg/svgo) | 22.7k | #1923 | 社区 | SVG 优化工具，可作为 Node.js 库和命令行使用，去除冗余元数据以缩小 SVG 体积。 |
| [postcss/autoprefixer](https://github.com/postcss/autoprefixer) | 22.2k | #1993 | 社区 | PostCSS 插件，依据 Can I Use 数据自动为 CSS 规则添加浏览器前缀。 |

### 代码规范与格式化

Lint、格式化工具与 JavaScript / Python 的代码风格规范（ESLint、Prettier、Ruff、Black、Biome 一类） · 8 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [airbnb/javascript](https://github.com/airbnb/javascript) | 148.3k | #62 | 官方 · Airbnb | Airbnb 的 JavaScript 代码风格指南，以「合理的做法」为原则逐条给出规则和示例，其 ESLint 配置被广泛采用。 |
| [prettier/prettier](https://github.com/prettier/prettier) | 52.3k | #465 | 社区 | 固执己见的代码格式化工具，解析代码后按统一风格重新输出，支持 JS / TS、CSS、HTML、Markdown、YAML 等多种语言。 |
| [astral-sh/ruff](https://github.com/astral-sh/ruff) | 49.9k | #504 | 官方 · Astral | 用 Rust 写的极速 Python Linter 和格式化工具，兼容 Flake8、Black 等规则，速度快 10 到 100 倍。 |
| [psf/black](https://github.com/psf/black) | 41.9k | #675 | 社区 | 「毫不妥协」的 Python 代码格式化工具，几乎不留配置项，换来统一风格、确定性输出和更快的代码评审。 |
| [standard/standard](https://github.com/standard/standard) | 29.4k | #1280 | 社区 | JavaScript 代码风格指南，附带 linter 和自动修复工具，零配置强制统一风格。 |
| [eslint/eslint](https://github.com/eslint/eslint) | 27.5k | #1433 | 社区 | JavaScript / TypeScript 的可插拔静态检查工具，发现并修复代码问题，规则和配置可高度自定义。 |
| [biomejs/biome](https://github.com/biomejs/biome) | 25.9k | #1581 | 社区 | 面向 Web 项目的一体化工具链，提供格式化与 Lint，可通过命令行和 LSP 使用，用 Rust 编写。 |
| [rome/tools](https://github.com/rome/tools) 🗄️已归档 | 23.4k | #1848 | 社区 | Rome，面向 JavaScript / TypeScript 的一体化开发工具，项目已停止维护，由社区继任者 Biome 接续。 |

### 测试与性能

单元 / 端到端测试、浏览器自动化、压测和网页性能审计 · 13 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [microsoft/playwright](https://github.com/microsoft/playwright) | 96.9k | #136 | 官方 · Microsoft | 微软的端到端测试与浏览器自动化框架，用同一套 API 驱动 Chromium、Firefox 和 WebKit，支持自动等待、追踪回放和多语言绑定。 |
| [puppeteer/puppeteer](https://github.com/puppeteer/puppeteer) | 95.6k | #142 | 社区 | 通过 DevTools 协议或 WebDriver BiDi 控制 Chrome / Firefox 的 Node.js 库，默认无头运行，常用于自动化测试、截图和爬取。 |
| [cypress-io/cypress](https://github.com/cypress-io/cypress) | 51k | #483 | 官方 · Cypress | 面向浏览器应用的端到端与组件测试框架，测试与应用运行在同一浏览器中，提供时间旅行调试和自动重试。 |
| [minimaxir/big-list-of-naughty-strings](https://github.com/minimaxir/big-list-of-naughty-strings) | 47.7k | #547 | 社区 | 一份在用作用户输入时极易引发问题的字符串清单，用于自动化和人工 QA 测试，可用来发现零宽字符、注入与编码等边界问题。 |
| [jestjs/jest](https://github.com/jestjs/jest) | 45.5k | #593 | 社区 | JavaScript 测试框架，开箱即用，提供快照测试、Mock、覆盖率和交互式监听模式，是 React 项目的常见选择。 |
| [SeleniumHQ/selenium](https://github.com/SeleniumHQ/selenium) | 34.5k | #954 | 社区 | 浏览器自动化框架及生态，通过 WebDriver 协议驱动各类浏览器，支持多种语言，是 Web 端到端测试的老牌方案。 |
| [grafana/k6](https://github.com/grafana/k6) | 31.7k | #1122 | 官方 · Grafana Labs | 面向开发者的现代压测工具，用 JavaScript 编写测试脚本、Go 实现引擎，可集成 CI 做性能回归。 |
| [GoogleChrome/lighthouse](https://github.com/GoogleChrome/lighthouse) | 30.8k | #1173 | 官方 · Google | 自动化网页质量审计工具，检测性能、可访问性、SEO 与最佳实践并给出改进建议，集成于 Chrome DevTools。 |
| [ariya/phantomjs](https://github.com/ariya/phantomjs) 🗄️已归档 | 29.4k | #1278 | 社区 | 可用 JavaScript 编写脚本的无头 WebKit 浏览器，用于无界面网页测试、页面自动化与截图；开发已暂停，最终稳定版为 2.1。 |
| [locustio/locust](https://github.com/locustio/locust) | 28.2k | #1394 | 社区 | 用纯 Python 编写场景的压测工具，支持分布式运行和实时 Web 界面，适用于 HTTP 与其他协议。 |
| [stretchr/testify](https://github.com/stretchr/testify) | 26.2k | #1549 | 社区 | Go 测试工具包，提供断言、Mock 和测试套件，与标准库 testing 配合良好。 |
| [tsenart/vegeta](https://github.com/tsenart/vegeta) | 25.2k | #1651 | 社区 | 多用途 HTTP 压测工具与库，以恒定速率发送请求，适合验证服务在给定负载下的表现。 |
| [mochajs/mocha](https://github.com/mochajs/mocha) | 22.9k | #1905 | 社区 | 经典可靠的 JavaScript 测试框架，运行于 Node.js 与浏览器，灵活，可搭配任意断言库。 |

### 包管理与版本管理

包管理器、语言版本管理器和依赖管理，包括 Homebrew、Scoop、winget、Nix 一类的系统级包管理器 · 18 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [nvm-sh/nvm](https://github.com/nvm-sh/nvm) | 95.2k | #143 | 社区 | POSIX 兼容的 Node 版本管理脚本，可在同一台机器上安装并切换多个 Node.js 版本，按项目的 .nvmrc 自动选择。 |
| [astral-sh/uv](https://github.com/astral-sh/uv) | 90.3k | #167 | 官方 · Astral | 用 Rust 写的极速 Python 包与项目管理器，可替代 pip、pip-tools、pipx、poetry、pyenv、virtualenv 等，比 pip 快 10 到 100 倍。 |
| [Homebrew/brew](https://github.com/Homebrew/brew) | 49.8k | #507 | 社区 | 面向 macOS 与 Linux 的包管理器 Homebrew，提供 brew bundle 等功能，由志愿者运营的非营利项目。 |
| [nvm-windows/nvm](https://github.com/nvm-windows/nvm) | 47.8k | #543 | 社区 | Windows 版 Node.js 版本管理器，使用原生 Windows 安装包，第二版已全面重写。 |
| [pyenv/pyenv](https://github.com/pyenv/pyenv) | 45.1k | #602 | 社区 | 简单的 Python 版本管理工具，通过 shim 在多个 Python 版本间切换，遵循 Unix 单一职责风格。 |
| [yarnpkg/yarn](https://github.com/yarnpkg/yarn) | 41.5k | #686 | 社区 | Yarn 1.x 的源码仓库，JavaScript 包管理器，1.x 已进入冻结状态，新版本在 yarnpkg/berry 中开发。 |
| [pnpm/pnpm](https://github.com/pnpm/pnpm) | 36.7k | #866 | 社区 | 快速且节省磁盘的 Node.js 包管理器，用内容寻址存储和硬链接共享依赖，并原生支持 monorepo 工作区。 |
| [jdx/mise](https://github.com/jdx/mise) | 34.5k | #957 | 社区 | 统一管理开发工具版本、环境变量和任务的工具，可替代 nvm、pyenv、asdf 等多个版本管理器。 |
| [python-poetry/poetry](https://github.com/python-poetry/poetry) | 34.3k | #966 | 社区 | Python 依赖管理与打包工具，用 pyproject.toml 声明依赖，生成锁文件并支持构建与发布。 |
| [composer/composer](https://github.com/composer/composer) | 29.5k | #1269 | 社区 | PHP 依赖管理器，用 composer.json 声明依赖并生成锁文件，是 PHP 生态的标准包管理工具。 |
| [Schniz/fnm](https://github.com/Schniz/fnm) | 27k | #1487 | 社区 | 用 Rust 写的快速 Node.js 版本管理器，跨平台、启动快，可读取 .nvmrc 自动切换版本。 |
| [microsoft/winget-cli](https://github.com/microsoft/winget-cli) | 26.5k | #1527 | 官方 · Microsoft | Windows 程序包管理器 WinGet 的客户端，包含命令行、PowerShell 模块与 COM API，可从 Microsoft Store 和社区仓库两个默认源安装软件。 |
| [Devolutions/UniGetUI](https://github.com/Devolutions/UniGetUI) | 26.3k | #1534 | 官方 · Devolutions | 面向 Windows 10 与 11 常用命令行包管理器的图形界面，也提供 macOS 与 Linux 版本，支持 WinGet、Scoop、Chocolatey、Homebrew、APT 等。 |
| [NixOS/nixpkgs](https://github.com/NixOS/nixpkgs) | 26.3k | #1542 | 社区 | 包含超过 14 万个软件包的 Nix 包集合，可用 Nix 包管理器安装，同时实现纯函数式 Linux 发行版 NixOS，附各类手册与社区渠道。 |
| [asdf-vm/asdf](https://github.com/asdf-vm/asdf) | 25.6k | #1613 | 社区 | 可通过插件扩展的多语言版本管理器，用一个命令行工具管理 Node.js、Ruby、Elixir、Python 等运行时版本。 |
| [pypa/pipenv](https://github.com/pypa/pipenv) | 25k | #1666 | 社区 | Python 开发工作流工具，把 pip 和 virtualenv 结合起来，用 Pipfile 与锁文件管理依赖和虚拟环境。 |
| [ScoopInstaller/Scoop](https://github.com/ScoopInstaller/Scoop) | 24.7k | #1698 | 社区 | Windows 上的命令行安装器，以最少的操作安装应用：不弹 UAC 提示、隐藏安装向导界面、不污染 PATH，并自动解析和安装依赖。 |
| [Homebrew/homebrew-cask](https://github.com/Homebrew/homebrew-cask) | 22.2k | #1990 | 社区 | Homebrew Cask 的默认软件包仓库，把 Homebrew 的命令行工作流扩展到上游厂商发布的预编译软件，包括 GUI 应用、命令行工具与字体等。 |

### 开发者体验与 Monorepo

Monorepo 构建、组件开发环境、Git 钩子、热重载、调试、徽章与代码截图等提升开发效率的小工具，以及面向开发者的在线工具箱 · 20 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [storybookjs/storybook](https://github.com/storybookjs/storybook) | 91.2k | #159 | 社区 | UI 组件的隔离开发环境，可以在独立于应用的沙盒里构建、预览、文档化和测试组件，支持 React、Vue、Angular 等多种框架。 |
| [anuraghazra/github-readme-stats](https://github.com/anuraghazra/github-readme-stats) | 79.8k | #212 | 社区 | 为 GitHub README 动态生成统计卡片的服务；README 说明该仓库不再维护，建议改用后继项目 GitHub Stats Extended。 |
| [FiloSottile/mkcert](https://github.com/FiloSottile/mkcert) | 59.7k | #378 | 社区 | 零配置生成本地受信任开发证书的工具，自动创建本地 CA 并装入系统信任库，方便在本地用 HTTPS 调试。 |
| [google/zx](https://github.com/google/zx) | 45.8k | #587 | 官方 · Google | 用 JavaScript 编写更好用的 shell 脚本，封装 child_process，提供 $ 模板字符串、并行和错误处理。 |
| [CorentinTh/it-tools](https://github.com/CorentinTh/it-tools) | 40.7k | #707 | 社区 | 面向开发者与 IT 人员的在线工具集合，体验良好，可通过 Docker 自托管。 |
| [carbon-app/carbon](https://github.com/carbon-app/carbon) | 36.1k | #888 | 社区 | 为源代码生成并分享精美图片的工具，可自定义外观，用于制作在社交媒体上分享的代码截图。 |
| [lerna/lerna](https://github.com/lerna/lerna) | 36k | #895 | 社区 | 管理并发布同一仓库中多个 JavaScript / TypeScript 包的构建系统，现由 Nx 团队维护。 |
| [typicode/husky](https://github.com/typicode/husky) | 35.3k | #921 | 社区 | 让 Git 钩子易用的工具，在 commit、push 前自动运行 lint、测试等脚本，团队共享。 |
| [DevToys-app/DevToys](https://github.com/DevToys-app/DevToys) | 32k | #1097 | 社区 | 面向开发者的瑞士军刀式桌面应用，2.0 版内置 30 个默认小工具，涵盖转换器、编码解码器、格式化器与生成器，并能根据剪贴板内容智能选择工具。 |
| [vercel/turborepo](https://github.com/vercel/turborepo) | 31.2k | #1157 | 官方 · Vercel | 用 Rust 写的 JavaScript / TypeScript Monorepo 构建系统，支持增量构建、任务并行和本地与远程缓存。 |
| [square/leakcanary](https://github.com/square/leakcanary) | 30k | #1225 | 官方 · Block | Android 内存泄漏检测库，在开发时自动监测对象泄漏并给出引用链，帮助定位问题。 |
| [nrwl/nx](https://github.com/nrwl/nx) | 29.4k | #1286 | 官方 · Nx | Monorepo 构建平台，提供智能任务缓存、受影响项分析、分布式 CI 与代码生成，支持多语言。 |
| [badges/shields](https://github.com/badges/shields) | 27.2k | #1462 | 社区 | Shields.io 服务的源码，为 GitHub README 等页面生成简洁一致的 SVG 与位图徽章，支持数十种持续集成、包仓库、覆盖率与社交网络等数据源。 |
| [remy/nodemon](https://github.com/remy/nodemon) | 26.7k | #1507 | 社区 | 监视文件变化并自动重启 Node.js 应用的开发工具，避免每次改代码手动重启服务。 |
| [bazelbuild/bazel](https://github.com/bazelbuild/bazel) | 25.9k | #1578 | 社区 | Google 开源的快速、可扩展、多语言构建系统，用于大型 Monorepo，支持增量构建与远程缓存。 |
| [responsively-org/responsively-app](https://github.com/responsively-org/responsively-app) | 25.2k | #1650 | 社区 | 面向响应式网页开发的桌面浏览器，可同时在多种设备尺寸下预览同一页面并同步滚动和交互。 |
| [go-delve/delve](https://github.com/go-delve/delve) | 24.9k | #1676 | 社区 | Go 语言调试器，支持断点、变量查看、goroutine 检查，可用于命令行和多种 IDE。 |
| [vuejs/devtools-v6](https://github.com/vuejs/devtools-v6) | 24.7k | #1703 | 社区 | 调试 Vue.js 应用的浏览器开发者工具扩展（旧版），新版已在 vuejs/devtools 中开发。 |
| [rahuldkjain/github-profile-readme-generator](https://github.com/rahuldkjain/github-profile-readme-generator) | 24.4k | #1723 | 社区 | 用简洁界面生成 GitHub 个人主页 README 的工具，填写姓名、简介、平台账号后可加入访客计数、GitHub 统计等附加内容。 |
| [air-verse/air](https://github.com/air-verse/air) | 24k | #1769 | 社区 | Go 应用的热重载命令行工具，监听文件变化后自动重新编译并运行。 |

## 编程语言与开发环境

开发者每天直接使用的东西：编程语言与编译器基础设施、代码编辑器、命令行与终端，以及构建命令行应用的框架

### 编程语言、运行时与编译器

面向应用开发的编程语言本体、运行时和官方工具链（TypeScript、Go、Rust、Python、Java、Kotlin、Swift、Node.js、Deno、Bun 等），以及编译器基础设施、解释器实现和语法解析库（LLVM、Tree-sitter 一类） · 25 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [golang/go](https://github.com/golang/go) | 139.1k | #72 | 社区 | Go 编程语言的官方仓库，包含编译器、标准库和工具链，主打简洁、并发和高效的编译，广泛用于后端服务与云原生基础设施。 |
| [nodejs/node](https://github.com/nodejs/node) | 122.2k | #91 | 社区 | 基于 V8 引擎的开源 JavaScript 运行时，采用事件驱动、非阻塞 I/O 模型，由 OpenJS 基金会治理，是服务端 JavaScript 的基础。 |
| [rust-lang/rust](https://github.com/rust-lang/rust) | 119.3k | #94 | 社区 | Rust 语言的官方仓库，包含编译器、标准库和文档，以所有权系统在无垃圾回收的前提下保证内存安全，常用于高性能服务和 WebAssembly。 |
| [microsoft/TypeScript](https://github.com/microsoft/TypeScript) | 111.3k | #105 | 官方 · Microsoft | JavaScript 的超集，增加可选静态类型并编译为标准 JavaScript，提供类型检查与语言服务，是大型前后端项目的主流选择。 |
| [denoland/deno](https://github.com/denoland/deno) | 108.6k | #113 | 官方 · Deno | 由 Node.js 作者创建的 JavaScript / TypeScript / WebAssembly 运行时，默认安全（显式授权权限）、原生支持 TypeScript，并内置格式化、测试等工具。 |
| [oven-sh/bun](https://github.com/oven-sh/bun) | 96.1k | #139 | 官方 · Oven | 一体化 JavaScript / TypeScript 工具包：运行时、打包器、测试运行器和包管理器合一，基于 JavaScriptCore，主打启动与安装速度。 |
| [python/cpython](https://github.com/python/cpython) | 77.4k | #222 | 社区 | Python 语言的官方参考实现，包含解释器、标准库和文档，广泛用于 Web 后端、脚本自动化和数据处理。 |
| [swiftlang/swift](https://github.com/swiftlang/swift) | 70.4k | #278 | 社区 | Swift 语言仓库，包含编译器和标准库，语法简洁、默认内存安全，用于 iOS / macOS 应用，也可写服务端。 |
| [JetBrains/kotlin](https://github.com/JetBrains/kotlin) | 53.5k | #451 | 官方 · JetBrains | JetBrains 开发的 Kotlin 语言仓库，简洁的多平台语言，可编译到 JVM、JavaScript 和原生，是 Android 官方首选语言，也用于服务端。 |
| [DefinitelyTyped/DefinitelyTyped](https://github.com/DefinitelyTyped/DefinitelyTyped) | 51.4k | #478 | 社区 | TypeScript 类型定义的社区仓库，为没有自带类型的 JavaScript 包提供 @types 声明文件。 |
| [JuliaLang/julia](https://github.com/JuliaLang/julia) | 49.2k | #517 | 社区 | Julia 编程语言的源码仓库：面向科学与技术计算的高层、高性能动态语言，附编译安装说明及文档、包与社区链接。 |
| [llvm/llvm-project](https://github.com/llvm/llvm-project) | 40.8k | #705 | 社区 | LLVM 项目：模块化、可复用的编译器与工具链技术集合，核心包括中间表示、优化器与代码生成，并含 Clang、LLDB、libc++ 等子项目。 |
| [php/php-src](https://github.com/php/php-src) | 40.4k | #716 | 社区 | PHP 解释器源码，一门专为 Web 开发设计的通用脚本语言，支撑 WordPress、Laravel 等大量网站与框架。 |
| [vlang/v](https://github.com/vlang/v) | 37.9k | #810 | 社区 | V 编程语言：简单、快速、安全的编译型语言，编译速度快、零依赖，支持 C 到 V 的自动翻译。 |
| [carbon-language/carbon-lang](https://github.com/carbon-language/carbon-lang) | 33.9k | #991 | 社区 | Carbon 语言的主仓库：作为 C++ 实验性继任者的设计文档、实现与工具，目标是性能与 C++ 相当并能与现有 C++ 代码互操作，官方注明尚不可用于生产。 |
| [tokio-rs/tokio](https://github.com/tokio-rs/tokio) | 33.3k | #1033 | 社区 | Rust 的异步运行时，提供 I/O、网络、调度和定时器，是 Rust 异步 Web 与网络服务的基础。 |
| [tree-sitter/tree-sitter](https://github.com/tree-sitter/tree-sitter) | 27.1k | #1475 | 社区 | 解析器生成工具与增量解析库，为源文件构建具体语法树并随编辑高效更新，支持多种语言语法，被编辑器与代码分析工具广泛使用。 |
| [elixir-lang/elixir](https://github.com/elixir-lang/elixir) | 26.7k | #1506 | 社区 | 运行在 Erlang 虚拟机上的函数式语言，面向高并发与容错，Phoenix 等 Web 框架基于它。 |
| [microsoft/typescript-go](https://github.com/microsoft/typescript-go) 🗄️已归档 | 26.2k | #1553 | 官方 · Microsoft | TypeScript 原生（Go）移植版的暂存仓库，项目随 TypeScript 7.0 发布已关闭，后续开发回到主仓库。 |
| [v8/v8](https://github.com/v8/v8) | 25.3k | #1644 | 社区 | Google 开源的 JavaScript 和 WebAssembly 引擎，Chrome 与 Node.js 的核心，实现 ECMAScript 标准。 |
| [ruby/ruby](https://github.com/ruby/ruby) | 23.8k | #1801 | 社区 | Ruby 语言官方仓库，面向对象的解释型语言，常用于 Web 开发，Rails 就基于它。 |
| [openjdk/jdk](https://github.com/openjdk/jdk) | 23.4k | #1845 | 社区 | OpenJDK 主线仓库，Java 开发工具包的开源实现，包含 JVM、类库与编译器，是 Java 语言的参考实现。 |
| [bendlang/bend](https://github.com/bendlang/bend) | 23.2k | #1875 | 社区 | Bend 编程语言：一门强调法则与证明的高性能语言，以机械验证确保 AI 生成的实现符合意图，并以在 CPU 上接近 C、在 GPU 上接近 CUDA 的速度为目标。 |
| [RustPython/RustPython](https://github.com/RustPython/RustPython) | 22.4k | #1978 | 社区 | 用 Rust 编写的 Python 3 解释器，可嵌入 Rust 程序并编译到 WebAssembly，提供在线演示。 |
| [facebook/flow](https://github.com/facebook/flow) | 22.3k | #1983 | 官方 · Meta | Meta 开发的 JavaScript 静态类型检查器，为 JS 增加类型标注以提升代码质量，现用 Rust 实现。 |

### 代码编辑器与 IDE

开发者日常使用的独立代码编辑器、IDE 和远程开发环境（VS Code、Vim / Neovim、Zed、Helix 一类），以及 Vim / Neovim / Emacs 的发行版、配置与插件管理；嵌入网页的编辑器组件归「编辑器与富文本」 · 23 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [microsoft/vscode](https://github.com/microsoft/vscode) | 193.3k | #33 | 官方 · Microsoft | 微软主导的开源代码编辑器 VS Code 的开发仓库（Code - OSS），提供扩展体系、调试、Git 集成与语言服务协议，并公开路线图与迭代计划。 |
| [neovim/neovim](https://github.com/neovim/neovim) | 102.7k | #124 | 社区 | Vim 的重构分支，目标是更易维护、更易扩展：提供异步任务与 RPC API、内置 LSP 与 Lua 支持，可被各语言和外部 GUI 驱动。 |
| [zed-industries/zed](https://github.com/zed-industries/zed) | 91.1k | #161 | 官方 · Zed Industries | 由 Atom 与 Tree-sitter 的创作者开发的高性能多人协作代码编辑器，用 Rust 编写，支持 macOS、Linux 和 Windows。 |
| [coder/code-server](https://github.com/coder/code-server) | 79.5k | #214 | 官方 · Coder | 在任意机器上运行 VS Code 并通过浏览器访问，把编译、测试等重任务放到服务器上，在多种设备上获得一致的开发环境。 |
| [atom/atom](https://github.com/atom/atom) 🗄️已归档 | 60.7k | #367 | 社区 | GitHub 出品、基于 Electron 的可定制文本编辑器，主打可深度定制又不失易用；Atom 及其下所有仓库已于 2022 年 12 月归档。 |
| [helix-editor/helix](https://github.com/helix-editor/helix) | 46.4k | #574 | 社区 | 受 Kakoune 与 Neovim 启发、用 Rust 编写的模态文本编辑器，提供多光标选择、内置语言服务器支持和基于 Tree-sitter 的语法高亮。 |
| [vim/vim](https://github.com/vim/vim) | 41k | #698 | 社区 | Vim 官方仓库，Unix 经典编辑器 Vi 的增强版，提供多级撤销、语法高亮、命令历史、补全、脚本语言等功能。 |
| [lapce/lapce](https://github.com/lapce/lapce) | 38.9k | #773 | 社区 | 用纯 Rust 编写的代码编辑器，界面基于 Floem，采用 wgpu 渲染，内置 LSP、模态编辑、插件与远程开发支持。 |
| [junegunn/vim-plug](https://github.com/junegunn/vim-plug) | 35.8k | #903 | 社区 | 极简的 Vim 插件管理器，单文件无依赖，支持并行安装与更新、按需加载和浅克隆，兼容自 2006 年以来的所有 Vim 与 Neovim 版本。 |
| [VSCodium/vscodium](https://github.com/VSCodium/vscodium) | 33.5k | #1019 | 社区 | 自动把微软 vscode 仓库构建成不含微软品牌、遥测和专有许可的自由许可二进制文件的脚本仓库，并提供多种包管理器的安装方式。 |
| [adobe/brackets](https://github.com/adobe/brackets) 🗄️已归档 | 33k | #1046 | 官方 · Adobe | 用 HTML、CSS 与 JavaScript 构建的面向 Web 开发的现代开源代码编辑器，提供实时预览和内联编辑；Adobe 已于 2021 年 9 月停止支持。 |
| [amix/vimrc](https://github.com/amix/vimrc) | 31.8k | #1109 | 社区 | 作者用了十多年的「终极」Vim 配置，提供精简的 basic 版本和带大量插件、配色方案与配置的 awesome 版本，可为单个用户或全局安装。 |
| [nvim-lua/kickstart.nvim](https://github.com/nvim-lua/kickstart.nvim) | 31.5k | #1135 | 社区 | Neovim 配置的起点：单文件、注释完整、体量小；并非发行版，而是让你在此基础上搭建自己的配置，只面向最新的稳定版与 nightly 版。 |
| [micro-editor/micro](https://github.com/micro-editor/micro) | 29.7k | #1258 | 社区 | 现代易用的终端文本编辑器，是 nano 的继任者，以无依赖的单一静态二进制发布，适合在 SSH 会话中全职使用。 |
| [notepad-plus-plus/notepad-plus-plus](https://github.com/notepad-plus-plus/notepad-plus-plus) | 29.4k | #1279 | 社区 | 免费的源码编辑器与记事本替代品，支持多种编程语言和自然语言，运行于 Windows，采用 GPL 许可，发布包带有 GPG 签名。 |
| [NvChad/NvChad](https://github.com/NvChad/NvChad) | 28.5k | #1360 | 社区 | 用 Lua 编写的 Neovim 配置框架，提供美观的界面与极快的启动速度，大部分插件按需懒加载，并调校了 telescope、nvim-tree 等界面插件。 |
| [LazyVim/LazyVim](https://github.com/LazyVim/LazyVim) | 27.6k | #1430 | 社区 | 基于 lazy.nvim 的 Neovim 配置，兼顾从零搭建的灵活性与预设发行版的便利，把 Neovim 变成完整 IDE，并便于自定义和扩展。 |
| [ycm-core/YouCompleteMe](https://github.com/ycm-core/YouCompleteMe) | 25.9k | #1580 | 社区 | 面向 Vim 的代码补全引擎，提供语义补全与诊断，通过语言服务器支持多种语言，推荐使用附带的 install.py 安装。 |
| [neoclide/coc.nvim](https://github.com/neoclide/coc.nvim) | 25.2k | #1653 | 社区 | 面向 Vim 与 Neovim 的 IntelliSense 引擎，通过 Node.js 服务带来类似 VS Code 的补全、诊断、导航、重构与扩展支持，可托管语言服务器。 |
| [syl20bnr/spacemacs](https://github.com/syl20bnr/spacemacs) | 24.6k | #1712 | 社区 | 社区驱动的 Emacs 发行版，融合 Vim 的模态编辑与 Emacs 的能力，按功能层组织配置，开箱即用并提供助记键位菜单。 |
| [VundleVim/Vundle.vim](https://github.com/VundleVim/Vundle.vim) | 23.9k | #1779 | 社区 | Vim 插件管理器，可在 .vimrc 中声明并配置插件，通过一次按键完成安装、更新、按名称搜索和清理未使用的插件。 |
| [CodeEditApp/CodeEdit](https://github.com/CodeEditApp/CodeEdit) | 23.1k | #1886 | 社区 | 完全为 macOS 编写的社区代码编辑器，功能包括语法高亮、代码补全、查找替换、终端、调试、Git 集成与扩展；README 说明仍在开发中，尚不建议用于生产。 |
| [doomemacs/core](https://github.com/doomemacs/core) | 22.7k | #1922 | 社区 | 面向 Vim 用户的 Emacs 配置框架，强调速度与可自定义，内置模块化功能与文档，以「顽固的火星人黑客」自居。 |

### Shell 与终端

Shell、终端模拟器与复用器，以及 Shell 的提示符、主题、插件、补全与 dotfiles 配置（Zsh、Fish、Tmux、Alacritty、Oh My Zsh、Starship 一类） · 29 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [ohmyzsh/ohmyzsh](https://github.com/ohmyzsh/ohmyzsh) | 190k | #35 | 社区 | 社区驱动的 zsh 配置管理框架，附带 300 多个可选插件（git、docker、node、python 等）、140 多个主题和自动更新工具。 |
| [microsoft/terminal](https://github.com/microsoft/terminal) | 105k | #118 | 官方 · Microsoft | Windows Terminal 与 Windows 控制台宿主的源码仓库，支持多标签、分屏、GPU 加速文本渲染，可运行命令提示符、PowerShell 与 WSL。 |
| [nvbn/thefuck](https://github.com/nvbn/thefuck) | 97.9k | #132 | 社区 | 自动纠正上一条错误控制台命令的命令行工具，可识别拼写错误、权限不足等常见问题并给出修正后的命令，还提供实验性的即时模式。 |
| [Eugeny/tabby](https://github.com/Eugeny/tabby) | 74.8k | #246 | 社区 | 高度可配置的现代终端应用，提供标签、分屏、SSH 与串口连接、插件系统，基于 Electron 并支持 Windows、macOS 和 Linux。 |
| [alacritty/alacritty](https://github.com/alacritty/alacritty) | 65.9k | #309 | 社区 | 跨平台、基于 OpenGL 的快速终端模拟器，默认配置合理并支持大量配置项，通过与其他程序集成而不重复实现其功能。 |
| [warpdotdev/warp](https://github.com/warpdotdev/warp) | 65.3k | #314 | 官方 · Warp | 从终端发展而来的智能开发环境，内置编码 Agent，也可接入 Claude Code、Codex、Gemini CLI 等命令行 Agent，支持 macOS、Linux 与 Windows。 |
| [ghostty-org/ghostty](https://github.com/ghostty-org/ghostty) | 61.7k | #352 | 社区 | 用 Zig 编写、使用平台原生界面与 GPU 加速的快速跨平台终端模拟器，并提供可嵌入的核心库 libghostty。 |
| [starship/starship](https://github.com/starship/starship) | 60.1k | #374 | 社区 | 适用于任意 Shell 的极简、快速、可高度定制的命令提示符，跨平台并按上下文显示 Git、语言版本、云环境等信息。 |
| [PowerShell/PowerShell](https://github.com/PowerShell/PowerShell) | 55.6k | #419 | 社区 | 跨平台（Windows、Linux、macOS）的自动化与配置工具，包含命令行 Shell、脚本语言与 cmdlet 处理框架，擅长处理 JSON、CSV、REST API 等结构化数据。 |
| [romkatv/powerlevel10k](https://github.com/romkatv/powerlevel10k) | 55.2k | #424 | 社区 | 强调速度、灵活性与开箱即用体验的 Zsh 主题，提供交互式配置向导和丰富的提示符信息；README 说明项目目前只提供极有限的支持。 |
| [tmux/tmux](https://github.com/tmux/tmux) | 49.6k | #511 | 社区 | 终端复用器，可在一个屏幕中创建、访问和控制多个终端，会话可脱离后台运行并在之后重新连接。 |
| [GitSquared/edex-ui](https://github.com/GitSquared/edex-ui) 🗄️已归档 | 45.1k | #604 | 社区 | 外观和体验像科幻电影界面的全屏跨平台终端模拟器与系统监视器，灵感来自《创：战纪》，兼顾实际可用性；项目已于 2021 年归档。 |
| [vercel/hyper](https://github.com/vercel/hyper) | 44.7k | #610 | 官方 · Vercel | 基于开放 Web 标准（HTML、CSS、JavaScript）构建的终端，重点是速度、稳定性和面向扩展作者的 API。 |
| [nushell/nushell](https://github.com/nushell/nushell) | 40.6k | #712 | 社区 | 新型 Shell，把管道中的数据当作结构化表格处理，支持 JSON、CSV 等格式的读取、过滤与转换，并提供插件与内置脚本语言。 |
| [zsh-users/zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) | 36.1k | #890 | 社区 | 为 zsh 提供类似 fish 的命令自动建议，根据历史记录和补全在输入时以灰色显示建议，按方向键即可接受。 |
| [zellij-org/zellij](https://github.com/zellij-org/zellij) | 35.6k | #914 | 社区 | 面向开发者与运维人员的终端工作区（终端复用器），强调开箱即用的体验，提供布局、插件与 WebAssembly 扩展。 |
| [kovidgoyal/kitty](https://github.com/kovidgoyal/kitty) | 35.1k | #929 | 社区 | 跨平台、基于 GPU 的快速终端模拟器，功能丰富，支持图像显示、分屏布局、脚本化扩展（kittens）与远程控制。 |
| [fish-shell/fish-shell](https://github.com/fish-shell/fish-shell) | 34.2k | #971 | 社区 | 友好的命令行 Shell，开箱即用地提供语法高亮、输入时自动建议和补全，适用于 macOS、Linux 等系统。 |
| [kingToolbox/WindTerm](https://github.com/kingToolbox/WindTerm) | 32.4k | #1075 | 社区 | 面向运维的跨平台 SSH / Telnet / 串口 / Shell / SFTP 终端客户端，支持商业与非商业免费使用，源码以 Apache-2.0 发布（第三方目录除外）。 |
| [atuinsh/atuin](https://github.com/atuinsh/atuin) | 31.9k | #1106 | 社区 | 用 SQLite 数据库取代 Shell 历史，额外记录退出码、耗时与目录等上下文，提供搜索界面和可选的端到端加密跨机器同步。 |
| [mathiasbynens/dotfiles](https://github.com/mathiasbynens/dotfiles) | 31.5k | #1136 | 社区 | Mathias 的个人 dotfiles，包含 bash 配置与 macOS 合理默认设置（~/.macos），通过引导脚本安装，作者提醒使用前先 fork 并审阅代码。 |
| [wezterm/wezterm](https://github.com/wezterm/wezterm) | 29.1k | #1310 | 社区 | 用 Rust 编写的 GPU 加速跨平台终端模拟器与复用器，支持标签、分屏、Lua 配置和内置多路复用。 |
| [mbadolato/iTerm2-Color-Schemes](https://github.com/mbadolato/iTerm2-Color-Schemes) | 27.2k | #1461 | 社区 | 600 多套终端配色方案，最初面向 iTerm2，并移植到 Terminal、Konsole、PuTTY、Windows Terminal、Alacritty、Ghostty 等众多终端与应用。 |
| [cmderdev/cmder](https://github.com/cmderdev/cmder) | 27k | #1481 | 社区 | 基于 ConEmu 的 Windows 便携式控制台模拟器套件，附带 Monokai 配色、clink 补全与自定义提示符，无需外部依赖，可放在 U 盘或云盘中携带。 |
| [Swordfish90/cool-retro-term](https://github.com/Swordfish90/cool-retro-term) | 26.5k | #1528 | 社区 | 模拟老式阴极射线管显示器外观的终端模拟器，注重视觉效果与可定制性，基于 Qt 6 的 QML 实现，支持 Linux 与 macOS。 |
| [gpakosz/.tmux](https://github.com/gpakosz/.tmux) | 25.4k | #1632 | 社区 | 自包含、美观且实用的 tmux 配置（Oh my tmux!），提供状态栏、鼠标与剪贴板集成等增强，可在 Linux、macOS、BSD 上使用。 |
| [withfig/autocomplete](https://github.com/withfig/autocomplete) | 25.2k | #1649 | 社区 | 为现有终端与 Shell 提供 IDE 风格补全的项目，为 git、npm、docker、aws 等数百个命令行工具补全子命令、选项与参数；该项目后来演变为 Amazon Q Developer CLI。 |
| [JanDeDobbeleer/oh-my-posh](https://github.com/JanDeDobbeleer/oh-my-posh) | 23.5k | #1831 | 社区 | 跨平台、低延迟且高度可定制的 Shell 提示符渲染器，起源于 PowerShell 的 oh-my-posh2，用 Go 重写，支持主题与多种 Shell。 |
| [zsh-users/zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) | 23k | #1889 | 社区 | 为 zsh 提供类似 fish 的命令语法高亮，在输入时高亮命令，便于在执行前发现拼写和语法错误。 |

### Git 与版本控制工具

Git 本体、其他版本控制系统，以及 Git 图形与终端客户端、差异查看和分支工作流工具（Git、Jujutsu、Lazygit、Delta 一类） · 9 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [jesseduffield/lazygit](https://github.com/jesseduffield/lazygit) | 82.8k | #197 | 社区 | 用于 Git 命令的简洁终端界面，在终端里完成暂存、提交、分支、变基与冲突处理等常见操作。 |
| [git/git](https://github.com/git/git) | 63.5k | #328 | 社区 | 分布式版本控制系统 Git 的源码镜像，提供高层操作与对内部机制的完整访问，最初由 Linus Torvalds 编写，补丁通过邮件列表提交。 |
| [cli/cli](https://github.com/cli/cli) | 46.5k | #571 | 官方 · GitHub | GitHub 官方命令行工具 gh，在终端里处理 PR、Issue、Actions 和仓库操作，可与 git 配合使用。 |
| [dandavison/delta](https://github.com/dandavison/delta) | 32.4k | #1072 | 社区 | 为 git、diff、grep 与 blame 输出提供语法高亮的分页器，支持并排显示、行内词级差异高亮和导航。 |
| [jj-vcs/jj](https://github.com/jj-vcs/jj) | 31.8k | #1110 | 社区 | Jujutsu：与 Git 兼容、既简单又强大的版本控制系统，以 Git 仓库为存储后端，提供自动重写提交、一等公民冲突与操作日志等特性。 |
| [nvie/gitflow](https://github.com/nvie/gitflow) 🗄️已归档 | 26.8k | #1502 | 社区 | 为 Vincent Driessen 的 Git 分支模型提供高层仓库操作的 Git 扩展；README 说明仓库已不再维护，已迁移到 git-flow-next。 |
| [Wilfred/difftastic](https://github.com/Wilfred/difftastic) | 26k | #1571 | 社区 | 基于语法的结构化 diff 工具，理解代码结构而非按行比较，重新格式化代码时只显示真正的语义变化。 |
| [mislav/hub](https://github.com/mislav/hub) | 23k | #1895 | 社区 | 包装 git 的命令行工具，为 git 增加与 GitHub 交互的命令，例如克隆仓库、创建拉取请求与查看议题；官方更推荐使用 GitHub CLI。 |
| [gitui-org/gitui](https://github.com/gitui-org/gitui) | 22.5k | #1948 | 社区 | 用 Rust 编写的快速 Git 终端界面，提供暂存、提交、分支、日志与差异查看，强调低内存占用与响应速度。 |

### 命令行工具

curl 等命令行基础工具，以及 fzf、ripgrep、jq、bat 一类的现代命令行工具、文件管理器、系统监控与基准测试工具 · 27 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [junegunn/fzf](https://github.com/junegunn/fzf) | 83.3k | #191 | 社区 | 通用命令行模糊查找器与交互式终端工具包，可用来选择文件、浏览命令历史、预览数据，并与 Shell 深度集成，以单个二进制发布。 |
| [BurntSushi/ripgrep](https://github.com/BurntSushi/ripgrep) | 68.7k | #284 | 社区 | 按行搜索的命令行工具，递归搜索目录中的正则匹配，默认遵守 gitignore 并跳过隐藏与二进制文件，支持 Windows、macOS 和 Linux。 |
| [sharkdp/bat](https://github.com/sharkdp/bat) | 60.6k | #368 | 社区 | 带语法高亮与 Git 集成的 cat 替代品，支持多种编程与标记语言、自动分页并可显示不可见字符。 |
| [jgm/pandoc](https://github.com/jgm/pandoc) | 46.5k | #572 | 社区 | 通用标记语言转换器：既是 Haskell 库也是命令行工具，可在 Markdown、AsciiDoc、HTML、LaTeX、DOCX 等多种格式之间转换。 |
| [sharkdp/fd](https://github.com/sharkdp/fd) | 44.6k | #615 | 社区 | find 的简单、快速、易用的替代品，默认支持正则与 glob、并行遍历目录、彩色输出并遵守 gitignore。 |
| [curl/curl](https://github.com/curl/curl) | 43k | #651 | 社区 | 用 URL 语法传输数据的命令行工具与 libcurl 库，支持 HTTP(S)、FTP、SFTP、SMTP、IMAP、MQTT、WebSocket 等数十种协议。 |
| [sxyazi/yazi](https://github.com/sxyazi/yazi) | 42.5k | #659 | 社区 | 用 Rust 编写、基于非阻塞异步 I/O 的终端文件管理器，所有 I/O 操作异步执行，CPU 任务分散到多线程，注重速度与可定制性。 |
| [wg/wrk](https://github.com/wg/wrk) | 40.4k | #717 | 社区 | 现代 HTTP 压测工具，多线程加事件通知机制，可在单台多核机器上产生大量负载，并支持用 LuaJIT 脚本生成请求与自定义报告。 |
| [koalaman/shellcheck](https://github.com/koalaman/shellcheck) | 40.1k | #724 | 社区 | 针对 bash / sh 脚本的静态分析工具，指出常见语法问题、语义陷阱与边界情况，并给出修复建议。 |
| [ajeetdsouza/zoxide](https://github.com/ajeetdsouza/zoxide) | 39.8k | #743 | 社区 | 更智能的 cd 命令，记住常用目录并按访问频率与最近使用排序，几个按键即可跳转，支持主流 Shell。 |
| [casey/just](https://github.com/casey/just) | 36.1k | #892 | 社区 | 保存并运行项目命令的命令运行器，用类 make 语法在 justfile 中定义任务（recipes），并支持参数、跨平台和 Shell 集成。 |
| [jqlang/jq](https://github.com/jqlang/jq) | 35.7k | #907 | 社区 | 轻量灵活的命令行 JSON 处理器，类似 sed、awk 之于文本，用于切片、过滤、映射和转换结构化数据，用 C 编写且无运行时依赖。 |
| [aristocratos/btop](https://github.com/aristocratos/btop) | 34.8k | #941 | 社区 | 命令行资源监视器，实时显示 CPU、内存、磁盘、网络与进程信息，界面美观、支持主题，可在 Linux、macOS 与 BSD 上运行。 |
| [microsoft/WSL](https://github.com/microsoft/WSL) | 33.8k | #999 | 官方 · Microsoft | 适用于 Linux 的 Windows 子系统，可在 Windows 上直接运行未经修改的 Linux 命令行工具和应用，无需传统虚拟机或双系统。 |
| [nicolargo/glances](https://github.com/nicolargo/glances) | 33.7k | #1005 | 社区 | 用 Python 编写的跨平台系统监控工具，是 top / htop 的替代品，可在终端或 Web 界面中查看 CPU、内存、磁盘与网络等系统信息。 |
| [sharkdp/hyperfine](https://github.com/sharkdp/hyperfine) | 28.9k | #1325 | 社区 | 命令行基准测试工具，可对任意 Shell 命令多次运行做统计分析，支持预热、清缓存、异常值检测并导出 CSV 与 JSON 等格式。 |
| [charmbracelet/glow](https://github.com/charmbracelet/glow) | 27.5k | #1436 | 官方 · Charm | 在终端里渲染 Markdown 的阅读器，可发现并浏览本地或 Git 仓库中的 Markdown 文件，直接在命令行阅读文档。 |
| [ggreer/the_silver_searcher](https://github.com/ggreer/the_silver_searcher) | 27.1k | #1473 | 社区 | 类似 ack 但更快的代码搜索工具（ag），自动忽略 .gitignore 与 .hgignore 中的文件，命令更短，适合在大型代码库中检索。 |
| [fastfetch-cli/fastfetch](https://github.com/fastfetch-cli/fastfetch) | 24.8k | #1685 | 社区 | 类似 neofetch 的系统信息展示工具，以 C 为主编写，强调性能与可定制性，支持 Linux、macOS、Windows、Android 与多种 BSD。 |
| [charmbracelet/gum](https://github.com/charmbracelet/gum) | 24.4k | #1724 | 官方 · Charm | 为 Shell 脚本提供现成的交互组件（选择、输入、确认、过滤、样式化等），基于 Bubbles 与 Lip Gloss，无需编写 Go 代码即可让脚本更好看易用。 |
| [ogham/exa](https://github.com/ogham/exa) | 24.4k | #1727 | 社区 | ls 的现代替代品，用颜色区分文件类型与元数据并识别 Git 状态；README 说明项目已无人维护，建议改用其分支 eza。 |
| [uutils/coreutils](https://github.com/uutils/coreutils) | 24.2k | #1757 | 社区 | 用 Rust 对 GNU coreutils 的跨平台重新实现，提供预编译二进制、手册页与 Shell 补全，所有程序都已实现，但部分选项可能缺失或行为不同。 |
| [dylanaraps/neofetch](https://github.com/dylanaraps/neofetch) 🗄️已归档 | 23.7k | #1813 | 社区 | 用 bash 编写的命令行系统信息工具，在操作系统标志旁展示系统与硬件信息，常用于系统截图；仓库已归档。 |
| [AlDanial/cloc](https://github.com/AlDanial/cloc) | 23.6k | #1826 | 社区 | 统计多种编程语言源码中空行、注释行与代码行数的命令行工具，用 Perl 编写，提供 Windows 可执行文件与 Docker 镜像。 |
| [yorukot/superfile](https://github.com/yorukot/superfile) | 23.6k | #1827 | 社区 | 美观现代的终端文件管理器，提供常见文件操作、插件、主题与快捷键，支持 macOS、Linux 与 Windows。 |
| [eza-community/eza](https://github.com/eza-community/eza) | 23.4k | #1841 | 社区 | ls 的现代替代品，用颜色区分文件类型与元数据，识别符号链接、扩展属性与 Git 状态，以单个小型二进制发布。 |
| [pranshuparmar/witr](https://github.com/pranshuparmar/witr) | 22.5k | #1947 | 社区 | 回答「为什么这个在运行」的命令行与终端界面工具，可把进程、端口、容器或文件追溯到启动它们的完整调用链，支持机器可读的 JSON 输出。 |

### CLI 与 TUI 框架

用来构建命令行与终端界面应用的框架和库：参数解析、终端样式、进度条与 TUI 组件（Cobra、Bubble Tea、Ratatui、Ink、Textual、Rich 一类） · 11 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [Textualize/rich](https://github.com/Textualize/rich) | 57.5k | #403 | 官方 · Textualize | 用于在终端中输出富文本与美观格式的 Python 库，可渲染彩色文本、表格、进度条、Markdown、语法高亮代码与回溯信息。 |
| [charmbracelet/bubbletea](https://github.com/charmbracelet/bubbletea) | 45.2k | #600 | 官方 · Charm | 基于 Elm 架构的 Go 终端应用框架，适用于内嵌或全屏的 TUI，提供高性能渲染、颜色降级与键鼠事件处理。 |
| [spf13/cobra](https://github.com/spf13/cobra) | 44.7k | #612 | 社区 | 用于构建现代 Go 命令行应用的库，提供子命令、标志解析、自动帮助与补全生成，被 Kubernetes、Hugo、GitHub CLI 等项目采用。 |
| [vadimdemedes/ink](https://github.com/vadimdemedes/ink) | 40k | #731 | 社区 | 面向命令行应用的 React 渲染器，用组件构建并测试 CLI 输出，借助 Yoga 在终端中实现 Flexbox 布局。 |
| [Textualize/textual](https://github.com/Textualize/textual) | 37.4k | #834 | 官方 · Textualize | 用简单的 Python API 构建复杂界面的应用框架，同一套代码既可在终端也可在浏览器中运行，提供组件、样式与测试工具。 |
| [tqdm/tqdm](https://github.com/tqdm/tqdm) | 31.4k | #1144 | 社区 | 快速、可扩展的 Python 与命令行进度条，只需包装任意可迭代对象即可显示进度、速度与剩余时间，并支持 Jupyter 与管道。 |
| [tj/commander.js](https://github.com/tj/commander.js) | 28.4k | #1365 | 社区 | Node.js 命令行接口的完整解决方案，用于声明命令、选项和参数并自动生成帮助信息。 |
| [google/python-fire](https://github.com/google/python-fire) | 28.2k | #1384 | 官方 · Google | 可从任意 Python 对象（函数、类、模块、字典等）自动生成命令行接口的库，便于调试、探索代码与在 Bash 与 Python 间切换。 |
| [urfave/cli](https://github.com/urfave/cli) | 24.3k | #1751 | 社区 | 用于构建 Go 命令行工具的声明式库，提供命令、子命令、标志与自动帮助。 |
| [chalk/chalk](https://github.com/chalk/chalk) | 23.3k | #1856 | 社区 | Node.js 终端字符串样式库，提供可嵌套的样式 API，支持 256 色与真彩色并自动检测颜色支持，无依赖。 |
| [ratatui/ratatui](https://github.com/ratatui/ratatui) | 22.8k | #1913 | 社区 | 用于构建终端用户界面（TUI）的 Rust 库，提供布局、组件与即时模式渲染，并有模板与大量示例应用。 |

## 后端与服务框架

服务端框架、微服务治理、API 层、认证与后端即服务

### 后端框架

Express、FastAPI、Spring Boot、Gin、NestJS 等服务端 Web 框架与网络应用框架 · 25 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [fastapi/fastapi](https://github.com/fastapi/fastapi) | 102.7k | #123 | 社区 | 现代高性能 Python Web 框架，基于类型注解自动做请求校验和序列化，并生成 OpenAPI 与交互式文档，支持异步。 |
| [gin-gonic/gin](https://github.com/gin-gonic/gin) | 89.3k | #174 | 社区 | Go 语言高性能 HTTP Web 框架，基于 httprouter，提供中间件、路由分组、参数绑定和 JSON 校验，是 Go 后端最常用的框架之一。 |
| [spring-projects/spring-boot](https://github.com/spring-projects/spring-boot) | 81.5k | #202 | 社区 | Java 生态最主流的应用框架，以自动配置、起步依赖和内嵌服务器让 Spring 应用「开箱即用」，适合构建生产级服务与微服务。 |
| [nestjs/nest](https://github.com/nestjs/nest) | 76.8k | #228 | 社区 | 基于 TypeScript 的渐进式 Node.js 服务端框架，借鉴 Angular 的模块、依赖注入与装饰器设计，底层可接 Express 或 Fastify，适合构建企业级后端。 |
| [pallets/flask](https://github.com/pallets/flask) | 74.8k | #245 | 社区 | 轻量级 Python WSGI Web 微框架，基于 Werkzeug 和 Jinja，核心精简、通过扩展按需增加功能，易上手也能扩展到复杂应用。 |
| [expressjs/express](https://github.com/expressjs/express) | 69.5k | #281 | 社区 | Node.js 上快速、极简、不预设结构的 Web 框架，提供路由和中间件机制，是最广泛使用的 Node 后端框架。 |
| [spring-projects/spring-framework](https://github.com/spring-projects/spring-framework) | 60.3k | #370 | 社区 | Spring 全家桶的基础框架，提供依赖注入、面向切面编程、Web MVC / WebFlux、数据访问与事务管理等核心能力。 |
| [gofiber/fiber](https://github.com/gofiber/fiber) | 40.2k | #721 | 社区 | 受 Express 启发的 Go Web 框架，构建在 Fasthttp 之上，强调零内存分配和开发效率。 |
| [dotnet/aspnetcore](https://github.com/dotnet/aspnetcore) | 38.5k | #791 | 社区 | 微软的跨平台 .NET Web 框架，用于构建 Web 应用、API、实时通信（SignalR）和微服务，可运行在 Windows、macOS、Linux。 |
| [fastify/fastify](https://github.com/fastify/fastify) | 37.2k | #845 | 社区 | 高性能低开销的 Node.js Web 框架，提供基于 JSON Schema 的校验与序列化、插件体系和完善的日志。 |
| [koajs/koa](https://github.com/koajs/koa) | 35.7k | #911 | 社区 | 由 Express 团队打造的 Node.js 中间件框架，基于 async 函数，核心极小，用洋葱模型组织中间件。 |
| [netty/netty](https://github.com/netty/netty) | 35.1k | #931 | 社区 | 事件驱动的异步网络应用框架，为 Java 提供高性能的 NIO 通信基础，是众多 RPC、网关和中间件的底层。 |
| [labstack/echo](https://github.com/labstack/echo) | 32.7k | #1061 | 社区 | 高性能、极简的 Go Web 框架，提供路由、中间件、数据绑定和自动 TLS，基于标准库 net/http。 |
| [beego/beego](https://github.com/beego/beego) | 32.4k | #1071 | 社区 | Go 语言高性能 Web 框架，用于快速开发企业级应用，含 RESTful API、ORM、缓存、日志与任务模块。 |
| [honojs/hono](https://github.com/honojs/hono) | 32.4k | #1073 | 社区 | 基于 Web 标准的小巧超快 Web 框架，可运行于 Cloudflare Workers、Deno、Bun、Node.js 等多种运行时。 |
| [symfony/symfony](https://github.com/symfony/symfony) | 31.2k | #1156 | 官方 · Symfony | PHP Web 与控制台应用框架，同时是一组可复用组件的集合，Laravel、Drupal 等项目大量使用其组件。 |
| [encode/django-rest-framework](https://github.com/encode/django-rest-framework) | 30.2k | #1208 | 社区 | Django 的 Web API 工具包，提供序列化、视图集、认证与可浏览 API，是 Django 项目构建 REST 接口的事实标准。 |
| [tokio-rs/axum](https://github.com/tokio-rs/axum) | 27.3k | #1454 | 社区 | Rust 的 HTTP 路由与请求处理库，基于 Tokio 和 Tower，强调易用与模块化，是 Rust Web 开发的主流选择。 |
| [vapor/vapor](https://github.com/vapor/vapor) | 26.2k | #1548 | 社区 | Swift 服务端 HTTP Web 框架，提供表达力强、易用的基础，可用 Swift 写后端 API 与网站。 |
| [rwf2/Rocket](https://github.com/rwf2/Rocket) | 25.8k | #1593 | 社区 | Rust 的异步 Web 框架，强调易用性、安全性和可扩展性，用类型系统与宏简化路由和请求处理。 |
| [kataras/iris](https://github.com/kataras/iris) | 25.6k | #1618 | 社区 | 高性能 Go HTTP/2 Web 框架，提供路由、MVC、中间件和会话等功能。 |
| [actix/actix-web](https://github.com/actix/actix-web) | 24.8k | #1683 | 社区 | 强大、务实且极快的 Rust Web 框架，基于 Actix 参与者系统，提供路由、中间件、WebSocket 与 HTTP/2 支持。 |
| [valyala/fasthttp](https://github.com/valyala/fasthttp) | 23.5k | #1835 | 社区 | 高性能 Go HTTP 包，热点路径零内存分配，宣称比 net/http 快数倍，适合高并发服务。 |
| [go-chi/chi](https://github.com/go-chi/chi) | 22.9k | #1902 | 社区 | 轻量、地道且可组合的 Go HTTP 路由，基于标准库 net/http，用于构建 HTTP 服务。 |
| [tornadoweb/tornado](https://github.com/tornadoweb/tornado) | 22.2k | #1998 | 社区 | Python Web 框架与异步网络库，最初由 FriendFeed 开发，采用非阻塞 I/O，适合长连接与高并发场景。 |

### 微服务与服务治理

微服务与 RPC 框架、服务发现、配置中心、熔断限流、分布式事务、任务调度与分布式服务运行时（Dubbo、Go Zero、Dapr、Nacos、Sentinel、etcd 一类） · 14 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [etcd-io/etcd](https://github.com/etcd-io/etcd) | 52.3k | #464 | 社区 | 分布式可靠键值存储，基于 Raft 共识，用于保存分布式系统的关键数据，是 Kubernetes 的核心组件。 |
| [apache/dubbo](https://github.com/apache/dubbo) | 41.6k | #685 | 社区 | Apache Dubbo 的 Java 实现，一个 RPC 与微服务框架，提供服务发现、负载均衡、流量治理，也有多语言实现。 |
| [alibaba/nacos](https://github.com/alibaba/nacos) | 33.4k | #1023 | 官方 · Alibaba | 动态服务发现、配置管理和服务管理平台，用于构建云原生应用，国内微服务体系中常用的注册与配置中心。 |
| [zeromicro/go-zero](https://github.com/zeromicro/go-zero) | 33.4k | #1028 | 社区 | 云原生 Go 微服务框架，内置限流、熔断、缓存、超时控制等工程实践，并带代码生成命令行工具。 |
| [xuxueli/xxl-job](https://github.com/xuxueli/xxl-job) | 30.6k | #1184 | 社区 | 国内常用的分布式任务调度平台，提供可视化调度中心、执行器、分片和失败重试，易于接入。 |
| [hashicorp/consul](https://github.com/hashicorp/consul) | 30.1k | #1213 | 官方 · HashiCorp | 服务发现、配置和服务网格解决方案，为动态分布式基础设施中的应用提供健康检查、键值存储与安全连接。 |
| [apolloconfig/apollo](https://github.com/apolloconfig/apollo) | 29.8k | #1239 | 社区 | 携程开源的分布式配置中心，集中管理多环境、多集群配置，支持实时推送、灰度发布与权限审计。 |
| [alibaba/spring-cloud-alibaba](https://github.com/alibaba/spring-cloud-alibaba) | 29.2k | #1300 | 官方 · Alibaba | 为阿里中间件提供的 Spring Cloud 一站式分布式解决方案，整合 Nacos、Sentinel、Seata、RocketMQ 等。 |
| [go-kit/kit](https://github.com/go-kit/kit) | 27.4k | #1446 | 社区 | Go 微服务工具包，提供服务发现、日志、指标、传输层抽象等组件，适合构建微服务或结构清晰的单体应用。 |
| [dapr/dapr](https://github.com/dapr/dapr) | 26.1k | #1556 | 社区 | 可移植的分布式应用运行时，通过 Sidecar 提供服务调用、状态管理、发布订阅和工作流等构建块，可运行于云端和边缘。 |
| [apache/incubator-seata](https://github.com/apache/incubator-seata) | 26k | #1565 | 社区 | 易用高性能的开源分布式事务方案，提供 AT、TCC、Saga、XA 等模式，常与 Spring Cloud 微服务配合。 |
| [go-kratos/kratos](https://github.com/go-kratos/kratos) | 26k | #1572 | 社区 | 轻量的 Go 云原生微服务框架，提供 HTTP / gRPC 服务、中间件、配置和注册发现等组件。 |
| [Netflix/Hystrix](https://github.com/Netflix/Hystrix) | 24.5k | #1721 | 官方 · Netflix | Netflix 开源的延迟与容错库，通过隔离远程调用、熔断和降级防止级联故障，已进入维护模式。 |
| [alibaba/Sentinel](https://github.com/alibaba/Sentinel) | 23.1k | #1876 | 官方 · Alibaba | 面向云原生微服务的高可用流控防护组件，提供限流、熔断降级、系统自适应保护与实时监控。 |

### API 与网关

API 设计、调试、文档、GraphQL / tRPC / gRPC、网关与代理框架、实时通信 · 25 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [hoppscotch/hoppscotch](https://github.com/hoppscotch/hoppscotch) | 80.6k | #208 | 官方 · Hoppscotch | 开源 API 开发工具，可调试 REST、GraphQL、WebSocket 等接口，提供 Web、桌面和命令行版本，定位为 Postman 和 Insomnia 的开源替代。 |
| [typicode/json-server](https://github.com/typicode/json-server) | 75.7k | #239 | 社区 | 用一个 JSON 文件在 30 秒内搭出完整的假 REST API，方便前端在后端就绪前联调和做原型。 |
| [protocolbuffers/protobuf](https://github.com/protocolbuffers/protobuf) | 72.1k | #270 | 社区 | Google 的语言无关、平台无关结构化数据序列化格式（Protocol Buffers），通过 .proto 定义生成多语言代码，常与 gRPC 搭配。 |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 63.2k | #335 | 社区 | 基于 WebSocket 的双向低延迟实时通信库，含服务端与客户端，自带断线重连、房间与广播、长轮询降级。 |
| [usebruno/bruno](https://github.com/usebruno/bruno) | 47.3k | #554 | 官方 · Bruno | 开源 API 调试工具，集合以纯文本文件保存在本地并可用 Git 管理，定位为 Postman 和 Insomnia 的轻量替代品。 |
| [grpc/grpc](https://github.com/grpc/grpc) | 45.4k | #596 | 社区 | Google 开源的高性能 RPC 框架，基于 HTTP/2 和 Protocol Buffers，支持多语言客户端与服务端，适合微服务通信。 |
| [mitmproxy/mitmproxy](https://github.com/mitmproxy/mitmproxy) | 45.2k | #599 | 社区 | 支持 SSL/TLS 的交互式拦截代理，面向渗透测试人员与软件开发者，提供 HTTP/1、HTTP/2 与 WebSocket 的控制台界面，另有命令行版 mitmdump 和网页版 mitmweb。 |
| [Kong/kong](https://github.com/Kong/kong) | 44.2k | #620 | 官方 · Kong | 云原生 API 网关（现也支持 LLM 网关），基于 Nginx 与 Lua，提供路由、认证、限流和插件扩展。 |
| [trpc/trpc](https://github.com/trpc/trpc) | 40.7k | #708 | 社区 | 端到端类型安全的 API 方案，前端直接调用服务端函数并获得类型推断，无需 schema 或代码生成。 |
| [Kong/insomnia](https://github.com/Kong/insomnia) | 40k | #729 | 官方 · Kong | 开源跨平台 API 客户端，支持 REST、GraphQL、WebSocket、SSE 和 gRPC，可选云端、本地或 Git 存储。 |
| [httpie/cli](https://github.com/httpie/cli) | 38.6k | #786 | 官方 · HTTPie | 面向人类的命令行 HTTP 客户端，语法直观，内置 JSON 支持、着色输出、会话与下载，适合调试 API。 |
| [slatedocs/slate](https://github.com/slatedocs/slate) 🗄️已归档 | 36k | #897 | 社区 | 静态 API 文档生成器，输出三栏式漂亮文档，曾被 NASA、Sony 等团队使用，现已少有更新。 |
| [hasura/graphql-engine](https://github.com/hasura/graphql-engine) | 32.1k | #1091 | 官方 · Hasura | 在数据库之上即时生成实时 GraphQL API 的引擎，支持细粒度权限控制和数据库事件触发 webhook。 |
| [OAI/OpenAPI-Specification](https://github.com/OAI/OpenAPI-Specification) | 31.2k | #1149 | 社区 | OpenAPI 规范仓库，定义描述 REST API 的标准格式，是接口文档、代码生成与测试工具的通用基础。 |
| [swagger-api/swagger-ui](https://github.com/swagger-api/swagger-ui) | 29k | #1314 | 官方 · SmartBear | 根据 OpenAPI / Swagger 规范动态生成交互式 API 文档的前端资源，可直接在页面上试调接口。 |
| [envoyproxy/envoy](https://github.com/envoyproxy/envoy) | 29k | #1315 | 社区 | 云原生高性能边缘 / 服务代理，支持 HTTP/2、gRPC、动态配置与丰富的可观测性，是 Istio 等服务网格的数据面。 |
| [YMFE/yapi](https://github.com/YMFE/yapi) | 27.7k | #1420 | 社区 | 可本地部署的可视化接口管理平台，打通前后端与测试，提供接口文档、Mock 和自动化测试。 |
| [PostgREST/postgrest](https://github.com/PostgREST/postgrest) | 27.7k | #1421 | 社区 | 直接把已有 PostgreSQL 数据库转成完整 RESTful API 的服务，依靠数据库自身的角色与行级安全做权限控制。 |
| [cloudflare/pingora](https://github.com/cloudflare/pingora) | 27.6k | #1431 | 官方 · Cloudflare | Cloudflare 用 Rust 编写的网络服务框架，用于构建快速、可靠、可编程的代理与网关，支持 HTTP/1/2、gRPC、WebSocket、TLS、负载均衡与热重载。 |
| [OpenAPITools/openapi-generator](https://github.com/OpenAPITools/openapi-generator) | 26.8k | #1503 | 社区 | 根据 OpenAPI 规范自动生成多语言 API 客户端 SDK、服务端桩代码、文档和配置。 |
| [google/flatbuffers](https://github.com/google/flatbuffers) | 26.5k | #1519 | 官方 · Google | 内存高效的跨平台序列化库，无需解析即可直接访问序列化数据，常用于游戏、移动端和高性能场景。 |
| [Redocly/redoc](https://github.com/Redocly/redoc) | 25.9k | #1576 | 官方 · Redocly | 根据 OpenAPI / Swagger 规范生成美观的三栏式 API 参考文档，可自定义主题并服务端渲染。 |
| [gorilla/websocket](https://github.com/gorilla/websocket) | 24.9k | #1680 | 社区 | Go 的 WebSocket 协议实现，速度快、经过充分测试，被广泛使用。 |
| [grpc/grpc-go](https://github.com/grpc/grpc-go) | 23.1k | #1884 | 社区 | gRPC 的 Go 语言实现，基于 HTTP/2 的高性能 RPC 框架。 |
| [websockets/ws](https://github.com/websockets/ws) | 22.8k | #1911 | 社区 | 简单易用、速度极快且经过充分测试的 Node.js WebSocket 客户端与服务端库。 |

### 认证、身份与密钥

登录、SSO、身份管理、权限控制和密钥管理 · 10 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [keycloak/keycloak](https://github.com/keycloak/keycloak) | 37.1k | #852 | 社区 | 开源身份与访问管理系统，提供单点登录、OIDC、SAML、社交登录、用户联邦和细粒度授权。 |
| [hashicorp/vault](https://github.com/hashicorp/vault) | 36.3k | #883 | 官方 · HashiCorp | 密钥管理、加密即服务和特权访问管理工具，集中存储和动态生成凭据、证书与令牌。 |
| [better-auth/better-auth](https://github.com/better-auth/better-auth) | 30.1k | #1209 | 官方 · Better Auth | 与框架无关的 TypeScript 认证与授权框架，内置邮箱密码、社交登录、多因素认证和插件体系，数据存于自有数据库。 |
| [Infisical/infisical](https://github.com/Infisical/infisical) | 29.5k | #1272 | 官方 · Infisical | 开源密钥、证书与特权访问管理平台，跨团队和基础设施同步机密配置，防止密钥泄露。 |
| [authelia/authelia](https://github.com/authelia/authelia) | 29.1k | #1306 | 社区 | 面向 Web 应用的开源单点登录与多因素认证门户，可与反向代理配合，支持 OpenID Connect。 |
| [nextauthjs/next-auth](https://github.com/nextauthjs/next-auth) | 28.4k | #1370 | 社区 | Auth.js（前身 NextAuth），面向 Web 的开源认证库，支持 OAuth、邮箱、凭据和多种数据库适配器，最初为 Next.js 设计。 |
| [goauthentik/authentik](https://github.com/goauthentik/authentik) | 25.8k | #1590 | 官方 · authentik | 开源身份提供商（IdP），支持 SSO、OAuth2、SAML、LDAP 等协议，用于统一管理应用登录。 |
| [heartcombo/devise](https://github.com/heartcombo/devise) | 24.4k | #1738 | 社区 | Rails 的灵活认证方案，基于 Warden，提供登录、注册、密码找回、可锁定等模块化功能。 |
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 23.5k | #1830 | 社区 | 兼容 Express 的 Node.js 认证中间件，通过数百种「策略」支持用户名密码、OAuth 等登录方式。 |
| [getsops/sops](https://github.com/getsops/sops) | 23.3k | #1864 | 社区 | 加密文件编辑器，支持 YAML、JSON、ENV 等格式，配合 KMS、PGP 等管理密钥，便于把机密安全地存入版本库。 |

### 后端即服务

开箱即用的后端服务（认证、数据库、存储、实时），Supabase、Appwrite 一类 · 4 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [supabase/supabase](https://github.com/supabase/supabase) | 110.9k | #106 | 官方 · Supabase | 以 Postgres 为核心的开源后端即服务，提供托管数据库、认证、自动生成的 REST / GraphQL API、实时订阅、存储和边缘函数，定位为开源版 Firebase。 |
| [pocketbase/pocketbase](https://github.com/pocketbase/pocketbase) | 61.2k | #362 | 社区 | 用 Go 写的单文件开源后端：内嵌 SQLite、实时订阅、用户与文件管理、管理后台和 REST 风格 API，适合小型应用和原型。 |
| [appwrite/appwrite](https://github.com/appwrite/appwrite) | 57.5k | #402 | 官方 · Appwrite | 开源后端即服务，提供认证、数据库、存储、云函数、消息、实时和托管，可自托管，覆盖 Web、移动与服务端 SDK。 |
| [clockworklabs/SpacetimeDB](https://github.com/clockworklabs/SpacetimeDB) | 25.2k | #1648 | 官方 · Clockwork Labs | 把数据库与服务端逻辑合一的后端平台，应用逻辑以模块形式运行在数据库内，客户端直接订阅数据，并提供实时同步。 |

## 数据与中间件

应用背后的数据库、ORM、缓存、搜索、消息、数据处理与分析

### 数据库引擎

关系型、文档型、时序、分析型（OLAP）、嵌入式与键值存储引擎 · 18 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [ClickHouse/ClickHouse](https://github.com/ClickHouse/ClickHouse) | 50.2k | #496 | 官方 · ClickHouse | 列式存储的实时分析型数据库，面向海量数据的聚合查询，查询速度极快，常用于日志和事件分析。 |
| [duckdb/duckdb](https://github.com/duckdb/duckdb) | 41.8k | #676 | 社区 | 进程内的分析型 SQL 数据库，无需服务端，可直接查询 Parquet、CSV 等文件，SQL 方言丰富。 |
| [pingcap/tidb](https://github.com/pingcap/tidb) | 40.6k | #711 | 官方 · PingCAP | 开源云原生分布式 SQL 数据库，兼容 MySQL 协议，支持事务、实时分析（HTAP）与水平扩展。 |
| [google/leveldb](https://github.com/google/leveldb) | 39.5k | #758 | 官方 · Google | Google 的快速键值存储库，提供按键有序的字符串映射，作为嵌入式存储引擎被多个数据库借用，目前仅有限维护。 |
| [surrealdb/surrealdb](https://github.com/surrealdb/surrealdb) | 33.1k | #1040 | 官方 · SurrealDB | 可扩展的分布式文档图数据库，面向实时 Web 应用，用 Rust 编写，提供自有查询语言 SurrealQL，并内置权限与实时订阅。 |
| [cockroachdb/cockroach](https://github.com/cockroachdb/cockroach) | 32.5k | #1067 | 官方 · Cockroach Labs | 云原生分布式 SQL 数据库，兼容 PostgreSQL 协议，强一致、高可用，支持水平扩展与数据放置控制。 |
| [facebook/rocksdb](https://github.com/facebook/rocksdb) | 32.2k | #1088 | 官方 · Meta | Meta 开发的可嵌入持久化键值存储库，针对闪存和内存优化，是众多数据库和流处理系统的存储引擎。 |
| [influxdata/influxdb](https://github.com/influxdata/influxdb) | 31.8k | #1114 | 官方 · InfluxData | 面向指标、事件与实时分析的开源时序数据库，本版本为 InfluxDB 3，基于 Rust 和 Apache Arrow。 |
| [mongodb/mongo](https://github.com/mongodb/mongo) | 28.6k | #1347 | 官方 · MongoDB | MongoDB 数据库源码，面向文档的 NoSQL 数据库，含 mongod 服务、mongos 分片路由等组件。 |
| [rethinkdb/rethinkdb](https://github.com/rethinkdb/rethinkdb) | 27k | #1482 | 社区 | 面向实时 Web 的开源数据库，支持变更推送（changefeeds），查询结果变化时主动通知应用。 |
| [taosdata/TDengine](https://github.com/taosdata/TDengine) | 25.1k | #1654 | 官方 · TDengine | 高性能可扩展的时序数据库，面向工业物联网场景，内置缓存、流计算和数据订阅。 |
| [dolthub/dolt](https://github.com/dolthub/dolt) | 24.5k | #1716 | 官方 · DoltHub | 可以像 Git 一样分叉、克隆、分支、合并、推送和拉取的 SQL 数据库，兼容 MySQL，为数据提供版本控制。 |
| [tursodatabase/turso](https://github.com/tursodatabase/turso) | 24.5k | #1722 | 官方 · Turso | 用 Rust 重写的 SQLite 兼容进程内 SQL 数据库，并提供实验性的 Postgres 前端。 |
| [timescale/timescaledb](https://github.com/timescale/timescaledb) | 23.6k | #1818 | 官方 · Timescale | 以 Postgres 扩展形式提供的时序数据库，为时间序列与事件数据提供高性能实时分析，保留完整 SQL 能力。 |
| [pubkey/rxdb](https://github.com/pubkey/rxdb) | 23.4k | #1843 | 社区 | 本地优先的响应式 JavaScript 数据库，可在各种 JS 运行时使用，并与现有后端复制同步，无厂商锁定。 |
| [neondatabase/neon](https://github.com/neondatabase/neon) | 23.2k | #1874 | 官方 · Neon | 开源的 Serverless Postgres 平台，存算分离，支持自动扩缩容、类似代码分支的数据库分支和闲置缩零。 |
| [typicode/lowdb](https://github.com/typicode/lowdb) | 22.6k | #1938 | 社区 | 简单快速的本地 JSON 数据库，类型安全，会用 JavaScript 就会用，适合小项目与原型。 |
| [postgres/postgres](https://github.com/postgres/postgres) | 22.2k | #1989 | 社区 | PostgreSQL 官方 Git 仓库镜像，功能强大的开源对象关系型数据库，以可靠性、扩展性和 SQL 合规著称。 |

### ORM 与数据库工具

ORM / 查询构建器、数据库客户端与建模工具 · 13 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [dbeaver/dbeaver](https://github.com/dbeaver/dbeaver) | 51.9k | #471 | 官方 · DBeaver | 跨平台通用数据库客户端，支持数十种关系型与 NoSQL 数据库，带 SQL 编辑器、数据编辑、ER 图与导入导出功能。 |
| [prisma/orm](https://github.com/prisma/orm) | 47.7k | #549 | 官方 · Prisma | 面向 Node.js 与 TypeScript 的新一代 ORM，用声明式 schema 生成类型安全的查询客户端，支持 PostgreSQL、MySQL、SQLite、MongoDB 等。 |
| [go-gorm/gorm](https://github.com/go-gorm/gorm) | 40k | #732 | 社区 | Go 语言的全功能 ORM，支持关联、钩子、事务、预加载、迁移和多种数据库，接口对开发者友好。 |
| [drawdb-io/drawdb](https://github.com/drawdb-io/drawdb) | 39.8k | #741 | 社区 | 浏览器中的数据库实体关系图编辑器，可视化设计表结构并导出 SQL，也支持从 SQL 生成图。 |
| [typeorm/typeorm](https://github.com/typeorm/typeorm) | 36.7k | #868 | 社区 | 面向 TypeScript 和 JavaScript 的 ORM，支持 Active Record 与 Data Mapper 模式，覆盖 PostgreSQL、MySQL、SQLite 等多种数据库，也能在浏览器与移动端运行。 |
| [drizzle-team/drizzle-orm](https://github.com/drizzle-team/drizzle-orm) | 35.9k | #900 | 官方 · Drizzle Team | 轻量的 TypeScript ORM，用类 SQL 的类型安全查询构建器和迁移工具，主打无运行时开销，支持多种数据库和边缘运行时。 |
| [qishibo/AnotherRedisDesktopManager](https://github.com/qishibo/AnotherRedisDesktopManager) | 34.8k | #942 | 社区 | Redis 桌面图形客户端，跨平台，加载海量 key 时依然稳定，支持集群与多种数据类型查看。 |
| [sequelize/sequelize](https://github.com/sequelize/sequelize) | 30.4k | #1195 | 社区 | Node.js 与 TypeScript 的功能丰富的 ORM，基于 Promise，支持 PostgreSQL、MySQL、SQLite、SQL Server 等多种数据库，含迁移与关联。 |
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 27.5k | #1442 | 官方 · Automattic | Node.js 的 MongoDB 对象建模库，提供 schema、校验、中间件和查询构建，是 MongoDB 生态最常用的 ODM。 |
| [sqlitebrowser/sqlitebrowser](https://github.com/sqlitebrowser/sqlitebrowser) | 24.6k | #1706 | 社区 | SQLite 数据库可视化浏览与编辑工具（DB Browser for SQLite），可创建表、编辑数据、执行 SQL。 |
| [beekeeper-studio/beekeeper-studio](https://github.com/beekeeper-studio/beekeeper-studio) | 23.7k | #1810 | 官方 · Beekeeper Studio | 现代易用的 SQL 客户端，支持 MySQL、Postgres、SQLite、SQL Server 等，跨平台。 |
| [chartdb/chartdb](https://github.com/chartdb/chartdb) | 23k | #1891 | 社区 | 数据库关系图编辑器，用一条查询即可生成图表，无需安装或提供数据库密码，用于可视化和设计数据库。 |
| [t8y2/dbx](https://github.com/t8y2/dbx) | 22.9k | #1909 | 社区 | 轻量级跨平台数据库客户端，约 25 MB，支持 MySQL、PostgreSQL、SQLite、Redis、MongoDB、DuckDB、SQL Server 等 100 多种数据库，提供桌面端、Docker 与命令行版本，并内置 AI 助手和 MCP Server。 |

### 缓存、搜索与对象存储

缓存与内存数据库、搜索引擎和对象存储（Redis、Elasticsearch、MinIO、Meilisearch 一类） · 9 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [elastic/elasticsearch](https://github.com/elastic/elasticsearch) | 78.2k | #218 | 官方 · Elastic | 分布式搜索与分析引擎，基于 Lucene，提供 RESTful 接口、全文检索、聚合分析和向量检索，是 Elastic Stack 的核心。 |
| [redis/redis](https://github.com/redis/redis) | 76.6k | #231 | 官方 · Redis | 内存数据结构服务器，可作缓存、数据库和消息代理，支持字符串、哈希、列表、集合、流等数据类型，并提供文档与向量查询能力。 |
| [minio/minio](https://github.com/minio/minio) 🗄️已归档 | 61.3k | #358 | 官方 · MinIO | 高性能、兼容 S3 的对象存储，可自托管；仓库已声明不再维护，官方推荐改用其商业产品 AIStor。 |
| [meilisearch/meilisearch](https://github.com/meilisearch/meilisearch) | 59.4k | #382 | 官方 · Meilisearch | 用 Rust 写的高速搜索引擎，开箱即用地支持容错拼写、过滤、分面和混合（关键词加向量）检索，适合给网站和应用加搜索。 |
| [seaweedfs/seaweedfs](https://github.com/seaweedfs/seaweedfs) | 35.1k | #930 | 社区 | 分布式存储系统，可存储数十亿文件并快速读取，提供 S3 兼容对象存储、文件系统等接口，易于水平扩展。 |
| [rustfs/rustfs](https://github.com/rustfs/rustfs) | 34.2k | #974 | 社区 | 用 Rust 写的高性能分布式对象存储，兼容 S3，支持与 MinIO、Ceph 等 S3 兼容平台迁移和并存。 |
| [dragonflydb/dragonfly](https://github.com/dragonflydb/dragonfly) | 31.7k | #1118 | 官方 · DragonflyDB | 现代化的 Redis 与 Memcached 兼容替代品，多线程架构，单机吞吐更高、内存效率更好。 |
| [valkey-io/valkey](https://github.com/valkey-io/valkey) | 27.3k | #1451 | 社区 | Redis 改用新许可证前分叉出的开源键值数据库，由 Linux 基金会托管，适用于缓存和实时负载，兼容 Redis 协议。 |
| [typesense/typesense](https://github.com/typesense/typesense) | 26.6k | #1512 | 官方 · Typesense | 开源的快速容错搜索引擎，内存中运行，可替代 Algolia，也比 Elasticsearch 更易用，支持向量与语义检索。 |

### 消息与任务队列

消息队列、事件流、后台任务队列与通知基础设施（Kafka、RocketMQ、Celery 一类） · 6 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [novuhq/novu](https://github.com/novuhq/novu) | 40.1k | #726 | 官方 · Novu | 开源的通知基础设施，一个 API 统一管理应用内、邮件、短信、推送等多渠道通知，附带收件箱组件。 |
| [binwiederhier/ntfy](https://github.com/binwiederhier/ntfy) | 34.5k | #951 | 社区 | 基于 HTTP 的简单发布订阅通知服务，可通过 PUT / POST 从脚本向手机或桌面推送通知，无需注册，也可自行部署。 |
| [apache/kafka](https://github.com/apache/kafka) | 33.9k | #993 | 社区 | 分布式事件流平台，用于高吞吐的数据管道、流分析和数据集成，广泛用作消息队列与事件总线。 |
| [celery/celery](https://github.com/celery/celery) | 28.9k | #1326 | 社区 | Python 分布式任务队列，通过消息代理异步执行任务，支持定时任务与结果存储，常与 Django、Flask 搭配。 |
| [nsqio/nsq](https://github.com/nsqio/nsq) | 25.8k | #1594 | 社区 | 实时分布式消息平台，用 Go 编写，去中心化、无单点故障，适合大规模消息投递与处理。 |
| [apache/rocketmq](https://github.com/apache/rocketmq) | 22.6k | #1932 | 社区 | 云原生消息与流处理平台，让事件驱动应用易于构建，具备低延迟、高吞吐和事务消息能力，在国内电商场景广泛使用。 |

### 数据处理与工作流编排

流 / 批处理、ETL、数据同步、DataFrame 引擎、工作流与任务编排引擎 · 10 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [apache/airflow](https://github.com/apache/airflow) | 47k | #562 | 社区 | 以代码编写、调度和监控工作流的平台，用 Python 定义 DAG，是数据工程中最常用的编排工具之一。 |
| [apache/spark](https://github.com/apache/spark) | 44.1k | #624 | 社区 | 面向大规模数据处理的统一分析引擎，提供 Scala、Java、Python 等 API，支持批处理、流处理、SQL 与机器学习。 |
| [pola-rs/polars](https://github.com/pola-rs/polars) | 39.9k | #737 | 官方 · Polars | 用 Rust 编写的 DataFrame 分析查询引擎，提供惰性与即时执行、查询优化、向量化多线程执行与超内存流式处理，有 Python、Rust、Node.js 与 R 接口。 |
| [conductor-oss/conductor](https://github.com/conductor-oss/conductor) | 32.2k | #1079 | 社区 | 事件驱动的工作流引擎，为应用和自动化流程提供持久、高可靠的执行，源自 Netflix Conductor。 |
| [alibaba/canal](https://github.com/alibaba/canal) | 29.7k | #1246 | 官方 · Alibaba | 基于 MySQL binlog 的增量订阅与消费组件，伪装成从库解析日志，用于数据同步、缓存更新和数据分发。 |
| [kestra-io/kestra](https://github.com/kestra-io/kestra) | 28.5k | #1358 | 官方 · Kestra | 事件驱动的编排与调度平台，用声明式 YAML 定义数据、基础设施和业务工作流，带有可视化界面。 |
| [apache/flink](https://github.com/apache/flink) | 26.4k | #1531 | 社区 | 开源流处理框架，同时支持批处理，提供低延迟、有状态的数据流计算和精确一次语义。 |
| [PrefectHQ/prefect](https://github.com/PrefectHQ/prefect) | 24k | #1774 | 官方 · Prefect | Python 工作流编排框架，用普通函数加装饰器构建可重试、可观测的数据管道，提供调度与部署。 |
| [temporalio/temporal](https://github.com/temporalio/temporal) | 23.4k | #1846 | 官方 · Temporal | 持久化执行（durable execution）平台，把长流程写成代码并保证可靠执行，自动处理重试、状态与故障恢复。 |
| [airbytehq/airbyte](https://github.com/airbytehq/airbyte) | 22.2k | 2000+ | 官方 · Airbyte | 开源数据搬运平台，用大量连接器把 API、数据库和文件同步到数据仓库或数据湖（ELT），可自托管或使用云服务。 |

### 数据分析、BI 与产品分析

可自托管的 BI 与数据分析平台，以及网站与产品分析工具（Superset、Metabase、PostHog、Plausible 一类） · 8 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [apache/superset](https://github.com/apache/superset) | 75k | #242 | 社区 | Apache 基金会的企业级商业智能 Web 应用，支持连接多种数据库、探索数据、构建图表与仪表盘，并提供 REST API 与扩展框架。 |
| [metabase/metabase](https://github.com/metabase/metabase) | 49.5k | #514 | 官方 · Metabase | 开源商业智能与嵌入式分析工具，让团队成员无需写代码即可提问、可视化数据并构建仪表盘，也支持 SQL 与自托管部署。 |
| [PostHog/posthog](https://github.com/PostHog/posthog) | 40k | #730 | 官方 · PostHog | 开源产品分析平台，集事件分析、会话回放、功能开关、A/B 实验和错误追踪于一体，可自托管。 |
| [umami-software/umami](https://github.com/umami-software/umami) | 39.1k | #764 | 官方 · Umami | 注重隐私的网站分析平台，无需 Cookie，统计流量、活动、行为与转化，可自托管，作为 Google Analytics 的替代品。 |
| [plausible/analytics](https://github.com/plausible/analytics) | 29.3k | #1296 | 官方 · Plausible | 轻量、注重隐私的网站分析工具，无 Cookie，可自托管或使用云服务，是 Google Analytics 的替代。 |
| [getredash/redash](https://github.com/getredash/redash) | 28.8k | #1332 | 官方 · Redash | 面向团队的数据查询与可视化平台，可连接多种数据源，用 SQL 在浏览器中查询、制作图表与仪表盘并分享。 |
| [dataease/dataease](https://github.com/dataease/dataease) | 24.6k | #1713 | 官方 · DataEase | 开源 BI 工具，通过拖拽制作图表与仪表盘，支持 OLTP、OLAP 数据库、数据仓库、文件与 API 等多种数据源，并支持嵌入与分享。 |
| [marimo-team/marimo](https://github.com/marimo-team/marimo) | 23k | #1896 | 官方 · marimo | 响应式 Python 笔记本：运行单元格或操作界面元素后自动运行相关单元格，笔记本以纯 Python 存储，可作为脚本执行或部署为应用，并支持 SQL 与 Git 版本管理。 |

## 通用库与 SDK

按语言生态归类的通用工具库和客户端库

### JS / TS 通用库

日期、校验、数据处理、文档与图片处理、HTTP 与响应式等 JavaScript / TypeScript 库 · 36 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [lodash/lodash](https://github.com/lodash/lodash) | 61.3k | #359 | 社区 | JavaScript 工具函数库，提供数组、对象、字符串、集合等的常用操作，模块化设计，是使用最广的 npm 包之一。 |
| [chenglou/pretext](https://github.com/chenglou/pretext) | 50.7k | #489 | 社区 | 纯 JavaScript / TypeScript 的多行文本测量与排版库，不依赖 DOM 测量以避免触发布局回流，支持多语言并可渲染到 DOM、Canvas 与 SVG。 |
| [iamkun/dayjs](https://github.com/iamkun/dayjs) | 48.7k | #529 | 社区 | 仅 2KB 的不可变日期时间库，API 与 Moment.js 基本兼容，可通过插件扩展。 |
| [moment/moment](https://github.com/moment/moment) | 47.9k | #541 | 社区 | 经典 JavaScript 日期库，用于解析、校验、操作和格式化日期，目前处于维护模式，官方建议新项目考虑其他库。 |
| [colinhacks/zod](https://github.com/colinhacks/zod) | 44k | #625 | 社区 | TypeScript 优先的 schema 校验库，定义一次即可同时得到运行时校验和静态类型推断，常用于表单与 API 参数校验。 |
| [markedjs/marked](https://github.com/markedjs/marked) | 37.2k | #844 | 社区 | 为速度设计的 Markdown 解析与编译器，可在浏览器和 Node.js 中把 Markdown 转成 HTML，支持扩展。 |
| [date-fns/date-fns](https://github.com/date-fns/date-fns) | 36.6k | #869 | 社区 | 模块化的 JavaScript 日期工具库，提供数百个纯函数，支持 tree-shaking，v4 起原生支持时区。 |
| [SheetJS/sheetjs](https://github.com/SheetJS/sheetjs) | 36.4k | #880 | 官方 · SheetJS | JavaScript 电子表格读写工具包，可在浏览器与 Node.js 中解析和生成 Excel、CSV 等格式，社区版在 Apache 2.0 下开源；代码已迁至新的官方仓库。 |
| [zenorocha/clipboard.js](https://github.com/zenorocha/clipboard.js) | 34.1k | #978 | 社区 | 仅 3KB 的现代复制到剪贴板库，无需 Flash，用简单的 HTML 属性或 API 即可使用。 |
| [immutable-js/immutable-js](https://github.com/immutable-js/immutable-js) | 33k | #1043 | 社区 | JavaScript 的不可变持久化数据结构库，提供 List、Map、Set 等集合，通过结构共享提升效率。 |
| [lovell/sharp](https://github.com/lovell/sharp) | 32.7k | #1062 | 社区 | 基于 libvips 的高性能 Node.js 图片处理模块，快速缩放和转换 JPEG、PNG、WebP、AVIF 等格式。 |
| [niklasvh/html2canvas](https://github.com/niklasvh/html2canvas) | 31.9k | #1103 | 社区 | 在浏览器里把网页元素渲染成 Canvas 截图的库，基于 DOM 和 CSS 信息重建而非真实截屏。 |
| [ReactiveX/rxjs](https://github.com/ReactiveX/rxjs) | 31.7k | #1124 | 社区 | JavaScript 的响应式编程库，用 Observable 组合异步和基于事件的程序，是 Angular 的核心依赖。 |
| [webtorrent/webtorrent](https://github.com/webtorrent/webtorrent) | 31.4k | #1141 | 社区 | 用纯 JavaScript 编写的流式 BitTorrent 客户端，同一份代码可运行在 Node.js 与浏览器中，浏览器里通过 WebRTC 数据通道实现点对点传输。 |
| [parallax/jsPDF](https://github.com/parallax/jsPDF) | 31.3k | #1146 | 社区 | 在客户端用 JavaScript 生成 PDF 的库，可直接在浏览器中创建和下载文档。 |
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 30.5k | #1187 | 社区 | 快速灵活的 HTML / XML 解析与操作库，在服务端提供类 jQuery 的 API，常用于网页抓取。 |
| [immerjs/immer](https://github.com/immerjs/immer) | 29k | #1320 | 社区 | 通过「直接修改草稿」来生成下一个不可变状态的库，简化 Redux 等场景下的不可变更新。 |
| [fingerprintjs/fingerprintjs](https://github.com/fingerprintjs/fingerprintjs) | 28.5k | #1359 | 官方 · Fingerprint | 开源的客户端浏览器指纹库，通过读取浏览器属性计算出哈希访问者标识，在无痕模式和清除浏览器数据后依然保持不变。 |
| [caolan/async](https://github.com/caolan/async) | 28.1k | #1397 | 社区 | 适用于 Node.js 和浏览器的异步工具库，提供 map、series、parallel、queue 等处理异步流程的函数。 |
| [jashkenas/underscore](https://github.com/jashkenas/underscore) | 27.3k | #1452 | 社区 | 经典 JavaScript 工具函数库，提供函数式辅助方法，是 Lodash 的前身。 |
| [ai/nanoid](https://github.com/ai/nanoid) | 27k | #1485 | 社区 | 仅 118 字节的安全、URL 友好的唯一 ID 生成器，可替代 UUID，支持多种语言实现。 |
| [discordjs/discord.js](https://github.com/discordjs/discord.js) | 26.8k | #1500 | 社区 | 用于与 Discord API 交互的 Node.js 库，仓库包含多个独立发布的包，如核心库、创建机器人的脚手架 CLI 与消息代理等。 |
| [apify/crawlee](https://github.com/apify/crawlee) | 25.9k | #1573 | 官方 · Apify | 面向 Node.js 的网页抓取与浏览器自动化库，用 JavaScript / TypeScript 构建可靠爬虫，可配合 Puppeteer、Playwright、Cheerio 与 JSDOM 使用，支持代理轮换与文件下载。 |
| [JakeChampion/fetch](https://github.com/JakeChampion/fetch) | 25.8k | #1585 | 社区 | window.fetch 的 JavaScript polyfill，让旧浏览器也能使用基于 Promise 的请求接口。 |
| [localForage/localForage](https://github.com/localForage/localForage) | 25.8k | #1588 | 社区 | 改进的浏览器离线存储库，用简单的异步 API 封装 IndexedDB、WebSQL 和 localStorage。 |
| [Modernizr/Modernizr](https://github.com/Modernizr/Modernizr) | 25.7k | #1601 | 社区 | 检测用户浏览器对 HTML5 与 CSS3 特性支持情况的 JavaScript 库，用于渐进增强和特性降级。 |
| [zloirock/core-js](https://github.com/zloirock/core-js) | 25.5k | #1622 | 社区 | JavaScript 标准库的 polyfill 集合，覆盖 ECMAScript 新特性和提案，Babel 等工具依赖它做按需填充。 |
| [request/request](https://github.com/request/request) | 25.5k | #1625 | 社区 | 曾经最流行的 Node.js HTTP 请求库，2020 年起已完全弃用，不再更新，新项目应使用 fetch、axios 等替代。 |
| [winstonjs/winston](https://github.com/winstonjs/winston) | 24.5k | #1718 | 社区 | Node.js 上功能全面的日志库，支持多种传输目标（文件、控制台、HTTP 等）与日志级别。 |
| [ramda/ramda](https://github.com/ramda/ramda) | 24k | #1768 | 社区 | 面向 JavaScript 程序员的实用函数式库，函数自动柯里化、不可变、强调组合。 |
| [validatorjs/validator.js](https://github.com/validatorjs/validator.js) | 23.7k | #1804 | 社区 | 字符串校验与清理库，提供邮箱、URL、IP、信用卡等常用格式的校验函数。 |
| [jquense/yup](https://github.com/jquense/yup) | 23.7k | #1814 | 社区 | 简单的对象 schema 校验库，用链式 API 描述并校验数据，常与 Formik 搭配做表单验证。 |
| [wechaty/wechaty](https://github.com/wechaty/wechaty) | 23.3k | #1851 | 社区 | 面向聊天机器人开发者的对话式 RPA SDK，为 WhatsApp、微信等多个消息平台提供统一接口，机器人代码只需写一次即可跨平台运行。 |
| [yjs/yjs](https://github.com/yjs/yjs) | 22.9k | #1908 | 社区 | 基于 CRDT 的共享数据类型库，用于构建实时协作软件，支持离线编辑与多种编辑器绑定。 |
| [wwebjs/whatsapp-web.js](https://github.com/wwebjs/whatsapp-web.js) | 22.7k | #1927 | 社区 | 通过 WhatsApp Web 浏览器应用连接的 Node.js WhatsApp 客户端库，借助 Puppeteer 调用其内部函数，提供接近网页版全部功能的 API。 |
| [js-cookie/js-cookie](https://github.com/js-cookie/js-cookie) | 22.6k | #1939 | 社区 | 简单轻量的客户端 Cookie 操作 JavaScript API，兼容各类浏览器。 |

### JVM / Android 通用库

Java、Kotlin 与 Android 的工具库、网络库与图片加载库 · 16 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [google/guava](https://github.com/google/guava) | 51.9k | #472 | 官方 · Google | Google 的 Java 核心库，提供集合扩展、不可变集合、缓存、并发、I/O、哈希等常用工具。 |
| [ReactiveX/RxJava](https://github.com/ReactiveX/RxJava) | 48.2k | #536 | 社区 | Java 虚拟机上的 Reactive Extensions 实现，用可观察序列组合异步和事件驱动程序，在 Android 开发中尤其常见。 |
| [lysine-dev/okhttp](https://github.com/lysine-dev/okhttp) | 47.1k | #561 | 社区 | Java、Kotlin 与 Android 上广泛使用的高效 HTTP 客户端，支持连接池、HTTP/2、透明压缩和拦截器。 |
| [lysine-dev/retrofit](https://github.com/lysine-dev/retrofit) | 43.9k | #631 | 社区 | 类型安全的 HTTP 客户端，用注解接口描述 REST API 并生成实现，广泛用于 Android 与 JVM 开发，基于 OkHttp。 |
| [bumptech/glide](https://github.com/bumptech/glide) | 35k | #934 | 社区 | Android 图片加载与缓存库，封装媒体解码、内存与磁盘缓存，重点优化列表滚动的流畅度。 |
| [zxing/zxing](https://github.com/zxing/zxing) | 34.1k | #977 | 社区 | Java 与 Android 的条码扫描与生成库（Zebra Crossing）；项目已进入维护模式，仅接受贡献的补丁。 |
| [alibaba/easyexcel](https://github.com/alibaba/easyexcel) 🗄️已归档 | 33.6k | #1010 | 官方 · Alibaba | 阿里巴巴的 Java Excel 读写工具，逐行流式处理以避免大文件内存溢出；项目已发布维护公告，进入维护模式。 |
| [Blankj/AndroidUtilCode](https://github.com/Blankj/AndroidUtilCode) | 33.6k | #1011 | 社区 | Android 开发常用工具类合集，覆盖 App、设备、网络、文件、图片、加密等，方便一行调用。 |
| [binarywang/WxJava](https://github.com/binarywang/WxJava) | 33.1k | #1038 | 社区 | 微信开发 Java SDK，覆盖微信支付、公众号、小程序、企业微信、视频号、开放平台等后端能力。 |
| [chinabugotech/hutool](https://github.com/chinabugotech/hutool) | 30.3k | #1202 | 社区 | Java 工具类库，封装文件、IO、加密、HTTP、JSON、日期等常用操作，让 Java 写起来更「甜」。 |
| [alibaba/druid](https://github.com/alibaba/druid) | 28.2k | #1396 | 官方 · Alibaba | 阿里巴巴出品的 Java 数据库连接池，内置监控统计、SQL 防火墙和加密，为监控而设计。 |
| [alibaba/fastjson](https://github.com/alibaba/fastjson) 🗄️已归档 | 25.6k | #1614 | 官方 · Alibaba | 阿里巴巴的 Java JSON 库，用于对象与 JSON 之间的转换，官方推荐升级到 2.0 系列以获得更好的速度与安全性；仓库已归档。 |
| [JakeWharton/butterknife](https://github.com/JakeWharton/butterknife) | 25.3k | #1641 | 社区 | Android 视图与回调绑定库，通过注解减少 findViewById 样板代码，已弃用，官方建议改用 View Binding。 |
| [greenrobot/EventBus](https://github.com/greenrobot/EventBus) | 24.7k | #1699 | 社区 | Android 与 Java 的发布 / 订阅事件总线，简化 Activity、Fragment、线程和服务之间的通信。 |
| [redisson/redisson](https://github.com/redisson/redisson) | 24.4k | #1733 | 社区 | Redis / Valkey 的 Java 客户端与实时数据平台，提供分布式锁、集合、队列等五十多种基于 Redis 的 Java 对象。 |
| [google/gson](https://github.com/google/gson) | 24.2k | #1755 | 官方 · Google | Google 的 Java 序列化 / 反序列化库，在 Java 对象与 JSON 之间互相转换，无需注解即可使用。 |

### Python / Go / Swift / PHP 通用库

其他语言生态的 HTTP 客户端、日志、配置与校验库 · 21 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [scrapy/scrapy](https://github.com/scrapy/scrapy) | 64.5k | #321 | 社区 | 快速的高层 Python 网页抓取与爬虫框架，用于从网站提取结构化数据。 |
| [psf/requests](https://github.com/psf/requests) | 54.4k | #437 | 社区 | Python 最常用的 HTTP 库，接口简洁优雅，处理会话、认证、Cookie 与 JSON 等常见需求。 |
| [Alamofire/Alamofire](https://github.com/Alamofire/Alamofire) | 42.4k | #663 | 社区 | Swift 的 HTTP 网络库，封装 URLSession，提供链式请求、响应序列化、认证和重试等功能，iOS 开发中的常用依赖。 |
| [AFNetworking/AFNetworking](https://github.com/AFNetworking/AFNetworking) 🗄️已归档 | 33.4k | #1027 | 社区 | iOS / macOS 经典网络库，基于 NSURLSession，2023 年起已弃用并归档，官方建议迁移到 Alamofire 等方案。 |
| [spf13/viper](https://github.com/spf13/viper) | 30.5k | #1189 | 社区 | Go 应用的配置管理库，支持多种格式（JSON、YAML、TOML 等）、环境变量、命令行参数与远程配置，常与 Cobra 搭配。 |
| [python-telegram-bot/python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot) | 29.5k | #1273 | 社区 | Telegram Bot API 的 Python 封装库，为构建 Telegram 机器人提供 Python 接口。 |
| [pydantic/pydantic](https://github.com/pydantic/pydantic) | 28.9k | #1328 | 官方 · Pydantic | 基于 Python 类型注解的数据校验库，核心用 Rust 实现，是 FastAPI 等众多 Python 框架的基础。 |
| [fzaninotto/Faker](https://github.com/fzaninotto/Faker) 🗄️已归档 | 26.6k | #1510 | 社区 | 生成假数据的 PHP 库，可用于填充数据库、生成 XML 文档、压力测试或匿名化生产数据；仓库已归档。 |
| [littlecodersh/ItChat](https://github.com/littlecodersh/ItChat) | 26.5k | #1526 | 社区 | 开源的微信个人号 Python 接口，三十行左右代码即可实现处理消息的微信机器人，也可用于命令行微信等场景。 |
| [sirupsen/logrus](https://github.com/sirupsen/logrus) | 25.8k | #1595 | 社区 | Go 的结构化日志库，API 与标准库 log 兼容，支持字段、钩子与多种输出格式，目前处于维护模式。 |
| [SDWebImage/SDWebImage](https://github.com/SDWebImage/SDWebImage) | 25.6k | #1606 | 社区 | iOS / macOS 异步图片下载与缓存库，为 UIImageView 提供分类，自动缓存并支持多种格式。 |
| [gocolly/colly](https://github.com/gocolly/colly) | 25.5k | #1621 | 社区 | Go 语言的优雅爬虫与抓取框架，提供简洁的接口来编写各类爬虫，用于数据挖掘、处理与归档，单核可达每秒上千次请求。 |
| [uber-go/zap](https://github.com/uber-go/zap) | 24.7k | #1704 | 官方 · Uber | Uber 开源的极快 Go 结构化分级日志库，几乎零内存分配，适合高性能服务。 |
| [ReactiveX/RxSwift](https://github.com/ReactiveX/RxSwift) | 24.6k | #1708 | 社区 | Swift 的响应式编程库，用 Observable 表达异步和事件流，iOS 开发中常配合 MVVM 使用。 |
| [onevcat/Kingfisher](https://github.com/onevcat/Kingfisher) | 24.4k | #1734 | 社区 | 纯 Swift 编写的图片下载与缓存库，提供内存 / 磁盘缓存、图片处理和 SwiftUI 支持。 |
| [Delgan/loguru](https://github.com/Delgan/loguru) | 24.1k | #1760 | 社区 | 让 Python 日志变得简单的库，开箱即用，一行代码配置输出、轮转、格式和异常捕获。 |
| [jhao104/proxy_pool](https://github.com/jhao104/proxy_pool) | 23.7k | #1805 | 社区 | 面向网络爬虫的 Python 代理 IP 池，自动从免费代理源抓取并校验代理，提供 API 获取可用代理，并支持扩展新的代理来源。 |
| [guzzle/guzzle](https://github.com/guzzle/guzzle) | 23.5k | #1838 | 社区 | 可扩展的 PHP HTTP 客户端，简化发送同步 / 异步请求并集成 Web 服务，遵循 PSR-7。 |
| [SwiftyJSON/SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON) | 22.9k | #1898 | 社区 | 让 Swift 处理 JSON 数据更简单的库，避免层层可选值解包。 |
| [PHPMailer/PHPMailer](https://github.com/PHPMailer/PHPMailer) | 22.3k | #1980 | 社区 | 经典的 PHP 邮件发送库，支持 SMTP、附件、HTML 邮件与多种认证方式。 |
| [redis/go-redis](https://github.com/redis/go-redis) | 22.3k | #1986 | 官方 · Redis | Redis 官方的 Go 语言客户端，支持集群、哨兵、管道与发布订阅。 |

### C / C++ 通用库

C / C++ 生态的通用基础库：JSON、格式化、日志、测试框架、异步 I/O 与包管理（nlohmann/json、fmt、spdlog、GoogleTest、libuv、vcpkg 一类） · 11 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [nlohmann/json](https://github.com/nlohmann/json) | 50.7k | #486 | 社区 | 现代 C++ 的 JSON 库，把 JSON 当作一等数据类型，提供类 STL 的访问、序列化与反序列化、JSON Pointer 与 Patch，并支持 BSON、CBOR 等二进制格式。 |
| [google/googletest](https://github.com/google/googletest) | 39.6k | #750 | 官方 · Google | Google 的 C++ 测试与 Mock 框架（GoogleTest 与 GoogleMock），提供断言、测试夹具、参数化测试与死亡测试。 |
| [nothings/stb](https://github.com/nothings/stb) | 34.7k | #944 | 社区 | stb 系列单头文件公共领域（或 MIT）C/C++ 库，包括图像加载与写入、缩放、字体光栅化和类型安全容器等；README 提醒安全问题的修复可能较慢。 |
| [openssl/openssl](https://github.com/openssl/openssl) | 30.9k | #1170 | 社区 | 通用 TLS 与密码学库，提供 TLS、DTLS 与 QUIC 协议实现和独立可用的密码学库，并包含符合 FIPS 标准的密码模块。 |
| [facebook/folly](https://github.com/facebook/folly) | 30.6k | #1186 | 官方 · Meta | Meta（Facebook）开源的 C++20 组件库，包含大量在 Meta 内部广泛使用的核心组件，也是其他 C++ 开源项目共享代码的基础。 |
| [gabime/spdlog](https://github.com/gabime/spdlog) | 29.6k | #1260 | 社区 | 快速的 C++ 日志库，可作为仅头文件或编译库使用，支持多种输出目标、异步日志与自定义格式，覆盖主流平台。 |
| [facebook/zstd](https://github.com/facebook/zstd) | 28k | #1408 | 官方 · Meta | Zstandard：面向实时场景的快速无损压缩算法，压缩率达到 zlib 水平及以上，格式已在 RFC 8878 中稳定定义，仓库提供 C 参考实现与命令行工具。 |
| [microsoft/vcpkg](https://github.com/microsoft/vcpkg) | 27.5k | #1438 | 官方 · Microsoft | 微软与社区维护的免费开源 C/C++ 包管理器，提供大量开源库，支持 Windows、macOS 与 Linux，并可配合 CMake 与清单文件管理依赖。 |
| [libuv/libuv](https://github.com/libuv/libuv) | 27.2k | #1465 | 社区 | 以异步 I/O 为核心的跨平台支持库，最初为 Node.js 开发，提供事件循环、异步 TCP/UDP、DNS、文件系统操作、进程与线程池等。 |
| [fmtlib/fmt](https://github.com/fmtlib/fmt) | 25.8k | #1586 | 社区 | C++ 格式化库，是 C stdio 与 iostreams 的快速安全替代，实现了 C++20 的 std::format 和 C++23 的 std::print。 |
| [simdjson/simdjson](https://github.com/simdjson/simdjson) | 24.3k | #1743 | 社区 | 利用 SIMD 指令每秒解析数 GB JSON 的 C++ 库，宣称比常用生产级解析器快 4 倍以上，被 Node.js、ClickHouse 等项目使用。 |

## 部署与运维

把应用发布上线、跑起来并保持健康

### 容器与运行时

容器引擎、容器运行时、Compose、镜像工具与容器管理界面（Docker、Podman、Portainer 一类） · 13 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [moby/moby](https://github.com/moby/moby) | 72.1k | #269 | 社区 | Docker 发起的容器化开源项目，提供可组装的容器组件工具集，是 Docker Engine 的上游。 |
| [wagoodman/dive](https://github.com/wagoodman/dive) | 54.6k | #432 | 社区 | 探索 Docker / OCI 镜像各层内容的工具，能查看每层变更并提示浪费的空间，帮助缩小镜像体积。 |
| [jesseduffield/lazydocker](https://github.com/jesseduffield/lazydocker) | 53k | #456 | 社区 | Docker 与 docker-compose 的终端 UI，可在一个界面里查看容器、日志、资源占用并执行常见操作。 |
| [apple/container](https://github.com/apple/container) | 50.4k | #491 | 官方 · Apple | 苹果推出的 macOS 容器工具，用 Swift 编写、针对 Apple 芯片优化，把 Linux 容器作为轻量级虚拟机运行，兼容 OCI 镜像。 |
| [docker/awesome-compose](https://github.com/docker/awesome-compose) | 46.4k | #573 | 官方 · Docker | Docker 官方的 Docker Compose 示例合集，演示如何用 compose 文件组合前端、后端、数据库等服务，可作为起步模板。 |
| [portainer/portainer](https://github.com/portainer/portainer) | 38.6k | #784 | 官方 · Portainer | Docker、Swarm、Podman 和 Kubernetes 的轻量容器管理界面，可视化管理容器、镜像、卷和网络。 |
| [docker/compose](https://github.com/docker/compose) | 38.3k | #798 | 官方 · Docker | 用 YAML 文件定义并运行多容器应用的工具，一条命令启动整套服务，常用于本地开发与小规模部署。 |
| [podman-container-tools/podman](https://github.com/podman-container-tools/podman) | 33k | #1048 | 社区 | 无守护进程的容器与 Pod 管理工具，命令兼容 Docker，可以无 root 权限运行 OCI 容器。 |
| [abiosoft/colima](https://github.com/abiosoft/colima) | 31k | #1162 | 社区 | 在 macOS 和 Linux 上以最少配置运行容器运行时（Docker、containerd）和 Kubernetes，可替代 Docker Desktop。 |
| [containrrr/watchtower](https://github.com/containrrr/watchtower) 🗄️已归档 | 24.6k | #1705 | 社区 | 自动更新 Docker 容器基础镜像的进程，项目已不再维护。 |
| [louislam/dockge](https://github.com/louislam/dockge) | 24.5k | #1720 | 社区 | 自托管的 docker compose 栈管理器，用响应式界面编辑和管理 compose.yaml，和 Uptime Kuma 出自同一作者。 |
| [slimtoolkit/slim](https://github.com/slimtoolkit/slim) | 23.4k | #1842 | 社区 | 容器镜像瘦身工具，不改动镜像内容即可把体积缩小最多约 30 倍，同时提升安全性。 |
| [GoogleContainerTools/distroless](https://github.com/GoogleContainerTools/distroless) | 23.1k | #1880 | 社区 | 只含应用及其运行时依赖、不带操作系统发行版的 Docker 镜像，体积小、攻击面小。 |

### Kubernetes 与集群管理

Kubernetes 及其发行版、本地集群、服务网格、包管理、镜像仓库与集群管理工具（Kubernetes、K3s、Istio、Helm、K9s 一类） · 10 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) | 128.1k | #83 | 社区 | 容器编排系统，负责跨主机的容器化应用部署、扩缩容和运维，是云原生基础设施的事实标准。 |
| [istio/istio](https://github.com/istio/istio) | 38.4k | #795 | 社区 | 服务网格，以透明方式叠加在分布式应用之上，统一提供流量管理、安全通信和可观测性。 |
| [derailed/k9s](https://github.com/derailed/k9s) | 34.7k | #946 | 社区 | Kubernetes 的终端 UI，用键盘在集群中导航、观察和管理资源，比 kubectl 更高效直观。 |
| [k3s-io/k3s](https://github.com/k3s-io/k3s) | 34.1k | #982 | 社区 | 轻量级 Kubernetes 发行版，单个不到 100MB 的二进制，内存占用减半，适用于边缘、IoT 和 CI 场景。 |
| [kubernetes/minikube](https://github.com/kubernetes/minikube) | 32.2k | #1087 | 社区 | 在本地运行单节点 Kubernetes 集群的工具，方便开发和试验，支持多种驱动与插件。 |
| [helm/helm](https://github.com/helm/helm) | 30.3k | #1199 | 社区 | Kubernetes 包管理器，用 Chart 打包预配置的 Kubernetes 资源，方便安装、升级和分享应用。 |
| [goharbor/harbor](https://github.com/goharbor/harbor) | 29.5k | #1274 | 社区 | 可信的云原生镜像仓库，存储、签名并扫描容器镜像与 Helm Chart，提供权限控制与镜像复制。 |
| [rancher/rancher](https://github.com/rancher/rancher) | 25.9k | #1574 | 社区 | 完整的容器管理平台，统一管理多个 Kubernetes 集群，提供集中认证、监控和应用目录。 |
| [cilium/cilium](https://github.com/cilium/cilium) | 25.6k | #1615 | 社区 | 基于 eBPF 的云原生网络、安全与可观测方案，为 Kubernetes 提供高性能网络策略和服务网格能力。 |
| [lensapp/lens](https://github.com/lensapp/lens) | 23.2k | #1866 | 社区 | Kubernetes 桌面管理界面，可图形化连接、查看和操作多个集群与资源。 |

### 基础设施即代码

用代码声明和管理基础设施与环境（Terraform、OpenTofu、Pulumi、Ansible、Vagrant） · 5 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [ansible/ansible](https://github.com/ansible/ansible) | 70.8k | #275 | 社区 | 极简的 IT 自动化平台，通过 YAML 剧本无代理地完成配置管理、应用部署和任务编排。 |
| [hashicorp/terraform](https://github.com/hashicorp/terraform) | 49.8k | #508 | 官方 · HashiCorp | 基础设施即代码工具，用声明式配置文件描述云资源，规划并安全地创建、变更和版本化基础设施，支持多云。 |
| [opentofu/opentofu](https://github.com/opentofu/opentofu) | 30.3k | #1197 | 社区 | Terraform 的开源分支，在 Terraform 改用非开源许可后由社区发起，用声明式配置管理云基础设施，由 Linux 基金会托管。 |
| [hashicorp/vagrant](https://github.com/hashicorp/vagrant) | 27.2k | #1467 | 官方 · HashiCorp | 构建和分发可复现开发环境的工具，通过配置文件管理虚拟机，保证团队环境一致。 |
| [pulumi/pulumi](https://github.com/pulumi/pulumi) | 25.7k | #1596 | 官方 · Pulumi | 用通用编程语言（TypeScript、Python、Go 等）编写的基础设施即代码工具，管理多云资源。 |

### 部署与自托管平台

自托管 PaaS、部署面板、Serverless 框架、进程管理与本地云模拟 · 12 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [localstack/localstack](https://github.com/localstack/localstack) 🗄️已归档 | 65.1k | #316 | 官方 · LocalStack | 在本地模拟完整 AWS 云环境的工具，可离线开发和测试云与 Serverless 应用，减少对真实 AWS 账号的依赖；仓库已归档。 |
| [coollabsio/coolify](https://github.com/coollabsio/coolify) | 62.4k | #344 | 官方 · Coolify | 可自托管的开源 PaaS，替代 Vercel、Heroku、Netlify，用于在自己的服务器上部署静态站、数据库、全栈应用和 280 多个一键服务。 |
| [serverless/serverless](https://github.com/serverless/serverless) | 46.9k | #564 | 官方 · Serverless Inc | Serverless Framework，通过配置文件把应用部署到 AWS Lambda 等托管云服务，自动伸缩、空闲不计费。 |
| [Unitech/pm2](https://github.com/Unitech/pm2) | 43.3k | #646 | 社区 | Node.js / Bun 生产环境进程管理器，内置负载均衡，支持守护进程、零停机重载、日志与监控。 |
| [Dokploy/dokploy](https://github.com/Dokploy/dokploy) | 37.6k | #826 | 官方 · Dokploy | 可自托管的开源 PaaS，替代 Vercel、Netlify 和 Heroku，通过界面部署应用、数据库和 Docker Compose 服务。 |
| [1Panel-dev/1Panel](https://github.com/1Panel-dev/1Panel) | 37.1k | #851 | 社区 | 现代化的开源 Linux 服务器管理面板，通过 Web 界面管理网站、数据库、容器、防火墙和应用商店。 |
| [firecracker-microvm/firecracker](https://github.com/firecracker-microvm/firecracker) | 37.1k | #853 | 社区 | 为无服务器计算设计的安全、快速的微虚拟机（microVM）技术，用轻量虚拟机运行多租户的容器与函数工作负载，兼具硬件虚拟化的隔离与容器的速度。 |
| [backstage/backstage](https://github.com/backstage/backstage) | 34.5k | #953 | 社区 | 构建开发者门户的开放框架，聚合服务目录、模板、文档与插件，统一团队的开发与部署入口。 |
| [dokku/dokku](https://github.com/dokku/dokku) | 32.2k | #1086 | 社区 | 基于 Docker 的迷你 Heroku，最小的自托管 PaaS，用 git push 部署应用并管理生命周期。 |
| [anomalyco/sst](https://github.com/anomalyco/sst) | 26.3k | #1536 | 社区 | 在自己的云基础设施上构建全栈应用的框架，用代码声明 AWS 等资源，并提供本地实时开发体验。 |
| [openfaas/faas](https://github.com/openfaas/faas) | 26.3k | #1546 | 社区 | OpenFaaS，让开发者在 Kubernetes 或 Docker 上简单部署函数即服务（Serverless）的平台。 |
| [floci-io/floci](https://github.com/floci-io/floci) | 26.1k | #1558 | 社区 | 轻量免费的 AWS 本地模拟器，可在没有账号和令牌的情况下本地运行云服务，作为 LocalStack 的替代。 |

### 反向代理、证书与隧道

Web 服务器与反向代理、Web 应用防火墙、HTTPS 证书自动化、内网穿透与本地隧道（Nginx、Caddy、Traefik、Certbot、frp 一类） · 14 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [fatedier/frp](https://github.com/fatedier/frp) | 109.7k | #110 | 社区 | 内网穿透用的高性能反向代理，可把 NAT 或防火墙后的本地服务（TCP、UDP、HTTP、HTTPS）暴露到公网，常用于本地调试和远程访问。 |
| [caddyserver/caddy](https://github.com/caddyserver/caddy) | 76.2k | #236 | 社区 | 默认启用 HTTPS 的可扩展 Web 服务器，自动申请和续期证书，支持 HTTP/1/2/3，用简洁的 Caddyfile 配置反向代理和静态站点。 |
| [traefik/traefik](https://github.com/traefik/traefik) | 65k | #318 | 官方 · Traefik Labs | 云原生 HTTP 反向代理与负载均衡器，能自动发现 Docker、Kubernetes 等后端并动态更新路由，内置 Let's Encrypt 支持。 |
| [acmesh-official/acme.sh](https://github.com/acmesh-official/acme.sh) | 47.8k | #545 | 社区 | 纯 Unix Shell 实现的 ACME 客户端，用来自动申请和续期 Let's Encrypt 等机构的 SSL / TLS 证书，无需额外依赖。 |
| [NginxProxyManager/nginx-proxy-manager](https://github.com/NginxProxyManager/nginx-proxy-manager) | 34.3k | #967 | 社区 | 带图形界面的 Nginx 反向代理管理 Docker 镜像，无需了解 Nginx 配置即可转发站点并自动申请免费 SSL 证书。 |
| [ehang-io/nps](https://github.com/ehang-io/nps) | 34.2k | #972 | 社区 | 轻量高性能的内网穿透代理服务器，支持 TCP、UDP、SOCKS5、HTTP 等协议转发，可用于访问内网网站、调试本地接口、SSH 与远程桌面，带 Web 管理端。 |
| [certbot/certbot](https://github.com/certbot/certbot) | 33.3k | #1034 | 社区 | EFF 出品的 Let's Encrypt 证书申请工具，可自动获取证书并为服务器启用 HTTPS，也支持其他 ACME 机构。 |
| [nginx/nginx](https://github.com/nginx/nginx) | 31.8k | #1113 | 官方 · F5 | NGINX 开源仓库，高性能 Web 服务器、反向代理、负载均衡与内容缓存，全球使用最广泛的 Web 服务器之一。 |
| [digitalocean/nginxconfig.io](https://github.com/digitalocean/nginxconfig.io) | 28.3k | #1379 | 官方 · DigitalOcean | NGINX 配置生成器，通过图形界面选择选项，生成包含 SSL、缓存、安全头等最佳实践的配置文件。 |
| [inconshreveable/ngrok](https://github.com/inconshreveable/ngrok) 🗄️已归档 | 24.4k | #1729 | 社区 | ngrok 1.x 的历史开源代码，早期把本地服务通过隧道暴露到公网的工具，仓库已归档，现由商业产品 ngrok 继续。 |
| [fosrl/pangolin](https://github.com/fosrl/pangolin) | 23k | #1893 | 官方 · Fossorial | 基于 WireGuard 的开源 SASE 平台，把零信任 VPN、零信任反向代理、特权访问管理和身份感知的 AI 网关放在同一套身份与策略模型下。 |
| [TecharoHQ/anubis](https://github.com/TecharoHQ/anubis) | 22.8k | #1917 | 官方 · Techaro | Web AI 防火墙工具，通过挑战机制衡量请求来源，保护上游资源免受爬虫机器人冲击，尽量保持轻量以便小型站点使用。 |
| [chaitin/SafeLine](https://github.com/chaitin/SafeLine) | 22.7k | #1924 | 官方 · Chaitin | 自托管的 Web 应用防火墙与反向代理，通过过滤和监控 HTTP 流量保护 Web 应用免受 SQL 注入、XSS、代码注入等攻击。 |
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 22.5k | #1957 | 社区 | 把本地服务通过公共 URL 暴露到互联网的隧道工具，一行命令即可分享本地开发服务器。 |

### CI/CD 与自动化

持续集成 / 交付、发布自动化、依赖更新，以及带 CI 能力的自托管 Git 代码托管平台 · 10 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [nektos/act](https://github.com/nektos/act) | 72.2k | #268 | 社区 | 在本地运行 GitHub Actions 工作流，用 Docker 模拟 runner，无需每次提交推送就能调试 CI 配置。 |
| [go-gitea/gitea](https://github.com/go-gitea/gitea) | 58.2k | #392 | 社区 | 用 Go 编写的自托管一体化软件开发服务，提供 Git 托管、代码评审、议题与看板、Wiki、包注册表以及可复用 GitHub Actions 的 CI/CD。 |
| [gogs/gogs](https://github.com/gogs/gogs) | 47.8k | #542 | 社区 | 用 Go 编写的轻量自托管 Git 服务，以单个二进制文件跨平台部署，目标是最简单、稳定、可扩展的搭建方式。 |
| [fastlane/fastlane](https://github.com/fastlane/fastlane) | 42.2k | #669 | 社区 | 自动化 iOS 与 Android 应用构建、截图、签名和发布的工具，用 Ruby 编写，用 Fastfile 串联流程。 |
| [harness/harness](https://github.com/harness/harness) | 38.5k | #790 | 官方 · Harness | 一体化开发者平台，集代码托管、CI/CD 流水线、云开发环境和制品库于一身，可自托管。 |
| [jenkinsci/jenkins](https://github.com/jenkinsci/jenkins) | 26.6k | #1513 | 社区 | 老牌开源自动化服务器，用于持续集成与交付，拥有庞大的插件生态，支持流水线即代码。 |
| [gitlabhq/gitlabhq](https://github.com/gitlabhq/gitlabhq) | 24.6k | #1715 | 官方 · GitLab | GitLab 社区版的镜像仓库：集代码托管、CI/CD、Issue、审查于一体的 DevOps 平台，主开发在 GitLab.com 进行。 |
| [argoproj/argo-cd](https://github.com/argoproj/argo-cd) | 24.3k | #1749 | 社区 | 声明式的 Kubernetes GitOps 持续交付工具，以 Git 仓库为唯一真实来源，自动同步集群状态。 |
| [semantic-release/semantic-release](https://github.com/semantic-release/semantic-release) | 24.1k | #1764 | 社区 | 全自动的版本管理与包发布工具，根据提交信息自动决定版本号、生成变更日志并发布到 npm 等。 |
| [renovatebot/renovate](https://github.com/renovatebot/renovate) | 22.6k | #1931 | 社区 | 自动化依赖更新工具（Mend Renovate），检测过期依赖并自动提交更新 PR，支持多平台与多包管理器。 |

### 监控与可观测

指标、日志、链路追踪、错误追踪、应用监控与性能诊断 · 13 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [louislam/uptime-kuma](https://github.com/louislam/uptime-kuma) | 92k | #153 | 社区 | 自托管的服务可用性监控工具，支持 HTTP、TCP、Ping、DNS 等多种检测，带状态页与多渠道告警通知。 |
| [netdata/netdata](https://github.com/netdata/netdata) | 80.8k | #207 | 官方 · Netdata | 实时基础设施监控工具，一行命令安装即可按秒采集主机、容器和应用的指标，自带仪表盘、异常检测与告警。 |
| [grafana/grafana](https://github.com/grafana/grafana) | 77k | #225 | 官方 · Grafana Labs | 开源可观测性与数据可视化平台，可查询 Prometheus、Loki、Elasticsearch、Postgres 等多种数据源，构建仪表盘并设置告警。 |
| [prometheus/prometheus](https://github.com/prometheus/prometheus) | 66.3k | #305 | 社区 | 云原生监控系统与时序数据库，按配置的目标拉取指标，提供 PromQL 查询语言与告警规则，是 CNCF 毕业项目。 |
| [getsentry/sentry](https://github.com/getsentry/sentry) | 44.9k | #606 | 官方 · Sentry | 开发者优先的错误追踪与性能监控平台，收集异常堆栈和性能数据，提供多语言 SDK，可自托管。 |
| [alibaba/arthas](https://github.com/alibaba/arthas) | 37.6k | #827 | 官方 · Alibaba | 阿里巴巴的 Java 诊断工具，无需重启即可在线排查线上问题，查看调用栈、监控方法、反编译与热更新。 |
| [SigNoz/signoz](https://github.com/SigNoz/signoz) | 32.3k | #1078 | 官方 · SigNoz | 基于 OpenTelemetry 的开源可观测平台，在一个工具里提供日志、指标、链路追踪，包括 APM 与告警，作为 Datadog 的替代。 |
| [grafana/loki](https://github.com/grafana/loki) | 29k | #1322 | 官方 · Grafana Labs | 受 Prometheus 启发的日志聚合系统，只索引标签而不索引日志内容，成本低，与 Grafana 深度集成。 |
| [henrygd/beszel](https://github.com/henrygd/beszel) | 25.9k | #1583 | 社区 | 轻量的服务器监控平台，提供历史数据、Docker 容器统计和告警，资源占用低，适合自托管小型环境。 |
| [apache/skywalking](https://github.com/apache/skywalking) | 25k | #1673 | 社区 | 应用性能监控（APM）系统，尤其面向微服务和云原生架构，提供分布式追踪、指标和拓扑分析。 |
| [jaegertracing/jaeger](https://github.com/jaegertracing/jaeger) | 23.3k | #1865 | 社区 | CNCF 的分布式追踪平台，收集和可视化微服务调用链，帮助定位延迟与依赖问题。 |
| [vectordotdev/vector](https://github.com/vectordotdev/vector) | 22.6k | #1928 | 社区 | 高性能可观测数据管道，采集、转换并路由日志与指标，用 Rust 编写，资源占用低。 |
| [openobserve/openobserve](https://github.com/openobserve/openobserve) | 22.2k | #1994 | 官方 · OpenObserve | 开源可观测平台，统一处理日志、指标、链路追踪、前端监控与会话回放，定位为 Datadog 的开源替代，存储成本低。 |

## 学习与教程

路线图、课程、语言教程与底层原理的学习资料

### 路线图与综合课程

开发者路线图、综合课程、编程书单、CS 自学路线、大学课程清单、论文阅读、项目创意与实战项目合集 · 26 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [codecrafters-io/build-your-own-x](https://github.com/codecrafters-io/build-your-own-x) | 550.8k | #1 | 官方 · CodeCrafters | 通过从零重新实现常用技术来学习编程的分步教程合集，按主题收录 3D 渲染器、数据库、Docker、Git、Shell、前端框架、编程语言、操作系统、区块链等数十类「自己动手写」的指南。 |
| [freeCodeCamp/freeCodeCamp](https://github.com/freeCodeCamp/freeCodeCamp) | 456.6k | #4 | 社区 | 非营利组织 freeCodeCamp 的开源代码与课程体系，通过互动练习和项目认证免费教授 Web 开发、数据库、Python 与计算机科学。 |
| [EbookFoundation/free-programming-books](https://github.com/EbookFoundation/free-programming-books) | 398.2k | #5 | 社区 | 免费编程学习资源索引，按语言和主题收录多种语言的免费书籍、课程、交互式教程、播客与速查表，附可搜索网站。 |
| [nilbuild/developer-roadmap](https://github.com/nilbuild/developer-roadmap) | 368.6k | #8 | 社区 | roadmap.sh 的内容仓库：为前端、后端、全栈、DevOps、移动开发等方向提供可交互的学习路线图，以及配套的文章、最佳实践和测验。 |
| [practical-tutorials/project-based-learning](https://github.com/practical-tutorials/project-based-learning) | 285.4k | #13 | 社区 | 按主要编程语言分类的项目式教程合集，带着读者从零构建 Web 应用、游戏、编译器等完整项目，涵盖多种技术栈。 |
| [ossu/computer-science](https://github.com/ossu/computer-science) | 209.6k | #26 | 社区 | 面向自学者的免费计算机科学完整课程体系，用线上课程组成本科级别的课程路径，覆盖编程、数学、系统、理论与应用。 |
| [Chalarangelo/30-seconds-of-code](https://github.com/Chalarangelo/30-seconds-of-code) | 129.3k | #82 | 社区 | 面向 JavaScript、Python、CSS、React、Git 等的短小实用代码片段与文章合集，可按标签和语言检索。 |
| [justjavac/free-programming-books-zh_CN](https://github.com/justjavac/free-programming-books-zh_CN) | 119.2k | #95 | 社区 | 免费编程类中文书籍索引，按语言无关类、操作系统、分布式系统、编译原理、Web 服务器、版本控制、数据库等目录整理。 |
| [papers-we-love/papers-we-love](https://github.com/papers-we-love/papers-we-love) | 110.1k | #108 | 社区 | 围绕阅读与讨论计算机科学学术论文的社区，仓库是社区推荐的优秀论文目录，因版权原因不一定托管论文，但提供链接。 |
| [mtdvio/every-programmer-should-know](https://github.com/mtdvio/every-programmer-should-know) | 100.5k | #127 | 社区 | 每位软件开发者都该了解的（主要是技术性的）资源合集，作者主观推荐，不分先后，涵盖各种技能水平与技术栈。 |
| [florinpop17/app-ideas](https://github.com/florinpop17/app-ideas) | 97.9k | #133 | 社区 | 为开发者提供应用创意的合集，帮助克服「无从下手」的问题，用于提升编码能力、尝试新技术并丰富作品集。 |
| [microsoft/Web-Dev-For-Beginners](https://github.com/microsoft/Web-Dev-For-Beginners) | 96.9k | #138 | 官方 · Microsoft | 微软出品的 12 周 24 课 Web 开发入门课程，用 JavaScript、CSS、HTML 完成实战小项目，附测验和作业。 |
| [Developer-Y/cs-video-courses](https://github.com/Developer-Y/cs-video-courses) | 83.6k | #190 | 社区 | 计算机科学视频课程清单，按算法、系统、编程语言、数据库、网络、软件工程等主题收录大学级别的公开视频课程。 |
| [PKUFlyingPig/cs-self-learning](https://github.com/PKUFlyingPig/cs-self-learning) | 76k | #238 | 社区 | 计算机自学指南：作者按方向整理并点评了国内外名校开源的计算机课程，涵盖编程入门、数学、系统、算法、数据库、Web 开发等，附学习经验。 |
| [prakhar1989/awesome-courses](https://github.com/prakhar1989/awesome-courses) | 71.5k | #273 | 社区 | 免费公开作业、讲义、笔记和考试的大学计算机课程精选清单，按算法、系统、编程语言与编译器、计算机图形学、安全等方向整理。 |
| [karan/Projects](https://github.com/karan/Projects) | 48k | #539 | 社区 | 可用任意编程语言完成的实战项目清单，按类别分文件夹，每个项目都可提交解法，适合通过动手练习巩固编程能力。 |
| [DataTalksClub/data-engineering-zoomcamp](https://github.com/DataTalksClub/data-engineering-zoomcamp) | 45.9k | #583 | 社区 | 免费的 9 周数据工程课程，通过从零搭建端到端数据管道，学习云、Docker、Kafka、Spark、dbt 等。 |
| [DataExpert-io/data-engineer-handbook](https://github.com/DataExpert-io/data-engineer-handbook) | 44.3k | #618 | 社区 | 数据工程学习资源合集，汇总课程、书籍、工具和实战项目的链接。 |
| [bradtraversy/50projects50days](https://github.com/bradtraversy/50projects50days) | 40.6k | #710 | 社区 | 50 多个 HTML / CSS / JavaScript 小项目合集，配套 50 天课程，适合边做边练前端基础。 |
| [freeCodeCamp/devdocs](https://github.com/freeCodeCamp/devdocs) | 39.5k | #755 | 社区 | API 文档浏览器，把多种开发文档整合在统一界面中，支持即时搜索、离线使用和深色主题。 |
| [FreeCodeCampChina/freecodecamp.cn](https://github.com/FreeCodeCampChina/freecodecamp.cn) | 37.8k | #815 | 社区 | freeCodeCamp 中文社区的开源代码与课程，包含浏览器内自学的前端、数据可视化、API 与微服务等全栈 JavaScript 课程体系。 |
| [PKUanonym/REKCARC-TSC-UHT](https://github.com/PKUanonym/REKCARC-TSC-UHT) | 37.7k | #823 | 社区 | 清华大学计算机系课程攻略，由同学们共同整理各门课程的学习资料与经验，并提供在线网页版本。 |
| [qianguyihao/Web](https://github.com/qianguyihao/Web) | 28.7k | #1341 | 社区 | 千古前端图文教程，从零基础到进阶的前端知识库，讲解 HTML、CSS、JavaScript、框架与工程化。 |
| [forthespada/CS-Books](https://github.com/forthespada/CS-Books) | 27.4k | #1449 | 社区 | 超过一千本计算机经典书籍的分享与学习资料，涵盖 C/C++、Java、Python、Go、数据结构与算法、操作系统、数据库、计算机网络、设计模式等方向。 |
| [ForrestKnight/open-source-cs](https://github.com/ForrestKnight/open-source-cs) | 23.8k | #1799 | 社区 | 开源计算机科学学位：用 MIT、斯坦福、普林斯顿等名校的免费课程，组成满足本科计算机专业要求（不含通识课）的学习清单。 |
| [izackwu/TeachYourselfCS-CN](https://github.com/izackwu/TeachYourselfCS-CN) | 22.2k | #2000 | 社区 | TeachYourselfCS 的中文翻译：一份面向自学者的计算机科学学习指南，按主题推荐教材与课程。 |

### 前端、JavaScript 与移动教程

JavaScript、TypeScript、React、CSS、HTML 与 Android / Flutter 的教程、速查表、练习、周刊与知识体系 · 19 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [getify/You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS) | 185k | #42 | 社区 | 深入讲解 JavaScript 语言核心机制（作用域、闭包、原型、类型、异步等）的系列书籍，目前为第二版。 |
| [leonardomso/33-js-concepts](https://github.com/leonardomso/33-js-concepts) | 66.5k | #300 | 社区 | 每个 JavaScript 开发者都应掌握的 33 个核心概念，配文章与学习资料链接，涵盖闭包、原型、事件循环、异步等。 |
| [lydiahallie/javascript-questions](https://github.com/lydiahallie/javascript-questions) | 65.3k | #313 | 社区 | 一组进阶 JavaScript 选择题及详细解析，考察作用域、原型、异步、类型转换等易错点。 |
| [type-challenges/type-challenges](https://github.com/type-challenges/type-challenges) | 48.5k | #530 | 社区 | TypeScript 类型体操题库，带在线评测，通过练习掌握类型系统的进阶用法，从简单到极端难度分级。 |
| [typescript-cheatsheets/react](https://github.com/typescript-cheatsheets/react) | 47.1k | #560 | 社区 | 面向有经验 React 开发者的 TypeScript 速查表，涵盖组件、hooks、事件与常见类型写法。 |
| [Asabeneh/30-Days-Of-JavaScript](https://github.com/Asabeneh/30-Days-Of-JavaScript) | 46.9k | #565 | 社区 | 30 天 JavaScript 学习挑战，按天讲解基础语法到 DOM、异步等主题，配有练习。 |
| [denysdovhan/wtfjs](https://github.com/denysdovhan/wtfjs) | 37.7k | #820 | 社区 | 收集 JavaScript 中有趣又易踩坑的代码示例，逐条解释背后的语言规范与类型转换行为。 |
| [ascoders/weekly](https://github.com/ascoders/weekly) | 31.2k | #1151 | 社区 | 「前端精读」周刊，每周精读一篇前端好文，涵盖前沿技术、源码解读，也涉及部分后端与商业思考。 |
| [mqyqingfeng/Blog](https://github.com/mqyqingfeng/Blog) | 31.1k | #1160 | 社区 | 冴羽的技术博客，系列文章包括 JavaScript 深入、专题、ES6 和 React，中文前端进阶资料。 |
| [AllThingsSmitty/css-protips](https://github.com/AllThingsSmitty/css-protips) | 30.3k | #1200 | 社区 | 提升 CSS 水平的实用技巧合集，每条带简短示例。 |
| [joshbuchea/HEAD](https://github.com/joshbuchea/HEAD) | 30.3k | #1201 | 社区 | 关于 HTML `<head>` 元素的速查指南，涵盖 meta、link、社交分享标签、图标等推荐写法。 |
| [wesbos/JavaScript30](https://github.com/wesbos/JavaScript30) | 29.3k | #1294 | 社区 | 30 天原生 JavaScript 挑战，每天做一个小项目，不用框架和库，练习 DOM 和浏览器 API。 |
| [lukehoban/es6features](https://github.com/lukehoban/es6features) | 29k | #1316 | 社区 | ECMAScript 6 新特性概览，用简短示例介绍箭头函数、类、模板字符串、解构、Promise、模块等。 |
| [codepath/android_guides](https://github.com/codepath/android_guides) | 28.3k | #1372 | 社区 | CodePath 的 Android 开发速查指南，从环境搭建到常见组件、网络和架构的开源教程集合。 |
| [Asabeneh/30-Days-Of-React](https://github.com/Asabeneh/30-Days-Of-React) | 27.5k | #1437 | 社区 | 30 天 React 学习挑战，按天讲解组件、props、状态、hooks 与路由等。 |
| [mbeaudru/modern-js-cheatsheet](https://github.com/mbeaudru/modern-js-cheatsheet) | 25.6k | #1610 | 社区 | 现代 JavaScript 项目中常见知识点的速查表，涵盖箭头函数、解构、Promise、模块等。 |
| [javascript-tutorial/en.javascript.info](https://github.com/javascript-tutorial/en.javascript.info) | 25.5k | #1626 | 社区 | 现代 JavaScript 教程（javascript.info 英文版内容仓库），从基础语法到浏览器 API 系统讲解。 |
| [MostlyAdequate/mostly-adequate-guide](https://github.com/MostlyAdequate/mostly-adequate-guide) | 23.8k | #1791 | 社区 | 以 JavaScript 讲解函数式编程的开源电子书，涵盖纯函数、柯里化、组合、Functor、Monad 等概念。 |
| [alibaba/flutter-go](https://github.com/alibaba/flutter-go) | 23.6k | #1816 | 官方 · Alibaba | 面向 Flutter 开发者的辅助应用，含 140 多个常用组件的演示和中文文档，目前已暂停维护。 |

### 编程语言教程

Python、Go、Rust、C++、Java 等语言的教程、速查表、练习和「陷阱」合集，以及正则表达式等通用语言技能 · 23 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [jackfrued/Python-100-Days](https://github.com/jackfrued/Python-100-Days) | 187k | #38 | 社区 | 《Python - 100天从新手到大师》：从语言基础、Web 开发、爬虫到数据分析的中文 Python 系统教程，按天数循序渐进。 |
| [Asabeneh/30-Days-Of-Python](https://github.com/Asabeneh/30-Days-Of-Python) | 74.9k | #243 | 社区 | 30 天 Python 学习挑战，按天讲解变量、数据结构、函数、模块、异常处理、正则、文件处理与 Web 框架入门等，并附练习。 |
| [rust-lang/rustlings](https://github.com/rust-lang/rustlings) | 64.3k | #324 | 社区 | 通过小练习熟悉 Rust 代码的阅读与编写，可与官方 Rust 书配合使用，在本地逐题修复编译错误。 |
| [ziishaned/learn-regex](https://github.com/ziishaned/learn-regex) | 46.1k | #581 | 社区 | 用易懂的方式学习正则表达式，逐项讲解元字符、量词、分组、断言与标志，并附示例，有多语言翻译。 |
| [astaxie/build-web-application-with-golang](https://github.com/astaxie/build-web-application-with-golang) | 43.9k | #633 | 社区 | 《Go Web 编程》电子书，讲解用 Go 语言构建 Web 应用，涵盖路由、模板、数据库、安全与部署，提供多语言版本。 |
| [Light-City/CPlusPlusThings](https://github.com/Light-City/CPlusPlusThings) | 43.5k | #641 | 社区 | 中文 C++ 学习资料合集，从基础进阶到现代 C++ 新特性、STL 源码、并发编程、设计模式和实战练习，含代码与视频。 |
| [gto76/python-cheatsheet](https://github.com/gto76/python-cheatsheet) | 38.7k | #781 | 社区 | Python 综合速查表，按集合、数据类型、语法规则、内置函数、标准库与第三方库等分章，可下载为文本文件。 |
| [mouredev/Hello-Python](https://github.com/mouredev/Hello-Python) | 37.6k | #825 | 社区 | 面向初学者的西班牙语 Python 课程，含 100 节课、约 44 小时视频、代码与项目，内容从基础到前端、后端、测试等。 |
| [eugenp/tutorials](https://github.com/eugenp/tutorials) | 37.3k | #836 | 社区 | Baeldung 教程配套的示例代码仓库，涵盖 Spring Boot、Java 核心、微服务、测试等大量主题的可运行示例。 |
| [satwikkansal/wtfpython](https://github.com/satwikkansal/wtfpython) | 37.1k | #850 | 社区 | 通过令人意外的代码片段探索并理解 Python，每个示例给出输出、原因解释与相关语言机制。 |
| [geekcomputers/Python](https://github.com/geekcomputers/Python) | 35.4k | #918 | 社区 | 作者收集的 Python 小程序与脚本合集，用来减少重复劳动并作为初学者的教学示例，欢迎他人指点和改进。 |
| [unknwon/the-way-to-go_ZH_CN](https://github.com/unknwon/the-way-to-go_ZH_CN) | 35k | #935 | 社区 | 《The Way to Go》中文译本，名为《Go 入门指南》，系统介绍 Go 语言语法、并发与标准库。 |
| [google/comprehensive-rust](https://github.com/google/comprehensive-rust) | 33.4k | #1025 | 官方 · Google | Google Android 团队使用的多日 Rust 课程，从基础语法、泛型与错误处理讲起，并有 Android、Chromium、裸机和并发专题。 |
| [sunface/rust-course](https://github.com/sunface/rust-course) | 31k | #1167 | 社区 | 《Rust 语言圣经》：面向中文读者的 Rust 教程，从入门语法、所有权、泛型与特征到并发、异步和实战，配套在线练习。 |
| [realpython/python-guide](https://github.com/realpython/python-guide) | 29.8k | #1236 | 社区 | 《Python 搭车指南》，面向实践的 Python 最佳实践手册，涵盖环境搭建、项目结构、代码风格与常用库。 |
| [Pierian-Data/Complete-Python-3-Bootcamp](https://github.com/Pierian-Data/Complete-Python-3-Bootcamp) | 29.8k | #1241 | 社区 | Udemy 上「Complete Python 3 Bootcamp」课程的配套文件，包含课程使用的代码与笔记本。 |
| [zhiwehu/Python-programming-exercises](https://github.com/zhiwehu/Python-programming-exercises) | 29.7k | #1252 | 社区 | 100 多道 Python 编程练习题，用挑战的形式练习语言与常见编程任务。 |
| [wuyouzhuguli/SpringAll](https://github.com/wuyouzhuguli/SpringAll) | 28.9k | #1324 | 社区 | 循序渐进的 Spring 系列教程源码，含 Spring Boot、Shiro、Batch、Cloud、Cloud Alibaba 与 Security OAuth2。 |
| [walter201230/Python](https://github.com/walter201230/Python) | 28k | #1405 | 社区 | 面向零基础的中文 Python 教程，基于 Python 3.10+，标注了新版本特性，并提供互动练习版与纯阅读的文档版两个在线站点。 |
| [changkun/modern-cpp-tutorial](https://github.com/changkun/modern-cpp-tutorial) | 25.9k | #1584 | 社区 | 现代 C++ 教程，按 C++11 到 C++26 逐版本讲解语言可用性、运行时增强、容器、智能指针、并发等新特性。 |
| [norvig/pytudes](https://github.com/norvig/pytudes) | 24.4k | #1731 | 社区 | Peter Norvig 的 Python 练习集，借用音乐练习曲的比喻，用短小而有难度的程序打磨特定的编程技巧。 |
| [quii/learn-go-with-tests](https://github.com/quii/learn-go-with-tests) | 23.9k | #1785 | 社区 | 以测试驱动开发的方式学习 Go 语言，边写测试边讲解语言特性与常见实践。 |
| [EnterpriseQualityCoding/FizzBuzzEnterpriseEdition](https://github.com/EnterpriseQualityCoding/FizzBuzzEnterpriseEdition) | 23.9k | #1787 | 社区 | 以企业级软件的设计原则夸张地实现 FizzBuzz 的讽刺性项目，展示过度设计的架构会是什么样子。 |

### 命令行、Git 与运维实践

命令行、Git、Docker、Kubernetes、DevOps 与云服务的教程、速查表和练习 · 17 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [jlevy/the-art-of-command-line](https://github.com/jlevy/the-art-of-command-line) | 162.5k | #52 | 社区 | 一页纸掌握命令行：整理日常使用、文件与数据处理、系统调试、单行命令和 macOS / Windows 注意事项，有多语言翻译。 |
| [bregman-arie/devops-exercises](https://github.com/bregman-arie/devops-exercises) | 84.7k | #185 | 社区 | 覆盖 Linux、Kubernetes、Docker、Terraform、AWS 等主题的 DevOps / SRE 练习题与面试题库，累计两千多道题。 |
| [tldr-pages/tldr](https://github.com/tldr-pages/tldr) | 63.8k | #326 | 社区 | 社区维护的命令行工具速查手册，为常见命令提供简短的示例式说明，可通过多种客户端在终端中查询。 |
| [tiimgreen/github-cheat-sheet](https://github.com/tiimgreen/github-cheat-sheet) | 59.4k | #384 | 社区 | Git 与 GitHub 的实用功能速查表，收录大量鲜为人知的隐藏功能，有多语言翻译。 |
| [firstcontributions/first-contributions](https://github.com/firstcontributions/first-contributions) | 56.2k | #414 | 社区 | 帮助新手完成第一次开源贡献的分步指南，通过 Fork、克隆、建分支、提交、发起 PR 的完整流程练手，并提供多语言与图形工具版说明。 |
| [kelseyhightower/kubernetes-the-hard-way](https://github.com/kelseyhightower/kubernetes-the-hard-way) | 50.3k | #494 | 社区 | 手把手教程，不借助自动化脚本，从零一步步手工搭建 Kubernetes 集群，帮助理解各组件之间的关系。 |
| [k88hudson/git-flight-rules](https://github.com/k88hudson/git-flight-rules) | 42.6k | #657 | 社区 | Git 出错时的应对手册：以「飞行规则」的形式，按场景一步步列出常见 Git 问题的原因与处理命令。 |
| [chubin/cheat.sh](https://github.com/chubin/cheat.sh) | 41.8k | #678 | 社区 | 统一查询社区速查表仓库的工具，力求简洁、快速、通用，随时随地即时获得答案。 |
| [dylanaraps/pure-bash-bible](https://github.com/dylanaraps/pure-bash-bible) 🗄️已归档 | 41.7k | #681 | 社区 | 用纯 bash 内置功能替代外部进程的方法合集，可去掉脚本中不必要的依赖并让脚本更快；仓库已归档。 |
| [jaywcjlove/linux-command](https://github.com/jaywcjlove/linux-command) | 37k | #856 | 社区 | 收集了 600 多个 Linux 命令的中文速查手册，提供命令详解，并生成可搜索的网站。 |
| [open-guides/og-aws](https://github.com/open-guides/og-aws) | 36.5k | #875 | 社区 | 亚马逊云（AWS）实用指南，按服务整理经验、陷阱和最佳实践，偏重实战而非官方文档。 |
| [pcottle/learnGitBranching](https://github.com/pcottle/learnGitBranching) | 34.1k | #979 | 社区 | 交互式 Git 可视化与学习工具：在浏览器沙盒中输入命令，实时看到提交树变化，并通过分关卡的挑战学习分支操作。 |
| [imthenachoman/How-To-Secure-A-Linux-Server](https://github.com/imthenachoman/How-To-Secure-A-Linux-Server) | 31.7k | #1120 | 社区 | 持续更新的 Linux 服务器加固指南，从选择发行版、安装到安全配置逐步讲解，也解释各项措施背后的原因。 |
| [MichaelCade/90DaysOfDevOps](https://github.com/MichaelCade/90DaysOfDevOps) | 29.8k | #1242 | 社区 | 「边学边分享」形成的 DevOps 学习路线，按天覆盖 Linux、容器、Kubernetes、IaC、CI/CD 等主题。 |
| [yeasy/docker_practice](https://github.com/yeasy/docker_practice) | 26.3k | #1544 | 社区 | 《Docker 从入门到实践》开源电子书，系统讲解容器核心概念、原理与实战。 |
| [mikeroyal/Self-Hosting-Guide](https://github.com/mikeroyal/Self-Hosting-Guide) | 22.9k | #1901 | 社区 | 自托管入门指南，介绍在本地或私有服务器上托管和管理软件应用的工具，涵盖容器、云、WireGuard、自动化、Home Assistant 与网络。 |
| [wsargent/docker-cheat-sheet](https://github.com/wsargent/docker-cheat-sheet) | 22.6k | #1945 | 社区 | Docker 速查表，汇总常用命令、镜像、容器、网络与 Compose 用法。 |

### 操作系统与编译原理

操作系统内核、从零写操作系统、编译器与小型系统实现的源码解读和教程 · 6 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [0xAX/linux-insides](https://github.com/0xAX/linux-insides) | 33.6k | #1012 | 社区 | 讲解 Linux 内核内部机制的在线书籍，涵盖引导过程、初始化、中断、系统调用、内存管理、定时器与同步原语等。 |
| [cfenollosa/os-tutorial](https://github.com/cfenollosa/os-tutorial) | 30.7k | #1177 | 社区 | 从零编写操作系统的分步教程，从引导扇区开始，逐课实现 32 位保护模式、驱动、中断和简易内核；作者提示项目已停止维护。 |
| [aosabook/500lines](https://github.com/aosabook/500lines) | 29.6k | #1266 | 社区 | 《500 Lines or Less》一书的源码：多位作者各用不到 500 行代码实现一个真实项目（如网络爬虫、模板引擎、数据库），并讲解其设计。 |
| [jamiebuilds/the-super-tiny-compiler](https://github.com/jamiebuilds/the-super-tiny-compiler) | 28.6k | #1354 | 社区 | 用极简 JavaScript 实现的小型编译器，配有逐段注释，带读者了解词法分析、解析、转换与代码生成的完整流程。 |
| [dibingfa/flash-linux0.11-talk](https://github.com/dibingfa/flash-linux0.11-talk) | 22.6k | #1930 | 社区 | 以连载文章的形式逐行讲解 Linux 0.11 内核源码，从引导、进入保护模式到内存、进程与文件系统初始化。 |
| [SamyPesse/How-to-Make-a-Computer-Operating-System](https://github.com/SamyPesse/How-to-Make-a-Computer-Operating-System) | 22.4k | #1971 | 社区 | 用 C/C++ 从零开发操作系统的在线书籍，涵盖开发环境、引导、内核、内存与文件系统；作者说明内容仍在重构。 |

### 算法与数据结构

算法与数据结构的多语言实现、刷题题解与攻略、可视化和学习路线 · 24 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [TheAlgorithms/Python](https://github.com/TheAlgorithms/Python) | 225.1k | #22 | 社区 | Python 版算法与数据结构大全，按数学、排序、图、动态规划、机器学习等主题整理，每个实现带说明，适合学习和查阅。 |
| [trekhleb/javascript-algorithms](https://github.com/trekhleb/javascript-algorithms) | 196.8k | #30 | 社区 | JavaScript 实现的算法与数据结构，每个条目配解释和延伸阅读链接，并附常见算法范式的总结。 |
| [labuladong/fucking-algorithm](https://github.com/labuladong/fucking-algorithm) | 136.1k | #75 | 社区 | LeetCode 刷题笔记，讲解解题的套路和原理，而不只是答案，以算法框架著称。 |
| [krahets/hello-algo](https://github.com/krahets/hello-algo) | 130.5k | #80 | 社区 | 《Hello 算法》：动画图解、可一键运行的数据结构与算法入门教程，提供多种语言实现和多语种版本。 |
| [MisterBooo/LeetCodeAnimation](https://github.com/MisterBooo/LeetCodeAnimation) | 76.7k | #230 | 社区 | 用动画演示 LeetCode 题目解题思路的项目，逐步图解，便于理解。 |
| [TheAlgorithms/Java](https://github.com/TheAlgorithms/Java) | 66.3k | #304 | 社区 | Java 版算法与数据结构实现合集，覆盖排序、搜索、图、动态规划等，配有测试和说明。 |
| [youngyangyang04/leetcode-master](https://github.com/youngyangyang04/leetcode-master) | 62.6k | #342 | 社区 | 《代码随想录》：按顺序刷 200 道经典 LeetCode 题目的攻略，附图解、视频讲解和思维导图，支持多语言。 |
| [azl397985856/leetcode](https://github.com/azl397985856/leetcode) | 55.7k | #418 | 社区 | LeetCode 题解与解题思路记录，提供套路总结与专题讲义，中文。 |
| [algorithm-visualizer/algorithm-visualizer](https://github.com/algorithm-visualizer/algorithm-visualizer) | 48.9k | #526 | 社区 | 交互式算法可视化平台，可基于代码逐步展示算法的运行过程。 |
| [doocs/leetcode](https://github.com/doocs/leetcode) | 36.6k | #870 | 社区 | 多种编程语言实现的 LeetCode、《剑指 Offer》和《程序员面试金典》题解，配有网站和讲解。 |
| [geekxh/hello-algorithm](https://github.com/geekxh/hello-algorithm) | 36.1k | #889 | 社区 | 面向初学者的算法训练资料，包括大厂面经、力扣图解和电子书、思维导图合集。 |
| [TheAlgorithms/C-Plus-Plus](https://github.com/TheAlgorithms/C-Plus-Plus) | 34.7k | #945 | 社区 | C++ 版算法实现合集，覆盖数学、机器学习、计算机科学和物理等领域。 |
| [TheAlgorithms/JavaScript](https://github.com/TheAlgorithms/JavaScript) | 34.3k | #968 | 社区 | JavaScript 版算法与数据结构实现，面向初学者并遵循最佳实践，带示例与测试。 |
| [halfrost/LeetCode-Go](https://github.com/halfrost/LeetCode-Go) | 33.8k | #1001 | 社区 | 用 Go 语言实现的 LeetCode 题解，覆盖率 100% 的测试，按题型分类。 |
| [donnemartin/interactive-coding-challenges](https://github.com/donnemartin/interactive-coding-challenges) | 31.9k | #1104 | 社区 | 120 多道交互式 Python 编码面试题（算法与数据结构），附解答、测试和 Anki 记忆卡片。 |
| [liquidslr/leetcode-company-wise-problems](https://github.com/liquidslr/leetcode-company-wise-problems) | 30.8k | #1175 | 社区 | 按公司整理的 LeetCode 高频题清单，每个公司一份 CSV，含题目频率和时间段。 |
| [kodecocodes/swift-algorithm-club](https://github.com/kodecocodes/swift-algorithm-club) | 29.1k | #1309 | 社区 | 用 Swift 实现的算法与数据结构，并配有讲解，来自 raywenderlich 社区。 |
| [OI-wiki/OI-wiki](https://github.com/OI-wiki/OI-wiki) | 26.8k | #1501 | 社区 | 面向信息学竞赛（OI / ICPC）的中文 Wiki，系统讲解数据结构、图论、数论、动态规划等竞赛算法。 |
| [TheAlgorithms/Rust](https://github.com/TheAlgorithms/Rust) | 26.1k | #1561 | 社区 | Rust 版算法与数据结构实现合集。 |
| [tayllan/awesome-algorithms](https://github.com/tayllan/awesome-algorithms) | 25.6k | #1611 | 社区 | 学习和练习算法的网站与资源精选清单。 |
| [keon/algorithms](https://github.com/keon/algorithms) | 25.6k | #1619 | 社区 | Python 的数据结构与算法最小化示例，代码简短易读。 |
| [kunal-kushwaha/DSA-Bootcamp-Java](https://github.com/kunal-kushwaha/DSA-Bootcamp-Java) | 23.9k | #1778 | 社区 | Java 数据结构与算法训练营的代码示例、作业和笔记，配套视频课程。 |
| [wangzheng0822/algo](https://github.com/wangzheng0822/algo) | 23.1k | #1877 | 社区 | 极客时间《数据结构与算法之美》配套的 50 个必知必会数据结构与算法代码实现。 |
| [TheAlgorithms/C](https://github.com/TheAlgorithms/C) | 22.5k | #1958 | 社区 | C 语言版算法与数据结构实现合集，涵盖数学、排序、加密、机器学习等主题。 |

## 面试、规范与清单

面试与系统设计指南、编码规范与最佳实践、精选清单

### 系统设计与面试

系统设计、分布式、编码面试和前后端岗位的面试指南（不含纯算法题库，那类归「算法与数据结构」） · 32 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [donnemartin/system-design-primer](https://github.com/donnemartin/system-design-primer) | 372.6k | #7 | 社区 | 系统设计入门指南：讲解可扩展系统的常见模式（负载均衡、缓存、分库分表、消息队列等），附面试题、示例方案和 Anki 记忆卡片，提供多语言翻译。 |
| [jwasham/coding-interview-university](https://github.com/jwasham/coding-interview-university) | 362.1k | #9 | 社区 | 成为软件工程师的完整计算机科学学习计划，按主题列出数据结构、算法、系统设计等学习资源，面向大厂编码面试。 |
| [CyC2018/CS-Notes](https://github.com/CyC2018/CS-Notes) | 186.4k | #40 | 社区 | 技术面试必备的基础知识笔记，涵盖算法、操作系统、计算机网络、数据库和系统设计等。 |
| [Snailclimb/JavaGuide](https://github.com/Snailclimb/JavaGuide) | 159k | #53 | 社区 | Java 与后端通用面试指南，涵盖计算机基础、数据库、分布式、高并发与系统设计等知识。 |
| [yangshun/tech-interview-handbook](https://github.com/yangshun/tech-interview-handbook) | 143k | #65 | 社区 | 面向忙碌工程师的编码面试准备资料，包括算法学习清单、行为面试、简历和谈薪建议。 |
| [ByteByteGoHq/system-design-101](https://github.com/ByteByteGoHq/system-design-101) | 90.1k | #170 | 社区 | 用图示和简明语言讲解复杂系统的合集，覆盖 API 设计、缓存、数据库、微服务、DevOps 等主题，兼顾系统设计面试准备。 |
| [DopplerHQ/awesome-interview-questions](https://github.com/DopplerHQ/awesome-interview-questions) 🗄️已归档 | 84.7k | #184 | 社区 | 各语言与技术的面试题清单的清单，按编程语言和技术栈分类；仓库已归档。 |
| [doocs/advanced-java](https://github.com/doocs/advanced-java) | 79.1k | #216 | 社区 | 面向 Java 后端工程师的进阶知识与面试题梳理，涵盖高并发、分布式、高可用、微服务和海量数据处理。 |
| [kdn251/interviews](https://github.com/kdn251/interviews) | 65.3k | #315 | 社区 | 求职面试资料合集，涵盖数据结构、算法、系统设计和各类面试题，含在线题目链接。 |
| [h5bp/Front-end-Developer-Interview-Questions](https://github.com/h5bp/Front-end-Developer-Interview-Questions) | 60.9k | #366 | 社区 | 前端面试题清单，按 HTML、CSS、JavaScript 等主题分类，既可用于面试候选人也可用来自测。 |
| [charlax/professional-programming](https://github.com/charlax/professional-programming) | 51.6k | #477 | 社区 | 面向软件工程师的学习资源合集，涵盖架构、可扩展性、数据库、测试、DevOps 与职业发展等主题。 |
| [karanpratapsingh/system-design](https://github.com/karanpratapsingh/system-design) | 46.4k | #575 | 社区 | 大规模系统设计课程，讲解网络、数据库、缓存、消息队列、微服务等概念，并附案例，兼顾系统设计面试。 |
| [sudheerj/reactjs-interview-questions](https://github.com/sudheerj/reactjs-interview-questions) | 44.8k | #608 | 社区 | 五百道 React 面试题及答案，涵盖组件、hooks、路由、Redux 等主题。 |
| [yangshun/front-end-interview-handbook](https://github.com/yangshun/front-end-interview-handbook) | 44k | #629 | 社区 | 前端面试准备手册，涵盖 JavaScript、HTML、CSS、系统设计与算法要点，由 GreatFrontEnd 团队维护。 |
| [alex/what-happens-when](https://github.com/alex/what-happens-when) | 43.3k | #644 | 社区 | 回答「在浏览器输入 google.com 并回车后发生了什么」这道经典面试题，从键盘输入一路讲到页面渲染，涵盖 DNS、TCP、TLS、HTTP。 |
| [ashishps1/awesome-system-design-resources](https://github.com/ashishps1/awesome-system-design-resources) | 41.9k | #671 | 社区 | 免费的系统设计学习资源合集，用于学习系统设计概念和准备面试。 |
| [huihut/interview](https://github.com/huihut/interview) | 38.2k | #799 | 社区 | C/C++ 技术面试基础知识总结，包括语言、库、数据结构、算法、系统、网络和面试经验。 |
| [0voice/interview_internal_reference](https://github.com/0voice/interview_internal_reference) | 37.3k | #840 | 社区 | 国内大厂后端技术面试题与答案汇总，含专家分析，涵盖网络、Redis、存储等主题。 |
| [AobingJava/JavaFamily](https://github.com/AobingJava/JavaFamily) | 37k | #858 | 社区 | Java 面试与学习指南，梳理 Java 程序员需要掌握的核心知识。 |
| [systemdesign42/system-design-academy](https://github.com/systemdesign42/system-design-academy) | 29.2k | #1304 | 社区 | 系统设计学习资料库，用图文讲解常见系统的设计案例和核心概念，按字母顺序整理案例并附订阅通讯。 |
| [viraptor/reverse-interview](https://github.com/viraptor/reverse-interview) | 28.6k | #1351 | 社区 | 技术岗位求职者在面试中可以反问公司的问题清单，既有想多了解的方面，也有需要警惕的信号。 |
| [sudheerj/javascript-interview-questions](https://github.com/sudheerj/javascript-interview-questions) | 27.7k | #1423 | 社区 | 上千道 JavaScript 面试题及答案，涵盖语言基础、异步、ES6+ 与常见陷阱。 |
| [Advanced-Frontend/Daily-Interview-Question](https://github.com/Advanced-Frontend/Daily-Interview-Question) | 27.4k | #1450 | 社区 | 每天一道大厂前端面试题的合集，覆盖 JavaScript、CSS、框架与工程化，附解析。 |
| [ashishps1/awesome-low-level-design](https://github.com/ashishps1/awesome-low-level-design) | 27.1k | #1471 | 社区 | 学习低层设计（LLD）并准备面试的免费资源合集，含设计模式和面向对象设计案例。 |
| [crossoverJie/JCSprout](https://github.com/crossoverJie/JCSprout) | 26.8k | #1498 | 社区 | Java 核心知识梳理，涵盖基础、并发、算法等主题的学习与面试资料。 |
| [qiurunze123/miaosha](https://github.com/qiurunze123/miaosha) | 26.6k | #1516 | 社区 | 秒杀系统的设计与实现，基于 Spring Boot、Redis、消息队列等演示高并发场景下的限流、缓存、异步下单与防刷方案，并附学习笔记。 |
| [haizlin/fe-interview](https://github.com/haizlin/fe-interview) | 26.3k | #1545 | 社区 | 前端面试每日题库，六千多道题目覆盖 HTML、CSS、JavaScript、Vue、React、Node.js、TypeScript、Webpack、小程序等。 |
| [hollischuang/toBeTopJavaer](https://github.com/hollischuang/toBeTopJavaer) | 25.3k | #1643 | 社区 | Java 工程师进阶知识体系与面试题合集，按基础、并发、JVM、框架、数据库、分布式等方向整理，可在线阅读。 |
| [checkcheckzz/system-design-interview](https://github.com/checkcheckzz/system-design-interview) | 23.8k | #1796 | 社区 | 面向 IT 公司的系统设计面试准备资料，汇集常见题目、思路和参考文章。 |
| [Vonng/ddia](https://github.com/Vonng/ddia) | 23.8k | #1798 | 社区 | 《设计数据密集型应用》（DDIA）的中文翻译，涵盖数据系统、分布式、一致性与流处理，第一版和第二版均有。 |
| [doocs/source-code-hunter](https://github.com/doocs/source-code-hunter) | 23.1k | #1878 | 社区 | 互联网常用框架源码解析，剖析 Spring 全家桶、MyBatis、Netty、Dubbo 以及 Redis、Tomcat 等的底层实现。 |
| [liquidslr/system-design-notes](https://github.com/liquidslr/system-design-notes) | 22.4k | #1962 | 社区 | 《System Design Interview: An Insider's Guide》一书的读书笔记，整理常见系统设计题的思路。 |

### 最佳实践与规范

编码规范、设计模式、API 指南、项目结构与工程实践清单 · 22 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [goldbergyoni/nodebestpractices](https://github.com/goldbergyoni/nodebestpractices) | 105.6k | #117 | 社区 | Node.js 最佳实践清单，涵盖项目结构、错误处理、代码风格、测试、生产环境、安全和性能等方面，逐条给出反例和正例。 |
| [ryanmcdermott/clean-code-javascript](https://github.com/ryanmcdermott/clean-code-javascript) | 94.8k | #146 | 社区 | 把《代码整洁之道》的原则改写为 JavaScript 实践，涵盖变量、函数、对象、类、SOLID、测试和错误处理等主题。 |
| [iluwatar/java-design-patterns](https://github.com/iluwatar/java-design-patterns) | 94.8k | #147 | 社区 | 用 Java 实现的设计模式集合，每个模式包含意图、适用场景、类图和示例代码，并覆盖多种企业与并发相关模式。 |
| [thedaviddias/Front-End-Checklist](https://github.com/thedaviddias/Front-End-Checklist) | 74.3k | #250 | 社区 | 现代 Web 开发的前端质量检查清单，涵盖 HTML、CSS、性能、无障碍、SEO 与安全等方面。 |
| [nilbuild/design-patterns-for-humans](https://github.com/nilbuild/design-patterns-for-humans) | 48.9k | #524 | 社区 | 用尽量通俗的语言与现实类比讲解创建型、结构型和行为型设计模式，附 PHP 示例代码。 |
| [isocpp/CppCoreGuidelines](https://github.com/isocpp/CppCoreGuidelines) | 45.3k | #597 | 社区 | 由 Bjarne Stroustrup 等主导的 C++ 核心指南，给出经过验证的编码规则与最佳实践，覆盖接口、资源管理、并发、性能与类型安全。 |
| [faif/python-patterns](https://github.com/faif/python-patterns) | 43k | #649 | 社区 | Python 设计模式与惯用法合集，按创建型、结构型、行为型等分类给出可运行的示例代码，并强调各模式的取舍。 |
| [google/styleguide](https://github.com/google/styleguide) | 39.6k | #749 | 官方 · Google | Google 内部使用并开源的各语言代码风格指南索引，涵盖 C++、Java、Python、Go、Shell、JavaScript 等，并提供 Lint 配置。 |
| [ryanhanwu/How-To-Ask-Questions-The-Smart-Way](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way) | 35.8k | #902 | 社区 | Eric S. Raymond 与 Rick Moen《提问的智慧》的中文译本，讲解如何正确提出技术问题、选择合适的论坛并获得满意的回答。 |
| [OWASP/CheatSheetSeries](https://github.com/OWASP/CheatSheetSeries) | 33.4k | #1029 | 社区 | OWASP 速查表系列：面向开发者、针对具体应用安全主题的简明高价值实践指南，Markdown 源文件同时发布为官方网站。 |
| [alibaba/p3c](https://github.com/alibaba/p3c) | 30.9k | #1171 | 官方 · Alibaba | 阿里巴巴 Java 开发手册及其 PMD 规则实现和 IDE 插件，整合了集团多年的编码规范，覆盖命名、并发、异常、数据库与工程结构。 |
| [elsewhencode/project-guidelines](https://github.com/elsewhencode/project-guidelines) | 29.4k | #1281 | 社区 | JavaScript 项目的最佳实践清单，涵盖 Git、文档、环境、依赖、测试、结构和代码风格。 |
| [tmrts/go-patterns](https://github.com/tmrts/go-patterns) | 28.3k | #1380 | 社区 | Go 语言设计模式、技巧与惯用法的精选合集，按创建型、结构型、行为型、并发等分类给出代码示例。 |
| [kdeldycke/awesome-falsehood](https://github.com/kdeldycke/awesome-falsehood) | 27.7k | #1418 | 社区 | 程序员容易相信的错误假设清单，覆盖邮箱、姓名、时间、地址等常见领域，提醒在实现校验逻辑时留意现实中的例外。 |
| [dwmkerr/hacker-laws](https://github.com/dwmkerr/hacker-laws) | 27.3k | #1455 | 社区 | 开发者常用的定律、理论、原则与模式合集，如 Amdahl 定律、Brooks 定律、CAP 定理、康威定律等，逐条给出解释与延伸阅读。 |
| [rwaldron/idiomatic.js](https://github.com/rwaldron/idiomatic.js) | 25.7k | #1598 | 社区 | 编写风格一致的地道 JavaScript 的原则文档，规定空格、命名、类型检查等约定。 |
| [goldbergyoni/javascript-testing-best-practices](https://github.com/goldbergyoni/javascript-testing-best-practices) | 24.6k | #1709 | 社区 | JavaScript 与 Node.js 测试最佳实践大全，五十多条经验，涵盖测试结构、隔离、Mock 与前后端测试。 |
| [johnpapa/angular-styleguide](https://github.com/johnpapa/angular-styleguide) | 23.6k | #1819 | 社区 | Angular 团队开发风格指南，提供一致性的命名、结构和最佳实践起点，含多个 Angular 版本分支。 |
| [microsoft/api-guidelines](https://github.com/microsoft/api-guidelines) | 23.3k | #1852 | 官方 · Microsoft | 微软 REST API 设计指南，规范资源命名、状态码、分页、版本管理和错误处理。 |
| [shieldfy/API-Security-Checklist](https://github.com/shieldfy/API-Security-Checklist) | 23.3k | #1853 | 社区 | 设计、测试和发布 API 时最重要的安全措施清单，涵盖认证、输入校验、限流与日志等。 |
| [google/eng-practices](https://github.com/google/eng-practices) 🗄️已归档 | 23.3k | #1861 | 官方 · Google | Google 的工程实践文档，主要包含代码评审的准则，分别面向评审者与作者；仓库已归档。 |
| [DesignPatternsPHP/DesignPatternsPHP](https://github.com/DesignPatternsPHP/DesignPatternsPHP) | 22.2k | #1996 | 社区 | 用 PHP 8 实现的常见设计模式示例，每个模式附 UML 图、代码和测试，并强调何时选用哪种模式。 |

### 前端与移动精选清单

围绕前端框架、组件、移动端与桌面端技术栈的 Awesome 列表和资源导航 · 18 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [enaqx/awesome-react](https://github.com/enaqx/awesome-react) | 74.7k | #247 | 社区 | React 生态精选清单，涵盖框架、组件库、状态管理与数据请求、样式、图标、工具和学习资源。 |
| [vuejs/awesome-vue](https://github.com/vuejs/awesome-vue) | 73.5k | #258 | 社区 | Vue.js 精选清单，收录官方资源、组件库、插件、工具、教程和示例项目。 |
| [bradtraversy/design-resources-for-developers](https://github.com/bradtraversy/design-resources-for-developers) | 67.1k | #295 | 社区 | 面向开发者的设计与 UI 资源清单，包含图片素材、字体、配色、图标、Web 模板、CSS 框架和 UI 库等。 |
| [Solido/awesome-flutter](https://github.com/Solido/awesome-flutter) | 61.4k | #357 | 社区 | Flutter 库、工具、教程和文章的精选清单，按状态管理、网络、UI、动画等分类。 |
| [wasabeef/awesome-android-ui](https://github.com/wasabeef/awesome-android-ui) | 57.8k | #394 | 社区 | Android UI / UX 库精选清单，按 Jetpack Compose、布局、列表、表单、图片、菜单等分类。 |
| [vsouza/awesome-ios](https://github.com/vsouza/awesome-ios) | 53.5k | #450 | 社区 | iOS 生态精选清单，收录 Objective-C 和 Swift 项目，按架构、网络、缓存、图表、认证等分类。 |
| [dkhamsing/open-source-ios-apps](https://github.com/dkhamsing/open-source-ios-apps) | 52.4k | #463 | 社区 | 开源 iOS、iPadOS、watchOS、tvOS 与 visionOS 应用的协作清单，按开发者工具、终端、教育、金融、游戏等类别整理，可作为学习范例。 |
| [brillout/awesome-react-components](https://github.com/brillout/awesome-react-components) | 48.5k | #531 | 社区 | React 组件与库的精选清单，只收有实际价值的组件，按主题分类。 |
| [dypsilon/frontend-dev-bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks) | 47.6k | #551 | 社区 | 人工整理的前端开发资源合集，按类别拆成多个小文件，方便浏览。 |
| [goabstract/Awesome-Design-Tools](https://github.com/goabstract/Awesome-Design-Tools) | 41.4k | #688 | 官方 · Abstract | 设计工具与插件的精选清单，涵盖设计插件、设计会议与设计 UI 套件等，由 Abstract 旗下 Flawless App 团队维护。 |
| [GorvGoyl/Clone-Wars](https://github.com/GorvGoyl/Clone-Wars) | 36.9k | #864 | 社区 | 一百多个热门网站（Airbnb、Netflix、Spotify 等）的开源克隆项目合集，附源码、演示、技术栈与 star 数，可作全栈练手参考。 |
| [jondot/awesome-react-native](https://github.com/jondot/awesome-react-native) | 35.7k | #909 | 社区 | React Native 库、工具和学习资源的精选清单，条目经过维护与相关性检查。 |
| [sorrycc/awesome-javascript](https://github.com/sorrycc/awesome-javascript) | 35k | #933 | 社区 | 浏览器端 JavaScript 库与资源精选清单，涵盖包管理、打包、UI、测试等分类。 |
| [Trinea/android-open-project](https://github.com/Trinea/android-open-project) | 31.8k | #1111 | 社区 | Android 开源项目分类汇总，按 UI、网络、数据库、工具等整理常用库。 |
| [sindresorhus/awesome-electron](https://github.com/sindresorhus/awesome-electron) | 27.3k | #1457 | 社区 | Electron 应用开发资源精选清单，含工具、库、教程和示例应用。 |
| [matteocrippa/awesome-swift](https://github.com/matteocrippa/awesome-swift) | 26.3k | #1539 | 社区 | Swift 库与资源精选清单，按类别整理并标注 Linux 支持与更新时间。 |
| [alexpate/awesome-design-systems](https://github.com/alexpate/awesome-design-systems) | 26k | #1563 | 社区 | 各公司和组织公开的设计系统精选清单，可作为搭建 UI 规范的参考。 |
| [markerikson/react-redux-links](https://github.com/markerikson/react-redux-links) | 22.5k | #1952 | 社区 | React、Redux、ES6 及相关技术的教程与资源链接精选，按主题整理，便于系统学习。 |

### 语言、后端与通用精选清单

围绕编程语言、后端、运维、自托管、系统管理、命令行、开源项目发现与开发者文化的 Awesome 列表和资源导航 · 39 个

| 项目 | Stars | 全站排名 | 出品 | 简介 |
|---|---:|---:|---|---|
| [sindresorhus/awesome](https://github.com/sindresorhus/awesome) | 512.7k | #2 | 社区 | 各类主题 Awesome 清单的总目录，按平台、编程语言、前端、后端、CS、工具等分类收录数百个高质量精选列表，并给出创建与贡献 Awesome 列表的规范。 |
| [public-apis/public-apis](https://github.com/public-apis/public-apis) | 484.6k | #3 | 社区 | 按类别整理的免费公共 API 清单，涵盖天气、地理、金融、开发工具等数十个领域，每条标注是否需要认证、是否支持 HTTPS 和 CORS。 |
| [vinta/awesome-python](https://github.com/vinta/awesome-python) | 324.2k | #10 | 社区 | 按用途分类的 Python 框架、库和工具精选清单，涵盖 Web 框架、ORM、异步、测试、部署等方向，并提供可搜索的网站。 |
| [awesome-selfhosted/awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) | 322.9k | #11 | 社区 | 可自行部署在自己服务器上的免费开源网络服务与 Web 应用清单，按分析、备份、自动化、博客、协作、监控、文件共享等数十个类别整理。 |
| [trimstray/the-book-of-secret-knowledge](https://github.com/trimstray/the-book-of-secret-knowledge) | 247k | #20 | 社区 | 作者日常工作中使用的资料合集，包含清单、手册、速查表、博客、单行命令、命令行与 Web 工具等。 |
| [avelino/awesome-go](https://github.com/avelino/awesome-go) | 186.2k | #41 | 社区 | Go 语言框架、库和软件的精选清单，按 Web 框架、数据库、认证、微服务等类别整理，是查找 Go 生态组件的入口。 |
| [521xueweihan/HelloGitHub](https://github.com/521xueweihan/HelloGitHub) | 179.4k | #44 | 社区 | 分享 GitHub 上有趣、入门级开源项目的中文月刊，每月 28 日发布，内容包含开源项目、开源书籍、实战项目与企业级项目。 |
| [ripienaar/free-for-dev](https://github.com/ripienaar/free-for-dev) | 138.9k | #74 | 社区 | 面向开发和运维的 SaaS、PaaS、IaaS 免费额度清单，涵盖托管、数据库、CI/CD、监控、邮件等，方便个人项目和初创团队选型。 |
| [jaywcjlove/awesome-mac](https://github.com/jaywcjlove/awesome-mac) | 115.2k | #102 | 社区 | 按类别系统整理的高质量 macOS 软件精选清单，涵盖开发工具、效率、办公、创意与实用工具等，便于检索和选用。 |
| [ruanyf/weekly](https://github.com/ruanyf/weekly) | 105k | #119 | 社区 | 阮一峰的科技爱好者周刊，每周五发布，记录每周值得分享的科技内容，也接受文章、软件与资源投稿。 |
| [MunGell/awesome-for-beginners](https://github.com/MunGell/awesome-for-beginners) | 89.7k | #172 | 社区 | 适合初学者提交第一个拉取请求的开源项目清单，标有 first-timers-only 一类标签，帮助新人找到可参与的入门任务。 |
| [sdmg15/Best-websites-a-programmer-should-visit](https://github.com/sdmg15/Best-websites-a-programmer-should-visit) 🗄️已归档 | 76.2k | #234 | 社区 | 程序员值得访问的网站合集，按遇到问题时、新闻、杂志、编程练习、加密货币等主题分类；仓库已归档。 |
| [binhnguyennus/awesome-scalability](https://github.com/binhnguyennus/awesome-scalability) | 74.4k | #249 | 社区 | 可扩展、高可靠、高性能大型系统的阅读清单，收集知名工程师的文章和各公司的架构案例，按扩展性、可用性、性能等主题分类。 |
| [fffaraz/awesome-cpp](https://github.com/fffaraz/awesome-cpp) | 73.5k | #257 | 社区 | C++（及 C）框架、库和资源的精选清单，涵盖标准库、异步事件循环、压缩、并发、数据库、GUI、序列化、测试、Web 框架等类别。 |
| [sindresorhus/awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs) | 67k | #296 | 社区 | Node.js 包与资源精选清单，按用途分类，涵盖框架、数据库、CLI、测试、文档等。 |
| [xingshaocheng/architect-awesome](https://github.com/xingshaocheng/architect-awesome) | 60.9k | #365 | 社区 | 面向后端架构师的技术图谱，梳理数据结构、网络、数据库、缓存、消息队列、微服务、高并发等知识点与参考资料。 |
| [rust-unofficial/awesome-rust](https://github.com/rust-unofficial/awesome-rust) | 59.6k | #380 | 社区 | Rust 代码与资源的精选清单，分应用、库、开发工具、嵌入式、数据库、Web 编程、操作系统等类别，并附学习与社区资源。 |
| [DovAmir/awesome-design-patterns](https://github.com/DovAmir/awesome-design-patterns) | 49.1k | #518 | 社区 | 软件与架构设计模式的精选清单，覆盖各语言的设计模式、通用架构、云架构、Serverless、微服务与分布式系统等资料。 |
| [akullpp/awesome-java](https://github.com/akullpp/awesome-java) | 49.1k | #520 | 社区 | Java 框架、库和软件精选清单，收录数百个项目，标注活跃度，按类别整理。 |
| [GitHubDaily/GitHubDaily](https://github.com/GitHubDaily/GitHubDaily) | 48k | #538 | 社区 | 自 2015 年起持续分享 GitHub 上高质量、有趣实用的开源技术教程、开发者工具、编程网站与成熟应用的中文项目，已累计分享一万多个开源项目。 |
| [LeCoupa/awesome-cheatsheets](https://github.com/LeCoupa/awesome-cheatsheets) | 46.5k | #570 | 社区 | 常用编程语言、框架和开发工具的速查表合集，每个主题浓缩成一个文件。 |
| [kilimchoi/engineering-blogs](https://github.com/kilimchoi/engineering-blogs) | 38.7k | #779 | 社区 | 软件工程博客精选清单，按公司、个人或团体、产品与技术分类，按字母顺序检索。 |
| [alebcay/awesome-shell](https://github.com/alebcay/awesome-shell) | 37.7k | #819 | 社区 | 命令行框架、工具包、指南和小工具的精选清单，涵盖 Shell 及各类命令行程序、终端配置与学习资料。 |
| [veggiemonk/awesome-docker](https://github.com/veggiemonk/awesome-docker) | 36.9k | #862 | 社区 | Docker 资源与项目精选清单，涵盖工具、教程、镜像、编排与安全等。 |
| [kuchin/awesome-cto](https://github.com/kuchin/awesome-cto) | 35.5k | #915 | 社区 | 面向创业公司 CTO 与研发副总裁的资源精选清单，涵盖招聘、团队管理、职业成长、项目管理、开发流程、架构与技术选型等。 |
| [awesome-foss/awesome-sysadmin](https://github.com/awesome-foss/awesome-sysadmin) | 35.3k | #923 | 社区 | 面向系统管理员的免费开源软件精选清单，涵盖自动化、备份、监控、配置管理、日志、代理、虚拟化等运维工具类别。 |
| [bayandin/awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) | 33.7k | #1006 | 社区 | Awesome 清单的清单，按编程语言、包管理器、前端、后端、数据库、运维等主题汇总各领域的 Awesome 列表。 |
| [ibraheemdev/modern-unix](https://github.com/ibraheemdev/modern-unix) | 33k | #1045 | 社区 | 常用 Unix 命令的现代、更快、更易用替代品清单，如 bat、eza、fd、ripgrep、fzf、delta 等，每项附简介。 |
| [ziadoz/awesome-php](https://github.com/ziadoz/awesome-php) | 32.7k | #1063 | 社区 | PHP 库、资源和工具的精选清单，按类别整理。 |
| [abhisheknaiidu/awesome-github-profile-readme](https://github.com/abhisheknaiidu/awesome-github-profile-readme) | 31.2k | #1152 | 社区 | 精美 GitHub 个人主页 README 的精选清单，按 GitHub Actions、动态实时、极简、徽章、图标等风格分类，并附工具与教程。 |
| [herrbischoff/awesome-macos-command-line](https://github.com/herrbischoff/awesome-macos-command-line) 🗄️已归档 | 30.9k | #1168 | 社区 | 在 macOS 终端里完成各种事情的命令与命令行应用精选清单；作者已把项目迁到个人 Git 实例，GitHub 仓库已归档。 |
| [jobbole/awesome-python-cn](https://github.com/jobbole/awesome-python-cn) | 30.6k | #1181 | 社区 | awesome-python 的中文版，Python 资源大全，涵盖 Web 框架、爬虫、模板引擎、数据库等。 |
| [viatsko/awesome-vscode](https://github.com/viatsko/awesome-vscode) | 29.1k | #1307 | 社区 | VS Code 扩展、主题和资源的精选清单，按语法、Lint 与智能提示、调试、各类技术栈以及从其他编辑器迁移等方向整理。 |
| [sdras/awesome-actions](https://github.com/sdras/awesome-actions) | 28.3k | #1378 | 社区 | GitHub Actions 精选清单，收录可复用的 Action、工作流示例与相关工具。 |
| [emmabostian/developer-portfolios](https://github.com/emmabostian/developer-portfolios) | 26.9k | #1493 | 社区 | 开发者个人作品集网站的合集，收录两千多个作品集，按字母顺序排列，可为自己的作品集提供灵感。 |
| [kahun/awesome-sysadmin](https://github.com/kahun/awesome-sysadmin) | 24.3k | #1739 | 社区 | 面向系统管理员的开源软件精选清单，涵盖备份、构建自动化、ChatOps、配置管理、CI/CD、部署自动化、DNS 等主题。 |
| [timqian/chinese-independent-blogs](https://github.com/timqian/chinese-independent-blogs) | 24k | #1771 | 社区 | 中文独立博客列表，按 RSS 订阅数据排序，收录博客的简介、地址与标签，也说明什么是独立博客以及如何提交。 |
| [n0shake/Public-APIs](https://github.com/n0shake/Public-APIs) | 23.9k | #1776 | 社区 | 按类别整理的公开 API 清单，涵盖广告、分析、日历、加密货币、天气等数十个领域，并标注开源与试用类 API。 |
| [dipakkr/A-to-Z-Resources-for-Students](https://github.com/dipakkr/A-to-Z-Resources-for-Students) | 22.3k | #1982 | 社区 | 面向学生与从业者的开发者资源精选清单，涵盖学习编程语言、参加社区活动、全球会议、黑客松与竞赛等。 |
