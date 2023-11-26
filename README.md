# -
保存着编译原理实验三的文件、TinyFinal是命令行版本的，Qt_TinyAnalyzor是QT版本的


## 命令行版本使用步骤如下：

使用visual C++ 6.0或Microsoft Visual Studio 2010 以上任何一个版本进行编译即可。

你只需要按以下步骤进行即可：

1. 使用visual C++ 6.0或Microsoft Visual Studio 2010 建立一个新项目，如名字为 tiny（win32控制台应用程序）。
2. 在附件选项中选择【空项目】
3. 在项目的文件列表中选择【源文件】，选择【添加】-->【现有项】，并选择tiny文件夹下的所有 C 程序
4. 在项目的文件列表中选择【头文件】，选择【添加】-->【现有项】，并选择tiny文件夹下的所有 h 程序
5. 编译该项目
6. 在该项目的文件夹找到【debug】文件夹，把该文件夹下的 TinyFinal.exe 复制到 某个 【位置】
7. 在程序【debug】文件夹中找到文件sample.tny，复制到上述相同【位置】。
8. 通过选择windows界面左下角的【开始】菜单进入【运行...】,并在出现的输入条中输入[cmd]回车。并让当前命令行的进入位置到【位置】
9. 在命令行状态下接着输入 TinyFinal sample回车，即可编译sample.tny程序，生成一个sample.tm的文件
