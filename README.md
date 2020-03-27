# 在编译OpenCV的时候经常出现缺少.i文件，所以一次性把他们做个集合  
# 在clone源码的时候，可能会出现文件下载不完全的情况，如缺少各种.i文件。在linux下查看bulid下的CMakeDownloadLog.txt文件，能找到.i文件的下载路径。
# 下载完以后移植到opencv_contrib/modules/xfeatures2d/src/目录下，然后重新编译。

## boostdesc_bgm.i
## boostdesc_bgm_bi.i
## boostdesc_bgm_hd.i
## boostdesc_lbgm.i
## boostdesc_binboost_064.i
## boostdesc_binboost_128.i
## boostdesc_binboost_256.i
## vgg_generated_120.i
## vgg_generated_64.i
## vgg_generated_80.i
## vgg_generated_48.i

