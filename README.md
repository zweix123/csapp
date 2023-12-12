# MIT 15-213/CSAPP Lab

+ Reference:
  + CSAPP
    + [Lab website](https://csapp.cs.cmu.edu/3e/labs.html): 官网说需要创建账号然后下载`for.tar`文件, 而实际上每个Lab后面的`Self-Study Handout`就是对应Lab的代码;

## Lab1: datalab

+ Reference:
  + [writeup pdf](https://csapp.cs.cmu.edu/3e/datalab.pdf)

+ Pre: 
  + 编译参数有`-m32`, 直接使用`make`会报错
    ```
    fatal error: bits/libc-header-start.h: No such file or directory
    #include <bits/libc-header-start.h>
    ```
    我的解决方案是:
    ```bash
    sudo apt -f install
    sudo apt update
    sudo apt-get intall gcc-multilib
    ```
