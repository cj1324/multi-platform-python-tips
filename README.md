如何编写跨平台的python代码
==========================

前言
----

+ 什么语言能跨平台
+ 什么语言不能跨平台
+ 你使用那种Python (PyPy IronPython,Jython)
+ Compatibility Tags for Built Distributions (425)
+ Pure Python/C Accelerator Module Compatibility Requirements (PEP 399)
+ Removing support for little used platforms (PEP 11)

路径和编码
----------

+ 文件名拼接方式
+ Unicode file name support for Windows NT (PEP 277)
+ 文件名国际化
+ 环境变量中编码
+ 打包文件问题
+ 文件名是否区分大小写
+ 路径硬编码
+ 临时文件的创建
+ 文件属性和权限
+ 使用符号链接
+ 相关的限制
  + 最大文件长度
  + 同时打开限制

依赖导入
--------

+ Python Virtual Environments (PEP 405)
+ 如何import
  + Imports: Multi-Line and Absolute/Relative (PEP 328)
  + Import on Case-Insensitive Platforms (PEP 235)
+ 标准库
  + 不都跨平台
  + 说了不算
  + 弃用 PEP 4
+ 第三方依赖质量

+ C/C++扩展模块
  + PEP 427
  + 兼容要求 PEP 399
  + 32bit or 64bit
+ subprocess - New process module (PEP 324)

平台特性
--------

+ Universal Newline Support (PEP 278)

无奈
----

+ A Logging System (PEP 282)
+ Warning Framework (PEP 230)

发布环节
--------

+ Using Distutils to Build Python (PEP 229)
+ Package Index and Metadata for Distutils (PEP 301)
+ Explicit bootstrapping of pip in Python installations (PEP 453)
+ Version Identification and Dependency Specification (PEP 440)
+ Module Version Numbers (PEP 396)
+ The "python" Command on Unix-Like Systems(PEP 394)
+ Python launcher for Windows (PEP 397)
