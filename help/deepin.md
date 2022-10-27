[Deepin](https://www.deepin.org/) ，一个基于Linux的开源国产操作系统。

您可以在 [deepin-cd](https://drive.wzwtt.cf/mirrors/deepin-cd/) 镜像中下载相应的 ISO 镜像文件。

要使用小章鱼镜像站作为您的 Deepin 操作系统默认软件源，请进行以下操作。

打开终端，然后输入以下命令：
```
sudo cp /etc/apt/sources.list /etc/apt/sources.list.bak #备份原文件
sudo vim /etc/apt/sources.list
```
删除原有内容并加入以下内容：
```
deb https://drive.wzwtt.cf/mirrors/deepin/ apricot main contrib non-free
```
保存并退出之后执行：
```
sudo apt-get update #更新软件源
```

