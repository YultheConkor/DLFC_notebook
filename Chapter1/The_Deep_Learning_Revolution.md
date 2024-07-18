#### 1.2.1 Synthetic data

> This noise might arise from intrinsically *stochastic*(i.e. random) process such as radioactive decay but more typically is due to **there being sources of variability that are themselves unobserved.**

这句话道出了为什么在使用深度学习方法进行拟合时，需要考虑随机噪声。

因为这些噪声不仅仅是对于模式的学习是需要重要考虑的，更何况这些噪声是一种数据本身、模式本身不可观测的**性质**，使用有限的数据（所获取到的一定是有限数据，因世界各种事件很复杂，且充满不同的随机小概率事件，不可能将其全部包含）必然会带来预测的不准确，也即出现了噪声。

这也可以理解为，为什么在拟合的时候不能追求过拟合，因为有限的数据并不代表整体模式就是那样，即包含了噪声，过拟合说明将噪声也学到了，这就对于拟合数据所代表的那类问题的模式带来了负面影响。
