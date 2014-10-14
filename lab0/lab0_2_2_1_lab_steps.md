
#### 2.2.1 开发OS实验的简单步骤

在校内OS FTP服务器上或在github网站[https://github.com/chyyuu/ucore_pub](https://github.com/chyyuu/ucore_pub）可下载我们提供的lab1~lab8实验软件和文档中，大致经过如下过程就可以完成使用。

1. 下载&解压软件包 例如执行：tar jxf lab1.tar.bz2
2. 进入各个OS实验工程目录 例如： cd lab1
3. 根据实验要求阅读源码并修改代码（用各种代码分析工具和文本编辑器）
4. 并编译源码 例如执行：make
5. 如编译不过则返回步骤3
6. 如编译通过则测试是否基本正确，例如执行：make grade
7. 如果实现基本正确（即看到步骤6的输出存在不是 OK的情况）则返回步骤3
8. 如果实现基本正确（即看到步骤6的输出都是 OK）则生成实验提交软件包，例如执行：make handin
9. 把生成的使用提交软件包和实验报告上传/email给助教和老师。
 
另外，可以通过”make qemu”让OS实验工程在qemu上运行；可以通过”make debug”或“make debug-nox “命令实现通过gdb远程调试 OS实验工程。