# Download Android SDK #
The SDK is huge (about 6 GiB). Please **DO NOT CLONE** from Bitbucket directly (It will fail due to network flow limit).

We have provided a tar ball of the .git directory at:

* [Baidu Pan](http://pan.baidu.com/s/1dDhDNGX#path=%252FDevBoard%252FFirePrime%252FSource%252FAndroid5.1)
* [Google Drive](https://drive.google.com/open?id=0B7HO8lbGgAqAZ3ZsU3RoMEJ3bzg)

Please check the md5 checksum before proceeding:
```
#!shell
$ md5sum /path/to/fireprime_android5.1_git_20150612.tar
b896848a3068b50be4c6780e8bd73a2c  fireprime_android5.1_git_20150612.tar
```

If it is correct, uncompress it:
```
#!shell
mkdir -p ~/proj/fireprime
cd ~/proj/fireprime
tar xf /path/to/fireprime_android5.1_git_20150612.tar
git reset --hard
git remote add bitbucket https://bitbucket.org/T-Firefly/firenow-lollipop.git
```

From now on, you can pull updates from Bitbucket:
```
#!shell
git pull bitbucket fireprime:fireprime
```

Please visit the following website for more details of our FirePrime development board. Thank you.

http://www.t-firefly.com/en/firenow/fireprime

# 下载 Android SDK #

SDK 非常巨大（约 6 GiB），请**不要直接从 Bitbucket 下载 **仓库源码（由于流量限制的原因会出错）。

我们提供了 .git 目录的打包，放到云盘上以供下载：

* [百度云盘](http://pan.baidu.com/s/1dDhDNGX#path=%252FDevBoard%252FFirePrime%252FSource%252FAndroid5.1)
* [Google Drive](https://drive.google.com/open?id=0B7HO8lbGgAqAZ3ZsU3RoMEJ3bzg)

下载完成后先验证一下 MD5 码：
```
#!shell
$ md5sum /path/to/fireprime_android5.1_git_20150612.tar
b896848a3068b50be4c6780e8bd73a2c  fireprime_android5.1_git_20150612.tar
```

确认无误后，就可以解压：
```
#!shell
mkdir -p ~/proj/fireprime
cd ~/proj/fireprime
tar xf /path/to/fireprime_android5.1_git_20150612.tar
git reset --hard
git remote add bitbucket https://bitbucket.org/T-Firefly/firenow-lollipop.git

```

之后就可以从 Bitbucket 处获取更新的提交，保持同步:
```
#!shell
git pull bitbucket fireprime:fireprime
```

想了解更多我们 FirePrime 开发板的详情，请浏览以下网址，谢谢！

  http://www.t-firefly.com/zh/firenow/fireprime
