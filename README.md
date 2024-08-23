# 安装¶
## 安装PaddlePaddle¶
如果您没有基础的Python运行环境，请参考运行环境准备。

您的机器安装的是CUDA 11，请运行以下命令安装
~~~
pip install paddlepaddle-gpu
~~~
您的机器是CPU，请运行以下命令安装
~~~
pip install paddlepaddle
~~~
更多的版本需求，请参照飞桨官网安装文档中的说明进行操作。

## 安装PaddleOCR whl包¶
~~~
pip install paddleocr
~~~
对于Windows环境用户：直接通过pip安装的shapely库可能出现[winRrror 126] 找不到指定模块的问题。建议从这里下载shapely安装包完成安装。