<p align="center">
  <a href="https://github.com/vuejs/vue-next">
    <img src="https://img.shields.io/badge/vue-3.0-brightgreen.svg" alt="vue">
  </a>
  <a href="https://github.com/element-plus/element-plus">
    <img src="https://img.shields.io/badge/element--plus-1.x-brightgreen.svg" alt="element-plus">
  </a>
</p>

[im-vue]主要目的在于学习 **`vue3`** + **`Element-plus`**,功能还未很完善,目前只支持好友私聊,还未支持群聊,后续会 **`持续迭代更新`**。

后端是基于 **`java`** 的 **`springboot`** **`netty`**。<br>

### 简介

[im-vue]是一个管理后台基础功能框架，基于 [vue3](https://github.com/vuejs/vue-next) 、 [element-plus](https://github.com/element-plus/element-plus) 实现。内置了好友私聊功能。

### 功能模块

- [x] 登录
- [x] 注册
- [x] 好友分组
- [x] 添加好友
- [x] 好友私聊
- [ ] 群聊

### 项目结构

```bash
vue3-src
├─api 接口模块
│
├─assets 静态资源模块
│  ├─icon svg图标
│  ├─images 图片
│  └─sass 样式
│
├─components 组件模块
│
├─router 动态
│
├─store vuex
│  ├─modules
│  │  ├─conversation 会话模块
│  │  ├─friend 好友模块
│  │  ├─message 消息模块
│  │  ├─status 侧边栏状态模块
│  │  ├─user 用户登录信息模块
│  │  └─websocket websocket模块
│  └─index 动态加载模块
│
├─types typescript接口
│
├─utils 工具模块
│  ├─constants 常量
│  ├─index 工具
│  ├─request axios二次封装
│  ├─storage 本地缓存工具
│  └─websocket websocket工具类
│
├─views 视图模块
│  ├─chat 聊天页
│  ├─login 登录页面

```

### 开发

```bash
# 克隆项目
git clone https://github.com/gmingchen/im-vue.git

# 进入项目目录
cd im-vue

# 安装依赖
npm install

# 启动服务
npm run dev   # 开发环境
npm run prod  # 正式环境
npm run test  # 测试环境

# 发布
npm run build:dev   # 开发环境
npm run build:prod  # 正式环境
npm run build:test  # 测试环境
```
