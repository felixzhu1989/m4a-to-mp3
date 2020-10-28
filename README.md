# m4a-to-mp3

This is a simple script to convert all the `.m4a` files inside a folder to `.mp3` into a folder. I did this script because I needed it for and old but useful mp3 player I got (it only reads *mp3* files).

# 环境支持

- 安装Ffmpeg
https://www.ffmpeg.org/
- Windows环境下安装Cygwin
http://www.cygwin.cn/site/install/

# 使用

将`convert.sh`文件拷贝至目标目录，打开Cygwin64 Terminal，使用`cd`命令定位倒目标目录，输入`bash convert.sh`。
脚本将自动执行，新的mp3文件将生成在`newfiles`文件夹内。
