# lab2

陆子睦

PB20051150

## shell:

(本shell的“|”,  “>>”,  ">", "<"等符号前后需要用空格分隔)

本shell除了可以支持所有必做的内容之外，还实现了：

1. ^D 退出

2. alias 添加别名：

   如果只输入alias或alias -p，则显示所有别名

   alias ll=‘ls -l’

   alias path=pwd

   等可以实现添加别名，会被写入一个名为myalias的文件，之后输入ll，path等可以起到同名作用。
   
3. echo ~root 功能

   可以正确输出～后用户的家目录

由于只有一个文件，使用 g++ myshell.cpp -o myshell 编译，./myshell运行即可。

## strace:

gcc strace.c -o strace 编译

./strace （true等） 运行
