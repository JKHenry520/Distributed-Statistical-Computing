# 实例分析：用 Spark 进行二分类学习


## 准备知识

* 二分类学习
* Spark





我们看到数据集一共有 27 个变量,前三个变量分别为 URL 地址,该页面在 StumbleUpon 的 ID,该页 面原始的文本内容,前两个在分析时用于标记网页,可以不考虑,第三个变量由于是文本数据,为了简 单期间,本文也不考虑文本数据。于是接下来要使用的变量为 4-27.我们对数据做如下处理。


### 训练逻辑回归模型



##结果分析 
将各个模型的训练结果列表如下:



## Spark 源代码

```
// 类别+标准化

// 训练分类模型
println(f"${svmModelScaledCats.getClass.getSimpleName}\nAccuracy:${svmAccuracyScaledCats * 100}%2.4f% %\nArea under PR: ${svmPrCats * 100.0}%2.4f%%\nArea under ROC: ${svmRocCats * 100.0}%2.4f%%")
```

	
（感谢北京大学刘智彬提供素材和案例。）