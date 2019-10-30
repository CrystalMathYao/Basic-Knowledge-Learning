1.学习Linux终端命令的原因

Linux刚面世的时候并没有图形界面，所有的操作全靠命令完成，如磁盘操作、文件存取、目录操作、进程管理、文件权限设定等

并且在职场中，大量的服务器维护工作都是载远程通过SSH客户端来完成的，并没有图形界面，所有的维护工作都需要通过命令来完成

2.常用Linux命令的基本使用

![常用Linux命令](https://github.com/CrystalMathYao/Basic-Knowledge-Learning/blob/master/Linux入门基础知识/Figure/常用Linux命令.png)

3.自动补全

在敲出 文件/目录/命令的前几个字母之后，按下tab键，如果输入的没用歧义，系统会自动补全

4.Linux终端命令格式

command [-options] [parameter]

command表示命令名，相应功能的英文单词或单词的缩写；[-options]表示选项，可用来对命令进行控制，也可以省略；[parameter]表示传给命令的参数，可以是零个、一个或者多个；[]代表可选

5.查阅命令帮助信息

学习常用命令及常用选项的使用即可，工作中遇到问题可以借助网络搜索

Linux提供的两种查阅命令

command --help

显示command命令的帮助信息

man command

查阅command命令的使用手册，man是manual的缩写，是Linux提供的一个手册，包含了绝大部分的命令、函数的详细使用说明

