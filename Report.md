# **FEW SHOT LEARNING PAPERS**

## Introduction
Few shot learning applies to the cases where we have *very small amount* of data of some or all classes.
Since the **parameter space** of model is very huge, there would be hard shifts in the parameters and generalization to new unseen examples would be hard.

2. *  * for successful training, there should be a balance between the parameters set and the dataset size.

* * * Standard *optimization* techniques will result in extreme *overfitting*  the data.

We need to comeup with a way to combat this.

### **Solution**
To force generalization, there are mainly 2 approaches -- 
1. **Data-level approach**
2. **Parameter-level approach**

### **Data-level approach**
* Generate New data
* Use external data(both labelled and unlabelled)

As the name suggests, if you can't generalize well i.e. if there is an overfit, simply increase the data.This can be done using the above 2 mentioned techniques i.e. External data([Douze et. al 2017][L1]) and generating new data([Mehrotra et al 2017][L2]).

---
### **Parameter-level approach**
**basic idea** -- Put constrain on parameter space i.e.
1. Regularization and smart choice of function([Yoo et al 2017][L3])

### hybrid approach
[bharat and girshick][L4]


* **References**

* [A Bayesian Approach to Unsupervised One-Shot Learning of Object Categories](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.334.9081&rep=rep1&type=pdf)

* [Learning to Learn berkeley blog](http://bair.berkeley.edu/blog/2017/07/18/learning-to-learn/)

* [Matching networks blog](https://blog.acolyer.org/2017/01/03/matching-networks-for-one-shot-learning/)










[L1]: https://arxiv.org/pdf/1706.02332.pdf
[L2]: https://arxiv.org/pdf/1703.08033.pdf
[L3]: https://arxiv.org/pdf/1710.02277.pdf
[L4]: https://arxiv.org/pdf/1606.02819.pdf