##### dll
```
    什么是dll?
    dll是动态链接库(Dynamic Link Library)

    什么是dll注入
    所谓DLL注入就是将一个DLL放进某个进程的地址空间里，让它成为那个进程的一部分。要实现DLL注入，首先需要打开目标进程。
    换句话说，dll注入就是在程序执行的时候，成为程序的一部分。

    dll注入需要什么?
    1.dll文件(例如c++)
    2.被注入的程序(例如游戏的进程)
    3.注入工具(如RemoteDLL，下载地址https://securityxploded.com/remotedll.php)

    dll注入的步骤?
    1.打开程序(启动某个游戏)
    2.打开注入工具，输入dll文件地址，找到要注入的程序
    3.进行注入

    注入工具是如何注入程序的？
    通过CreateRemoteThread、NTCreateThread等方法远程植入

```

