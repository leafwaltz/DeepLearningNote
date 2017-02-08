# DeepLearningNote
Deep Learning 学习笔记
## 2017/2/1 创建第一个神经网络
## 2017/2/3 关于tanh和sigmoid和softmax
<br>tanh相比sigmoid：</br>
<br>①输出与输入的关系能保持非线性单调上升和下降关系;</br>
<br>②该函数连续，可以微分求出函数关系，符合BP网络的梯度求解;</br>
<br>③具有非线性超平面(wtf?)，柔和光滑有利于优化搜索;</br>
<br>④对神经网络容错性好;</br>
<br>⑤比sigmoid延迟了饱和期.</br>
<br>对于softmax函数:</br>
<br>相当于多分类时的sigmoid.</br>
## 2017/2/5 避免梯度下降陷入局部极小值的方法
<br>http://sebastianruder.com/optimizing-gradient-descent/index.html#momentum</br>
## 2017/2/8 project1 预测自行车使用情况
