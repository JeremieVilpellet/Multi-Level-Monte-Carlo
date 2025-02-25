Monte Carlo methods are widely used in finance to approximate the value of financial products, particularly options. 
Within the framework of the Black-Scholes paradigm (and its extensions), options are valued as the expectation of their actualized pay-off under a specific probability space.

The value of an option depends on the functional of the path of one or several underlying financial instruments, such as, but not limited to, stock prices, exchange rates, or commodity prices. 
The dynamics of these underlying instruments are typically modeled using stochastic differential equations (SDEs), which often do not admit closed-form solutions.

In this context, numerical methods, and in particular Monte Carlo simulations, play a crucial role. 
The classical Monte Carlo method approximates the expectation of the payoff by simulating numerous paths of the underlying variables, which are discretized over time. 
While efficient and robust, this approach can be computationally expensive when high accuracy is required, as the error decreases slowly with the number of simulations.

In this project, we first present the classical Monte Carlo method and discuss its principles and limitations. 
We then introduce the Multi-Level Monte Carlo (MLMC) method, which improves the accuracy and efficiency of Monte Carlo simulations. 
MLMC achieves this by leveraging simulations at different levels of discretization of the SDE and efficiently combining the results. 
This approach significantly reduces computational cost while maintaining the desired level of precision. Afterward, we introduce another approach that establishes a connection between partial differential equations (PDEs) and the expectation of the pay-off. 
This method takes advantage of the fact that the pricing of options can often be reformulated as a PDE problem. Finally, we present our numerical results and offer interpretations based on our findings.
