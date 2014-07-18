frozen
======

#### css组件

### 工具配置

需要提前安装nodejs，npm，spm2.X，nico

参考http://aralejs.org/docs/installation.html

### 如何使用

1. `spm build`  生成dist中的frozen.css

2. ` cd  nico` 进入nico目录

3.  `make` 命令，这时可以看到在当前目录下生成了一个 _site 文件夹，index.html即是我们需要生成的文档页面
  或者使用 `cp ../dist/* _theme/static/css/` 和 `nico build`来替代
  
 4.  执行`nico server` ，开启本地服务，用来预览文档，调试，访问http://127.0.0.1:8000/
