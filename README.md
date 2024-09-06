# PKU Compiler Course

编译器接受四个参数如：
```
compiler 模式 输入文件 -o 输出文件
```

例如，在 Docker 的实验环境中, 我们可以在项目的目录里执行:
```
make
build/compiler -koopa test/hello.c -o hello.koopa
```
将会输出 hello.c 的内容。