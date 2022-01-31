# 实验环境
python3.8 

pytorch1.8

算力租赁为极链AI云平台

# 数据集下载
MNIST数据集：直接使用pytorch的torchvision中的datasets库导入

Cifar10数据集：直接使用pytorch的torchvision中的datasets库导入

# 运行方式
直接在jupyter文档中运行

# 实验结果
### 实验一
实验一为BGD、SGD和mini-batch GD的特点对比试验，图表见报告

### 实验二 momentum、RMSprop、adagrad、adam四种优化器的对比实验

|  | loss | accuacy |
|-----|----|----|
| Momentum | 0.7478 | 84.06% |
| Adagrad | 0.0845 | 97.36% |
| RMSprop | 0.0672 | 97.79% |
| Adam | 0.0589 | 98.15% |

### 实验三 SGD with Momentum算法的参数调优实验
|| 调整前 | 调整后 |
|-----|-----|-----|
|准确率|84.06%|97.57%|

### 实验四 针对Adam算法在后期收敛效果不佳进行改进
![图片](https://user-images.githubusercontent.com/73414003/151736624-2078dbe8-0890-451a-b5b0-4cd4b16cfe6d.png)
