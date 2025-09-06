---
already_read: false
link: https://distill.pub/2017/momentum/
read_priority: 1
relevance: 0
source: null
tags:
- Deep_Learning
- Mathematics
- Model_evaluation
type: Content
upload_date: '2022-09-15'
---

https://distill.pub/2017/momentum/
## Summary

The content discusses the momentum optimization algorithm, which is used to accelerate gradient descent in machine learning. Here are the key points and takeaways:

1. **Introduction to Momentum**:
   - Momentum is often thought of as a way to dampen oscillations and speed up iterations in gradient descent.
   - It allows for a larger range of step sizes and creates its own oscillations.

2. **Gradient Descent Basics**:
   - Gradient descent is simple but slow, making small steps in the direction of the gradient.
   - It converges to a local minimum but can be slow, especially in regions with pathological curvature.

3. **Momentum Algorithm**:
   - Momentum introduces a short-term memory to gradient descent, using a parameter β to control the momentum.
   - The update rules for momentum are given, showing how it combines the current gradient with a fraction of the previous update.

4. **Convergence Analysis**:
   - The convergence of momentum is analyzed using a convex quadratic model.
   - The eigenvalues of the Hessian matrix (or a similar matrix) play a crucial role in determining the convergence rate.
   - The condition number (ratio of the largest to smallest eigenvalue) is a measure of how well gradient descent will perform.

5. **Optimal Parameters**:
   - Optimal step size (α) and momentum parameter (β) are derived to minimize the convergence rate.
   - The optimal parameters depend on the eigenvalues of the Hessian matrix.

6. **Example: Polynomial Regression**:
   - The analysis is applied to polynomial regression, showing how momentum accelerates convergence.
   - The eigenvectors of the design matrix correspond to different features, and momentum helps in correcting errors in these features.

7. **Stochastic Gradients**:
   - The analysis is extended to stochastic gradients, which are commonly used in practice.
   - The noise introduced by stochastic gradients is modeled as Gaussian noise, and its impact on convergence is analyzed.

8. **Limits of Momentum**:
   - The limits of momentum and other first-order optimization methods are discussed using a pathological function (Convex Rosenbrock).
   - It is shown that momentum and similar methods cannot converge faster than a certain rate on this function.

9. **Further Reading and Acknowledgments**:
   - The article suggests further reading on the topic and acknowledges contributions from various reviewers and collaborators.

Overall, the content provides a detailed analysis of the momentum algorithm, its convergence properties, and its limitations, using a combination of theoretical analysis and practical examples.
## Links

- [Some methods of speeding up the convergence of iteration methods](https://www.researchgate.net/profile/Boris_Polyak2/publication/243648538_Some_methods_of_speeding_up_the_convergence_of_iteration_methods/links/5666fa3808ae34c89a01fda1.pdf) : A paper discussing methods to accelerate the convergence of iterative methods, relevant to the discussion on momentum in optimization algorithms.
- [The Zen of Gradient Descent](http://blog.mrtz.org/2013/09/07/the-zen-of-gradient-descent.html) : A blog post discussing the principles and insights of gradient descent, which is a foundational topic for understanding momentum in optimization.
- [On the momentum term in gradient descent learning algorithms](https://pdfs.semanticscholar.org/735d/4220d5579cc6afe956d9f6ea501a96ae99e2.pdf) : A paper exploring the role of momentum in gradient descent learning algorithms, providing theoretical insights and practical applications.

## Topics

![](topics/Concept/Gradient%20Descent)

![](topics/Concept/Momentum)

![](topics/Concept/Convex%20Quadratic%20Model)

![](topics/Concept/Pathological%20Curvature)

![](topics/Concept/Condition%20Number)

![](topics/Concept/Eigenvalue%20Decomposition)

![](topics/Concept/Early%20Stopping)

![](topics/Concept/Stochastic%20Gradient%20Descent)