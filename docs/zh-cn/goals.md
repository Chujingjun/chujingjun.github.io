# 目标  

AI Matrix是一个测试AI软件框架和硬件平台的标准。它旨在为用户提供一个测量不同AI软件和硬件的方法并且比较它们对好坏。它帮助用户了解影响AI硬件性能的因素并帮助用户改进硬件设计。  

![img](./structure.jpg)  
AI Matrix包含四类测试：微测试，层测试，完整测试，和合成测试。测试粒度逐渐增加。微测试着重于AI硬件计算中重要的GEMM计算，层测试着重于评价神经网络里面的每一层，完整测试着重于评价不同应用领域的完整模型。大部分应用是基于Tensorflow，小部分应用是基于caffe。Tensorflow是AI应用领域最重要的软件框架之一，在阿里巴巴内部广泛应用。Caffe是AI软件框架的先行者，有很多模型还是基于caffe框架。因为资源有限，我们只收集了基于这两个软件框架的应用，但是在未来我们会扩展到其他软件框架。  