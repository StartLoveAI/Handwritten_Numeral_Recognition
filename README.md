# 项目

基于tensorflow+多种神经网络算法实现手写数字识别

# 说明

## 环境配置

```html
电脑环境：windows10

python3.6.5

第三方库：requirements.txt
```

## 数据集

共有7万张图片。其中6万张用于训练神经网络，1万张用于测试神经网络。

每张图片是一个28\*28像素点的0~9的手写数字图片。

黑底白字。黑底用0表示，白字用0~1之间的浮点数表示，越接近1，颜色越白。

[MNIST下载](http://yann.lecun.com/exdb/mnist/)

> 提示：项目中**已经包含数据集**，不需要你再下载！

## 仓库

本仓库包括以下：

- `MNIST_data`：里面包含下载号的`MNIST`手写体数据集；
- `requirements.txt`：第三方库；
- `tensorflow_self.py`：自实现的神经网络;
- `tensorflow_softmax.py`：`Tensorflow`实现的简单`Softmax`网络;
- `tensorflow_DNNsoftmax.py`：`Tensorflow`实现的`DNN Softmax`网络;
- `tensorflow_cnn.py`：`Tensorflow`实现的卷积神经网络

# 使用

请先配置`python`运行环境：
```html
pip install -r requirements.txt
```

运行程序：
```html
python tensorflow_self.py
or
pytho tensorflow_softmax.py
or
python tensorflow_DNNsoftmax.py
or
python tensorflow_cnn.py
```
请选择一个进行运行~







