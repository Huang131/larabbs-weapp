## 项目概述

* 产品名称：LaraBBS-WEAPP
* 项目代号：larabbs-weapp

LaraBBS 是一个简洁的论坛应用，使用 Laravel5.5 编写而成。一步步开发此项目的教程请见 [《Web 开发实战进阶  - 从零开始构建论坛系统》](https://laravel-china.org/topics/6592)。LaraBBS-WEAPP 是利用 LaraBBS 接口实现的小程序，教程请见 [《Laravel 微信小程序开发》](https://laravel-china.org/courses/laravel-weapp)

## 功能如下

- 用户认证 —— 注册、登录、退出；
- 个人页面 —— 用户个人信息，编辑资料，上传头像；
- 用户授权 —— 作者才能删除自己的内容；
- 话题 —— 列表，详情，删除；
- 话题回复 —— 列表，发布，删除；
- 消息通知 —— 轮训显示消息提示，消息列表，标记已读；
- 用户权限；
- 页面分享；


## 运行环境要求

- WePY 1.7+

## 开发环境部署/安装

本项目代码使用 WePY 框架 [WePY](https://github.com/Tencent/wepy) 开发

### 基础安装

#### 1. 克隆源代码

克隆 `larabbs-weapp` 源代码到本地：

    > git clone git@github.com:Huang131/larabbs-weapp.git

#### 2. 安装扩展包依赖

```
> yarn
> yarn global add wepy-cli
```

#### 3. 编译

```
> npm run build
```
