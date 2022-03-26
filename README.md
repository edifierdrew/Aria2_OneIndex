# Aria2_OneIndex
backup of Aria2_OneIndex


# 暂时发现的问题
## 1.由于脚本内证书签发有点问题
## 请在执行本脚本之前执行

curl https://get.acme.sh | sh -s email=你的邮箱

## 2.php7.0需要其他非官方的包

## 3.安装后需要更改/home/wwwroot/你的域名/config/Admin...php啥的,注释找到转跳网站，修改成https://oneindex.github.io


## 4.安装完成后，很大概率会进不去首页，下面是解决方法
   1.先进入后台
   2.先修改自己onedrive里面的需要展示在主页的目录，主题请切换成nextmoe，保存。
   3.清理缓存
   4.这时候千万什么都不要动，大概5-10分钟回来继续
   5.这时候应该可以发现打开首页了
   6.Press & Play了，可以愉快玩耍啦xD~~~~~




# 本库存Aria2Ng_Oneindex魔改版脚本

## 1.本脚本魔改Moerats脚本（原脚本：https://www.moerats.com/usr/shell/Aria2_OneIndex.sh

## 2.本脚本使用魔改Oneindex脚本（脚本：https://github.com/edifierdrew/oneindex-h
