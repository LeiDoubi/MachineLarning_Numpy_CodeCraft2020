# 脚本使用说明

使用`convert.py`脚本即可自动将
基于`core`的多文件程序转换成单文件程序，
以符合服务器的上传要求，
它将默认生成目标程序在`release/Main.py`处。

此外，上传服务器的程序原则上不应含有debug部分，
可单独使用`eval_prediction.py`进行评估，已内置一个混淆矩阵的实现。