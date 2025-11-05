# cangjiehello

使用华为仓颉语言编写的 Hello World 程序

## 项目简介

这是一个使用华为仓颉（Cangjie）编程语言编写的简单 Hello World 程序。仓颉是华为开发的新一代编程语言。

## 文件结构

```
.
├── main.cj        # 主程序文件
├── cjpm.toml      # 项目配置文件
└── README.md      # 说明文档
```

## 运行要求

- 安装华为仓颉编译器（cjc）
- 仓颉开发工具包

## 构建和运行

1. 使用仓颉编译器编译程序：
```bash
cjc main.cj
```

2. 运行编译后的程序：
```bash
./main
```

或者使用仓颉包管理器：
```bash
cjpm build
cjpm run
```

## 代码说明

程序非常简单，只包含一个 `main()` 函数，使用 `println()` 函数输出 "Hello World"：

```cangjie
main() {
    println("Hello World")
}
```

## 预期输出

```
Hello World
```

## 关于仓颉语言

仓颉（Cangjie）是华为公司开发的新一代编程语言，旨在为鸿蒙生态系统提供高性能、安全可靠的开发体验。

## License

MIT