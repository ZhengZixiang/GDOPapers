# GDOPapers
Must-read papers and related resources on gradient descent and optimization in deep learning.

Suggestions about fixing errors or adding papers, repositories and other resources are welcomed!

深度学习中的梯度下降与优化领域值得一读的论文与相关资源集合。

欢迎修正错误以及新增论文、代码仓库与其他资源等建议！

## Papers & Methods
- Two Problems With Backpropagation and Other Steepest-Descent Learning Procedures for Networks (1986) [[paper]](https://www.researchgate.net/publication/243776424_Two_problems_with_backpropagation_and_other_steepest-descent_learning_procedures_for_networks)
- On The Momentum Term in Gradient Descent Learning Algorithms (Neural Networks 1999) [[paper]](http://www.columbia.edu/~nq6/publications/momentum.pdf) - ***Momentum***
- A Method for Unconstrained Convex Minimization Problem With The Rate of Convergence (1983) [[paper]](https://www.researchgate.net/publication/260365606_A_method_for_unconstrained_convex_minimization_problem_with_the_rate_of_convergence) - ***NAG***
- Adaptive Subgradient Methods for Online Learning and Stochastic Optimization (COLT 2010) [[paper]](https://www.researchgate.net/publication/220320677_Adaptive_Subgradient_Methods_for_Online_Learning_and_Stochastic_Optimization) - ***Adagrad***
- CSC231: Neural Networks for Machine Learning - Lecture 6a: Overview of mini-batch gradient descent	[[slide]](http://www.cs.toronto.edu/~tijmen/csc321/slides/lecture_slides_lec6.pdf) - ***RMSprop***
- ADADELTA: An Adaptive Learning Rate Method (CoRR 2012) [[paper]](https://arxiv.org/abs/1212.5701) - ***Adadelta***
- Adam: A Method for Stochastic Optimization (ICLR 2015) [[paper]](https://arxiv.org/abs/1412.6980) - ***Adam & AdaMax***
- Incorporating Nesterov Momentum into Adam (ICLR 2016 Workshop) [[paper]](https://openreview.net/forum?id=OM0jvwB8jIp57ZJjtNEZ&noteId=OM0jvwB8jIp57ZJjtNEZ) - ***Nadam***
- Adafactor: Adaptive Learning Rates with Sublinear Memory Cost (ICML 2018) [[paper]](http://proceedings.mlr.press/v80/shazeer18a.html)
- The Marginal Value of Adaptive Gradient Methods in Machine Learning (NIPS 2017) [[paper]](https://arxiv.org/abs/1705.08292)
- On the Convergence of Adam and Beyond (ICLR 2018) [[paper]](https://openreview.net/forum?id=ryQu7f-RZ) - ***AMSGrad***
- Decoupled Weight Decay Regularization (ICLR 2019) [[paper]](https://arxiv.org/abs/1711.05101) - ***AdamW***
- Adaptive Gradient Methods with Dynamic Bound of Learning Rate (ICLR 2019) [[paper]](https://openreview.net/forum?id=Bkg3g2R9FX)[[code]](https://github.com/Luolc/AdaBound)  - ***AdaBound***
- FRAGE: Frequency-Agnostic Word Representation (NeurIPS 2019) [[paper]](http://papers.nips.cc/paper/7408-frage-frequency-agnostic-word-representation)
- Large Batch Optimization for Deep Learning: Training BERT in 76 minutes (CoRR 2019) [[paper]](https://arxiv.org/abs/1904.00962) - ***LAMB***
- Lookahead Optimizer: k steps forward, 1 step back (CoRR 2019) [[paper]](https://arxiv.org/abs/1907.08610) - ***Lookahead***
- On the Variance of the Adaptive Learning Rate and Beyond (ICLR 2020 Under Review) [[paper]](https://arxiv.org/abs/1908.03265)[[code]](https://github.com/LiyuanLucasLiu/RAdam)[[A Zhihu Answer]](https://www.zhihu.com/question/340834465/answer/810512064) - ***RAdam***
- New Deep Learning Optimizer, Ranger: Synergistic Combination of RAdam + LookAhead for The Best of Both [[blog]](https://medium.com/@lessw/new-deep-learning-optimizer-ranger-synergistic-combination-of-radam-lookahead-for-the-best-of-2dc83f79a48d)[[code]](https://github.com/lessw2020/Ranger-Deep-Learning-Optimizer) - ***Ranger***
- An Adaptive and Momental Bound Method for Stochastic Learning (CoRR 2019) [[paper]](https://arxiv.org/abs/1910.12249)[[code]](https://github.com/lancopku/AdaMod) - ***AdaMod***

### Multi-Task Learning
- GradNorm: Gradient Normalization for Adaptive Loss Balancing in Deep Multitask Networks (ICML 2018) [[paper]](http://proceedings.mlr.press/v80/chen18a.html)

### Adversarial Training
- Explaining and Harnessing Adversarial Examples (ICLR 2015) [[paper]](https://arxiv.org/abs/1412.6572) - ***FGSM***
- Distributional Smoothing with Virtual Adversarial Training (ICLR 2016) [[paper]](https://arxiv.org/abs/1507.00677) - ***VAT***
- Adversarial Training Methods for Semi-Supervised Text Classification (ICLR 2017) [[paper]](https://arxiv.org/abs/1605.07725) - ***FGM***
- Towards Deep Learning Models Resistant to Adversarial Attacks (ICLR 2018) [[paper]](https://arxiv.org/abs/1706.06083) - ***PGD***
- Adversarial Training for Free! (NeurIPS 2019) [[paper]](https://arxiv.org/abs/1904.12843)[[code]](https://github.com/mahyarnajibi/FreeAdversarialTraining/) - ***FreeAT***
- You Only Propagate Once: Accelerating Adversarial Training via Maximal Principle (NeurIPS 2019) [[paper]](https://arxiv.org/abs/1905.00877)[[code]](https://github.com/a1600012888/YOPO-You-Only-Propagate-Once) - ***YOPO***
- FreeLB: Enhanced Adversarial Training for Language Understanding (CoRR 2019) [[paper]](https://arxiv.org/abs/1909.11764) - ***FreeLB***
- SMART: Robust and Efficient Fine-Tuning for Pre-trained Natural Language Models through Principled Regularized Optimization (CoRR 2019) [[paper]](https://arxiv.org/abs/1911.03437) - ***SMART***

## Survey
- An Overview of Gradient Descent Optimization Algorithms (CoRR 2016) [[paper]](https://arxiv.org/abs/1609.04747)

## Repository & Tool
- [lessw2020/Best-Deep-Learning-Optimizers](https://github.com/lessw2020/Best-Deep-Learning-Optimizers) - Collection of the latest, greatest, deep learning optimizers for PyTorch - ***DiffMod***
- [jettify/pytorch-optimizer](https://github.com/jettify/pytorch-optimizer)

## Blog Post
### Chinese Blog
- [科学空间 / “让Keras更酷一些！”：小众的自定义优化器](https://kexue.fm/archives/5879)
- [科学空间 / 用时间换取效果：Keras梯度累积优化器](https://kexue.fm/archives/6794)
- [科学空间 / Keras实现两个优化器：Lookahead和LazyOptimizer](https://kexue.fm/archives/6869)
- [LazyOptimizer的知乎回答](https://www.zhihu.com/question/265357659/answer/580469438)
- [科学空间 / 6个派生优化器的简单介绍及其实现](https://kexue.fm/archives/7094)
- [知乎回答 / 神经网络中 warmup 策略为什么有效；有什么理论解释么？](https://www.zhihu.com/question/338066667/answer/771252708)
- [香侬读 | Transformer中warm-up和LayerNorm的重要性探究](https://zhuanlan.zhihu.com/p/84614490)
- [【AI初识境】为了围剿SGD大家这些年想过的那十几招(从momentum到Adabound)](https://zhuanlan.zhihu.com/p/57860231)
- [【炼丹技巧】功守道：NLP中的对抗训练 + PyTorch实现](https://zhuanlan.zhihu.com/p/91269728)
- [一文搞懂NLP中的对抗训练](https://zhuanlan.zhihu.com/p/103593948?utm_source=wechat_session&utm_medium=social&utm_oi=56756566753280)
- [科学空间 / 对抗训练浅谈：意义、方法和思考（附Keras实现）](https://kexue.fm/archives/7234)
- [科学空间 / 泛化性乱弹：从随机噪声、梯度惩罚到虚拟对抗训练](https://kexue.fm/archives/7466)

### English Blog
- [AdamW and Super-convergence is now the fastest way to train neural nets](https://www.fast.ai/2018/07/02/adam-weight-decay/) [[Chinese translation version]](https://www.jiqizhixin.com/articles/2018-07-03-14)
