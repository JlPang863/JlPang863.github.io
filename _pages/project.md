Academic Projects
======


1. Cluster Resource Scheduling in Distributed Machine Learning (JSA 2022), Oct 2020 – Aug 2021.      
![avatar](/JlPang863/images/jsa2022.png)                   
**This work focuses on resource scheduling and pricing for distributed ML jobs at the edge to maximize total social welfare without any future information.**      
* Model and formulate the social welfare maximization problem into a mixed integer nonlinear program (MINLP). And reformulate it into a typical knapsack-type problem by introducing exponential number of variables.
* Design tailored price functions for resources based on market rules. And propose a heuristic algorithm for dynamically allocating resources for jobs tominimize average job completion time, corresponding to social welfare.
* Conduct rigorous theoretical analysis to prove that the proposed framework is truthful and computationally effcient meanwhile achieving a good approximation ratio in social welfare.
* Evaluation on a Kubernetes cluster shows the proposed algorithm achieves high resource effciency, and outperforms baselines more than 55%.

2. Clients Incentivizing in Federated Learning (ICDCS 2021), Mar 2020 – Sep 2020.   
![avatar](/JlPang863/images/icdcs2021.png)                
**This work studies the incentive mechanism design in federated learning through a procurement auction, and targets to achieve social cost minimization.** 
* Capture the distinct feature of FL jobs about training accuracy, and formulate the social cost minimization problem as an integer linear program (ILP).
* Design an auction framework to select heterogeneous clients to participate in while achieving a balance between communication and computation.
* Conduct rigorous theoretical analysis to prove that the proposed framework is truthful, individually rational, and computationally effcient meanwhile achieving a good approximation ratio in social cost.
* Evaluation based on PyTorch shows that the proposed framework reduces the social cost by up to 75% compared with baselines.



