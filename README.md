# [镜像](https://drive.wzwtt.cf/mirrors/)同步管理器 [Mirrors](https://drive.wzwtt.cf/mirrors/) Synchronization Manager

| 镜像名称 Mirror Name    | 描述 Description | 上游 Upstream | 计划时间<br>Scheduled time | 当前同步状态<br>Current Sync Status  | 镜像大小 Mirror Size |
| :----:        |    :----:   |         :----: |   :----:   |   :----:   |   :----:   |
| [archlinux-iso](https://drive.wzwtt.cf/mirrors/archlinux-iso/) | Arch Linux 安装镜像<br> Installation image of Arch Linux | rsync://geo.mirror.pkgbuild.com/packages/iso/ | 0 21 * * * | [![archlinux-iso](https://github.wzwtt.cf/wzwtt/mirror-sync/actions/workflows/archlinux-iso.yml/badge.svg)](https://github.com/wzwtt/mirror-sync/actions/workflows/archlinux-iso.yml)|11G	.|
| [debian-cd](https://drive.wzwtt.cf/mirrors/debian-cd/) |  Debian 安装镜像<br> Installation image of Debian | rsync://cdimage.debian.org/debian-cd/ | 0 12 * * * | [![debian-cd](https://github.wzwtt.cf/wzwtt/mirror-sync/actions/workflows/debian-cd.yml/badge.svg)](https://github.com/wzwtt/mirror-sync/actions/workflows/debian-cd.yml)|421G	.|
| [deepin](https://drive.wzwtt.cf/mirrors/deepin/) （[帮助](https://wzwtt.cf/mirror-sync/help/deepin)）| Deepin 操作系统软件仓库<br>Deepin packages repository | rsync://rsync.deepin.com/deepin/  | 0 4,10,16,22 * * * | [![deepin](https://github.wzwtt.cf/wzwtt/mirror-sync/actions/workflows/deepin.yml/badge.svg)](https://github.com/wzwtt/mirror-sync/actions/workflows/deepin.yml)| 未知 |
| [deepin-cd](https://drive.wzwtt.cf/mirrors/deepin-cd/) | Deepin 操作系统安装镜像<br> Installation image of Deepin | rsync://rsync.deepin.com/releases/ | 0 16 * * * | [![deepin-cd](https://github.wzwtt.cf/wzwtt/mirror-sync/actions/workflows/deepin-cd.yml/badge.svg)](https://github.com/wzwtt/mirror-sync/actions/workflows/deepin-cd.yml)|49G	.|
|  [github-release](https://drive.wzwtt.cf/mirrors/github-release/current/) |  一些 GitHub [优秀项目](https://github.com/wzwtt/mirror-sync/blob/main/repos.yaml)的发行版<br> Releases of some [excellent projects](https://github.com/wzwtt/mirror-sync/blob/main/repos.yaml) on GitHub |  https://api.github.com/repos/ | 0 2,14 * * * | [![github-release](https://github.wzwtt.cf/wzwtt/mirror-sync/actions/workflows/github-release.yml/badge.svg)](https://github.com/wzwtt/mirror-sync/actions/workflows/github-release.yml)|23G	.|
|  [kali-images](https://drive.wzwtt.cf/mirrors/kali-images/) |  Kali Linux 安装镜像<br> Installation image of Kali Linux |  rsync://ftp.halifax.rwth-aachen.de/kali-images/ | 0 10 * * * |  [![kali-images](https://github.wzwtt.cf/wzwtt/mirror-sync/actions/workflows/kali-images.yml/badge.svg)](https://github.com/wzwtt/mirror-sync/actions/workflows/kali-images.yml)|138G	.|
|  [termux](https://drive.wzwtt.cf/mirrors/termux/) |  Termux 软件仓库<br>Termux packages repository  | rsync://grimler.se/termux/  | 0 0,6,12,18 * * | [![termux](https://github.wzwtt.cf/wzwtt/mirror-sync/actions/workflows/termux.yml/badge.svg)](https://github.com/wzwtt/mirror-sync/actions/workflows/termux.yml)|23G	.|
|  [ubuntu](https://drive.wzwtt.cf/mirrors/ubuntu/) |  Ubuntu 操作系统软件仓库<br>Ubuntu packages repository  | rsync://archive.ubuntu.com/ubuntu/  | 0 0,6,12,18 * * * | [![ubuntu](https://github.wzwtt.cf/wzwtt/mirror-sync/actions/workflows/ubuntu.yml/badge.svg)](https://github.com/wzwtt/mirror-sync/actions/workflows/ubuntu.yml)|未知|
|  [ubuntu-releases](https://drive.wzwtt.cf/mirrors/ubuntu-releases/) |  近年来发行的 Ubuntu 安装镜像<br> Ubuntu installation images released in recent years  | rsync://rsync.releases.ubuntu.com/releases/  | 0 21 * * * | [![ubuntu-releases](https://github.wzwtt.cf/wzwtt/mirror-sync/actions/workflows/ubuntu-releases.yml/badge.svg)](https://github.com/wzwtt/mirror-sync/actions/workflows/ubuntu-releases.yml)|103G	.|
|  [ubuntukylin-cdimage](https://drive.wzwtt.cf/mirrors/ubuntukylin-cdimage/) | 优麒麟操作系统安装镜像<br> Installation image of Ubuntukylin  | rsync://cdimage.ubuntukylin.com/releases/  | 30 17 * * * | [![ubuntukylin-cdimage](https://github.wzwtt.cf/wzwtt/mirror-sync/actions/workflows/ubuntukylin-cdimage.yml/badge.svg)](https://github.com/wzwtt/mirror-sync/actions/workflows/ubuntukylin-cdimage.yml)|53G	.|
|  [Windows-iso](https://drive.wzwtt.cf/mirrors/Windows-iso/) | Windows 的 GA 版 ISO 安装镜像<br> ISO Installation Image of General Availability Version for Windows  | https://www.microsoft.com/zh-cn/software-download/  | 0 0 10,20,30 * * |  [![Windows-iso](https://github.wzwtt.cf/wzwtt/mirror-sync/actions/workflows/Windows-iso.yml/badge.svg)](https://github.com/wzwtt/mirror-sync/actions/workflows/Windows-iso.yml)|803G	.|
