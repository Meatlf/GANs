# GANs

![GANs结构图](https://img-blog.csdn.net/20180629195553877?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MTI3ODcyMA==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

## 对抗网络(Discriminator Network)

**Q**:如何理解对抗过程?

**A**:对抗过程简单来说就是一个判断真假的判别器，相当于一个二分类问题.

## 生成网络(Generative Network)

**Q**:生成网络的输出是什么?

**A**:生成网络的输出为假图片;

**Q**:如何理解生成网络的训练过程?

**A**:以生成网络输出的假图片通过对抗网络判断为真的概念为目的而更新生成器的参数,需要注意的是,这里不会更新判别器的参数.

## 参考资料

[1] [GANs入门系列之（二）用GAN生成MNIST数据集之pytorch实现](https://blog.csdn.net/weixin_41278720/article/details/80861284)