####　LINUX Platform
There would be some packages you have to install fisrt based on your running error information
过程中可能有一些前序工具需要安装

decompres  kconfig-frontends 
``autoscan`` it matters little if error occured　如果没有正常运行问题不大，这个工具按照我的理解是发包的开发者需要正常运行
``aclocal``  promise it runs scuccessful 这条指令应该能够正常运行// aclocal   generates aclocal.m4 based on configure.in  //aclocal 指令会根据　当前目录下的configure.in 文件　生成　aclocal.m4 （文件中包含生成的configure文件中的所有宏）
``autoconf`` promise it runs scuccessful // autoconf 会根据前序的两个文件　申城shell 脚本,
``autoheader`` 
``libtoolize --automake --copy --debug --force`` 用途不详，但是有必要执行成功
``automake --add-missing`` generate Makefile.in based on Makefile.am //根据Makefile.am　和系统环境 产生 Makefile.in
``autoreconf –f –i –Wall,no–obsolete`` 用途不详; 完成到这一步就可以使用./configure 开始正常的安装流程了



#### MacOS Platform (M1 is not supported) 
Should have install following package
``brew install autoconf``
``brew install automake``
``brew install libtool``
``gem install cocoapods``
``gem installed``
``git clone https://github.com/ngageoint/geopackage-ios.git``
``cd geopackage-ios``
``pod repo update``   pod 指令来自与刚才安装的cocoapods

decompres  kconfig-frontends 
之后和Linux 安装相似，主要是前序工具安装不太一样

``autoscan`` it matters little if error occured　如果没有正常运行问题不大，这个工具按照我的理解是发包的开发者需要正常运行
``aclocal``  promise it runs scuccessful 这条指令应该能够正常运行// aclocal   generates aclocal.m4 based on configure.in  //aclocal 指令会根据　当前目录下的configure.in 文件　生成　aclocal.m4 （文件中包含生成的configure文件中的所有宏）
``autoconf`` promise it runs scuccessful // autoconf 会根据前序的两个文件　申城shell 脚本,
``autoheader`` 
``libtoolize --automake --copy --debug --force`` 用途不详，但是有必要执行成功
``automake --add-missing`` generate Makefile.in based on Makefile.am //根据Makefile.am　和系统环境 产生 Makefile.in
``autoreconf –f –i –Wall,no–obsolete`` 用途不详; 完成到这一步就可以使用./configure 开始正常的安装流程了

``./configure``
``make``
``make install``

 gem 是一个包管理框架，brew是一个软件包管理工具
