该项目非官方项目
The project is an unofficial project

该项目最初是为了应对目标运行环境中不存在smartctl所建立的
The project was initially established in response to the non-existence of smartctl in the target operating environment

项目来源
project origin : http://www.smartmontools.org

使用方法:
method of application:

将代码编译成动态库
Compile code into a shared library

include smartctl.h
link library

使用smartctl的参数调用smartctl_main
Use the parameter of smartctl call smartctl_main

随后解析smartRet全局变量
Global variables are then resolved smartRet
