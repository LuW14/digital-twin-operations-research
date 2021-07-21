## [Content](#content)

<table>
<tr><td colspan="2"><a href="#related-research-papers-in-or">Related research papers in OR</a></td></tr>
<tr><td colspan="2">&emsp;<a href="#solving-problems-in-real-time">Solving problems in real-time</a></td></tr>
<tr>
	<td>&emsp;&emsp;<a href=#offline-simulation-online-application>Offline simulation online application</a></td>
	<td>&emsp;&emsp;<a href=#computational-resource>Computational resource utilization</a></td>
</tr>
<tr>
	<td>&emsp;&emsp;<a href=#multi-fidelity-approaches>Multi-fidelity approaches</a></td>
	<td>&emsp;&emsp;<a href=#metamodeling>Metamodeling</a></td>
</tr>
<tr>
	<td>&emsp;&emsp;<a href=#simulation-optimization>Simulation optimization</a></td>
	<td>&emsp;&emsp;<a href=#system-level-optimization>System-level optimization (interacton in an aggregated DT)</a></td>
	
</tr>
<tr>
	<td>&emsp;&emsp;<a href=#data-driven-decisions>Data-driven decisions</a></td>
	<td>&emsp;&emsp;<a href=#synchronization-frequency>Synchronization frequency</a></td>
<tr>
	<td>&emsp;&emsp;<a href=#applications>Applications</a></td>
</tr>
</table>

[Back to homepage](../papers4dtor.md)

## [Solving problems in Real-time](#content)

### [Offline simulation online application](#content)
1. **'Some tactical problems in digital simulation' for the next 10 years**. Journal of Simulation, 2016. [paper](https://link.springer.com/article/10.1057/jos.2015.22). *BL Nelson*.

2. **A simulation analytics approach to dynamic risk monitoring.** Proceedings of the 2016 Winter Simulation Conference, 2016. [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7822110). *Guangxin Jiang, L. Jeff Hong, Barry L. Nelson*.

3. **Simulation-based predictive analytics for dynamic queueing systems**. Proceedings of the 2017 Winter Simulation Conference, 2017. [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8247910). *Huiyin Ouyang, Barry L Nelson*.

4. **Offline Simulation Online Application: A New Framework of Simulation-Based Decision Making**. Asia-Pacific Journal of Operational Research, 2019. [paper](https://doi.org/10.1142/S0217595919400153).

> It is rarely used in making real-time decisions due to the long computation delay of executing simulation models. However, with the fast growth of computing capability, we have observed more and more works on reusing simulation efforts for repeated experiments with the help of data analytics tools, and the target of these works is to solve real-time decision problems.

> With the fast growth of computing capability and with more and more data analytics tools, there are more and more recent works considering how to use complex simulation models and experiments to solve real-time decision problems....In this paper we summarize these works to a unified framework, which uses the offline simulation results on applications where online decisions need to be made. We call it the offline- simulation-online-application (OSOA) framework. The key to linking the offline simulation and online application are predictive models.

> The OSOA framework, which treats simulation as a data generator, applies state-of-the-art analytics tools to build predictive models, and then uses the predictive models for real-time applications.

> further research directions about OSOA
> - Building new metamodeling techniques and theories in OSOA. As we have introduced in Sec. 2.1, the goal of metamodeling problems in the OSOA framework is different from that of classical metamodeling problems. In classical metamodeling problems, fitting accuracy is the most important criterion. However, in the OSOA framework, the metamodel (fitted surface) is used to make decisions, so the accuracy is not the only criterion. How to best support the decisions is the most important goal of the metamodeling in the OSOA framework. Therefore, building new metamodeling techniques and new theories under the OSOA framework are good research directions.
> - Treating OSOA as a feedback loop. In the OSOA framework, the metamodels are often used repeatedly (with different observed values of the covariates). Real data are often observed after the decisions are made. Based on the real data and the simulated data, the simulation models need to be updated to capture the features of the stochastic system, e.g., better calibrating the model parameters and reducing model misspecifications. Therefore, how to handle these feedback loops becomes another interesting research direction.
> - Dealing with high dimensional covariates. In many practical problems, the dimension of the covariates may be very high. For example in healthcare, a lot of information, such as the demographic information and gene information, may be collected for a patient. However, some diseases are only affected by a few of factors. That is, the effective dimension is low. In the OSOA framework, since we may repeat the simulation experiments and receive feedbacks regularly, we may utilize these information and some machine learning techniques to identify the effective dimensions. How to deal with high dimensional covariates and how to reduce dimensionality are interesting research directions in the OSOA framework.
> - Embedding SO algorithms in OSOA. There are many efficient SO algorithms proposed in last two decades. An interesting research direction is to embed these algorithms to solve SO problems with covariates. Note that, in the OSOA framework, the problems of SO with covariates may have both high-dimensional decision variables and high-dimensional covariates. When designing the SO algorithms, these features need to be considered.

5. **Plan Online, Learn Offline: Efficient Learning and Exploration via Model-Based Control**. Working paper, 2019. [paper](https://arxiv.org/abs/1811.01848). *Kendall Lowrey, Aravind Rajeswaran, Sham Kakade, Emanuel Todorov, Igor Mordatch*

> We propose a plan online and learn offline (POLO) framework for the setting where an agent, with an internal model, needs to continually act and learn in the world. Our work builds on the synergistic relationship between local model-based control, global value function learning, and exploration.

6. **Online Risk Monitoring Using Offline Simulation**. INFORMS Journal on Computing, 2020. [paper](https://doi.org/10.1287/ijoc.2019.0892). *Guangxin Jiang, L. Jeff Hong, Barry L. Nelson*. 

7. **Offline–Online Approximate Dynamic Programming for Dynamic Vehicle Routing with Stochastic Requests**. Transportation Science, 2019. [paper](https://doi.org/10.1287/ trsc.2017.0767). *Marlin W. Ulmer, Justin C. Goodson, Dirk C. Mattfeld, Marco Hennig*.

### [Computational resource](#content)
1. **Analytics with digital-twinning: A decision support system for maintaining a resilient port**. Decision Support Systems, 2021. [paper](https://doi.org/10.1016/j.dss.2021.113496). *Chenhao Zhou, Jie Xu, Elise Miller-Hooks, Weiwen Zhou, Chun-Hung Chen, Loo
Hay Lee, Ek Peng Chew, Haobin Li*. <font color=purple>@TAG real-time optimization; synchronization fidelity</font>

> Because digital twin runs are time-consuming, there are important <font color=green>trade-offs between making enough runs for accurate estimates and computation time</font>. For real-world size applications, especially when used to support real-time operations, efficient run designs with good statistical accuracy are needed. It is likely that with insufficient runs to guarantee statistical accuracy the DSS will select a sub-optimal c for a given scenario and, simultaneously, develop an incorrect (reduced) resilience assessment. To tackle this computational challenge, the proposed DSS integrates a state-of-the-art simulation-optimization method known as optimal computing budget allocation (OCBA) (Chen and Lee [12,13]) to determine the number of simulations to be executed for each candidate recovery action under a given simulation budget.

2. **Fully Sequential Procedures for Large-Scale Ranking-and-Selection Problems in Parallel Computing Environments**. OR, 2015. [paper](http://dx.doi.org/10.1287/opre.2015.1413). *Jun Luo, L. Jeff Hong, Barry L. Nelson, Yang Wu*

> In this paper, we propose two types of fully sequential procedures that can be used in parallel computing environments. We call them vector-filling procedures and asymptotic parallel selection procedures, respectively. Extensive numerical experiments show that the proposed procedures can take advantage of multiple parallel processors and solve large-scale R&S problems.

3. **Knockout-Tournament Procedures for Large-Scale Ranking and Selection in Parallel Computing Environments**. Working paper, 2020. [paper](https://www.researchgate.net/publication/339200267_Knockout-Tournament_Procedures_for_Large-Scale_Ranking_and_Selection_in_Parallel_Computing_Environments). *Ying Zhong, L. Jeff Hong*

> When using parallel computing environments, we argue that the existing stage-wise procedures and fully-sequential procedures are both inefficient, and we need a new framework that takes a holistic view at the total computation time, including the time spent on simulation, comparison, and communication. Stage-wise procedures were first proposed to handle physical experiments, and fully-sequential procedures were more suitable to handle computer experiments generated in a single processor. Using them directly in parallel computing environments for large-scale problems will cause either too many simulation observations or too many comparisons or too many communications among the processors. In this paper, we propose new R&S procedures that consider the total computation time and work well in parallel computing environments, especially commercial clouds.

> We show that no matter whether the variances of the alternatives are known or not, our procedures can theoretically achieve the lowest growth rate on the expected total sample size with respect to the number of alternatives and thus are optimal in rate. 

4. **Speeding Up Paulson’s Procedure for Large-Scale Problems Using Parallel Computing**. INFORMS Journal on Computing, 2021. [paper](https://doi.org/10.1287/ijoc.2020.1054)

5. **Parallel computational optimization in operations research: A new integrative framework, literature review and research directions**. EJOR, 2020. [paper](https://doi.org/10.1016/j.ejor.2019.11.033). *Guido Schryen*.

6. **Distributed simulation: state-of-the-art and potential for operational research**. EJOR, 2019. [paper](https://doi.org/10.1016/j.ejor.2018.04.032). *Simon J. E. Taylor*.

### [Multi-fidelity approaches](#content)

1. **Survey of multi-fidelity methods in uncertainty propagation, inference, and optimization**. SIAM REVIEW, 2018. [paper](https://epubs.siam.org/doi/pdf/10.1137/16M1082469). *Benjamin Peherstorfer, Karen Willcox, Max Gunzburger*

> This work surveys multi-fidelity methods that accelerate the solution of outer-loop applications by combining high-fidelity and low-fidelity model evaluations, where the low-fidelity evaluations arise from an explicit low-fidelity model (e.g., a simplified physics approximation, a reduced model, a data-fit surrogate) that approximates the same output quantity as the high-fidelity model.

2. **Multi-fidelity simulation optimization for airline disruption management**. Proceedings of the 2018 Winter Simulation Conference, 2018. [paper](https://ieeexplore.ieee.org/document/8632329). *Luke Rhodes-Leader, David J. Worthington, Barry L. Nelson, Bhakti Stephan Onggo*. <font color=purple>@TAG real-time optimization; synchronization fidelity</font>

> This paper presents a method for the aircraft recovery problem that uses multi-fidelity modeling including a trust region simulation optimization algorithm to mitigate the computational costs of using high-fidelity simulations with its benefits for providing good estimates of the true performance.

> <font color=green>@RQ The contribution of this paper is a method to balance the need to use a high-fidelity simulation model to estimate the performance of a recovery option with the computational difficulties associated with simulation in this context. These difficulties include a large and complicated solution space and short computation time constraints.</font>

> In each case, 2000 simulation replications were allowed for the optimisation procedure, with $nd = 5$ replications at each design point, and 20 replications used for the acceptance tests. (The solution times are not reported.)

> Future work will include considering how the repeated nature of the problem could be exploited to improve both the models and the optimization process in a symbiotic manner.

### [Metamodeling](#content)
1. **Metamodel-Based Simulation Optimization**. Handbook in OR & MS, 2006. [paper](https://doi.org/10.1016/S0927-0507(06)13018-2). *Russell R. Barton, Martin Meckesheimer*

> A metamodel, or model of the simulation model, simplifies the simulation optimization in two ways: the metamodel response is deterministic rather than stochastic, and the run times are generally much shorter than the original simulation. 

2. **Kriging metamodeling in simulation: A review**. European Journal of Operational Research, 2009. [paper](https://doi.org/10.1016/j.ejor.2007.10.013). *Jack P.C.Kleijnen*.

3. **Better simulation metamodeling: The why, what, and how of stochastic kriging**. Proceedings of the 2009 Winter Simulation Conference, 2009. [paper](https:/
/ieeexplore.ieee.org/document/5429320). *Jeremy Staum*.

4. **Stochastic Kriging for Simulation Metamodeling**. OR, 2010. [paper](https://doi.org/10.1287/opre.1090.0754). *Bruce Ankenman, Barry L. Nelson, Jeremy Staum*.

5. **Multilevel Monte Carlo Metamodeling**. OR, 2017. [paper](https://doi.org/10.1287/opre.2017.1607). *Imry Rosenbaum, Jeremy Staum*

6. **Gaussian Markov Random Fields for Discrete Optimization via Simulation: Framework and Algorithms**. OR, 2019. [paper](https://doi.org/10.1287/opre.2018.1778). *Peter L. Salemi, Eunhye Song, Barry L. Nelson, Jeremy Staum*

7. **Generalized Integrated Brownian Fields for Simulation Metamodeling**. OR, 2019. [paper](https://doi.org/10.1287/opre.2018.1804). *Peter Salemi, Jeremy Staum, Barry L. Nelson*.

### [Simulation optimization](#content)
1. **Optimization via Simulation Over Discrete Decision Variables.** In INFORMS TutORials in Operations Research, 2010. [paper](https://doi.org/10.1287/educ.1100.0069). *Barry L. Nelson*

2. **History of seeking better solutions, AKA simulation optimization**. Proceedings of the 2017 Winter Simulation Conference, 2017. [paper](http://simulation.su/uploads/files/default/2017-fu-henderson.pdf). *Michael C. Fu, Shane G. Henderson*

3. **An Adaptive Hyperbox Algorithm for High-Dimensional Discrete Optimization via Simulation Problems**. NFORMS Journal on Computing, 2013. [paper](https://doi.org/10.1287/ijoc.1110.0481). *Jie Xu, Barry L. Nelson, L. Jeff Hong*

4. **Faster Kriging: Facing High-Dimensional Simulators**. OR, 2020. [paper](https://doi.org/10.1287/opre.2019.1860). *Xuefei Lu, Alessandro Rudi, Emanuele Borgonovo, Lorenzo Rosasco*.

> Kriging is one of the most widely used emulation methods in simulation. How- ever, memory and time requirements potentially hinder its application to data sets generated by high-dimensional simulators. We borrow from the machine learning literature to propose a new algorithmic implementation of kriging that, while preserving prediction accuracy, notably reduces time and memory requirements. The theoretical and computational foundations of the algorithm are provided. The work then reports results of extensive numerical experiments to compare the performance of the proposed algorithm against current kriging implementations, on simulators of increasing dimensionality. Findings show notable savings in time and memory requirements that allow one to handle inputs across more that 10,000 dimensions.

5. **Rapid Discrete Optimization via Simulation with Gaussian Markov Random Fields**. INFORMS Journal on Computing, 2020. [paper](https://doi.org/10.1287/ijoc.2020.0971). *Mark Semelhago, Barry L. Nelson, Eunhye Song, Andreas Wächter*

> In our setting, the output is stochastic, and the number of feasible solutions is huge, but individual replications of a solution may be relatively cheap compared with a deterministic computer experiment. In combination, the computational overhead for inference is no longer negligible compared with the simulation cost.

> Our primary contribution is to greatly extend the reach of GMRF-based optimization by dramatically reducing the computational cost of inference.

### [System level optimization](#content)
1. **A Real-Time Multiobjective Optimization Algorithm for Discovering Driving Strategies**. TS, 2018. [paper](https://doi.org/10.1287/trsc.2018.0872). *Erik Dovgan, Matjaž Gams, Bogdan Filipič*. 

> This paper presents a real-time multiobjective optimization algorithm for discovering driving strategies that uses a black-box driving simulator to search for driving strategies on a given route and minimizes the traveling time and the fuel consumption.

> During the driving prediction, the computational time is checked several times. When the computational time is going to exceed the available computational time, the driving prediction stops, that is, the algorithm jumps to Line 27 and continues with the selection of the best control action for the next step. The computational time available for the selection of the control action for the next step is equal to the traveling time of the current step.

> A particular challenge would be the deployment of the algorithm in a real-life vehicle and its evaluation on a real route, where real-life neighboring vehicles and unexpected events have to be considered.

### [Data-driven decisions](#content)
1. **Data-Driven Optimization: A Reproducing Kernel Hilbert Space Approach.** Operations Research, 2021. [paper](https://pubsonline.informs.org/doi/pdf/10.1287/opre.2020.2069). *Dimitris Bertsimas, Nihal Koduri* 

2.  **Confidence Intervals for Data-Driven Inventory Policies with Demand Censoring**. Operations Research, 2020. [paper](https://doi.org/10.1287/opre.2019.1883). *Gah-Yi Ban*

3. **Robust Data-Driven Vehicle Routing with Time Windows**. Operations Research, 2021. [paper](https://doi.org/10.1287/opre.2020.2043). *Yu Zhang, Zhenzhen Zhang, Andrew Lim, Melvyn Sim*

4. **Online Optimization—An Introduction**. INFORMS TutORials in Operations Research, 2010. [paper](https://doi.org/10.1287/educ.1100.0072). *Patrick Jaillet, Michael R. Wagner.*

> An online problem is one where the problem data are revealed incrementally. 
> - In the sequential model, when a request is revealed, a decision by the online algorithm must be made before the next request is revealed. 
> - In the dynamic model, the requests are revealed dynamically over time, irrespective of the actions of the online algorithm. The time at which a request is revealed is (usually) denoted as the request’s release date.

5. **Data-Driven Appointment-Scheduling Under Uncertainty: The Case of an Infusion Unit in a Cancer Center.**. Management Science, 2020. [paper](https://doi.org/10.1287/mnsc.2018.3218). *Avishai Mandelbaum, Petar Momčilović, Nikolaos Trichakis, Sarah Kadish, Ryan Leib, Craig A. Bunnell*

> In reality, there exists a significant discrepancy between the planned and actual operations. .. This mismatch can be traced back to the aforementioned assumptions of deterministic service times and punctuality - assumptions routinely made in appointment scheduling implementations, which are capable of handling large-scale operations that involve hundreds of servers and hundreds of customers.

> It (Actual Durations of Infusion Treatments Scheduled for Two Hours) was compiled using high-resolution data from a real-time locating system (RTLS) deployed at DFCI.

> RTLS data from the eight clinical floors were “synchronized” with appointment book data, as well as data from the in-house pharmacy. Having access to all these logs enables us to accurately determine not only locations of patients but also the activities in which they are engaged.

6. **Online Vehicle Routing: The Edge of Optimization in Large-Scale Applications**. OR, 2018. [paper](https://doi.org/10.1287/opre.2018.1763). *Dimitris Bertsimas, Patrick Jaillet, Sébastien Martin*.

> Challenges. With the emergence of ride-sharing companies that offer transportation on demand at a large scale and the increasing availability of corresponding demand data sets, new challenges arise to develop routing optimization algorithms that can solve massive problems in real time. 

> In this paper, we develop an optimization framework, coupled with a novel and generalizable backbone algorithm, that allows us to dispatch in real time thousands of taxis serving more than 25,000 customers per hour.

> With the recent interest in real-time ride sharing, several large-scale online decision systems for taxi scheduling have been proposed and implemented although these applications focus more on managing large-scale decision systems than optimizing vehicle actions. 

> Several strategies have been proposed for dynamic vehicle routing... Unfortunately, these exact algorithms rarely scale past a few dozens or hundreds of customers and vehicles, depending on the application. We use such formulations in this paper although applying them on problems with tens of thousands of customers and thousands of vehicles.

> A classical way to solve these static vehicle-routing problems at a larger scale is the use of heuristics... Unfortunately, these heuristics are usually special purposed and have to be adapted to each particular new problem... In this paper, we were not able to successfully apply any of these algorithms because of the size of our problem and the very small time available for computations.

7. **Online Algorithms for Multilevel Aggregation**. OR, 2020. [paper](https://doi.org/10.1287/opre.2019.1847). 

> In practice, however, packet aggregation decisions must be done on the fly, in real time. This gives rise to the online version of TCP-AP, in which an online algorithm receives information about messages as they are released over time. At each time step, this algorithm needs to decide whether to transmit the packet with pending messages or not, without any information about future message releases.

8. **The Myopic Property in Decision Models**. Decision Analysis, 2019. [paper](https://doi.org/10.1287/deca.2018.0384). *Manel Baucells, Rakesh K. Sarin*

> the optimal decision strategy is obtained by considering the impact of the current decision on all future decisions... Instead, he may think of small chunks of the problem in isolation. It is intuitively obvious that such myopic strategy generally produces suboptimal choices (Rabin and Weizsacker 2009)...We examine decision situations and utility functions for which solving a sequence of problems in isolation is globally optimal.

9. **The Bayesian Prophet: A Low-Regret Framework for Online Decision Making**. Management Science 67(3):1368-1391. https://doi.org/10.1287/mnsc.2020.3624
Alberto Vera, Siddhartha Banerjee (2021) 

> Broadly speaking, an online decision-making problem is defined by a current state and a set of actions, which together determine the next state as well as generate rewards. In Markov decision processes (MDPs), the rewards and state transitions are also affected by some random shock. Optimal policies for such problems are known only in some special cases when the underlying problem is sufficientlysimpleand knowledgeofthe generative model sufficiently detailed. For many problems of of interest, an MDP approach is infeasible for two reasons: (1) insufficiently detailed models of the generative process of the randomness and (2) the complexity of computing the optimal policy (the so-called “curse of dimensionality”). These shortcomings have inspired a long line of work on approximate dynamic programming. 

10. **Solving Myopia in Real-time Decision-making using Petri nets Models’ Knowledge for Service-oriented Manufacturing Systems**. IFAC Proceedings Volumes, 2010. [paper](https://doi.org/10.3182/20100701-2-PT-4011.00026). *Paulo Leitão, Joel Alves1, Ana I. Pereira*

> This paper introduces a novel approach to the real-time decision-making in service-oriented manufacturing systems, addressing the myopia problem usually presented in such systems. 

11. **Generalized Online Routing: New Competitive Ratios, Resource Augmentation, and Asymptotic Analyses**. Operations Research, 2008. [paper](https://doi.org/10.1287/opre.1070.0450). *Patrick Jaillet, Michael R. Wagner*.

12. **Likelihood robust optimization for data-driven problems**. Computational Management Science, 2016. [paper](https://link.springer.com/article/10.1007/s10287-015-0240-3). *Zizhuo Wang, Peter W. Glynn, Yinyu Ye*.

13. **Efficient Steady-State Simulation of High-Dimensional Stochastic Networks**. Stochastic Systems, 2021. [paper](https://doi.org/10.1287/stsy.2021.0077).  *Jose Blanchet, Xinyun Chen, Nian Si, Peter W. Glynn*

### [Synchronization frequency](#content)
1. **An Introduction to Event-triggered and Self-triggered Control**. IEEE 51st IEEE Conference on Decision and Control (CDC), 2012. [paper](https://ieeexplore.ieee.org/document/6425820). *W.P.M.H. Heemels, K.H. Johansson, P. Tabuada*

> It is desirable in these systems to limit the sensor and control computation and/or communication to instances when the system needs attention. However, classical sampled-data control is based on performing sensing and actuation periodically rather than when the system needs attention.

2. **Challenges of Real-Time Decision Support**. In book Supporting Real Time Decision-Making, 2011. [paper](https://www.springer.com/gp/book/9781441974051). *Daniel J. Power*

>  Many strategic decisions do not need real-time data, but decision makers may benefit from improved rich media, real-time communications. Choosing when and how to deploy real-time decision support is an important decision that creates opportunities and challenges for managers and organization stakeholders. <font color=purple>@TAG synchronization frequency</font>

> When response time or delay in retrieving data impacts decision-making timeliness and effectiveness, managers are faced with a trade-off between technological expenditures, decision quality, and decision risk.

>  Real time also means ‘near real time’ in practice because there is always some latency between (a) the actual state change, (b) the reflection of that state change in data in one or more systems of record and (c) the availability of the changed data to decision makers. Real time is not the same for every decision task. ((d) the availability of the best decisions, (e) the reflection of that best decisions in actuators (e) the actual state change given the decisions)

### [Applications](#content)

1. **Digital Twin Framework and Its Application to Power Grid Online Analysis**. CSEE JOURNAL OF POWER AND ENERGY SYSTEMS, 2019. [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8779809). *Mike Zhou, Jianfeng Yan, Donghao Feng*

> Digital twin (DT) framework is introduced in the context of application for power grid online analysis. In the development process of a new power grid real-time online analysis system, an online analysis digital twin (OADT) has been implemented to realize the new online analysis architecture. 

> A high-performance parallel computing approach has been implemented on the top of the virtual models.

2. **Industrial IoT integrated with Simulation – A Digital Twin approach to support real-time decision making**. Proceedings of the International Conference on Industrial Engineering and Operations Management, 2019. [paper](http://ieomsociety.org/pilsen2019/papers/225.pdf)

> The suggested approach involves a Manufacturing Executing System (MES) producing a production schedule, an IoT Platform composed by a message broker and a real-time database, a Simulator including simulation software and a wrapper, and a user application serving as an interface between the user and the IoT Platform and Simulator integrated system. 



3. **Challenges of Real-Time Decision Support**. In book Supporting Real Time Decision-Making, 2011. [paper](https://www.springer.com/gp/book/9781441974051). *Daniel J. Power*

> When evaluating implementation of these systems, managers need to consider and respond to three categories of continuing challenges: (1) technical, (2) organizational and (3) social/psychological.

>  Many strategic decisions do not need real-time data, but decision makers may benefit from improved rich media, real-time communications. Choosing when and how to deploy real-time decision support is an important decision that creates opportunities and challenges for managers and organization stakeholders. <font color=purple>@TAG synchronization frequency</font>

> When response time or delay in retrieving data impacts decision-making timeliness and effectiveness, managers are faced with a trade-off between technological expenditures, decision quality, and decision risk.

>  Real time also means "near real time" in practice because there is always some latency between (a) the actual state change, (b) the reflection of that state change in data in one or more systems of record and (c) the availability of the changed data to decision makers. Real time is not the same for every decision task.

4. **6 Best Practices for Real-Time Analytics**, Gartner, 2016. [article](https://www.gartner.com/smarterwithgartner/six-best-practices-for-real-time-analytics/).

