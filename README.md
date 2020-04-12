# transformers_pytorch
使用transformers库时最常见的用例，包含诸如问答、序列分类、命名实体识别等任务的用法

每项任务一般提供了两种机制：
* pipline
* 直接将模型与Tokenizer(PyTorch/TensorFlow)结合使用

## 安装transformers
* 直接安装
```
pip install transformers
```
* 或者在Colab上使用以下命令:
```
!pip install transformers
```
> 前提：Python 3.5+，PyTorch 1.0.0+ ，TensorFlow 2.0.0-rc1
> 建议使用谷歌Colab，可以用谷歌的GPU

## 测试是否使用GPU
```
import torch
torch.cuda.get_device_name(0)
```
