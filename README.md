# 兆能 ZN-M2 OpenWrt 固件

无 WiFi / 无 USB / 弱电箱专用 · 内核 4.4.60 · 推荐内存 512M+

## 刷机 & 升级

- 控制台：`192.168.1.1` · 默认密码：`password`

| 场景 | 文件 |
|------|------|
| uboot 刷机 | `*factory-basic.ubi` |
| 系统升级 | `*sysupgrade-basic.bin` |
| 软件包清单 | `*basic.manifest` |

---

## 手动构建

1. Fork 本仓库
2. 在 Actions 页面选择 `zn-m2 build` → `Run workflow`
3. 等待约 2-3 小时，构建产物自动发布到 Release
