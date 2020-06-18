# Interview_sum
This repo is to record the result of every interview I failed

6/15/2020
字节跳动游戏开发测试面试

初步结论：基础还是要多多复习，不仅仅是C++的STL，指针的用法，编译原理也很重要

CS32的link：https://ucsb-cs32.github.io/w19/lectures/

CS16的link：https://ucsb-cs16-m18.github.io/lectures/

自己的项目还是要更加了解，很多细枝末节就是体现技术的时候，比如monobehavior，其实每个脚本都用到了，但是自己敲代码的时候并没有思考作用是什么

以上两个链接每次面试之前务必过一遍

本次面试没有答上来的点：

1, Unity中的Monobehavior的作用：

  MonoBehaviour是Unity中所有脚本的基类，如果你使用JS的话，脚本会自动继承MonoBehaviour。如果使用C#的话，你需要显式继承MonoBehaviour
  
  这是我们控制GameObject的方法
  
  具体参见https://www.cnblogs.com/neverdie/p/Unity3D_Monobehaviour.html
  
  
2, C#中结构体和类的区别

  结构体是值类型，类是引用类型
  
  具体参见https://www.runoob.com/csharp/csharp-struct.html
  
  
3,  C++的编译原理，如iosteam的实现在哪里，文件的编译过程

  每个编译器有自己的对标准库的实现，头文件include的只是声明
  
  文件的编译过程具体见https://ucsb-cs16-m18.github.io/lectures/
  
  面试问到的“为何需要link”的答案应该是分别编译可以更加方便，不用每次牵一发而动全身，反正这是我在我知识范围内给出的理解了
  

4, 指针的一些基础用法

  具体见https://ucsb-cs16-m18.github.io/lectures/
  
5, 代码题，感觉考点还是对指针的灵活运用吧，是用char做字符替换，确实没有了解过，才疏学浅，学到了

  具体实现见 https://blog.csdn.net/weixin_30457551/article/details/95000669?utm_medium=distribute.pc_relevant_bbs_down.none-task-blog-baidujs-1.nonecase&depth_1-utm_source=distribute.pc_relevant_bbs_down.none-task-blog-baidujs-1.nonecase
  
  然后就是斐波那契数列的两种实现方式比较简单，不过递归方法的要注意溢出和边际条件，这个没有考虑好
  
  函数stack的默认大小是1MB
