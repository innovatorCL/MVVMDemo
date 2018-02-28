这个 Demo 的结构思路：

XML： 绑定 ViewModel

Activity：初始化 ViewModel
              ||
              ||
ViewModel：驱动 M 层获取数据，转成 Observable，更新 V 层 
              ||
              ||
Model：通过 Retrofit 获取数据，再通过 Rxjava 转成需要的 Observable 数据

