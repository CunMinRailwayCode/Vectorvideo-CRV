# `CRVError001` _EndNewLineError_

在使用播放器播放文件末尾 __没有换行符__ 的文件时，通常会出现这个错误。

该错误一般也称为EndNewLineError。

## 播放器应该如何显示此错误？

如果您正在构建自己的Vectorvideo CRV播放器，建议的错误提示是：

```
CRVError001：EndNewLineError位于line ~,
访问https://github.com/CunMinRailwayCode/Vectorvideo-CRV/new/main查看更多。
（具体的错误行代码以及前一行代码）
```

## 我如何解决此错误？

要解决此错误，请您在文件末尾填上换行符。

## 为什么在文件的末尾需要换行符？

- 某些软件在处理末尾没有换行符的文件会出现错误；
- 使得文件看起来更加美观。

## 错误和正确示例：

__会__ 触发该错误的文件示例：

```
draw('point', size=1)
```

当使用播放器播放该文件示例时，会触发以下错误：

```
CRVError001：EndNewLineError位于line 1,
访问https://github.com/CunMinRailwayCode/Vectorvideo-CRV/new/main查看更多。
draw('point', size=1)
^~~~~
文件末尾没有换行符“/n”。
```

__不会__ 触发该错误的文件示例：

```
draw('point', size=1)

```
