# 问题以及解决方法

## ANDROID_HOME not found

参考链接：[Environment variable $ANDROID_HOME not found](https://www.jianshu.com/p/a77396301b22)

我电脑上的android sdk是安装as时自动安装的所以目录是：～/Library/Android/sdk

修改 .bash_profiles

```bash

export ANDROID_HOME=/Users/wanghaotian/Library/Android/sdk
export PATH=$PATH:$ANDROID_HOME/tools:$ANDROID_HOME/platform-tools

```
 然后运行 source ~/.bash_profile，但是我的没起作用，重启电脑就好了