(java:run)=
# 运行

参考：[Getting Started with Java](https://dev.java/learn/getting-started-with-java/)

## 常规操作

一般地，Java 代码运行分为如下步骤：

1. 在文本编辑器中编写 Java 代码文件（后缀一般为 `.java`）；
2. 使用 Java 编译器（`javac`）编译 `.java` 生成二进制文件（后缀一般为 `.class`，可被计算机理解的语言）；（此时有错误，被称为编译时错误）
3. 使用 `java` 命令运行代码。（此时有错误，被称为运行时错误）


```java
public class MyFirstClass {
    
    public static void main(String... args) {
        System.out.println("Hello, World!");
    }
}
```