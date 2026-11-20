# Android 客户端安装包合集

这里放几个 Android 客户端安装包，按下面的表格直接下载即可。

## 下载

| 应用 | 版本 | 包名 | 大小 | 系统要求 | CPU 架构 | 安装包 |
| --- | --- | --- | --- | --- | --- | --- |
| 星连VPN | 2.6.6 | `com.singlink.singlinkvpn` | 73.1 MB | Android 8.0+ | arm64-v8a | [VPN.apk](https://github.com/jlhc1216/vpn-/releases/download/v2.6.6/VPN.apk) |
| Edge VPN | 1.4.9 | `com.edgevpn.secure.proxy.unblock` | 28.1 MB | Android 8.0+ | arm64-v8a | [Edge.VPN.apk](https://github.com/jlhc1216/vpn-/releases/download/v1.4.9/Edge.VPN.apk) |
| GoFlyVPN | 6.1.0 | `com.ambrose.overwall` | 55.7 MB | Android 9.0+ | arm64-v8a / armeabi-v7a | [GoFlyVPN.apk](https://github.com/jlhc1216/vpn-/releases/download/v6.1.0/GoFlyVPN.apk) |
| V2VPN | 26.10.21 | `com.wrongchao.v2vpn` | 8.6 MB | Android 12.0+ | arm64-v8a | [v2vpn.apk](https://github.com/jlhc1216/vpn-/releases/download/v26.10.21/v2vpn.apk) |

> 历史版本、更新说明与 SHA256 校验值见 [Releases](https://github.com/jlhc1216/vpn-/releases)。

## 安装步骤

1. 点击上方表格中的链接下载对应 APK。
2. 在系统设置中允许「安装未知应用」（一般在：设置 → 安全 / 应用管理 → 安装未知应用）。
3. 打开下载好的 APK，按提示完成安装。

## 校验安装包

每个包在上传前都做过 CRC 完整性校验、包信息读取与签名验证，SHA256 值写在各 Release 页面。下载后可自行核对：

```bash
sha256sum VPN.apk
```

与 Release 页面记录的 SHA256 一致即可。

## 常见问题

**安装时提示「解析包出错」？**

多半是系统版本过低或 CPU 架构不匹配，请对照上方表格确认系统要求与 CPU 架构。

**安装按钮不可用 / 被系统拦截？**

确认已在系统设置中允许「安装未知应用」。

## 说明

- 所有安装包均为原样搬运，未做任何修改。
