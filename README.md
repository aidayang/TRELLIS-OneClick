# TRELLIS-OneClick

![](https://github.com/microsoft/TRELLIS/raw/main/assets/teaser.png)

TRELLIS是微软联合国内大学开源的一款非常强大的图片转3D模型应用，处理速度非常快，而且生成的3D资产质量非常高，为了方便大家快速上手体验省去安装部署耗时，我制作了最新版的一键启动整合包，有需要的可以自行下载体验。

## TRELLIS一键启动整合包使用说明

虽然说大部分工作我已经完成了，但是你电脑上仍然需要先安装CUDA和visual studio才行，不过这个安装过程非常简单。

### 安装visual studio 2022

visual studio 2022[点击下载](https://visualstudio.microsoft.com/zh-hans/thank-you-downloading-visual-studio/?sku=Community&channel=Release&version=VS2022&source=VSLandingPage&cid=2030&passive=false)
勾选使用C++的桌面开发，然后点击右下角安装按钮开始安装

![](https://github.com/aidayang/TRELLIS-OneClick/blob/main/docs/images/image-31.png?raw=true)

安装完成后将编译程序cl.exe路径添加到电脑系统环境变量path中，路径地址一般为：
你的Microsoft Visual Studio安装目录\2022\Community\VC\Tools\MSVC\14.42.34433\bin\Hostx64\x64

### 安装cuda

点击链接：[https://developer.nvidia.com/cuda-12-4-0-download-archive](https://developer.nvidia.com/cuda-12-4-0-download-archive)，根据你的电脑系统下载12.4cuda安装程序。鼠标右键点击download按钮，选择复制链接地址，将下载地址复制到迅雷里可实现高速下载，安装程序下载到电脑上之后双击安装，全程保持默认就可以。

![](https://github.com/aidayang/TRELLIS-OneClick/blob/main/docs/images/2.jpg?raw=true)

### 使用TRELLIS

将TRELLIS整合包下载到电脑上并解压，双击【启动软件.exe】，稍等一会即可启动webUI界面。上传图片素材点击生成按钮即可生成预览，点击GLB提取，即可生成GLB格式文件，界面操作比较简单。
![](https://raw.githubusercontent.com/aidayang/TRELLIS-OneClick/refs/heads/main/docs/images/2.webp)

TRELLIS整合包视频教程：[youtube>>](https://youtu.be/pcuaZPrb0zo?si=Ld89QmCPgk0XGDfr)



### 注意事项

由于低端显卡性能较低生成时间较长，建议英伟达显卡30、40系列用户使用。

整合包只支持Windows 10或11系统

软件运行路径中不要有非英文字符和空格

使用前请先将英伟达显卡驱动更新到最新版本，否则可能会报错

### TRELLIS一键启动整合包下载链接

[https://pan.quark.cn/s/3f0d9af595a8](https://pan.quark.cn/s/3f0d9af595a8)

[https://pan.baidu.com/s/1HUx8HCSKX3CHypwnkiIawA?pwd=beft](https://pan.baidu.com/s/1HUx8HCSKX3CHypwnkiIawA?pwd=beft)

## TRELLIS项目地址

https://github.com/microsoft/TRELLIS
