# libreoffice_android
## 目的
是LibreOffice的Android版(5.3.4.2.0+/228a4ff4)，提供方便的编译版本
## 使用说明
<p>clone好后，修改android/source/liboSettings.gradle文件中ext的定义，如liboSrcRoot的路径信息，改写成实际的路径信息，即可编译。
<p>此版本只是修改配置文件信息，提供了so库（没有源文件），因此也只能完成上层的修改优化。
后续有需要了再及时同步LibreOffice最新版本，自己想编译的话参考[编译开源LibreOffice的Android版本](http://blog.csdn.net/w7849516230/article/details/52556469)
<p>增加了x86的so，但是体积很大，如果需要，直接将android/source/x86_so.zip中的so解压到jniLibs下的x86目录再编译即可。
<p>看到wps的安装包不到30M，还是很希望能减小libreoffice的体积，你的star和打赏是可以告诉需要继续去做的：

![微信打赏](http://arainfo.cn/wx_20170709102954.jpg)
