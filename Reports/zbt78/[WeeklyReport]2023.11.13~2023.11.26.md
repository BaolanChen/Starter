### 姓名

周波涛

### 开发中的快乐开源任务

复数数据类型扩展

### 本双周工作

1. **调研其他算子**

  - cumpord的实现

2. **调研norm**

  复数类型在进行norm计算时，使用的是复数的模，所以在正向计算时，得到的结果是个实数，与其他算子略有不同。

$z=\sqrt{x^{2}+y^{2}}$

3. 复习复数的基本运算，学习复数求导过程

4. 提了一个文档修复任务的pr

5. 问题

  - 尚未理清norm与p_norm之间的关系



### 未来双周计划

1. 完成norm算子正向传播。

2. 完成norm算子p=2情况下的反向传播来验证自己对反向传播的理解是否正确。
