# Useful Links

## About system

初始安装系统的一些主要链接
### Ubuntu 16.04
1. [系统美化](http://www.linuxidc.com/Linux/2016-09/135165.htm)
2. [输入法的安装](http://blog.csdn.net/iamplane/article/details/70447517)
3. [wechat安装](http://blog.csdn.net/mingtiandeqiang/article/details/76168066)

## About Machine Learning
1. [tensorflow](http://blog.csdn.net/roach_zfq/article/details/78121743?locationNum=8&fps=1)
主要尽量配置cuda8以及对应的cudnn6 2017/11/16
2. [tflearn](tflearn.org/examples/)
### Demo Links
主要在配置GPU版本的tensorflow可能会遇到一些麻烦.下面基于配置给予相关链接
|属性|值|
|:-:|:-:|
|系统|Ubuntu 16.04|
|GPU|1080p|
|cuda|8.0|
|libcudnn|6.0|

>其中显卡驱动程序使用`NVIDIA-Linux-x86_64-375.26`,直接从[官网](http://www.nvidia.com/Download/index.aspx?lang=en-uk)下载.
>`cuda`使用与`375`对应的版本,名为`NVIDIA-Linux-x86_64-375.26`,可以从[这里](https://developer.nvidia.com/cuda-80-ga2-download-archive)下载
>对应的`cudnn`版本为`6`,版本名为`libcudnn6_6.0.21-1+cuda8.0_amd64`,通过[这里](http://10.254.1.82/cache/14/01/developer2.download.nvidia.com/61a23adbac096be3b3a355ba9673c803/libcudnn6_6.0.21-1%2Bcuda8.0_amd64.deb?qODyyzC67sDI5XOIYJqRFd1L_PwaoBGqSEootSs-i5Vhmjd-OO8HpSrJFnpWWOgQcn8N7JjwtQRa8yg3vllrN0hai6l160PiScy__oYMiDeeKriTpSIV1oHDLCj7LVL1VcxsnixCNO4WSAZcHohYkP7ZvvYLkRb9qeX6P3HQ02T9gPbos95DMDQwBphMOS5CaC2N6FunCjn5ybxaU-emaP2Du-LWqCFhbkjyOY-kRis)安装.
>下一步就比较easy了,通过下面方式安装`tensorflow`以及`tflearn`:
>```bash
>sudo pip3 install tensorflow-gpu	# for python3
>sudo pip install tensorflow		# for python2
>sudo pip install tflearn			# for python3
>sudo pip3 install tflearn			# for python2
>```


## About Academic
1. [semanticscholar](https://www.semanticscholar.org)
2. [学术会议影响排名](www.scimagojr.com/journalrank.php)
3. [查询英语语法](www.linggle.com)

## About 3D
1. [坐标系旋转变换](www.euclideanspace.com)
2. [相机投影](ksimek.github.io/perspective_camera_toy.html)
