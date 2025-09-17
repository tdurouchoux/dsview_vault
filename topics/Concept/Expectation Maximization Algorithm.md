---
type: Concept
---

The Expectation-Maximization (EM) algorithm is a iterative method used for finding maximum likelihood estimates of parameters in statistical models, particularly useful when the data has missing values or latent variables. In the context of Probabilistic Chess, the EM algorithm is used to calculate the expected value of moves by considering the probabilities of success and failure. This involves computing the score if a move succeeds and the score if it fails, then combining these scores weighted by their respective probabilities to determine the best move. This approach allows the AI to make decisions that account for the probabilistic nature of the game.