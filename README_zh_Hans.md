<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Etherpad

[![集成程度](https://dash.yunohost.org/integration/etherpad.svg)](https://ci-apps.yunohost.org/ci/apps/etherpad/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/etherpad.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/etherpad.maintain.svg)

[![使用 YunoHost 安装 Etherpad](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=etherpad)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Etherpad。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Etherpad is a real-time collaborative editor scalable to thousands of simultaneous real time users. It provides full data export capabilities, and runs on your server, under your control.
This version of Etherpad is installed without plugins and uses Rustydb as database.
If you want to install Etherpad with plugins and MySQL database: https://github.com/YunoHost-Apps/etherpad_mypads_ynh",


**分发版本：** 2.2.5~ynh1

**演示：** <https://video.etherpad.com/>

## 截图

![Etherpad 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://etherpad.org/>
- 官方管理文档： <https://etherpad.org/doc/v2.0.2/>
- 上游应用代码库： <https://github.com/ether/etherpad-lite>
- YunoHost 商店： <https://apps.yunohost.org/app/etherpad>
- 报告 bug： <https://github.com/YunoHost-Apps/etherpad_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/etherpad_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/etherpad_ynh/tree/testing --debug
或
sudo yunohost app upgrade etherpad -u https://github.com/YunoHost-Apps/etherpad_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
