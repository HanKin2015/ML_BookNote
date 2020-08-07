[TOC]
# 数据分析（EDA）学习总结

参考：https://mp.weixin.qq.com/s/DWUmup4P_tdYWaK3buK72w

## 0、简介
探索性数据分析（Exploratory Data Analysis，EDA）是一种探索数据的结构和规律的一种数据分析方法。
- 对数据进行清洗
- 对数据进行描述（描述统计量，图表）
- 查看数据的分布
- 比较数据之间的关系
- 培养对数据的直觉
- 对数据进行总结

## 一、数据及背景
https://tianchi.aliyun.com/competition/entrance/531810/information（阿里天池-零基础入门NLP赛事）

## 二、实验环境
导入需要使用的包
```
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.model_selection import train_test_split
import seaborn as sns
import scipy
from collections import Counter
```

## 三、数据探索
首先，利用Pandas对数据进行读取。
```
df_train = pd.read_csv(train_path, sep='\t')
df_test = pd.read_csv(test_path, sep='\t')
```
