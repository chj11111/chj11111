主要是说下如何反编译apk的步骤：
1. 两个工具包：
``jd-gui``
``dex-tools-2.1``
2. 使用dex2jar反编译dex文件
将需要反编译的APK后缀名改为.rar或则 .zip，解压看到目录

得到其中的classes.dex文件，将获取到的
classes.dex复制到解压出来的工具dex-tools-2.1 文件夹内，

在命令行下，进入到``d2j-dex2jar.bat``所在目录，输入命令：
输入``d2j-dex2jar.bat classes.dex``
运行结束后，在该目录下会生成一个``classes_dex2jar.jar``的文件
然后打开工具``jd-gui``文件夹里的``jd-gui.exe``，用该工具打开生成的``classes_dex2jar.jar``文件，便可以看到源码
