HBase用户指南（中文版）
===================
序
-------------------
当前HBase英文版的用户指南相比较之前的版本更新了很多内容，而之前其他人翻译的版本因为某些原因已经中断。所以，打算翻译新版的HBase英文版参考指南。

由于涉及的概念和术语较多，许多概念和术语尚没有公认的中文译法，加上译者水平有限，若译文中有不妥之处，还请批评指正。

生成html方式
-------------------
1、安装maven

如果已安装，则跳过本步骤。判断是否安装可使用mvn --version命令。

2、下载源代码编译

        git clone https://github.com/aaronshan/hbase-user-guide-cn.git
        cd hbase-user-guide-cn
        mvn site
3、使用

编译完成后，会在target/docbkx目录下生成multipage和onepage两个目录，分别代表多页和单页。 分别进入这两个目录，打开对应的book.html文件即可。

