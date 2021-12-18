# 安装

下面以 Java JDK 17 为例。

```{tab} Windows
直接下载 [Java JDK](http://www.oracle.com/technetwork/java/javase/downloads/index.html) Windows 版本，并安装。
```

````{tab} Ubuntu
终端安装：

```sh
sudo apt install openjdk-17-jre-headless
```
````

测试是否安装成功：

````{tab} Windows
```sh
java --list-modules | findstr "jdk.jshell"
```
````

````{tab} Ubuntu
```sh
java --list-modules | grep "jdk.jshell"
```
````

两者都应该输出 `jdk.jshell@`，后面是你的 Java 版本。

安装 IJava 的步骤见：[IJava README](https://daobook.github.io/IJava/README.html)。
