## [Content](#content)

<table>
<tr><td colspan="2"><a href="#related-research-papers-in-or">3. Related research papers in OR</a></td></tr>
<tr><td colspan="2">&emsp;<a href="#building-digital-models">3. 1 Building digital models</a></td></tr>
<tr>
	<td>&emsp;&emsp;<a href=#quantitative-modeling>3.1.x Quantitative modeling approaches</a></td>
	<td>&emsp;&emsp;<a href=#mixed-quantitative-and-qualitative-modeling>3.1.x Mixed quantitative and qualitative modeling approaches</a></td>
</tr>
<tr>
	<td>&emsp;&emsp;<a href=#automatically-generating-simulation-models>3.1.x Automatically generating simulation models</a></td>
</tr>
<tr><td colspan="2">&emsp;<a href="#combining-supporting-data">3. 2 Combining the Supporting Data</a></td></tr>
<tr>
	<td>&emsp;&emsp;<a href=#data-fusion>3.2.x Data Fusion</a></td>
	<td>&emsp;&emsp;<a href=#information-system-integration>3.2.x Information systems integration</a></td>
</tr>
<tr>
	<td>&emsp;&emsp;<a href=#auto-data-processing>3.2.x Autonomous data processing</a></td>
	<td>&emsp;&emsp;<a href=#measuring-value>3.2.x Measuring the value of data</a></td>
</tr>
<tr>
	<td>&emsp;&emsp;<a href=#sensor-deployment>3.2.x Sensor deployment</a></td>
</tr>
</table>

[Back to homepage](../papers4dtor.md)

## [Building digital models](#content)
Virtual representation is a set of correlated digital models and supporting data. Therefore, we first discuss the 


Modeling: abstract the real-world EoP by digital models. three types of digital model. Mathematical equations (problem structuring, soft OR.) Simulation model (Hybrid.) AI-based. Directly learn from data. Complexity evaluation.

Supporting data. Inter-departmental, inter-firm. Methods: connecting information systems within a firm; sharing of the key information between firms (information sharing). Difficulties in processing data: missing data. duplicated, inconsistency. information fusion. (Discussion on data fusion, integration, aggregation). What types of data are most useful?

### [Quantitative modeling](#content)
Quantitative models: mathematical formulation + simulation models (data-driven calibration methods)

1. **A review of dynamic vehicle routing problems**. EJOR, 2013. [paper](http://dx.doi.org/10.1016/j.ejor.2012.08.015). *Victor Pillac, Michel Gendreau, Christelle Guéret, Andrés L. Medaglia*

2. **Models for production planning under uncertainty: A review**. IJPE, 2006. [paper](https://doi.org/10.1016/j.ijpe.2005.09.001). *J. Mula, R. Poler, J.P. Garcıa-Sabater, F.C. Lario*.

3. **Taking stock of behavioural OR: A review of behavioural studies with an intervention focus**. EJOR, 2021. [paper](https://doi.org/10.1016/j.ejor.2020.11.031).

4. **The Object-Oriented discrete event simulation modeling: A case study on aircraft spare part management**. WSC, 2015. [paper](https://ieeexplore.ieee.org/document/7408511). *Haobin Li; Yinchao Zhu; Yixin Chen; Giulia Pedrielli; Nugroho A. Pujowidianto*

5. **Tutorial on agent-based modeling and simulation**. WSC, 2005. [paper](https://ieeexplore.ieee.org/abstract/document/1574234). *C.M. Macal; M.J. North*.

6. **Agent-based modeling and simulation**. WSC, 2009. [paper](https://ieeexplore.ieee.org/abstract/document/5429318). *C.M. Macal; M.J. North*.

7. **Introductory Tutorial: Agent-based Modeling And Simulation**. WSC, 2014. [paper](https://ieeexplore.ieee.org/abstract/document/7019874). *C.M. Macal; M.J. North*.

8. **System Dynamics Modeling: Tools for Learning in a Complex World**. California Management Review, 2001. [paepr](https://doi.org/10.2307/41166098. *
John D. Sterman*. 

9. **Hybrid simulation modelling in operational research: A state-of-the-art review**. EJOR, 2018. [paper](https://doi.org/10.1016/j.ejor.2018.10.025). *Sally C. Brailsford , Tillal Eldabi , Martin Kunc , Navonil Mustafee , Andres F. Osorio*. 

> Simulation approaches in manufacturing and business: discrete-event simulation (DES), system dynamics (SD) and agent-based simulation (ABS) 

> An increasing interest in hybrid simulation (defined as models that combined at least two of these approaches) to model complex enterprise-wide systems.

> Bennett (1985) discusses three levels at which different OR methods could be combined. The lowest level, Comparison, involves using two or more methods entirely separately for the purpose of solving different aspects of a problem which could not be tackled by any one method on its own. The next level, Enrichment, aims to enhance one method (the main method) by using elements of another. The highest level, Integration, treats the methods on an equal footing and uses elements of each to generate something to- tally new.

> Most real-world problems and systems are complex, with many different features and characteristics, and very rarely is one single method ideally suited to capture all of them. The modeller who chooses to use only one method is therefore faced with a dilemma: to model the whole problem using one single method, accepting that it makes invalid assumptions or oversimplifies some aspects, or to model only those parts of the problem for which their chosen method is suitable and simply say that the remaining parts are out of scope? The former approach may lead to poor solutions (and bad decisions), but from a practical perspective it may be neither useful nor sensible to study only one aspect of a real-world problem in isolation. This dilemma has also driven the need for hybrid simulation.

> We originally hypothesised that hybrid simulation approaches have become more popular because modern business problems are more complex. However, it may be that business problems were always complex, and simulation modellers have simply become more ambitious about the types of problem that can be tackled. Either way, hybrid simulation is clearly here to stay.

![](../image/Stages-of-simulation-study.png) 

10. **Particle Methods for Data-Driven Simulation and Optimization**. In INFORMS TutORials in Operations Research, 2012. [paper](https://doi.org/10.1287/educ.1120.0104). *John R. Birge*. 

> Particle methods have become a common approach to estimate the distribution of an unknown state in a Markov process (i.e., a hidden Markov model) from noisy observations with general nonlinear transitions. 

11. **Maximum Likelihood Estimation by Monte Carlo Simulation: Toward Data-Driven Stochastic Modeling**. Operations Research, 2020. [paper](https://doi.org/10.1287/opre.2019.1978). *Yijie Peng, Michael C. Fu, Bernd Heidergott, Henry Lam*

> -  We propose a new method for estimating un- known parameters of a stochastic model without assuming an analytical likelihood function.
> - We directly fit the underlying stochastic model to the output data, which opens the possibility of extending data-driven ideas to causal stochastic models.
> - We generalize our scheme to efficiently utilize the simulated samples in calculating the MLE for an HMM.

12. **Learning to simulate**. ICLR, 2019. [paper](https://arxiv.org/abs/1810.02513). *Nataniel Ruiz, Samuel Schulter, Manmohan Chandraker*

13. **Learning to Simulate Vehicle Trajectories from Demonstrations**. 2020 IEEE 36th International Conference on Data Engineering (ICDE). [paper](https://ieeexplore.ieee.org/document/9101553). *Guanjie Zheng; Hanyang Liu; Kai Xu; Zhenhui Li*.

### [Mixed quantitative and qualitative modeling](#content) 
1. **The characteristics of problem structuring methods: A literature review**. EJOR, 2019. [paper](https://doi.org/10.1016/j.ejor.2018.05.003). *Chris M. Smith, Duncan Shaw*

![](../image/quantitative-vs-qualitative-OR.png)

> Problem structuring methods (PSMs) are a class of qualitative operational research (OR) modeling approaches.

> Methods associated with quantitative OR follow a more objectivist stance and are better suited to ‘tame’ problems that can be more easily comprehended. In contrast, PSMs take a subjectivist stance (within an interpretivist paradigm) and are suited to ‘wicked’ problems that are difficult to specify. **Problems that has nonprocedural solutions.**

> Such problems are pluralistic (Jackson & Keys, 1984), as stakeholders have divergent views about goals and objectives. The problems exist in dynamic and complex systems that interact with each other (Ackoff, 1979).

> They cannot be exhaustively formulated, every formulation is a statement of a solution, there is no stopping rule, there is no true or false, there is no exhaustive list of operations, there are many explanations for the same problem, every problem is a symptom of another problem, there is no immediate or ultimate test, solutions are ‘one shot’ and every problem is unique. 

> PSMs see problems as systems in which elements are connected by interrelationships rather than static snapshots. 

![](../image/psm-1.png)


2. **Soft OR and Practice: The Contribution of the Founders of Operations Research**. Operations Research, 2021. [paper](https://doi.org/10.1287/opre.2020.2051). *Robert G. Dyson, Frances A. O’Brien, Devan B. Shah*.
<font color=purple>@TAG modeling</font>
> The motivation for the development of soft OR stemmed from a concern that hard (quantitative) OR could not solve wicked (i.e., ill-structured, complex) problems (Rittel and Webber 1973) or engage effectively with swamp conditions—messy, confusing problems(Scho ̈n1987)

> A set of characteristics of soft OR
> - An ill-defined problem situation (context)
> - The existence of multiple actors or stakeholders with different perspectives and conflicting objectives (context)
> - A high degree of uncertainty, intangibles, and qualitative and limited quantitative data (context)
> - Engagement with and interactions between stake- holders to seek agreement on the nature of the problem and of learning and on actions. This may involve the use of facilitated workshops (real or virtual) (process)
> - Concern for process issues/procedural rationality (process)
> - The use of models as a focus for the discussions that are transparent and understandable. These are typically diagrammatic models such as causal maps, cognitive maps, influence diagrams, decision graphs, and rich pictures (content)

> ... the emergence of mixed soft and hard modelling indicates that hard models can have an important decision support role in such contexts.

> Hence a vicious circle can develop where some academics know more and more about less and less and can become dis- connected from the real world. (This issue has been a concern in the Academy of Management for some years; see, e.g., Vishwanath et al. 2017.) The potential danger of this trend is that much of OR could become ossified, focusing mainly on an historical problem set that has increasingly limited economic or social impact thus denying its heritage.

3. **Combining problem structuring methods with simulation: The philosophical and practical challenges**. Discrete-Event Simulation and System Dynamics for Management Decision Making, Chapter 4, 2014. [paper](https://onlinelibrary.wiley.com/doi/pdf/10.1002/9781118762745). *Kathy Kotiadis and John Mingers*.

4. **Problem structuring methods in action**. EJOR, 2004. [paper](https://doi.org/10.1016/S0377-2217(03)00056-0). *John Mingers, Jonathan Rosenhead*.

### [Automatically generating simulation models](#content)
1. **A Survey on Automatic Model Generation for Material Flow Simulation in Discrete Manufacturing**. 52nd CIRP Conference on Manufacturing Systems, 2019. [paper](https://doi.org/10.1016/j.procir.2019.03.022). *Heiner Reinhardt, Marek Weber, Matthias Putz*.

2. **Challenges for the Automatic Generation of Simulation Models for Production Systems**. 2010 International Simulation Multiconference / Summer Computer Simulation Conference, SCSC. [paper](https://www.db-thueringen.de/servlets/MCRFileNodeServlet/dbt_derivate_00022287/SCSC-10_S445-449.pdf). *Bergmann, Sören; Strassburger, Steffen*

3. **Trends in Automatic Composition of Structures for Simulation Models in Production and Logistics**. WSC, 2019. [paper](https://ieeexplore.ieee.org/document/9004959). *Sigrid Wenzel; Jana Stolipin; Jakob Rehof; Jan Winkels*

4. **Applying model-reconstruction by exploring MES and PLC data for simulation support of production systems**. WSC, 2012. [paper](https://ieeexplore.ieee.org/document/6465069). *András Pfeiffer; Botond Kádár; Gergely Popovics; Csaba Kardos; Zoltán Vén; Lőrinc Kemény; László Monostori*.

5. **Automatic Simulation Model Generation Based on PLC Codes and MES Stored Data**. Procedia CIRP, 2012. [paper](https://doi.org/10.1016/j.procir.2012.07.013). *G.Popovics, A. Pfeiffer, B.Kádár, Z. Vén, L. Kemény, L. Monostori*

6. **Feature Article: Optimization for simulation: Theory vs. Practice**. INFORMS Journal on Computing, 2002. [paper](https://doi.org/10.1287/ijoc.14.3.192.113). *Michael C. Fu*.

7. **An approach to Determine Simulation Model Complexity**. Procedia CIRP, 2016. [paper](https://doi.org/10.1016/j.procir.2016.07.072). *Gergely Popovics, László Monostori*.


## [Combining supporting data](#content)

### [Data fusion](#content)
1. **The of data fusion in predictive maintenance using digital twin**. AIP Conference Proceedings, 2018. [paper](https://doi.org/10.1063/1.5031520). *Zheng Liu, Norbert Meyendorf, and Nezih Mrad*.

> The flow of information from raw data to high-level decision making is propelled by sensor-to-sensor, sensor-to-model, and model-to- model fusion.

> The more general concept of “information fusion” is defined as “the study of efficient methods for automatically or semi-automatically transforming information from different sources and different points in time into a representation that provides effective support for human or automated decision making.”

> The potential of data fusion operations & the benefits of the fusion operations:
> 1. Sensor fusion – better signal quality
> 2. Physics model fusion – better model performance
> 3. Data model fusion – better model performance
> 4. Sensor and physics-based model fusion – adaptive physics-based model
> 5. Sensor and data model fusion – robust data-driven model
> 6. Physics and data model fusion – improved prediction
> 7. Sensor, physics, and data model fusion – reliable decision making

2. **An Introduction to Multisensor Data Fusion**. PROCEEDINGS OF THE IEEE, 1997. [paper](https://ieeexplore.ieee.org/document/554205). *David L. Hall, James Llinas*.

> Data fusion techniques combine data from multiple sensors, and related information from associated databases, to achieve improved accuracies and more specific inferences than could be achieved by the use of a single sensor alone

3. **Handling Sensor Data in Rapidly Changing Environments to Support Soft Real-Time Requirements**. INFORMS Journal on Computing， 2000. [paper](http://dx.doi.org/10.1287/ijoc.12.2.84.11893). *Anindya Datta, Igor R. Viguier*.

> ARCS (active rapidly changing systems): 
> - Sensor Data: One assumption we make is that sensors are distributed and work in their own private data partition— thus, a particular instance variable is always reported by the same sensor.
> - Non-sensor Data: structural and control data.

> We identify a number of algorithms and perform a detailed performance study. This study enables us to make certain general recommendations regarding the properties of algorithms designed to handle rapidly changing sensor data. 

> Sensor tuning problem: This problem is of critical importance in ARCS system design—if a sensor is tuned to a smaller than ideal reporting period, it will report information too rapidly to the database. This, in turn, will consume a disproportionate amount of system resources (e.g., processor and memory) and potentially cause inefficient processing of other database tasks (such as control/monitoring transactions and user queries). Conversely, if a sensor reports data too slowly, control trans- actions and user queries will, potentially, avail stale (i.e., old) information. In other words, there is a clear-cut tradeoff between efficient processing and maintaining system recency.

> Algorithms: Sensor Data Handler (SDH), Other Scheduling Algorithms, The Correct Execution of QTs: Ensuring Temporal Consistency, 

4. **Multisensor data fusion: A review of the state-of-the-art**. Information Fusion, 2013. [paper](https://doi.org/10.1016/j.inffus.2011.08.001). *Bahador Khaleghi, Alaa Khamis, Fakhreddine O.Karray, Saiedeh N.Razavi*

> different definitions: ‘‘Information fusion is the study of efficient methods for automatically or semi-automatically transforming information from different sources and different points in time into a representation that provides effective support for human or automated decision making’’

> Most of the work is being done in simulation and based on sometimes idealized assumption(s), which make it difficult to predict how the algorithm would perform in real-life applications.

5. **Data Fusion and Data Aggregation/Summarization Techniques in WSNs: A Review**. International Journal of Computer Applications, 2015. [paper](https://www.ijcaonline.org/archives/volume121/number19/21648-4755). *Sakshi Chhabra, Dinesh Singh*

> Data aggregation which is a subset of data fusion is just a process of summarizing the data coming from multiple SNs in order to reduce or eliminate redundant data.

6. **Data aggregation mechanisms in the Internet of things: A systematic review of the literature and recommendations for future research**. Journal of Network and Computer Applications, 2017. [paper](https://doi.org/10.1016/j.jnca.2017.08.006). *Behrouz Pourghebleh, Nima Jafari Navimipour*.

> Data aggregation as an efficient method is used to decrease the number of transmissions among objects. The loss of data redundancy leads to lengthen the network lifetime and decrease the energy consumption.
> - In the IoT, billions of objects can be found through various types of actuators and sensors, which are related to the Internet via wireless sensor network (WSN) (Abdollahzadeh and Navimipour, 2016). Connectivity, sensing, and interactivity among objects are considered as the main features of the IoT (Levi and Sarimurat, 2016). 
> - Aggregation of the data from various sites as an efficient method is utilized within the network in which nodes are resource and energy constrained (Chao and Hsiao, 2014).

> The data aggregation mechanisms are categorized into three main groups, including tree-based, cluster-based and centralized.


7. **Data Quality of Query Results with Generalized Selection Conditions**. Operations Research, 2013. [paper](https://doi.org/10.1287/opre.1120.1128). *Debabrata Dey, Subodha Kumar*

> Modern organizations maintain large databases and data warehouses with multiple feeds from heterogeneous data streams and heavily depend on the information gleaned from these databases and data streams for making different strategic, tactical, and operational decisions.

> However, unlike traditional assets, data are highly dynamic, so maintaining a consistent quality is somewhat problematic (Batini et al. 2009, Orr 1998).

> Data streams that span multiple systems from multiple organizations, such as in the case of electronic data interchange, are often at a high risk of degradation. For example, when an organization depends on a data stream from another organization (such as a vendor or a customer), the existence of missing or inconsistent data in the source could result in the corruption of the data at the destination

8. **Scalable Data Fusion with Selection Correction: An Application to Customer Base Analysis**. Marketing Science, 2021. [paper](https://doi.org/10.1287/mksc.2020.1259). *Daniel Minh McCarthy, Elliot Shin Oblander*

> As a result, it is increasingly common that there is more than one data set available covering a particular population of interest. Modelers may naturally want to perform analysis using a fusion of data sources, but doing so creates new methodological challenges because of the difficulty of incorporating differing granularities of data and selection bias. We propose a methodology to solve these challenges, allowing the fusing together of (1) aggregated data about the population as a whole with (2) granular data for a possibly nonrepresentative subsample of that population, when the size of the population may be very large. When a representative sample of granular data is not available, training a model on aggregated population-level data and granular data from a possibly nonrepresentative sample could allow modelers to derive the benefits of both sources—representativeness and rich individual-level visibility, respectively— while ameliorating their limitations.

### [Information system integration](#content)
1. **An empirical study of IS architectures in French SMEs: integration approaches**. European Journal of Information Systems, 2012. [paper](https://doi.org/10.1057/ejis.2012.12). *Marc Bidan, Frantz Rowe & Duane Truex*. 

> The most common means for approaching enterprise architecture and any form of integration is via the construction of software bridges and interfaces. Partially standardized architectures based on Enterprise Systems (ERP) are the next most common type. Hybrid architectures – mixed Enterprise Applications Integration and ERP – are the third most common. The contribution of this paper lies not in the identification of the three types but resides (1) in the description of their distribution in SMEs; (2) in the absence of other integration/interoperability types in this population; and (3) most importantly in the interpretation of the organizational and historical rationale explaining the emergence of these types in this organizational context.

2. **A Dynamic Model of Embeddedness in Digital Infrastructures**. Information Systems Research, 2019. [paper](https://doi.org/10.1287/isre.2019.0864). *Daniel Fürstenau, Abayomi Baiyere, Natalia Kliewer*.

> Digital infrastructures are a result of individual yet interdependent systems evolving in relation to each other. In this paper, we identify three processes by which individual systems become embedded into digital infrastructures. First, there are parallel processes, in which systems become embedded independently of each other. Second, there are competitive processes, in which the embeddedness of one system increases at the expense of another. Finally, there are spanning processes, in which bridges are built between different embedded systems. The three processes, synthesized into a dynamic model of digital infrastructure embeddedness, offer much-needed conceptual clarity to the area of digital infrastructure evolution. They also provide insight into the emergence of three forms of digital infrastructures: silofied, regenerated, and unified. Reflecting an interconnection view, our research further facilitates an understanding of infrastructure inertia and its associated consequence.

### [Auto data processing](#content)
Managing the data assets in DTs: Unlike traditional assets, data are highly dynamic (missing and consistency)

1. **From Predictive Methods to Missing Data Imputation: An Optimization Approach**. Journal of Machine Learning Research, 2018. [paper](https://jmlr.org/papers/v18/17-073.html). *Dimitris Bertsimas, Colin Pawlowski, Ying Daisy Zhuo*.

> We propose a flexible framework based on formal optimization to impute missing data with mixed continuous and categorical variables. This framework can readily incorporate various predictive models including K- nearest neighbors, support vector machines, and decision tree based methods, and can be adapted for multiple imputation. 


2. **In-situ AI: Towards Autonomous and Incremental Deep Learning for IoT Systems**, 2018 IEEE International Symposium on High Performance Computer Architecture. [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8327001). *Mingcong Song; Kan Zhong; Jiaqi Zhang; Yang Hu; Duo Liu; Weigong Zhang; Jing Wang; Tao Li*

> Rather than constantly moving a tremendous amount of raw data to the Cloud, it would be beneficial to leverage the emerging powerful IoT devices to perform the inference task.
> - Two factors in the real IoT systems: data is dynamic and unlabeled. 

> <font color=green>@RQ Nevertheless, the statically trained model could not efficiently handle the dynamic data in the real in-situ environments, which leads to low accuracy. Moreover, the big raw IoT data challenges the traditional supervised training method in the Cloud.</font>

> We propose In-situ AI, the first Autonomous and Incremental computing framework and architecture for deep learning based IoT applications. We equip deep learning based IoT system with autonomous IoT data diagnosis (minimize data movement), and incremental and unsupervised training method (tackle the big raw IoT data generated in ever-changing in-situ environments).

> The result shows:
> - (1) a tradeoff exists between fast response time and energy-efficiency; 
> - (2) latency and energy-efficiency are two key metrics for inference task, while energy-efficiency is the only design concern for the diagnosis task.

3. **Modeling Data and Process Quality in Multi-Input, Multi-Output Information Systems**. Management Science, 1985. [paper](http://dx.doi.org/10.1287/mnsc.31.2.150). *Donald P. Ballou, Harold L. Pazer*

> In distributed systems with a high level of data replication, asynchronous updating of multiple copies could leave the copies inconsistent

> Data accuracy can be defined as the conformity of the recorded value to the actual value

4. **When Is the Right Time to Refresh Knowledge Discovered from Data?**. Operations Research, 2013. [paper](https://doi.org/10.1287/opre.1120.1148). *Xiao Fang, Olivia R. Liu Sheng, Paulo Goes*

> Knowledge discovery in databases (KDD) techniques have been extensively employed to extract knowledge from massive data stores to support decision making in a wide range of critical applications. Maintaining the currency of discovered knowledge over evolving data sources is a fundamental challenge faced by all KDD applications. 

> This paper addresses the challenge from the perspective of deciding the right times to refresh knowledge. We define the knowledge-refreshing problem and model it as a Markov decision process. Based on the identified properties of the Markov decision process model, we establish that the optimal knowledge-refreshing policy is monotonically increasing in the system state within every appropriate partition of the state space. We further show that the problem of searching for the optimal knowledge- refreshing policy can be reduced to the problem of finding the optimal thresholds and propose a method for computing the optimal knowledge-refreshing policy.

> For real-world KDD applications, new data are continuously accumulated and data are dynamic in reality. 

> As a result, knowledge discovered using KDD becomes obsolete over time.

> Future research: handle variable cost of running KDD; accommodate the situation where data and request arrival rates change over time.
 
5. **A Markov-Based Update Policy for Constantly Changing Database Systems**. IEEE TRANSACTIONS ON ENGINEERING MANAGEMENT, 2017. [paper](https://ieeexplore.ieee.org/document/7835169). *Wei Zong, Feng Wu, and Zhengrui Jiang*

> In order to maximize the value of an organization’s data assets, it is important to keep data in its databases up-to-date. In the era of big data, however, constantly changing data sources make it a challenging task to assure data timeliness in enterprise systems. For instance, due to the high frequency of purchase trans- actions, purchase data stored in an enterprise resource planning system can easily become outdated, affecting the accuracy of in- ventory data and the quality of inventory replenishment decisions. Despite the importance of data timeliness, updating a database as soon as new data arrives is typically not optimal because of high update cost. Therefore, a critical problem in this context is to deter- mine the optimal update policy for database systems. In this study, we develop a Markov decision process model, solved via dynamic programming, to derive the optimal update policy that minimizes the sum of data staleness cost and update cost. Based on real-world enterprise data, we conduct experiments to evaluate the performance of the proposed update policy in relation to benchmark policies analyzed in the prior literature. The experimental results show that the proposed update policy outperforms fixed interval update policies and can lead to significant cost savings.

6. **Maintaining Diagnostic Knowledge-Based Systems: A Control-Theoretic Approach**. Management Science, 2009. [paper](https://doi.org/10.1287/mnsc.1080.0908). *Alain Bensoussan, Radha Mookerjee, Vijay Mookerjee, Wei T. Yue*

> Diagnostic knowledge-based systems are used in a variety of application domains to support classification decisions. The effectiveness of such systems often decreases as the application environment or user preferences change over time. Hence, frequent adjustments to the system knowledge by a human expert become necessary. We study the problem of determining the optimal amount of effort that should be exerted to maintain the system over a planning horizon (finite or infinite). Using the receiver operating characteristic curve to derive a measure for system performance, we maximize system value by balancing system benefits with maintenance costs. The problem is cast as an optimal control model in which the goal is to choose the timing and extent of maintenance that must be expended to maximize system value. We find that the optimal solution usually possesses a steady-state component. The maintenance problem is also solved as a discrete, impulse control problem, as well as one where maintenance effort has a nonlinear impact on system performance.

7. **Optimal Synchronization Policies for Data Warehouses**. INFORMS Journal on Computing, 2006.[paper](https://doi.org/10.1287/ijoc.1040.0094). *Debabrata Dey, Zhongju Zhang, Prabuddha De*

> The notion of a data warehouse for integrating operational data into a single repository is rapidly becoming popular in modern organizations. An important issue in this context is how often one should synchronize the data warehouse to reflect the changes in the constituent operational data sources. If the synchronization is performed very frequently, the associated cost might be quite high, although the data warehouse would only have a small amount of stale data. On the other hand, if the data warehouse is synchronized infrequently, it might result in costly errors in business decisions arising from the stale data. This paper examines the trade-off between the synchronization and staleness costs and derives the optimal synchronization frequency.


8. **A Time-based Dynamic Synchronization Policy for Consolidated Database Systems**. MIS Quarterly, 2019. [paper](https://misq.org/a-time-bassed-dynamic-synchronization-policy-for-consolidated-database-systems.html). *Xinxue Qu, Zhengrui Jiang*

> Data is becoming an increasingly important asset in today’s organizations. Various challenges in the age of big data, such as high volume and high velocity, call for efficient database maintenance policies. This study focuses on deriving an optimal synchronization policy for consolidated database systems. By trading off synchronization cost with data staleness cost, we propose a time-based dynamic synchronization (TDS) policy, which evaluates the system state at predetermined checkpoints and synchronizes a database only if given staleness thresholds are crossed. Although several database synchronization and knowledge refreshment policies have been proposed in the prior literature, the TDS policy retains their advantages and overcomes their inflexibility in that, under the TDS policy, system check and synchronization are easy to schedule, disruptions to business operations can be avoided, and synchronization is run only if necessary. Experimental results show that the TDS policy consistently outperforms benchmark policies, leading to substantial cost savings. In particular, the performance gap between the TDS policy and a static periodic policy is greater when data changes arrive less frequently but carry higher unit staleness costs, or when queries arrive more frequently and suffer higher unit staleness costs.


9. **Maintaining Diagnostic Knowledge-Based Systems: A Control-Theoretic Approach**. Management Science, 2009. [paper](https://doi.org/10.1287/mnsc.1080.0908). *Alain Bensoussan, Radha Mookerjee, Vijay Mookerjee, Wei T. Yue*.

> Diagnostic knowledge-based systems are used in a variety of application domains to support classification decisions. The effectiveness of such systems often decreases as the application environment or user preferences change over time. Hence, frequent adjustments to the system knowledge by a human expert become necessary. We study the problem of determining the optimal amount of effort that should be exerted to maintain the system over a planning horizon (finite or infinite). Using the receiver operating characteristic curve to derive a measure for system performance, we maximize system value by balancing system benefits with maintenance costs. The problem is cast as an optimal control model in which the goal is to choose the timing and extent of maintenance that must be expended to maximize system value. We find that the optimal solution usually possesses a steady-state component. The maintenance problem is also solved as a discrete, impulse control problem, as well as one where maintenance effort has a nonlinear impact on system performance.

10. **Which Brand Purchasers Are Lost to Counterfeiters? An Application of New Data Fusion Approaches**. Marketing Science, 2014. [paper](https://doi.org/10.1287/mksc.2013.0823). *Yi Qian, Hui Xie*.

> Firms and organizations often need to collect and analyze sensitive consumer data. A common problem encountered in such evidence-based research is that they cannot collect all essential information from one sample, and they may need to link nonoverlapping data items across independent samples. We propose an automated nonparametric data fusion solution to this problem. The proposed methods are not restricted to specific types of variables and distributions. They require no prior knowledge about how data at hand may behave differently from standard theoretical distributions, and they automate the process of generating suitable distributions that match data, therefore making our methods particularly useful for linking data with complex distributional shapes. In addition, these methods have strong theoretical support; permit highly efficient direct fusion to relate a mixture of continuous, semicontinuous, and discrete variables; and enable nonparametric identification of entire distributions of fusion variables, including higher moments and tail percentiles. These novel and promising features overcome important limitations of existing methods and have the potential to increase fusion effectiveness. We apply the proposed methods to overcome data constraints in a study of counterfeiting. By combining data sets from multiple sources, data fusion provides a feasible approach to studying the relationship between counterfeit purchases and various marketing elements, such as consumers’ purchase motivations, behaviors, and attitudes; brand marketing channels; promotions; and advertisements. Therefore, data fusion sheds light on counterfeit purchase behaviors and suggests ways to counter counterfeits that would not be available if these data sets were analyzed separately.


11. **Fast Approximation Algorithm for Maximum Lifetime Aggregation Trees in Wireless Sensor Networks**. INFORMS Journal on Computing, 2016. [paper](https://doi.org/10.1287/ijoc.2015.0688). *Xiaojun Zhu, Guihai Chen, Shaojie Tang, Xiaobing Wu, Bing Chen* 

> One ultimate goal of wireless sensor networks is to collect the sensed data from a set of sensors and transmit them to some sink node via a data gathering tree. In this work, we are interested in data aggregation, where the sink node wants to know the value for a certain function of all sensed data, such as minimum, maximum, average, and summation. Given a data aggregation tree, sensors receive messages from children periodically, merge them with its own packet, and send the new packet to its parent. The problem of finding an aggregation tree with the maximum lifetime has been proved to be NP-hard and can be generalized to finding a spanning tree with the minimum maximum vertex load, where the load of a vertex is a nondecreasing function of its degree in the tree. Although there is a rich body of research in those problems, they either fail to meet a theoretical bound or need high running time. In this paper, we develop a novel algorithm with provable performance bounds for the generalized problem. We show that the running time of our algorithm is in the order of O(mn\alpha(m,n)), where m is the number of edges, n is the number of sensors, and \alpha is the inverse Ackerman function. Though our work is motivated by applications in sensor networks, the proposed algorithm is general enough to handle a wide range of degree-oriented spanning tree problems, including bounded degree spanning tree problem and minimum degree spanning tree problem. When applied to these problems, it incurs a lower computational cost in comparison to existing methods. Simulation results validate our theoretical analysis.

5.  **A Branch-and-Bound Algorithm for Building Optimal Data Gathering Tree in Wireless Sensor Networks**. INFORMS Journal on Computing, 2021. [paper](https://doi.org/10.1287/ijoc.2020.1012). *Xiaojun Zhu, Shaojie Tang*.

> In this paper, we consider the maximum lifetime data gathering tree (MLDT) problem in sensor networks. A data gathering tree is a spanning tree rooted at a specified sink so that every node can send its messages to the sink along the tree. The lifetime of a tree is defined as the minimum lifetime among nodes where each node’s lifetime is determined by its initial energy and transmission load. The MLDT problem is NP-hard, and the state- of-the-art solution formulates a decision version of the problem as an integer linear program (ILP) and then solves it by conducting binary search over all possible lifetimes. In this paper, we first give an ILP for the optimization problem rather than its decision version, and then show that using ILP solvers to solve these programs could be highly inefficient. We then propose a branch-and-bound algorithm that incorporates two novel features. First, the bounding method takes into account integer flows, and contains a new set of constraints. Second, a special set of edges are deleted to reduce the number of subproblems generated by the branching process. Numerical simulations on randomly generated networks show that the proposed algorithm outperforms existing algorithms in terms of the number of solved problem instances in a fixed amount of time.

Summary of Contribution: We study the maximum lifetime data gathering tree (MLDT) problem in the context of wireless sensor network. MLDT is a fundamental problem in both computer science and operations research. Since sensor nodes are often resource limited, the data gathering tree must be carefully constructed to prolong the network lifetime. In this paper, we first give an integer linear program for the optimization problem rather than its decision version, and then show that using ILP solvers to solve these programs could be highly inefficient. We then propose a branch and bound algorithm that incorporates two novel features.


### [Measuring value](#content)
1. **Application of IoT-Aided Simulation to Manufacturing Systems in Cyber-Physical System**. Machines, 2019. [paper](https://doi.org/10.3390/machines7010002). *Yifei Tan, Wenhe Yang, Kohtaroh Yoshida, Soemon Takakuwa*

> <font color=green>@RQ Issues such as the reception of real-time data from the IoT, as well as the conversion and inputting of the data into a simulation model have not yet been completely solved. Even though some general roadmaps and frameworks have been proposed, it is still not clear what kind of data and information must be integrated.</font>

> When constructing a DT, a specific framework to guide the process of extracting the necessary data from the physical system and a scheme for entering these data into the cyber-side simulation model are required.


2. **The Internet of Things and Information Fusion: Who Talks to Who?**. M&SOM, 2021. [paper](https://pubsonline.informs.org/doi/10.1287/msom.2020.0958). *Soroush Saghafian, Brian Tomlin, Stephan Billerc* <font color=purple>@TAG integration of data (interfirm); data quality; ownership</font>

> Problem definition: <font color=green>@RQ Autonomous sensors connected through the internet of things (IoT) are deployed by different firms in the same environment. The sensors measure an important operating-condition state variable, but their measurements are noisy, so estimates are imperfect. Sensors can improve their own estimates by soliciting estimates from other sensors. The choice of which sensors to communicate with (target) is challenging because sensors (1) are constrained in the number of sensors they can target and (2) only have partial knowledge of how other sensors operate—that is, they do not know others’ underlying inference algorithms/models. We study the targeting problem, examine the evolution of interfirm sensor communication patterns, and explore what drives the patterns.</font>

> Consider any given sensor $i$, and assume (without loss of generality) that it can select its target from two sensors: a high-quality sensor (labeled $h$) and a lower-quality sensor (labeled $l$). When should sensor $i$ target sensor $h$? When should it target sensor $l$? How does this choice depend on the initial state $s_0$?





### [Sensor deployment](#content)

1. **Reliable Traffic Sensor Deployment Under Probabilistic Disruptions and Generalized Surveillance Effectiveness Measures**. Operations Research, 2012. [paper](https://doi.org/10.1287/opre.1120.1082). *Xiaopeng Li, Yanfeng Ouyang*.

> Sensor systems as critical components of a transportation network provide a variety of real-time traffic surveillance information for traffic management and control. The deployment of sensors significantly affects their overall surveillance effectiveness. This paper proposes a reliable sensor location model to optimize surveillance effectiveness when sensors are subject to site-dependent probabilistic failures, and a general effectiveness measure is proposed to encompass most existing measures needed for engineering practice (e.g., flow volume coverage, vehicle-mile coverage, and squared error reduction). The problem is first formulated into a compact mixed-integer program, and we develop a variety of solution algorithms (including a custom-designed Lagrangian relaxation algorithm) and analyze their properties. We also propose alternative formulations including a continuum approximation model for single corridor problems and reliable fixed-charge sensor location models. Numerical case studies are conducted to test the performance of the proposed algorithms and draw managerial insights on how different parameter settings (e.g., failure probability and spatial heterogeneity) affect overall surveillance effectiveness and the optimal sensor deployment.

2. **Anticipatory Dynamic Traffic Sensor Location Problems with Connected Vehicle Technologies**. Transportation Science, 2018. [paper](https://doi.org/10.1287/trsc.2018.0838). *Hyoshin (John) Park, Ali Haghani, Song Gao, Michael A. Knodler, Siby Samuel*. 

> Technological advancements in wireless systems enable the advancement of traffic operations. When onboard equipment in connected vehicles transmits data to roadside sensors integrated with a traffic signal controller, green phases are redistributed to directly and indirectly reduce network delays. Despite the potential benefits of sensor technologies, the challenges associated with identifying optimal sensor locations for multiple time stages throughout a day with uncertain demand patterns has received little attention. In this paper, we focus on proactively reducing the network delay by controlling traffic signals through an optimized sensor deployment. The framework is based on portable sensors that may be repositioned within day and day to day to new locations such that delay savings over multiple time stages will be maximized. To tackle this multiperiod stochastic problem, dynamic models are proposed, considering the future sensor locations given budget constraints on the sensor costs and relocation costs, and the effect of control is tested on various demand profiles and penetration rates of an urban transportation network. A subproblem decomposed by Lagrangian relaxation enhanced with valid cuts has a better bound, and a variable neighborhood search algorithm quickly finds solutions. Two dynamic models that constrain flexible and restricted relocation, respectively, present higher savings compared to the stationary model without sensor relocation. The flexible relocation model guarantees higher savings than the restricted model by achieving the same maximum savings with fewer sensors. The gap between two dynamic models decreases when more sensors are available.

3. **Sequential Sensor Installation for Wiener Disorder Detection**. Mathematics of Operations Research, 2016. [paper](https://doi.org/10.1287/moor.2015.0756). *Savas Dayanik, Semih O. Sezer*

> We consider a centralized multisensor online quickest disorder detection problem where the observation from each sensor is a Wiener process gaining a constant drift at a common unobservable disorder time. The objective is to detect the disorder time as quickly as possible with small probability of false alarms. Unlike the earlier work on multisensor change detection problems, we assume that the observer can apply a sequential sensor installation policy. At any time before a disorder alarm is raised, the observer can install new sensors to collect additional signals. The sensors are statistically identical, and there is a fixed installation cost per sensor. We propose a Bayesian formulation of the problem. We identify an optimal policy consisting of a sequential sensor installation strategy and an alarm time, which minimize a linear Bayes risk of detection delay, false alarm, and new sensor installations. We also provide a numerical algorithm and illustrate it on examples. Our numerical examples show that significant reduction in the Bayes risk can be attained compared to the case where we apply a static sensor policy only. In some examples, the optimal sequential sensor installation policy starts with 30% less number of sensors than the optimal static sensor installation policy and the total percentage savings reach to 12%.