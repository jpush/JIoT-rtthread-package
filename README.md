# JIoT for RTthread Package

## 1 介绍 

极光 IoT 是极光面向物联网开发者推出的 SaaS 服务平台，依托于极光在开发者服务领域的技术积累能力。专门为 IoT 设备优化协议，提供高并发，高覆盖，高可用的设备接入及消息通信能力。同时针对物联网使用场景提供安全连接，实时统计，设备管理 ，影子设备等一些列解决方案。

### 1.1 目录结构

| 名称            | 说明 |
| ----            | ---- |
| jiot-c-sdk | sdk源码目录 |
| docs            | 文档目录 |
| samples  | 示例文件目录 |
| LICENSE    | 许可证文件 |
| README.md | 软件包使用说明 |
| SConscript | RT-Thread 默认的构建脚本 |

### 1.2 SDK接口说明

[JIoT C SDK 接口文档](https://docs.jiguang.cn//jiot/client/c_sdk_api/)

### 1.3 许可证

MIT License 协议许可。

## 2 获取软件包

使用 `jiot-c-sdl` 软件包使用 menuconfig 命令打开 Env 配置界面，在 `RT-Thread online packages → IoT - internet of things → IoT Cloud` 中选择 jiot-c-sdk 软件包，操作界面如下图所示：

![选中 jiot-c-sdk 软件包](https://github.com/RT-Thread-packages/paho-mqtt/raw/master/docs/figures/select_mqtt_package.png)

选择合适的配置项后，使用 `pkgs --update` 命令下载软件包并添加到工程中即可。

## 3 软件包使用

