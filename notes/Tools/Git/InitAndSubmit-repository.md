# 创建版本库（仓库）
repository是一个目录，该目录下所有文件的变动都可以被git跟踪并记录，以便将来查看或还原。

## 命令解释
`mkdir`：创建目录
`cd`：跳转到指定目录
`pwd`：显示当前目录
is -ah：查看隐藏目录

为避免遇到莫名其妙的问题，路径不能包含中文。

## 初始化仓库 initialize repository
在要初始化的目录下：`git init`

## 一些注意事项
- git只能知道纯文本文件的具体改动，类似图片、Word，就只能知道它从100kb变成了120kb。

- 纯本文文件建议使用utf-8编码。

- 记事本会在纯文本文件开头加一个0xefbbbf，建议使用其他文本编辑器。

## 将文件添加到本地git repository
比如我们要添加一个readme.md文件到git仓库：
`git add readme.md`

执行上面的代码如果没有任何显示就说明执行成功了。

## 将改动提交到云git repository
`git commit -m "description"`

description是改动说明。

