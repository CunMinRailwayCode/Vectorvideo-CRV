# `CRVError002` _NameError_

在使用播放器播放出现 __未被定义的变量__ 的文件时，通常会出现这个错误。

该错误一般也称为NameError。

## 播放器应该如何显示此错误？

如果您正在构建自己的Vectorvideo CRV播放器，建议的错误提示是：

```
CRVError002：NameError位于line ~,
访问https://github.com/CunMinRailwayCode/Vectorvideo-CRV/edit/main/ErrorDoc/CRVError002.md查看更多。
（具体的错误行代码以及前一行代码）
```

## 我如何解决此错误？

要解决此错误，请您定义未声明的变量。

## 错误和正确示例：

__会__ 触发该错误的文件示例：

```
a

```

当使用播放器播放该文件示例时，会触发以下错误：

```
CRVError002：NameError位于line ~,
访问https://github.com/CunMinRailwayCode/Vectorvideo-CRV/edit/main/ErrorDoc/CRVError002.md查看更多。
a
^
未定义该变量
```

__不会__ 触发该错误的文件示例：

```
a = 0

```
