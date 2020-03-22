@[TOC] 本仓库用来学习rollup构建工具

### [文档地址](https://www.rollupjs.com/guide/tutorial/)

### 第一个输出指令
```bash
rollup src/main.js -f cjs
````

```
-f 选项（--output.format 的缩写）指定了所创建 bundle 的类型——这里是 CommonJS（在 Node.js 中运行）。由于没有指定输出文件，所以会直接打印在 stdout 中：
```

### 构建文件
```bash
rollup src/main.js -f cjs > bundle.js
```

### 使用配置文件rollup.config.js

### [使用插件](https://rollupjs.org/guide/en/#plugins)


