<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 motionEye

[![集成程度](https://dash.yunohost.org/integration/motioneye.svg)](https://ci-apps.yunohost.org/ci/apps/motioneye/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/motioneye.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/motioneye.maintain.svg)

[![使用 YunoHost 安装 motionEye](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=motioneye)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 motionEye。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

**motionEye** is an online interface for the software [_motion_](https://motion-project.github.io/), a video surveillance program with motion detection.

Check out the [__wiki__](https://github.com/motioneye-project/motioneye/wiki) for more details.

Default user for login is: `admin` and empty password.


**分发版本：** 0.43.1b1~ynh2

## 截图

![motionEye 的截图](./doc/screenshots/example.png)

## 文档与资源

- 官方用户文档： <https://github.com/motioneye-project/motioneye/wiki>
- 上游应用代码库： <https://github.com/motioneye-project/motioneye>
- YunoHost 商店： <https://apps.yunohost.org/app/motioneye>
- 报告 bug： <https://github.com/YunoHost-Apps/motioneye_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/motioneye_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/motioneye_ynh/tree/testing --debug
或
sudo yunohost app upgrade motioneye -u https://github.com/YunoHost-Apps/motioneye_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
