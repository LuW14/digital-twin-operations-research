## [Content](#content)

<table>
<tr><td colspan="2"><a href="#related-research-papers-in-or">3. Related research papers in OR</a></td></tr>
<tr><td colspan="2">&emsp;<a href="#building-virtual-representations">3. 1 Building virtual representations</a></td></tr>
<tr>
	<td>&emsp;&emsp;<a href=#integration-of-data>3.1.x Integration of data</a></td>
</tr>
</table>

[Back to homepage](../papers4dtor.md)

## [Building virtual representations](#content)
Each system brings its own blind spots, but a digital twin system can integrate them to cover other's blind spots and yield a comprehensive view.

Modeling: abstract the real-world EoP by digital models. three types of digital model. Mathematical equations (problem structuring, soft OR.) Simulation model (Hybrid.) AI-based. Directly learn from data. Complexity evaluation.

Supporting data. Inter-departmental, inter-firm. Methods: connecting information systems within a firm; sharing of the key information between firms (information sharing). Difficulties in processing data: missing data. duplicated, inconsistency. information fusion. (Discussion on data fusion, integration, aggregation). What types of data are most useful?

### Digital models - mathematical equations
11. **The characteristics of problem structuring methods: A literature review**. EJOR, 2019. [paper](https://doi.org/10.1016/j.ejor.2018.05.003). *Chris M. Smith, Duncan Shaw*

4. **Soft OR and Practice: The Contribution of the Founders of Operations Research**. Operations Research, 2021. [paper](https://doi.org/10.1287/opre.2020.2051). *Robert G. Dyson, Frances A. O’Brien, Devan B. Shah*.
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

### Digital models - simulation models

10. **Hybrid simulation modelling in operational research: A state-of-the-art review**. EJOR, 2018. [paper](https://doi.org/10.1016/j.ejor.2018.10.025). *Sally C. Brailsford , Tillal Eldabi , Martin Kunc , Navonil Mustafee , Andres F. Osorio*. 

> Simulation approaches in manufacturing and business: discrete-event simulation (DES), system dynamics (SD) and agent-based simulation (ABS) 

> An increasing interest in hybrid simulation (defined as models that combined at least two of these approaches) to model complex enterprise-wide systems.

> Bennett (1985) discusses three levels at which different OR methods could be combined. The lowest level, Comparison, involves using two or more methods entirely separately for the purpose of solving different aspects of a problem which could not be tackled by any one method on its own. The next level, Enrichment, aims to enhance one method (the main method) by using elements of another. The highest level, Integration, treats the methods on an equal footing and uses elements of each to generate something to- tally new.

> Most real-world problems and systems are complex, with many different features and characteristics, and very rarely is one single method ideally suited to capture all of them. The modeller who chooses to use only one method is therefore faced with a dilemma: to model the whole problem using one single method, accepting that it makes invalid assumptions or oversimplifies some aspects, or to model only those parts of the problem for which their chosen method is suitable and simply say that the remaining parts are out of scope? The former approach may lead to poor solutions (and bad decisions), but from a practical perspective it may be neither useful nor sensible to study only one aspect of a real-world problem in isolation. This dilemma has also driven the need for hybrid simulation.

> We originally hypothesised that hybrid simulation approaches have become more popular because modern business problems are more complex. However, it may be that business problems were always complex, and simulation modellers have simply become more ambitious about the types of problem that can be tackled. Either way, hybrid simulation is clearly here to stay.

![](./image/Stages-of-simulation-study.png) 


### [Supporting data] - methods and difficulties

1. **The Internet of Things and Information Fusion: Who Talks to Who?**. M&SOM, 2021. [paper](https://pubsonline.informs.org/doi/10.1287/msom.2020.0958). *Soroush Saghafian, Brian Tomlin, Stephan Billerc* <font color=purple>@TAG integration of data (interfirm); data quality; ownership</font>

> Problem definition: <font color=green>@RQ Autonomous sensors connected through the internet of things (IoT) are deployed by different firms in the same environment. The sensors measure an important operating-condition state variable, but their measurements are noisy, so estimates are imperfect. Sensors can improve their own estimates by soliciting estimates from other sensors. The choice of which sensors to communicate with (target) is challenging because sensors (1) are constrained in the number of sensors they can target and (2) only have partial knowledge of how other sensors operate—that is, they do not know others’ underlying inference algorithms/models. We study the targeting problem, examine the evolution of interfirm sensor communication patterns, and explore what drives the patterns.</font>

> Consider any given sensor $i$, and assume (without loss of generality) that it can select its target from two sensors: a high-quality sensor (labeled $h$) and a lower-quality sensor (labeled $l$). When should sensor $i$ target sensor $h$? When should it target sensor $l$? How does this choice depend on the initial state $s_0$?

2. **In-situ AI: Towards Autonomous and Incremental Deep Learning for IoT Systems**, 2018 IEEE International Symposium on High Performance Computer Architecture. [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8327001). *Mingcong Song; Kan Zhong; Jiaqi Zhang; Yang Hu; Duo Liu; Weigong Zhang; Jing Wang; Tao Li*

> Rather than constantly moving a tremendous amount of raw data to the Cloud, it would be beneficial to leverage the emerging powerful IoT devices to perform the inference task.
> - Two factors in the real IoT systems: data is dynamic and unlabeled. 

> <font color=green>@RQ Nevertheless, the statically trained model could not efficiently handle the dynamic data in the real in-situ environments, which leads to low accuracy. Moreover, the big raw IoT data challenges the traditional supervised training method in the Cloud.</font>

> We propose In-situ AI, the first Autonomous and Incremental computing framework and architecture for deep learning based IoT applications. We equip deep learning based IoT system with autonomous IoT data diagnosis (minimize data movement), and incremental and unsupervised training method (tackle the big raw IoT data generated in ever-changing in-situ environments).

> The result shows:
> - (1) a tradeoff exists between fast response time and energy-efficiency; 
> - (2) latency and energy-efficiency are two key metrics for inference task, while energy-efficiency is the only design concern for the diagnosis task.

3. **Application of IoT-Aided Simulation to Manufacturing Systems in Cyber-Physical System**. Machines, 2019. [paper](https://doi.org/10.3390/machines7010002). *Yifei Tan, Wenhe Yang, Kohtaroh Yoshida, Soemon Takakuwa*

> <font color=green>@RQ Issues such as the reception of real-time data from the IoT, as well as the conversion and inputting of the data into a simulation model have not yet been completely solved. Even though some general roadmaps and frameworks have been proposed, it is still not clear what kind of data and information must be integrated.</font>

> When constructing a DT, a specific framework to guide the process of extracting the necessary data from the physical system and a scheme for entering these data into the cyber-side simulation model are required.

