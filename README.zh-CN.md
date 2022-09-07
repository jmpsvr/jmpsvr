<div align="center">
  <a href="https://github.com/jmpsvr/jmpsvr">
    <img alt="Jump Server Logo" src="./assets/jmpsvr.png">
  </a>
  <br><br>
</div>

[English](./README.md) | **中文**

[项目文档](https://docs.jmpsvr.com) | [API 文档](https://docs.jmpsvr.com/api.html)

## 简介

Jump Server 是一个优雅而开源的物联网堡垒机，它有以下特性:

* 💡 一键部署：基于容器化技术，傻瓜式一键部署
* ⚡️ 轻量而快速：后端采用 Node.js，前端采用 Vue3
* 🛠️ 快速上手：学习成本低，容易短时间上手
* 🔑 细粒度权限管理：支持为每个用户独立设置权限
* 📦 二次开发：可扩展性强，可通过二次开发接入新的设备
* 🔩 视频监控：适配市场上绝大多数的视频监控设备

## 部署
> 本项目的容器基于 Docker，容器编排采用 docker-compose，在部署前请确认环境的配置。
>
> 部署需要用到 80 和 1883 端口，请确保空闲。如需要修改端口可自行编辑 docker-compose.yaml。

执行下面的命令即可完成部署:
```bash
git clone https://github.com/jmpsvr/jmpsvr && cd jmpsvr
docker-compose up -d
```
完成后访问 http://localhost 即可，默认管理员用户名和密码均为 `admin`。

## 架构图

![Structure](assets/structure.png)

## 预览

![Preview](assets/preview.png)

![Devices](assets/devices.png)

![Camera](assets/camera.png)

![Location](assets/location.png)

## 维护者

[@mmdjiji](https://github.com/mmdjiji)

## 赞助

![afdian](assets/afdian.jpg)

## 开源协议

[GPL-3.0](./LICENSE)
