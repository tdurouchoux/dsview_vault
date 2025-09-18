---
already_read: false
link: https://distill.pub/2017/momentum/
read_priority: 1
relevance: 0
source: null
tags:
- Deep_Learning
- Mathematics
type: Content
upload_date: '2022-09-15'
---

https://distill.pub/2017/momentum/
## Summary

The content discusses the mathematical underpinnings of the momentum algorithm in optimization, particularly in the context of gradient descent. It begins by introducing the concept of momentum as a means to accelerate convergence and dampen oscillations in gradient descent. The author argues that momentum can be better understood by studying it on a convex quadratic model, which is simple enough to be analyzed in closed form yet rich enough to capture the local dynamics of real-world problems.

The article delves into the dynamics of gradient descent and momentum, explaining how momentum introduces a short-term memory to the gradient descent algorithm, which can lead to faster convergence. It discusses the optimal parameters for momentum and how they relate to the eigenvalues of the Hessian matrix. The author also explores the behavior of momentum in the presence of stochastic gradients, which is relevant in modern machine learning where exact gradients are often not available.

The content also touches on the limits of first-order optimization methods, including momentum, and discusses the "worst function in the world" which is designed to challenge these methods. The article concludes with a discussion on the broader implications of momentum and its potential for further research and optimization.

Key takeaways include the mathematical formulation of momentum, the conditions under which it converges, and its potential to accelerate convergence in optimization problems. The author also highlights the importance of understanding the underlying mathematics to appreciate the full potential of momentum and other optimization algorithms.
## Links

- [On the importance of initialization and momentum in deep learning](http://www.jmlr.org/proceedings/papers/v28/sutskever13.pdf) : This paper discusses the importance of initialization and momentum in deep learning, which is directly related to the topic of the provided content.
- [Some methods of speeding up the convergence of iteration methods](https://www.researchgate.net/profile/Boris_Polyak2/publication/243648538_Some_methods_of_speeding_up_the_convergence_of_iteration_methods/links/5666fa3808ae34c89a01fda1.pdf) : This paper discusses methods for speeding up the convergence of iteration methods, which is directly related to the topic of the provided content.
- [The Nth Power of a 2x2 Matrix](http://people.math.carleton.ca/~williams/papers/pdf/175.pdf) : This paper discusses the Nth power of a 2x2 matrix, which is directly related to the topic of the provided content.

## Topics

![[topics/Concept/Gradient Descent]]

![[topics/Concept/Condition Number]]

![[topics/Concept/Pathological Curvature]]

![[topics/Concept/Momentum]]

![[topics/Concept/Eigenvalue Decomposition]]

![[topics/Concept/Convex Rosenbrock Function]]

![[topics/Concept/Convex Quadratic Model]]

![[topics/Concept/Stochastic Gradient Descent]]