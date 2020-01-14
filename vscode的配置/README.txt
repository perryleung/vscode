0、安装vscode，安装中文插件chinese
1、放到C盘绝对路径并添加其中的bin到环境变量
2、将配置文件放在工作目录下
3、在工作目录下新建一个“build”文件夹
4、下载插件clang command adaptor，安装LLVM-9.0.0-win64，并在设置中的Clang: Executable添加自己安装的路径下：D:\Program Files\LLVM\bin\clang.exe
5、安装cmake，安装插件cmake和cmakeTools，要用cmake list，在设置中的cmake tool中的mingw64设置为c盘的那个：c:/mingw64
6、安装插件code runner，是一个不经过调试的代码运行插件，按 ctrl + alt + n 运行
7、安装git，参考网址：https://blog.csdn.net/jingtingfengguo/article/details/51892864
8、setting.json
{
    "workbench.iconTheme": "material-icon-theme",
    "files.autoSave": "afterDelay",
    "editor.fontSize": 19,
    "editor.wordWrap": "on",
    "editor.formatOnType":true,
    "clang.executable": "D:\\Program Files\\LLVM\\bin\\clang.exe",
    "cmake.mingwSearchDirs": [
        "C:\\mingw64"
    ]
}
9、安装插件：Icon Fonts、Material Icon Theme、Prettier-Code formatter