# ResNest
本代码是在作者代码(https://github.com/zhanghang1989/ResNeSt)基础上，删减目前用不到的代码部分，如RFConv2d卷积，torch.nn.Conv2d卷积的dilation参数.

本仓库代码：
1. 精简源代码中的卷积类型为torch.nnConv2d(dilation=1);
2. 添加与ResNet模块的类比注解；
3. 添加每层的输出维度。
