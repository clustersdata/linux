# linux
linux
linux下解压rar文件
二、下载并安装rar软件

2.1 下载
mkdir -p  /home/oldboy/tools
cd /home/oldboy/tools
wget http://www.rarlab.com/rar/rarlinux-3.8.0.tar.gz

2.2 安装
tar zxvf rarlinux-3.8.0.tar.gz
cd rar
make
make install 

三、rar命令语法

将/etc 目录压缩为etc.rar 命令为：

rar a etc.rar /etc

将etc.rar 解压 命令为：
rar x etc.rar 
unrar -e etc.tar



 
