
## Tools

### dex2jar

[Download](http://sourceforge.net/projects/dex2jar/)

### JD-GUI

[Download](http://jd.benow.ca/)

[Github](https://github.com/java-decompiler/jd-gui)

### apktool

[Download](http://ibotpeaches.github.io/Apktool/)

[Bitbucket](https://bitbucket.org/iBotPeaches/apktool/downloads)

### AXMLPrinter2.jar

[Download](https://code.google.com/p/android4me/downloads/list)

[Error Info](http://blog.csdn.net/zzp_403184692/article/details/7959147)

[可以用的jar](http://download.csdn.net/download/simbaba/8625893)

### baksmali.jar/smali.jar

[Download](https://bitbucket.org/JesusFreke/smali/downloads)

[Github](https://github.com/JesusFreke/smali)


### jadx

[Download](http://sourceforge.net/projects/jadx/files/latest/download)

[to useing](http://www.jianshu.com/p/65c2f447946e)


## User

### XML反编译

* AXMLPrinter2.jar(minsdkversion<=7)
* AXMLPrinter2.S.jar(OK)

基本语法:`java -jar AXMLPrinter2.S.jar AndroidManifest.xml > AndroidManifest.txt`

工具使用说明:将`xml反编译.bat`、`AXMLPrinter2.S.jar`、`layout`放置同级目录，执行bat即可

注：`layout`里面放置布局xml文件

至于为啥 直接转成 xml 时，xml头部代码乱码，未知？？？