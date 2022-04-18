
## HISI

[鸿蒙文档](https://device.harmonyos.com/cn/docs/documentation/guide/guide-description-0000001054913231)

### 下载编译

[从镜像站点获取 全量代码3.0](https://gitee.com/openharmony/docs/blob/master/zh-cn/device-dev/get-code/sourcecode-acquire.md)

[编译Hi3516DV300开发板源码](https://device.harmonyos.com/cn/docs/documentation/guide/ide-hi3516dv300-compile-0000001146686054#section7381241105314) 

全量代码（标准、轻量和小型系统），我们在这仅使用标准系统。
Standard System，标准系统：面向应用处理器，例如Arm Cortex-A的设备，参考内存≥128MiB，提供增强的交互能力，提供3D GPU以及硬件合成能力，提供更多控件以及动效更丰富的图形能力，提供完整的应用框架。典型产品有高端的冰箱显示屏等。

#### 编译step1
编译命令：

    ./build.sh --product-name Hi3516DV300 --ccache
[错误解决](https://blog.csdn.net/weixin_41865104/article/details/124258249?spm=1001.2014.3001.5501)
#### 编译step2

### 源码目录

    目录名	描述

    applications	应用程序样例，包括camera等

    base	基础软件服务子系统集&硬件服务子系统集

    build	组件化编译、构建和配置脚本

    docs	说明文档

    domains	增强软件服务子系统集

    drivers	驱动子系统

    foundation	系统基础能力子系统集

    kernel	内核子系统

    prebuilts	编译器及工具链子系统

    test	测试子系统

    third_party	开源第三方组件

    utils	常用的工具集

    vendor	厂商提供的软件

    build.py	编译脚本文件