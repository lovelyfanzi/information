#blogs

Team Blogs 根据老师给出的步骤，我先安装了是Visual C++ 2010 express （指学习版），

然后下载了要用的gdal文件 打开VC++2010后，首先创建控制台项目，然后在firstDemo.cpp里先把引用头文件的代码敲进去，因为此时还没有把gdal的头文件拷到项目目录里，所以提示错误，我把头文件拷进去之后，又添加了项目的主要代码。

![so](E:\ruangong\so.png)

 但是依旧不能运行。 将gdal的三种文件都移到项目目录里之后，还要添加一段代码

#pragma comment(lib, "gdal_i.lib")

之后我的项目还是一直出错，检查后发现代码中的trees.jpg我没有添加到项目文件夹里，添加之后程序就能正常运行了。

![fo](E:\ruangong\fo.png)

运行截图如上图所示，图片即老师给的那张。

![trees](E:\ruangong\trees.jpg)



