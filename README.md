# OVH Root Login Enabler

这是一个专为 OVH 等云服务商（以及其他默认禁用 Root 登录的 VPS）设计的 Shell 脚本。

它可以在不丢失 SSH 密钥的情况下，一键开启 Root 用户登录权限，并自动处理 Ubuntu/Debian/CentOS 等系统的兼容性问题。

## 🚀 一键安装命令

**无需切换 Root 账号**，直接在默认用户（如 `ubuntu`）下复制并执行以下命令即可：

```bash
curl -sL https://raw.githubusercontent.com/NX2406/ovhroot/refs/heads/main/OVHroot-install | sudo bash
