""" All results are based on the notebook are based on the paper in this repo """

In this project, we first present the classical Monte Carlo method and discuss its principles and limitations. 
We then introduce the Multi-Level Monte Carlo (MLMC) method, which improves the accuracy and efficiency of Monte Carlo simulations. 
MLMC achieves this by leveraging simulations at different levels of discretization of the SDE and efficiently combining the results. 
This approach significantly reduces computational cost while maintaining the desired level of precision. Afterward, we introduce another approach that establishes a connection between partial differential equations (PDEs) and the expectation of the pay-off. 
This method takes advantage of the fact that the pricing of options can often be reformulated as a PDE problem. Finally, we present our numerical results and offer interpretations based on our findings.
