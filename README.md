## week 1
0.找到了一些新feature(gplearn inv)

1.确定了对相似度过高的feature的处理方式（reg,取相关性最高）

todo:完成1

## week 2
0.从kaggle notebook上下了一个50000的数据集用于测试

1.处理day1 0

2.对corr > 0.05的feature进行exp和log变化，选取变换后>原本*1.6且大于0.1的因子加入池子

3.找到corr > 0.8的因子 保留其中与target corr最大的因子 删除其余

todo:完成对105个类别的处理

## week 3
0.测试不同的label encoding效果 发现还是catboost好用= =

1、通过public baseline 寻找 有效的metric hacking 方式

todo:完成对105个类别的处理
