# OpenCV-.i-
# 在编译OpenCV的时候经常出现缺少.i文件，所以一次性把他们做个集合  
#在clone源码的时候，可能会出现文件下载不完全的情况，如缺少各种.i文件。在linux下查看bulid下的CMakeDownloadLog.txt文件，能找到.i文件的下载路径。
下载完以后移植到opencv_contrib/modules/xfeatures2d/src/目录下，然后重新编译。
