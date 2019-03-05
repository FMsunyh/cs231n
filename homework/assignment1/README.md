Details about this assignment can be found [on the course webpage](http://cs231n.github.io/), under Assignment #1 of Spring 2017.

## KNN
### L2距离实现
- 两层循环实现L2距离
- 一层循环L2距离计算，并用F范数与两个loop时的结果比较验证正确性
- 不使用循环实现L2

### 交叉验证
1. 将训练集分成5等分，同时观察不同的k下的分类精度
2. 执行5次kNN算法，将其中一份数据作为验证集，其他作为测试集，取测试集的精度
3. 取平均精度，画出k-精度图

结论：
可以看出，kNN的分类精度高也就30%，不实用。

最佳k咱们取10
