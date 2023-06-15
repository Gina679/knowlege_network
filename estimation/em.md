推荐看这一篇https://blog.csdn.net/v_JULY_v/article/details/81708386， 我知道为什么mixture of gamma用em来估计，因为相当于第一步给定两个gamma的概率初值，在这个初值的条件下
去估计alpha，beta的值，然后再调整概率值，再去重新估计alpha，beta，这样一直循环下去，直到目标值不变为止。

r中有专门的函数https://rdrr.io/cran/mixtools/man/gammamixEM.html。 
