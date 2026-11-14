# Linux服务器配置

> 文档均为真实服务器实测落地，点击标题直接在线阅读。

| # | 技术文档 | 在线地址 |
|---|---|---|
| 1 | [CentOS 8 Cron 定时任务与 systemd timer 安装与命令参数详解](https://www.quzuo.net/document/ZSIDyaXikWPr) | [https://www.quzuo.net/document/ZSIDyaXikWPr](https://www.quzuo.net/document/ZSIDyaXikWPr) |
| 2 | [CentOS 8 journalctl 安装与命令参数详解](https://www.quzuo.net/document/HJwDTUdmwm8n) | [https://www.quzuo.net/document/HJwDTUdmwm8n](https://www.quzuo.net/document/HJwDTUdmwm8n) |
| 3 | [CentOS yum 源更换为阿里云镜像](https://www.quzuo.net/document/H1HsAhhfOQ5z) | [https://www.quzuo.net/document/H1HsAhhfOQ5z](https://www.quzuo.net/document/H1HsAhhfOQ5z) |
| 4 | [CentOS/RHEL EPEL 源配置](https://www.quzuo.net/document/KnyE2aF5JxmS) | [https://www.quzuo.net/document/KnyE2aF5JxmS](https://www.quzuo.net/document/KnyE2aF5JxmS) |
| 5 | [Cron 定时任务配置与管理指南](https://www.quzuo.net/document/oXkHMuBbFJud) | [https://www.quzuo.net/document/oXkHMuBbFJud](https://www.quzuo.net/document/oXkHMuBbFJud) |
| 6 | [Linux 两块数据盘合并为同一逻辑卷目录（含旧 LVM 清理重建）](https://www.quzuo.net/document/MTgVFNLFZ9t4) | [https://www.quzuo.net/document/MTgVFNLFZ9t4](https://www.quzuo.net/document/MTgVFNLFZ9t4) |
| 7 | [Linux 大磁盘(>2T)用 parted/GPT 分区与挂载（交互式回显）](https://www.quzuo.net/document/GPG9m8egxmh3) | [https://www.quzuo.net/document/GPG9m8egxmh3](https://www.quzuo.net/document/GPG9m8egxmh3) |
| 8 | [Linux 持久化挂载与开机自启（/etc/fstab 详解）](https://www.quzuo.net/document/0CvLJK4ruHm7) | [https://www.quzuo.net/document/0CvLJK4ruHm7](https://www.quzuo.net/document/0CvLJK4ruHm7) |
| 9 | [Linux 数据盘在线扩容已挂载分区（growpart/resize2fs 详解）](https://www.quzuo.net/document/VIqzy1zYmfRW) | [https://www.quzuo.net/document/VIqzy1zYmfRW](https://www.quzuo.net/document/VIqzy1zYmfRW) |
| 10 | [Linux 新增数据盘扩容已有逻辑卷目录（LVM 在线扩容）](https://www.quzuo.net/document/vSNJSfCEEUWy) | [https://www.quzuo.net/document/vSNJSfCEEUWy](https://www.quzuo.net/document/vSNJSfCEEUWy) |
| 11 | [Linux 磁盘初始化与分区配置（fdisk/parted 详解）](https://www.quzuo.net/document/LgeuJcOEuBE2) | [https://www.quzuo.net/document/LgeuJcOEuBE2](https://www.quzuo.net/document/LgeuJcOEuBE2) |
| 12 | [Linux 磁盘只读与故障排查（fsck/remount/dmesg）](https://www.quzuo.net/document/0XvsGsBIS05F) | [https://www.quzuo.net/document/0XvsGsBIS05F](https://www.quzuo.net/document/0XvsGsBIS05F) |
| 13 | [Linux 磁盘格式化与挂载（mkfs/mount 详解）](https://www.quzuo.net/document/T2OQcsW2asfP) | [https://www.quzuo.net/document/T2OQcsW2asfP](https://www.quzuo.net/document/T2OQcsW2asfP) |
| 14 | [Linux 磁盘运维命令与参数详解大全](https://www.quzuo.net/document/4rNj5nbNbpWI) | [https://www.quzuo.net/document/4rNj5nbNbpWI](https://www.quzuo.net/document/4rNj5nbNbpWI) |
| 15 | [Linux服务器配置 介绍与选型指南](https://www.quzuo.net/document/tZog5Te2WNZE) | [https://www.quzuo.net/document/tZog5Te2WNZE](https://www.quzuo.net/document/tZog5Te2WNZE) |
| 16 | [SSH 密钥认证配置](https://www.quzuo.net/document/fWU2D3tro7LE) | [https://www.quzuo.net/document/fWU2D3tro7LE](https://www.quzuo.net/document/fWU2D3tro7LE) |
| 17 | [SSH 端口修改与连接保活](https://www.quzuo.net/document/hcQPXrBwZK18) | [https://www.quzuo.net/document/hcQPXrBwZK18](https://www.quzuo.net/document/hcQPXrBwZK18) |
| 18 | [Ubuntu 22.04 Cron 定时任务与 systemd timer 安装与命令参数详解](https://www.quzuo.net/document/TvbECduYpih6) | [https://www.quzuo.net/document/TvbECduYpih6](https://www.quzuo.net/document/TvbECduYpih6) |
| 19 | [Ubuntu 22.04 journalctl 安装与命令参数详解](https://www.quzuo.net/document/1Bbzhrx1gxh8) | [https://www.quzuo.net/document/1Bbzhrx1gxh8](https://www.quzuo.net/document/1Bbzhrx1gxh8) |
| 20 | [Ubuntu apt 源更换为阿里云镜像](https://www.quzuo.net/document/CbE7bNuzBDI1) | [https://www.quzuo.net/document/CbE7bNuzBDI1](https://www.quzuo.net/document/CbE7bNuzBDI1) |
| 21 | [apt 源更换为清华大学/中科大镜像](https://www.quzuo.net/document/bNOqOcmgwwBG) | [https://www.quzuo.net/document/bNOqOcmgwwBG](https://www.quzuo.net/document/bNOqOcmgwwBG) |
| 22 | [journald 日志查看与分析指南](https://www.quzuo.net/document/lxaMeKeH4Ivy) | [https://www.quzuo.net/document/lxaMeKeH4Ivy](https://www.quzuo.net/document/lxaMeKeH4Ivy) |
| 23 | [yum 源更换为清华大学镜像](https://www.quzuo.net/document/2FCGelBE1mdx) | [https://www.quzuo.net/document/2FCGelBE1mdx](https://www.quzuo.net/document/2FCGelBE1mdx) |
| 24 | [yum 源更换为网易 163 镜像](https://www.quzuo.net/document/MqdzLCgpcHLj) | [https://www.quzuo.net/document/MqdzLCgpcHLj](https://www.quzuo.net/document/MqdzLCgpcHLj) |
| 25 | [主机名与 Hosts 解析配置](https://www.quzuo.net/document/QY9T4EKUKzqE) | [https://www.quzuo.net/document/QY9T4EKUKzqE](https://www.quzuo.net/document/QY9T4EKUKzqE) |
| 26 | [文件描述符与进程数限制（nofile / nproc）](https://www.quzuo.net/document/bUceXOgyv7eB) | [https://www.quzuo.net/document/bUceXOgyv7eB](https://www.quzuo.net/document/bUceXOgyv7eB) |
| 27 | [日志轮转配置指南（logrotate）](https://www.quzuo.net/document/tqKtPTtVm1pE) | [https://www.quzuo.net/document/tqKtPTtVm1pE](https://www.quzuo.net/document/tqKtPTtVm1pE) |
| 28 | [时区与本地化配置](https://www.quzuo.net/document/tj2XRYlJYG6S) | [https://www.quzuo.net/document/tj2XRYlJYG6S](https://www.quzuo.net/document/tj2XRYlJYG6S) |
| 29 | [服务器操作系统选型与安装](https://www.quzuo.net/document/m0amCT64DlAJ) | [https://www.quzuo.net/document/m0amCT64DlAJ](https://www.quzuo.net/document/m0amCT64DlAJ) |
| 30 | [系统启动项与服务管理（systemd）](https://www.quzuo.net/document/5Vh7TTk7VC2j) | [https://www.quzuo.net/document/5Vh7TTk7VC2j](https://www.quzuo.net/document/5Vh7TTk7VC2j) |
| 31 | [系统日志持久化与 Journald 配置](https://www.quzuo.net/document/Pno56kmm2l6F) | [https://www.quzuo.net/document/Pno56kmm2l6F](https://www.quzuo.net/document/Pno56kmm2l6F) |
| 32 | [系统更新与基础工具安装](https://www.quzuo.net/document/kV5H0lbeE3MJ) | [https://www.quzuo.net/document/kV5H0lbeE3MJ](https://www.quzuo.net/document/kV5H0lbeE3MJ) |
| 33 | [运维用户创建与 Sudo 权限](https://www.quzuo.net/document/GrUvBqDztwz0) | [https://www.quzuo.net/document/GrUvBqDztwz0](https://www.quzuo.net/document/GrUvBqDztwz0) |

[← 返回文档总览](../README.md)
