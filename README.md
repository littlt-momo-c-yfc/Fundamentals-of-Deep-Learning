# Fundamentals-of-Deep-Learning
# 从python到跑通一些简单的神经网络的学习路线的分享  
## 1、Python基础学习  
- 建议哔哩哔哩的[黑马程序员][python教程]（直接点击即可进入）  
>建议最少要学完面向对象编程（了解类的定义、继承等）  
## 2、pytorch学习  
### （1）pytorch环境配置：  
- 个人建议哔哩哔哩的[小土堆的pytorch环境配置教程][pytorch环境配置教程]（直接点击即可进入）  
>配置完虚拟环境后，我们主要是用PyCharm和vscode来进行编程，但是anaconda的jupter notebook也有时候会用到，具体的使用方法自己去网上寻找。 
### （2）pytorch的基础学习：  
- 还是建议[小土堆的教程][pytorch基础]（直接点击即可进入）  
>虽然这个教程的内容不多，但是基本上的深度学习入门的东西都提及了，其他更多的东西可以到下面在跑简单的网络的时候学习，因为在练习中学习更快，那时候可以边学习，边补习自己欠缺的基础。
## 3、简单神经网络的学习  
### （1）神经网络基础  
- 理论学习推荐网易云课堂（章节一，课时2）：https://d.study.163.com/NgMfW  （需要购买 0.1元，我个人认为很值）  
> 这个课吧就是感觉讲的太多了，嗯........ 就是什么都讲，自己选择吧，也可以去听别的理论教程，反正前期基本的理论还是要知道的。
- 代码练习
```  
lin_reg.ipynb  
```    
> 代码练习只有线性回归的，其他的感兴趣的话可以自己去找找。而且写的代码是在jupter note book上写的，如果上面配置好了环境，anaconda自带这个软件（去网上自己学习使用的方法），PyCharm的专业版和VSCode（Jupter的插件）也有这也的功能，可以自己去B站找找，当然也不是非要用这个编辑器，其他的都可以跑这些代码。  
### （2）卷积神经网络（CNN）  
- 理论学习还是网易云课堂的那个（章节二，课时4）  
- 代码练习一：基础卷积神经网络的训练与测试  
```  
CNN.ipynb  
```  
- 代码练习二：使用CNN对CIFAR10完成分类任务  
```  
CNN_CIFAR10.ipynb
```  
### （3）VGG  
- 理论学习的话自己去CSDN或者是B站自己去找这方面的讲解，这里只给出代码练习  
- 代码练习：VGG16 对 CIFAR10 分类  
```  
VGG16.ipynb  
```  
### （4）ResNet18  
- 理论学习的话自己去找。  
- 代码练习：ResNet18 对 CIFAR10 分类  
```  
ResNet18.ipynb  
```  
  








## 声明：  
- 本人不对任何网络的准确性负责，仅供学习交流使用，请勿用于商业用途。  
- 这只是一部分内容的学习，想要真正的入门深度学习还得再走一段路
- 另外这个会在我有空的时候继续更新，也欢迎大家一起交流学习。


[python教程]: https://www.bilibili.com/video/BV1qW4y1a7fU/?share_source=copy_web&vd_source=d525d206ba3d00d6f0713e1fe790ebf9
[pytorch环境配置教程]: https://www.bilibili.com/video/BV1S5411X7FY/?share_source=copy_web&vd_source=d525d206ba3d00d6f0713e1fe790ebf9
[pytorch基础]: https://www.bilibili.com/video/BV1hE411t7RN/?share_source=copy_web&vd_source=d525d206ba3d00d6f0713e1fe790ebf9
