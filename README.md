# CNN_Flower
Online courses in NTU AI lab. The first trial with CNN.

# 一些记录
- 登陆colab可以实现同时导入sklearn 和 keras 两个包 ，是连接到本地之后只能导入keras包 —— 成功下载了tensorflow 但是sklearn没有成功下载。
- 试图调整环境配置的一些尝试：
  - 在YouTube发现一个视频 [How to install TensorFlow and NumPy on Apple Silicon (M1)](https://www.youtube.com/watch?v=6W8pjnW65Q8) 操作过程中出现问题：python版本必须是3.8。
  - 安装pyenv和vitualenv，试图创建虚拟环境，修改虚拟环境中的python版本。安装pyenv必须用x86架构，因此重新下载了homebrew，并且命名为ibrew。完成pyenv下载，并且命名为ipyenv。参考网页链接：[Mac-M1安装pyenv教程](https://www.xiang007.com/2021/07/22/Mac-M1%E5%AE%89%E8%A3%85pyenv%E6%95%99%E7%A8%8B/) 以及 [M1芯片的Mac安装homebrew](https://blog.csdn.net/qq1808814025/article/details/112667458?spm=1001.2101.3001.6650.1&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7Edefault-1.opensearchhbase&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7Edefault-1.opensearchhbase)
  - 创建虚拟环境，修改虚拟环境中的python版本。参考网页链接：[使用pyenv和virtualenv搭建python虚拟环境实践总结](https://blog.csdn.net/eric_sunah/article/details/56289937)  注意⚠️：该操作步骤未实现。原因：ipyenv install 3.8.0，python下载失败。报错信息：```1 error generated.
make: *** [Modules/posixmodule.o] Error 1
make: *** Waiting for unfinished jobs....
1 warning generated.``` 
  - 等待解决中。。。
