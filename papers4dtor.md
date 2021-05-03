# Papers: Digital Twin and Operations Research
We would like to maintain resources that discuss digital twins (DT) and the related issues in operations research (OR).

*2021-05-03:*
- We use <font color=green>green font (in visual studio code)/@RQ (in GitHub) to highlight the research questions</font>
- We use <font color=purple>purple font</font> (in visual studio code)/@TAG (in GitHub)to highlight the tags, including:
	- introduction
	- integration of data/intelligent/human
	- real-time optimization
	- ownership
	- inter-operability
	- composability
	- servitization
	- synchronization fidelity
	- synchronization frequency
	- modeling
	- data quality
	- ...


## [Content](#content)

<table>
<tr><td colspan="2"><a href="#research-papers-in-dt">1. Research papers in DT</a></td></tr> 
<tr>
	<td>&emsp;<a href=#concept-development>1.1 Concept development</a></td>
	<td>&emsp;<a href=#survey-paper>1.2 Survey</a></td>
</tr>
<tr><td colspan="2"><a href="#industry-reports-in-dt">2. Industry reports in DT</a></td></tr> 
<tr><td colspan="2"><a href="#related-research-papers-in-or">3. Related research papers in OR</a></td></tr>
<tr>
	<td>&emsp;<a href=#survey>2.1 Survey</a></td>
	<td>&emsp;<a href=#modeling-complex-eop>2.2 Modeling complex EoP</a></td>
</tr>
<tr>
	<td>&emsp;<a href=#symbiotic-simulation>2.3 Symbiotic simulation</a></td>
	<td>&emsp;<a href=#integration-of-data>2.4 Integration of data</a></td>
</tr>
<tr>
	<td>&emsp;<a href=#real-time-optimization>2.5 Real-time optimization</a></td>
	<td>&emsp;<a href=#inter-operability>2.6 Inter-operability</a></td>
</tr>
</tr>
</table>



## [Research papers in DT](#content)

### [Concept development](#content)
1. 

### [Survey paper](#content)
1. 

## [Industry reports in DT](#content)
1. **Digital Twin Consortium Defines Digital Twin**. The Digital Twin Consortium, 2020. [article](https://blog.digitaltwinconsortium.org/2020/12/digital-twin-consortium-defines-digital-twin.html)

>A digital twin is a virtual representation of real-world entities and processes, synchronized at a specified frequency and fidelity. 
> - Digital twin systems transform business by accelerating holistic understanding, optimal decision-making, and effective action.
> - Digital twins use real-time and historical data to represent the past and present and simulate predicted futures.
> - Digital twins are motivated by outcomes, tailored to use cases, powered by integration, built on data, guided by domain knowledge, and implemented in IT/OT systems.

>The foundational elements of the definition are captured in the first sentence: the virtual representation, the real-world entities and processes it represents, and the mechanism by which the virtual and real-world entities are synchronized.

2. **How Digital Twins Enable Holistic Understanding**. The Digital Twin Consortium, 2021. [article](https://blog.digitaltwinconsortium.org/2021/01/how-digital-twins-enable-holistic-understanding.html)

> The five key components required to achieve holistic value with a digital twin are: 
> - Data connections, such as IoT sensors and enterprise design and operational data, to enable real-world synchronization 
> - Descriptive models to accurately inform, monitor and react 
> - Predictive models, such as Simulation or Machine learning to anticipate situations and provide awareness of the evolution of a system
> - Common ontologies and a common modeling language to guarantee consistency
> - Analytics services to detect trends and anomalies, trigger user notifications, test alternative scenarios and robustness, optimize levers, and control automation.

> In addition, there are three key enablers that contribute to delivering this holistic value, namely:
> - High scalability of components to scale to the system level
> - High performance to synchronize with the real-world systems, predict and act in real-time
> - Capacity to twin a complex system composed of heterogeneous and interconnected components.

<font color=purple>@TAG integration of data and intelligence; inter-operability; modeling</font>

3. **The Case for the Digital Thread**. The Digital Twin Consortium, 2021. [article](https://blog.digitaltwinconsortium.org/2020/12/the-case-for-the-digital-thread.html)

> Digital Twin Consortium defines the digital thread as a mechanism for correlating information across multiple dimensions of the virtual representation, where the dimensions include (but are not limited to) time or lifecycle stage (including design intent), kind-of-model, and configuration history; the mechanism generally relies on stable, consistent real-world identifiers

> Five steps can increase the value of your digital twin by containing the cost of implementation.
> - Provide standards from an owner’s perspective
> - Identify opportunities to do once and deploy many times 
> - Enable a digital thread through all processes and phases - Assess and understand all the components and processes that contribute to the value chain and package them in an integrated manner rather than allowing the current silos apparent in all organizations to propagate and strengthen. Collaboration cannot flourish in a siloed organization but a requirement to implement a digital thread will quickly confront the silos and enable efficiencies in the organization.
> - Configure systems to support the digital thread
> - Provide supervision to enable the digital thread 

4. **Transforming Businesses using Digital Twin**. The Digital Twin Consortium, 2021. [article](https://blog.digitaltwinconsortium.org/2021/01/transforming-businesses-using-digital-twin-.html)
> Each system brings its own blind spots, but a digital twin system can integrate them to cover each others’ blind spots and yield a comprehensive view.

5. **Technology Vision 2021**. Accenture, 2021. [report](https://www.accenture.com/us-en/insights/technology/_acnmedia/Thought-Leadership-Assets/PDF-4/Accenture-Tech-Vision-2021-Full-Report.pdf)
> The mirrored world is the amalgamation of these threads; as more enterprises build and connect intelligent twins, bringing more of their organization into digital space, they are opening a cornucopia of new opportunities and ways of doing business. 

> Leaders will be able to make data and intelligence the primary orchestrators of the business, increasing real-time agility at scale, overhauling their innovation processes, and forming entirely new mirrored-world ecosystems and partnerships.

> Many organizations struggled because they couldn’t easily answer these big-picture queries....Bringing data and intelligence together at this magnitude is what makes building intelligent twins and the mirrored world so critical. They will let enterprises ask and answer big-picture questions: How will it impact my operations if I have to shutter this warehouse? What will happen if this vendor’s supply chain fails? How can I update this product to be more sustainable—and is that achievable with my existing vendors?

> When intelligent twins are connected in mirror environments, they are a powerful way
to turn data into actionable, big-picture insights. But incomplete or incorrect data will lead to false conclusions. ... High-quality historic data is critical for intelligent twins—it’s what the twin uses to monitor real-time machine performance, build models of customer behavior to help design custom products, and more...Going forward, enterprises cannot rely on historic data blindly—they need to check and correct their models as the world changes.
> ... the tools to prepare, analyze, and visualize the massive amounts of information gathered. Today, many enterprises are already investing in IoT devices and sensors, but struggle to fully utilize the data these devices generate. 
<font color=purple>@TAG data quality; integration of data and intelligence</font>

> They are, essentially, a risk-free playground to explore new product ideas, strategize for many possible futures, and explore limitless “what-if” scenarios. Most businesses experimenting with this kind of simulation today are doing so at a smaller scale, but the capabilities they are demonstrating will only become more valuable when enterprises can tap into multiple twins in fully mirrored environments.

> Have ecosystem-scale thinking lead digital twin strategies.Target large systems as the long-term target digital twins. Think entire offices, supply chains, and more. Use individual twins as a means to gain greater visibility into larger collaborations.

> 18% (24%) of the organization are scaling up or experimenting the technology of digital twins with this year.

> 65% of executives expect their organization’s investment in intelligent digital twins to increase over the next three years

> Only 11% of executives estimate that 100 percent of the data provided through IoT devices and/or sensors in their organizations is fully utilized.

6. **Enabling Technologies for Industry 5.0**. 
Publications Office of the European Union, 2020. [report](https://op.europa.eu/en/publication-detail/-/publication/8e5de100-2a1c-11eb-9d7e-01aa75ed71a1/language-en)

> digital twins and simulation technologies optimize production, test products and processes and detect possible harmful effects, for instance:
> - Digital twins of products and processes
> - Virtual simulation and testing of products and processes (e.g., for human-centricity, working and operational safety)
> - Multi-scale dynamic modeling and simulation
> - Simulation and measurement of environmental and social impact
> - Cyber-physical systems and digital twins of entire systems
> - Planned maintenance

7. **IoT 2.0 and the INTERNET of TRANSFORMATION (Web of Things and Digital Twins)**. Publications Office of the European Union, 2020. [report](https://publications.jrc.ec.europa.eu/repository/handle/JRC120372)

> This new paradigm builds on top of existing digital infrastructures and, taking care of connecting as many living (persons) and non-living entities (things) as possible, generates actionable intelligence by leveraging the integration and analytics of the data shared by the connected entities.

8. **Gartner Top 10 Strategic Technology Trends for 2019**. Gartner, 2019. [report](https://www.gartner.com/smarterwithgartner/gartner-top-10-strategic-technology-trends-for-2019/)

## [Related research papers in OR](#content)

### [Survey](#content)
1. **Industry 4.0: Opportunities and Challenges for Operations Management**. M&SOM, 2019. [paper](https://pubsonline.informs.org/doi/pdf/10.1287/msom.2019.0796)
*Tava Lennon Olsen, Brian Tomlin*
>The crucial aspect here is the “live setting”; that is, it is not simply a static digital representation of an object before use, but it is a dynamic representation of the object that evolves in use. Real-time sensor measurements across a range of elements enable a system-level representation of a complex asset (e.g., a turbine) or indeed, an entire production system. The physical world has a dynamically coupled representation in the digital world, and this data-rich environment can enable operations managers to uncover previously unknown relationships between system conditions and outcomes. This understanding can drive continuous improvement in defect reduction, uptime, and other key performance indicators of the existing system while also generating improved manufacturability design ideas for future products and factories. <font color=purple>@TAG real-time optimization; </font>

> “Digital twins exist at the nexus of physical engineering, data science, and machine learning” (GE 2016, p. 2), and this holds true for IoT-enabled operations more broadly. Distilling the vast data generated from sensors into actionable knowledge will be a formidable challenge. Real-time, data-rich, system-level optimization within and across networks of factories and assets will require algorithms that can solve extremely large problems almost instantaneously. Such difficulties offer ample research opportunities in the realm of data analytics and optimization methods. <font color=purple>@TAG real-time optimization</font>

> Therefore, viewing IoT-enabled operations as information-rich ones, one might conclude that the interesting research questions have already been explored. This would be an unfortunate conclusion. IoT-enabled operations will deliver a much broader array of production- and logistics-relevant data, <font color=green>@RQ opening up questions as to what types of data are most useful, how the data should be best used, and how data ownership in inter-firm production systems (e.g., servitization of processing assets) would be best configured.</font> That is, the IoT will lead to a wide variety of research questions related to the design of the processes and procedures for managing operations and supply chains. <font color=purple>@TAG integration of data; ownership; servitization</font>

2. **Enabling Smarter Cities with Operations Management**. M&SOM, 2020. [paper](https://pubsonline.informs.org/doi/pdf/10.1287/msom.2020.0929). *Ho-Yin Mak*

> The real-time generation of data enables the digital twin concept: on the IoT, it is possible to create a digital replica of each physical device, which can be monitored and analyzed digitally in real time. Supported by data supplied by the IoT, integrated models of the network of digital twins allows for visualization, experimentation, simulation, and optimization of various operations before physical implementation. <font color=purple>@TAG real-time; integration of data and intelligence</font>

> Research questions in efficiency: <font color=green>@RQ With access to such real-time data, it is possible to design and operate a much more dynamic, demand-responsive service than the current fixed-schedule service. ... There is likely to be a tradeoff between the (costs of) information and the potential efficiency improvements that OM-trained researchers and practitioners are well equipped to model and assess.</font> <font color=purple>@TAG real-time optimization</font>

> Research questions in smart parking: <font color=green>@RQ Making real-time parking data public is difficult due to challenges in data acquisition and access....it is also of interest to investigate the problem of how many sensors to deploy (and where), balancing between the costs and the potential revenue (or some efficiency-based objective) that is optimized based on data acquired by the sensors. One issue of interest is the possible tradeoff between revenue extraction and information acquisition—it could be optimal, for instance, to deploy (more) sensors at locations not deemed important from the revenue perspective, but could provide important information to optimize the overall performance of the parking network.</font> <font color=purple>@TAG real-time optimization</font>

> Beyond data collection, managing data ownership and access is also a key issue... This motivates two important and related questions for researchers to investigate, namely, the incentives for private operators to open access to their data and the potential value of developing a centralized platform to pool such data. <font color=purple>@TAG synchronization fidelity</font>

3. **What Is Different About Digital Strategy? From Quantitative to Qualitative Change**. STRATEGY SCIENCE, 2019. [paper](https://pubsonline.informs.org/doi/pdf/10.1287/stsc.2019.0099). *Ron Adner, Phanish Puranam, Feng Zhu*

> We suggest that this “something” can be understood as a transition from quantitative improvements to qualitative changes. While we do not minimize the miracles that have led to, and been enabled by, the exponential improvement in processing power, storage capacity, bandwidth, and their associated costs, we suggest that their impact has been well accommodated within the existing strategy canon until recently. Therefore, we focus on the qualitative changes that interact to produce truly novel outcomes. We posit that the changes we highlight demand a re-examination and expansion of the strategy principles that have guided the field’s approach to technological transitions thus far. This is a conversation we hope others will swiftly join—to challenge, complement, and ultimately improve our collective understanding of firm strategy in the digital era. <font color=purple>@TAG introduction</font>

> Finally, beyond the quantitative growth in data storage capacity and reduction in storage costs is a third qualitative shift—that of data aggregation. A qualitative shift arises from the ability to combine previously disjoint data (e.g., location, search query, and social network) to answer questions that were formerly impossible to address. <font color=purple>@TAG integration of data</font>

> While each of these effects of digitization is significant, truly dramatic changes become visible when they interact and reinforce each other.
> > To provide a concrete example, “digital twins” currently enable physical processes (e.g., the wear and tear of a jet engine) to be represented digitally in the form of a simulation model. Such a model derives its predictive power from the dynamic connectivity to the actual engine being modeled, aggregation of data across similar engines in other planes, and the use of algorithms to extract predictive insights from these data. Crucially, the resulting model enables not just preventive maintenance but may also enable virtual experimentation for design improvements. As McAfee (2019) argues, simulation supports a dramatic increase in the effectiveness of search for efficiencies, given that virtual prototyping does not face the same resource constraints as prototyping in the real world. Connectivity, aggregation, and representation lay the digital foundations on which such virtual prototyping can take place. <font color=purple>@TAG introduction</font>

> - *Resource-Based View (RBV): Data and Algorithms as Self-Generating Resources*. In order to understand the complexities that arise from how data are generated and consumed, consider a particularly interesting new form of digital data creation that can be described as “*autogenic*.” This arises when the very act of engaging with data creates new data. ... <font color=green>@RQ If data and algorithms are resources, their replication may be a qualitatively distinct phenomenon from knowledge transfer among humans (Szulanski 1996). On the one hand, issues of stickiness and causal ambiguity might appear less relevant in replicating digital content. Indeed, one might be concerned that costless large-scale replication may imply a homogeneity of beliefs throughout a system that may curtail organizational exploration (March 1991). **On the other hand, stickiness may be even more important in the use by humans of the insights generated algorithmically from data. The confidence that human decision makers place in algorithmically derived insight may depend, at least in some cases, on their ability to comprehend the causal structure of the process that generates the insight, and numerous state-of-the art techniques in machine learning do not offer such causal understanding. (trust)**</font> <font color=purple>@TAG integration of data, intelligence, and human</font>

> - *Data, Ownership, and Factor Markets:* General Motors and John Deere, among other manufacturers, argued that ownership of a vehicle does not include ownership of the underlying computer software in a vehicle (Wiens 2015). <font color=green>@RQ data—particularly their algorithmic use—create ownership difficulties; this is because near costless and perfect replication imply that, unlike a physical good, data can be reused, repackaged, and resold ad infinitum. As the combination of autogenesis, scalability, and fungibility becomes more common, we can expect greater variety in observed solutions to the contracting challenges their potential creates.</font> <font color=purple>@TAG integration of data and intelligence; ownership</font>

> - **Digitization, Replication, and Super-Scalable Business Models:** Once a process or some information is in digital format, replication becomes error free and often costless. Consequently, scalability can improve significantly when this property interacts with connectivity. For example, when Amazon develops a better algorithm to match consumers with products, a digital copy of that algorithm can instantly be made available in millions of virtual storefronts for Amazon customers worldwide. <font color=purple>@TAG inter-operability</font>

> However, within organizations, digital transformation has also created numerous new opportunities for “algorithmic management,” in which algorithms and data augment or perhaps even automate managerial work. The way that algorithms and humans can work together is rapidly emerging as a high-interest research area in many fields, such as computer science, human–computer interactions, and consumer behavior, and the implications for organization design are definitely of interest to strategy researchers (Puranam 2018). <font color=purple>@TAG integration of intelligence and human</font>

> **Organizational Sense-making in an Algorithmic World:** In this regard, cutting-edge techniques such as machine learning produce an additional qualitative shift in how data are used—from representing data to improving human perception of phenomena to prediction, which may or may not involve or be subject to human comprehension. There is a delicate balance that managers may have to strike in this area: they may need to let go of the need to understand in order to satisfy the need to predict. Yet, the risks of ethically repellant outcomes and regulatory constraints and the desire to satisfy sheer human curiosity make this balancing act far from trivial. Theorists may well soon face similar challenges (Puranam 2019). In the meantime, as algorithmic representation becomes ever more effective while becoming ever less comprehensible, the rise of new organizational roles—like *Data Storyteller*—may not be as surprising as it initially appears. As Weick suggested, a comprehensible and motivating story may have value independent of its veracity (Weick 1995). In a “mixed economy” of algorithmic decision analysis but ultimately human decision responsibility, compelling and clear narratives may become more, not less, important. <font color=purple>@TAG integration of intelligence and human</font>

### [Modeling complex EoP](#content)

### [Symbiotic Simulation](#content)

1. **Symbiotic Simulation Systems: An Extended Definition Motivated by Symbiosis in Biology**. 22nd Workshop on Principles of Advanced and Distributed Simulation, 2008. [paper](https://ieeexplore.ieee.org/document/4545331). *Heiko Aydt, Stephen John Turner, Wentong Cai, Malcolm Yoke Hean Low* 

> We define a symbiotic simulation system as a close association between a simulation system and a physical system.
> However, control feedback to the physical system is optional. (closed-loop and open-loop)
> - (closed-loop) symbiotic simulation decision support system: indirectly influences the physical system
> - symbiotic simulation control system: directly influences the physical system
> - (open-loop) symbiotic simulation forecasting system: forecast the behavior of the physical system
> - symbiotic simulation model validation system
> - symbiotic simulation anomaly detection system

2. **Research issues in symbiotic simulation**. Proceedings of the 2009 Winter Simulation Conference, 2019. [paper](https://ieeexplore.ieee.org/document/5429419/). *Heiko Aydt, Stephen John Turner, Wentong Cai, Malcolm Yoke Hean Low*.

> Symbiotic simulation is a paradigm in which a simulation system and a physical system are closely associated with each other.
> - The simulation system benefits from real-time measurements about the physical system which are provided by corresponding sensors. 
> - The physical system, on the other side, may benefit from the effects of decisions made by the simulation system. 

> An important concept in symbiotic simulation is that of the what-if analysis process which is concerned with the evaluation of a number of what-if scenarios by means of simulation.


3. **Symbiotic simulation system: hybrid systems model meets big data analytics**. Proceedings of the 2018 Winter Simulation Conference, 2018. [paper](). *Bhakti Stephan Onggo, Navonil Mustafee, Andi Smart, Angel A. Juan, Owen Molloy*. 

> In a symbiotic simulation system (SSS), there is a level of interaction between a simulation model and the physical system that it represents (Aydt et al. 2008). 

> It is designed to support decision making at the operational levels by making use of real- or near real-time data (generated by the physical system), and which is streamed subsequent to the development of the simulation model. In addition to the simulation model, a symbiotic simulation system may comprise data analytics and machine learning models, optimization models, as well as data acquisition module and actuators.
> - Type 1 (Decision Support Symbiotic Simulation System) – Here the output from a scenario manager or an optimization model will be used to help a decision maker to control the physical system.
> - Type 2 (Control Symbiotic Simulation System) – Here the output will directly affect the physical
system through an actuator.
> - Type 3 (Open Loop Symbiotic Simulation System) – No direct feedback mechanism exists.

4. **Combining symbiotic simulation systems with enterprise data storage systems for real-time decision-making**. Enterprise Information Systems, 2021. [paper](https://doi.org/10.1080/17517575.2020.1777587). *B. S. Onggo, Canan G. Corlu, Angel A. Juan , Thomas Monks, Rocio de la Torre*. 

> A symbiotic simulation system (S3) enables interactions between a physical system and its computational model representation. To support operational decisions, an S3 uses real-time data from the physical system, which is gathered via sensors and saved in an enterprise data storage system (EDSS).

> Open research challenges
> - to integrate its different technologies, i.e., data acquisition, analytics, and machine learning.
> - standardization and inter-operability
> - scalability issues
> - security and data-privacy issues
> - methodological challenges <font color=green>@RQ (i)how to deal with highly dynamic physical systems; (ii) the need for suitable algorithms (e.g. optimization, machine learning) in a short-term decision-making environment; and (iii) how to create simulation models that are also adaptive in order to reflect changes in the physical system.</font>


### [Integration of Data](#content)

1. **The Internet of Things and Information Fusion: Who Talks to Who?**. M&SOM, 2021. [paper](https://pubsonline.informs.org/doi/10.1287/msom.2020.0958). *Soroush Saghafian, Brian Tomlin, Stephan Billerc* <font color=purple>@TAG integration of data (interfirm); data quality; ownership</font>

> Problem definition: <font color=green>@RQ Autonomous sensors connected through the internet of things (IoT) are deployed by different firms in the same environment. The sensors measure an important operating-condition state variable, but their measurements are noisy, so estimates are imperfect. Sensors can improve their own estimates by soliciting estimates from other sensors. The choice of which sensors to communicate with (target) is challenging because sensors (1) are constrained in the number of sensors they can target and (2) only have partial knowledge of how other sensors operate—that is, they do not know others’ underlying inference algorithms/models. We study the targeting problem, examine the evolution of interfirm sensor communication patterns, and explore what drives the patterns.</font>

> Consider any given sensor $i$, and assume (without loss of generality) that it can select its target from two sensors: a high-quality sensor (labeled $h$) and a lower-quality sensor (labeled $l$). When should sensor $i$ target sensor $h$? When should it target sensor $l$? How does this choice depend on the initial state $s_0$?

## [Real-time Optimization](#content)

The challenges in real-time optimization is to address the difficulties of a large and complicated solution space and short computation time constraints. Related methods include but not limited to:
- multi-fidelity approaches
- parallel computing
- offline simulation online application

1. **Multi-fidelity simulation optimization for airline disruption management**. Proceedings of the 2018 Winter Simulation Conference, 2018. [paper](https://ieeexplore.ieee.org/document/8632329). *Luke Rhodes-Leader, David J. Worthington, Barry L. Nelson, Bhakti Stephan Onggo*. <font color=purple>@TAG real-time optimization; synchronization fidelity</font>

> This paper presents a method for the aircraft recovery problem that uses multi-fidelity modeling including a trust region simulation optimization algorithm to mitigate the computational costs of using high-fidelity simulations with its benefits for providing good estimates of the true performance.

> <font color=green>@RQ The contribution of this paper is a method to balance the need to use a high-fidelity simulation model to estimate the performance of a recovery option with the computational difficulties associated with simulation in this context. These difficulties include a large and complicated solution space and short computation time constraints.</font>

> Future work will include considering how the repeated nature of the problem could be exploited to improve both the models and the optimization process in a symbiotic manner.

## [Inter-operability](#content)

1. **Learning to Approximate Industrial Problems by Operations Research Classic Problems**. OR, 2021. [paper](https://doi.org/10.1287/opre.2020.2094). *Axel Parmentier* <font color=purple>@TAG inter-operability</font>

> Challenges: Practitioners of operations research often consider difficult variants of well-known optimization problems and struggle to find a good algorithm for their variants although decades of research have produced highly efficient algorithms for the well-known problems. 

> Methods: We introduce a machine learning for operations research paradigm to build efficient heuristics for such variants: use a machine learning predictor to turn an instance of the variant into an instance of the well-known problem, then solve the instance of the well-known problem, and finally retrieve a solution of the variant from the solution of the well-known problem. This paradigm requires learning the predictor that transforms an instance of the variant into an instance of the well-known problem. We introduce a structured learning methodology to learn that predictor.