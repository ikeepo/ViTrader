## cl用法介绍
cl: Compiler and Linker是由微软维护的C&C++编译器，类似gcc/g++;
/DWIN32: 定义宏WIN32, 其中/D是参数开头，WIN32是参数内容，宏用于预编译阶段的条件编译;
/I: 告诉编译器去哪里找头文件；主要用于指定外部库的头文件，因为其一般不在默认目录；
源文件相对路径：可以有任意数量，可以使用通配符，不能指定文件夹作为源文件；
/link: 用于将链接器选项和编译器选项分开，/link后面的参数会传递给链接器；
/LIBPATH：用于指定链接器搜索库文件的目录，参数是目录不同于源文件是文件，选项不区分大小写；并不是所有的链接器选项都需要:输入参数；
库文件：头文件.h;源文件.cpp；库存文件,静态库.lib .a，动态库.dll .so .dylib；
链接器也可以直接给定库文件的具体路径，而不是先给目录再给文件名；但是编译器只能直接给路径，而不能先给目录再给文件名；
动态链接库是执行环节使用，因此要求要位于可执行文件的搜索路径中，搜索路径包括：
1. 可执行文件所在目录；
2. 当前工作目录（并不会递归查找子目录）
3. 系统目录
4. 环境变量PATH指定的目录
/OUT:name:生成的可执行文件名，不指定则默认为源文件名；