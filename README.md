# ZOO-ADMM
Zeroth Order Online Alternating Direction Method of Multipliers (ZOO-ADMM)

We design and analyze a new zeroth-order online algorithm, namely, the zeroth-order online alternating direction method of multipliers (ZOO-ADMM), which enjoys dual advantages of being gradient-free operation and employing the ADMM to accommodate complex structured regularizers. Compared to the first-order gradient-based online algorithm, we show that ZOO-ADMM requires $\sqrt{d}$ times more iterations, leading to a convergence rate of $O(\sqrt{m}/\sqrt{T})$, where $m$ is the number of optimization variables, and $T$ is the number of iterations. To accelerate ZOO-ADMM, we propose two minibatch strategies: gradient sample averaging and observation averaging. We also demonstrate ZOO-ADMM to applications in signal processing, statistics, and machine learning.

See details in paper "Zeroth-Order Online Alternating Direction Method of Multipliers: Convergence Analysis and Applications", AISTATS, 2018

Authors: Sijia Liu, Jie Chen, Pin-Yu Chen, and Alfred O. Hero
