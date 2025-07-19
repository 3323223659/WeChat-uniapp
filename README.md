# 仿微信 UniApp 项目

## 项目简介

本项目是基于 [UniApp](https://uniapp.dcloud.io/) 框架开发的仿微信聊天社交应用，支持多端（微信小程序、H5、App 等）运行。项目实现了微信的主要功能模块，包括登录注册、好友管理、聊天、朋友圈、个人中心等，适合学习和二次开发。

后端地址：https://github.com/3323223659/WeChat-backEnd

## 技术架构

- **前端框架**：[UniApp](https://uniapp.dcloud.io/)
- **UI 组件**：uView、原生 CSS
- **数据存储**：本地存储（Storage）、后端接口（需自建）
- **页面结构**：Vue 单文件组件（.vue）
- **样式**：SCSS/CSS
- **多端支持**：微信小程序、H5、App（需 HBuilderX 打包）

## 目录结构

```text
uni-weixin/
├── App.vue                # 应用入口
├── main.js                # 入口 JS
├── pages/                 # 主要页面目录
│   ├── contacts/          # 通讯录相关页面
│   ├── discovery/         # 发现（朋友圈等）
│   ├── loginRegist/       # 登录注册相关页面
│   ├── me/                # 个人中心相关页面
│   ├── msgList/           # 消息列表与聊天
│   ├── others/            # 其他页面
│   └── welcome/           # 欢迎页
├── components/            # 公共 JS 工具
├── static/                # 静态资源（图片、音频、字体等）
├── uni_modules/           # uni-app 插件模块
├── json/                  # 城市等静态数据
├── manifest.json          # 项目配置
├── pages.json             # 页面路由配置
├── uni.scss               # 全局样式
└── README.md              # 项目说明文档
```

## 使用说明

### 1. 环境准备

- 安装 [HBuilderX](https://www.dcloud.io/hbuilderx.html)
- 安装微信开发者工具（如需运行小程序）

### 2. 运行项目

1. 使用 HBuilderX 打开 `uni-weixin` 目录。
2. 运行到浏览器、微信小程序或 App 模拟器。
3. 如需真机调试或发布，参考 UniApp 官方文档。
4. 确保后台端口与前端对应

### 3. 目录说明

- `pages/` 目录下为主要功能页面，按模块划分。
- `components/` 为通用 JS 工具类。
- `static/` 存放图片、音频、字体等静态资源。
- `uni_modules/` 为 uni-app 插件模块。

### 4. 常见命令

- 项目无需命令行构建，推荐使用 HBuilderX 可视化操作。
- 如需命令行打包，可参考 [uni-app CLI 文档](https://uniapp.dcloud.io/cli?id=cli-%E6%A6%82%E8%A7%88)。

## 参考资料

- [UniApp 官方文档](https://uniapp.dcloud.io/)
- [uView UI](https://www.uviewui.com/)
- [微信小程序开发文档](https://developers.weixin.qq.com/miniprogram/dev/)

## 免责声明

本项目仅用于学习和交流，禁止用于商业用途。如有侵权请联系删除。
