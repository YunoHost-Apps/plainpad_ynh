<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Plainpad

[![集成程度](https://apps.yunohost.org/badge/integration/plainpad)](https://ci-apps.yunohost.org/ci/apps/plainpad/)
![工作状态](https://apps.yunohost.org/badge/state/plainpad)
![维护状态](https://apps.yunohost.org/badge/maintained/plainpad)

[![使用 YunoHost 安装 Plainpad](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=plainpad)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Plainpad。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Plainpad is a self hosted, open source note taking application that is very easy to setup on your server. Your data will never leave your server and you will be able to access them from any device connected to the internet.
With Plainpad you can allow multiple users to access the application without being able to see each other's notes. The notes are being encrypted and stored safely in the database.

**分发版本：** 1.0.0~ynh3

**演示：** <https://alextselegidis.com/try/plainpad/#/login>

## 截图

![Plainpad 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://alextselegidis.com/get/plainpad>
- 官方管理文档： <https://alextselegidis.com/get/plainpad/self-hosted>
- 上游应用代码库： <https://github.com/alextselegidis/plainpad>
- YunoHost 商店： <https://apps.yunohost.org/app/plainpad>
- 报告 bug： <https://github.com/YunoHost-Apps/plainpad_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/plainpad_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/plainpad_ynh/tree/testing --debug
或
sudo yunohost app upgrade plainpad -u https://github.com/YunoHost-Apps/plainpad_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
