# PyTorch二分类
* 三种主要的全连接层、激活函数和loss function组合的方法，分别是：torch.nn.Linear+torch.sigmoid+torch.nn.BCELoss，torch.nn.Linear+BCEWithLogitsLoss和torch.nn.Linear（输出维度为2）+torch.nn.CrossEntropyLoss，后两个loss function分别集成了Sigmoid和Softmax
