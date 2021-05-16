# Papers: Digital Twin and Operations Research
We would like to maintain resources that discuss digital twins (DT) and the related issues in operations research (OR).

- We use <font color=green>green font (in visual studio code)/@RQ (in GitHub) to highlight the research questions</font>
- We use <font color=purple>purple font</font> (in visual studio code)/@TAG (in GitHub)to highlight the tags, including:
	- introduction
	- integration of data/intelligent/human
	- real-time optimization
	- ownership
	- standardization
	- inter-operability
	- composability
	- servitization
	- synchronization fidelity
	- synchronization frequency
	- modeling
	- data quality
	- ...

*2021-05-05:*
- Working on the research question and related research on the real-time decision-making issue.

*2021-05-16:*
- Update related research on solving problems in real-time
- Working on the research question and related research on building digital models.

## [Content](#content)

<table>
<tr><td colspan="2"><a href="#research-papers-in-dt">1. Research papers in DT</a></td></tr> 
<tr><td colspan="2">&emsp;<a href="#concept-and-survey">1.1 Concept development and survey</a></td></tr>
<tr><td colspan="2"><a href="#industry-reports-in-dt">2. Industry reports in DT</a></td></tr> 
<tr><td colspan="2"><a href="#related-research-papers-in-or">3. Related research papers in OR</a></td></tr>
<tr><td colspan="2">&emsp;<a href="#survey">2.0 Survey</a></td></tr>
<tr><td colspan="2">&emsp;<a href="#building-digital-models">2. 1 Building digital models</a></td></tr>
<tr>
	<td>&emsp;&emsp;<a href=#integration-of-data>2.1.x Integration of data</a></td>
	<td>&emsp;&emsp;<a href=#sychronization-frequency>2.1.x Synchronization frequency</a></td>
</tr>
<tr><td colspan="2">&emsp;<a href="#solving-problems-in-real-time">2.2 Solving problems in real-time</a></td></tr>
<tr>
	<td>&emsp;&emsp;<a href=#symbiotic-simulation>2.2.1 Symbiotic simulation</a></td>
	<td>&emsp;&emsp;<a href=#online-problems>2.2.2 Online problems</a></td>
</tr>
<tr>
	<td>&emsp;&emsp;<a href=#simulation-optmization>2.2.3 Simulation optmization</a></td>
	<td>&emsp;&emsp;<a href=#offline-simulation-online-application>2.2.4 Offline simulation online application</a></td>
</tr>
<tr>
	<td>&emsp;&emsp;<a href=#multi-fidelity-approaches>2.2.5 Multi-fidelity approaches</a></td>
	<td>&emsp;&emsp;<a href=#parallel-computing>2.2.6 Parallel computing</a></td>
</tr>
<tr>
	<td>&emsp;&emsp;<a href=#metamodeling>2.2.7 Metamodeling</a></td>
	<td>&emsp;&emsp;<a href=#applications>2.2.8 Applications</a></td>
</tr>
<tr><td colspan="2">&emsp;<a href="#dt-management">2.3 DT management</a></td></tr>
<tr>
	<td>&emsp;&emsp;<a href=#stakeholder-management>x.x.x stakeholder management</a></td>
	<td>&emsp;&emsp;<a href=#inter-operability>x.x.x inter-operability</a></td>
</tr>
</table>


## [Research papers in DT](#content)

### [Concept and Survey](#content)
1. **Product lifecycle management: the new paradigm for enterprises**. Int. J. Product Development, 2005. [paper](https://ideas.repec.org/a/ids/ijpdev/v2y2005i1-2p71-84.html). *Michael W. Grieves*

> Mirrored Spaces Model (MSM): The model consists of three elements: real space, virtual space(s), and a linking mechanism, referred to as data, and information/process connection real space and virtual space(s).

> Incompatibilities
> - incompatibility of data: Incompatibility of data refers to the issue of data representations about characteristics being present in one representation of an object and not being present in another. (<font color=purple>@TAG data quality</font>)
> - incompatibility of structure (<font color=purple>@TAG inter-operability</font>)

2. **NASA Modeling, Simulation, Information
Technology & Processing Roadmap - TA11**. NASA, 2010. [report](https://www.nasa.gov/pdf/501321main_TA11-MSITP-DRAFT-Nov2010-A1.pdf)

> What is not considered by these individual efforts is a comprehensive integration of best-physics models across disciplines. If those best-physics (i.e., the most accurate, physically realistic and robust) models can be integrated, they will form a basis for certification of vehicles by simulation and real-time, continuous, health management of those vehicles during their missions. They will form the foundation of a NASA digital twin. <font color=purple>@TAG modeling; domain knowledge</font>
> - One application of the digital twin is to fly the actual vehicle’s future mission(s) before its launch.
> - A second application is to mirror the actual flight of its flying twin.
> - A third application is to perform in-situ forensics in the event of a potentially catastrophic fault or damage.
> - A fourth application is to serve as a platform where the effects of modifications to mission parameters, not considered during the design phase of the flying twin, can be studied.

3. **NASA Technology Roadmaps TA 11: Modeling, Simulation, Information Technology, and Processing (final)**. NASA, 2015. [report](https://www.nasa.gov/sites/default/files/atoms/files/2015_nasa_technology_roadmaps_ta_11_modeling_simulation_final.pdf).

4. **The Digital Twin Paradigm for Future NASA and U.S. Air Force Vehicles**. 53rd AIAA/ASME/ASCE/AHS/ASC Structures, Structural Dynamics and Materials Conference, 2012. [paper](https://arc.aiaa.org/doi/10.2514/6.2012-1818). *Edward Glaessgen, David Stargel*

5. **Digital Twin: Manufacturing Excellence through Virtual Factory Replication**, ResearchGate, 2015. [paper](https://www.researchgate.net/publication/275211047_Digital_Twin_Manufacturing_Excellence_through_Virtual_Factory_Replication). *Michael Grieves*

6. **Digital Twin: Mitigating Unpredictable, Undesirable Emergent Behavior in Complex Systems (Excerpt)**, In book: Transdisciplinary Perspectives on Complex Systems, 2017. [paper](https://www.researchgate.net/publication/306223791_Digital_Twin_Mitigating_Unpredictable_Undesirable_Emergent_Behavior_in_Complex_Systems). *Michael Grieves, John Vickers*

7. **Digital twin-driven product design, manufacturing and service with big data**. Int J Adv Manuf Technol, 2018. [paper](https://link.springer.com/article/10.1007/s00170-017-0233-1) *Fei Tao, Jiangfeng Cheng, Qinglin Qi, Meng Zhang, He Zhang, Fangyuan Sui*

8. **The Digital Twin: Demonstrating the Potential of Real Time Data Acquisition in Production Systems**. Procedia Manufacturing, 2017. [paper](https://www.sciencedirect.com/science/article/pii/S2351978917301610). *Thomas H.-J Uhlemann, Christoph Schock, Christian Lehmann, Stefan Freiberger, RolfS teinhilper*

9. **Digital Twin in manufacturing: A categorical literature review and classification**. IFAC-PapersOnLine, 2018. [paper](https://www.sciencedirect.com/science/article/pii/S2405896318316021). *Werner Kritzinger, Matthias Karner, Georg Traar, Jan Henjes, Wilfried Sihn*

10. **Next Generation Digital Twin: an Ecosystem for Mechatronic Systems?**. IFAC-PapersOnLine, 2019.[paper](https://www.sciencedirect.com/science/article/pii/S2405896319316763). *Roland Rosen, Jan Fischer, Stefan Boschert*

11. **Digital twin driven human–robot collaborative assembly**. CIRP Annals - Manufacturing Technology, 2019. [paper](https://doi.org/10.1016/j.cirp.2019.04.011). *Arne Bilberg, Ali Ahmad Malik **

12. **New disruption risk management perspectives in supply chain: digital twins, the ripple effect, and resileanness**. IFAC PapersOnLine, 2019. [paper](https://doi.org/10.1016/j.ifacol.2019.11.138). *Dmitry Ivanov, Alexandre Dolgui*

13. **Enabling technologies and tools for digital twin**. Journal of Manufacturing Systems, 2019. [paper](https://doi.org/10.1016/j.jmsy.2019.10.001). *Qinglin Qia, Fei Taoa, Tianliang Hub, Nabil Anwerc, Ang Liud, Yongli Weib, Lihui Wange, A.Y.C. Neef*

14. **Digital twin for smart manufacturing: the simulation aspect**. [paper](https://ieeexplore.ieee.org/document/9004659). Proceedings of the 2019 Winter Simulation Conference, 2019. *Guodong Shao, Sanjay Jain, Christoph Laroque, Loo Hay Lee, Peter Lendermann, Oliver Rose*

> In the simulation community, we need to help solve issues related to  <font color=green>@RQ
> - data management including data collection, data processing, and data analytics; 
> - real-time model synchronization that guarantees the digital twin reflects the current status of its physical twin; 
> - model generation that includes automatic data driven model creation and standard-based model generation; 
> - and model verification, validation, uncertainty quantification (VVUQ) (Shao and Kibira 2018; Lugaresi and Matta 2018).</font>

> Thus, new processes and interoperable systems must be designed, and existing ones have to be improved, since Industry 4.0 has placed extremely high expectations on production systems to have substantial increase in productivity, resource efficiency, and level of automation. <font color=purple>@TAG inter-operability</font>

15. **Digital Twin: Values, Challenges and Enablers From a Modeling Perspective**. IEEE Access, 2020. [paper](https://ieeexplore.ieee.org/document/8972429). *Adil Rasheed, Omer San, Trond Kvamsdal*

16. **Digital Twin in Industry: State-of-the-Art**.  IEEE Transactions on Industrial Informatics, 2018. [paper](https://ieeexplore.ieee.org/document/8477101). *Fei Tao, He Zhang, Ang Liu, A. Y. C. Nee*

17. **Review and comparison of the methods of designing the Digital Twin**. CIRP Design 2020, 2020. [paper](https://doi.org/10.1016/j.procir.2020.02.146). *Dmytro Adamenkoa,Steffen Kunnena, Robin Pluhnaua, André Loibla, Arun Nagarajaha*

18. **Towards a semantic Construction Digital Twin: Directions for future research**. Automation in Construction, 2020. [paper](https://doi.org/10.1016/j.autcon.2020.103179). *Calin Bojea, Annie Guerrieroa, Sylvain Kubickia, Yacine Rezguib*

19. **A Requirements Driven Digital Twin Framework: Specification and Opportunities**. IEEE Access, 2020. [paper](https://ieeexplore.ieee.org/document/9109299). *James Moyne; Yassine Qamsane; Efe C. Balta; Ilya Kovalenko; John Faris; Kira Barton; Dawn M. Tilbury*

> The framework includes a definition of an object-oriented (O-O) architecture for DTs that incorporates the bottom-up knowledge gained from practical development and implementation of today’s DT classes, while addressing requirements such as re-usability, extensibility, interoperability, interchangeability and autonomy incurred by SM trends and the ultimate SM vision. 
> - A common element of most DT solutions today is the use of a wide variety of models and analytics
>   - the developed solutions provide directed intelligence of a specific type in a specific context area utilizing specific data and behavior.
> 	- This usually means that a method of DT maintenance must be part of the solution, and this method must support an update of the DT intelligence to under- stand and adapt to changes in the application environment [46], [47].
>  	- Most of the DTs in use in factory operation are dedicated DTs, each with a specific purpose such as predict- ing remaining useful life or optimizing product quality. ("closed-loop")
> - One important gap is that most DT approaches today lack mechanisms that convey elements of prediction quality, such as prediction uncertainty and model accuracy, with respect to the application environment.

> Gaps and opportunities: <font color=purple>@TAG inter-operability; modeling</font>
> - Improving integrability, interoperability and inter-changeability of objects within the DT through definition of the interaction between models and with the computational engine in the DT object
> - Improving interoperability, interchangeability, reusability, etc. of DTs throughout the entire DT lifecycle with detailed specifications for support of the DT at each stage of the lifecycle and its transition between these stages.
> - Improving interoperability between DT and non-DT components with specifications that define the interaction between the DT service and clients to deliver the DT capability in an increasingly flexible environment.
> - Improving the maintainability component of the DT life-cycle with methods and specifications for DT maintenance as part of lifecycle on-line (e.g., model tuning), as well as off-line (e.g., model rebuilding) activities [30], [46]. Generally speaking, automation of the on-line maintenance capability should be supported today, while automation of the off-line capability is a longer-term objective (see below).
> - Automating all aspects of the DT lifecycle. The proliferation of and increased reliance on DTs across the entire manufacturing ecosystem eventually will require automation across most stages of the DT lifecycle, from design through maintenance. <font color=green>@RQ Many of the lifecycle steps such as evaluation and on-line maintenance are already automated in some applications, however automation of other stages, such as design, development, V&V and off-line rebuilding represent ongoing technical challenges. Additionally, automation of SME-to-analytics interaction in the various stages of the DT lifecycle will be required [4], [6].</font>
> - Accommodating analytical trends in DT technology. The analytics frontier is dynamic and unpredictable. Evolutionary and revolutionary (disruptive) technologies must be accommodated, or, at minimum, any DT framework should not prevent the use of these technologies. <font color=green>@RQExpected directions in this space include the move towards less narrow context-restricted solutions (e.g., AGI), and more automation of the role of analytics throughout the DT lifecycle.</font>

20. **Characterising the Digital Twin: A systematic literature review**. CIRP Journal of Manufacturing Science and Technology, 2020. [paper](https://doi.org/10.1016/j.cirpj.2020.02.002). *David Jones, Chris Snider, Aydin Nassehi, Jason Yon, Ben Hicks*.

> 13 characteristics (Physical Entity/Twin; Virtual Entity/Twin; Physical Environment; Virtual Environment; State; Realisation; Metrology; Twinning; Twinning Rate; Physical-to-Virtual Connection/Twinning; Virtual- to-Physical Connection/Twinning; Physical Processes; and Virtual Processes) 

21. **Review of digital twin about concepts, technologies, and industrial applications**. Journal of Manufacturing Systems, 2020. [paper](https://doi.org/10.1016/j.jmsy.2020.06.017). *Mengnan Liu, Shuiliang Fang, Huiyue Donga, Cunzhi Xua*.

> Through in-depth analysis, conclusion can be drawn that the connotation of digital twin concept includes:
> - Individualized: This means that digital twin is one-to-one with the individual physical twin. In other words, digital twin is as designed, as manufactured, as used, as maintained as the physical twin.
> - High-fidelity: This means that digital twin can simulate the physical twin’s behavior in the virtual space as exact as possible, which requires multi-physics modeling and continuous model updating through the whole lifecycle.
> - Real-time: This means that digital twin responds to physical twin with relatively low latency, which is made possible by current development of mobile communication technology and IoT technology.
> - Controllable: This means that changes on digital twin or physical twin control the other twin. This is the last step that closes the loop between digital twin and physical twin and realizes digital-physical convergence.

22. **Digital Twin-driven smart manufacturing: Connotation, reference model, applications and research issues**. Robotics and Computer Integrated Manufacturing, 2020. [paper](https://doi.org/10.1016/j.rcim.2019.101837). *Yuqian Lu, Chao Liu, Kevin I-Kai Wang, Huiyue Huang, Xun Xu*

> Two common methods can be used to gather data from physical devices, i.e., capturing changes and taking snapshots. There is extensive use in large scale computer systems for both methods, and sometimes a system uses a mix of them. Both methods need to be validated for specific application cases.
> Digital Twin model version management. A Digital Twin model can evolve over time as a result of engineering changes to its physical counterpart, changes to the modelling interests throughout the lifecycle of the physical counterpart, or other cases. In these cases, the different versions of a Digital Twin models over time should be captured, stored and integrated. Snapshot-based and change-based version management principles can be applied for the effective management different versions of a Digital Twin model.

23. **Knowledge-driven digital twin manufacturing cell towards intelligent manufacturing**. International Journal of Production Research, 2020. [paper](https://doi.org/10.1080/00207543.2019.1607978). *Guanghui Zhou, Chao Zhang, Zhi Li, Kai Ding, Chuang Wang*

> However, the current approaches still focus on the development of a general framework or modelling technology for digital twin towards smart manufacturing, which ignores the importance of knowledge for supporting autonomous operations of digital twin.

> Three key enabling technologies including digital twin model, dynamic knowledge bases and knowledge-based intelligent skills for supporting the above strategy are analysed, which equip KDTMC with the capacities of self-thinking, self-decision-making, self-execution and self-improving.

24. **New Paradigm of Data-Driven Smart Customisation through Digital Twin**. Journal of Manufacturing Systems, 2020. [paper](https://doi.org/10.1016/j.jmsy.2020.07.023). *Xingzhi Wang, Yuchen Wang, Fei Tao, Ang Liu*

25. **Framework for a digital twin in manufacturing: Scope and requirements**. Manufacturing Letters, 2020. [paper](https://doi.org/10.1016/j.mfglet.2020.04.004). *Guodong Shao, Moneer Helu*

> Note that an offline digital twin describes the case where real-time communication is not critical. Rather, an offline digital twin would connect to the physical system periodically. This periodic connection is an important distinction between an offline digital twin and a traditional simulation model.

> Temporal Integration: Offline, (Near) Real-time

26. **Digital Twins in manufacturing: An assessment of drivers enablers and barriers to implementation**. 53rd CIRP Conference on Manufacturing Systems, 2020. [paper](https://doi.org/10.1016/j.procir.2020.04.131). *Anis Assad Netoa et al.*

> The barriers to implementation of digital twins in manufacturing <font color=purple>@TAG integration of data (organizational)</font>
> - Concerning systems and technology, experts mentioned the lack of maturity of some of the utilized technologies (especially those employed to allow for decision support and autonomous action) as potential barriers to implementation, depending on the complexity of the digital twin application.
> - With reference to processes, experts pointed out issues with process integration as a barrier to implementation.
> - Concerning people and competence, experts pointed out that employees with missing qualifications, and the people’s resistance to change, are barriers to successful implementations of the digital twin.
> - experts mentioned the occurrence of department silos as a barrier to digital twin implementations, addressing yet again the key importance of organizational integration.

27. **Prediction maintenance integrated decision-making approach supported by digital twin-driven cooperative awareness and interconnection framework**. Journal of Manufacturing Systems, 2020. [paper](https://doi.org/10.1016/j.jmsy.2020.08.001). *Shanghua Mi, Yixiong Feng, Hao Zheng, Yong Wang, Yicong Gao, Jianrong Tan*

28. **The modelling and operations for the digital twin in the context of manufacturing**. Enterprise Information Systems, 2019. [paper](https://doi.org/10.1080/17517575.2018.1526324). *Jinsong Bao, Dongsheng Guo, Jie Li & Jie Zhang*.

29. **Digital Twin in the IoT Context: A Survey on Technical Features, Scenarios, and Architectural Models**. PROCEEDINGS OF THE IEEE, 2020. [paper](https://ieeexplore.ieee.org/document/9120192). *Roberto Minerva; Gyu Myoung Lee; Noël Crespi*

> A first important set of features of the definition of the DTs must be emphasized.
> - A DT strictly refers to a PO.
> - A DT contains all the information needed to fully characterize a PO and its intended or predicted behavior.
> - Since the DT is framed in a lifecycle composed of different steps, it can encompass data and information that describe the “history” of the PO. (Design, production, operations, disposal)

> This linkage between the PO and the LO is also a key element for introducing new capabilities and thus new business opportunities for the industry.

> Agents typically operate in complex systems that are difficult to model. Agents try to apply strategies of different complexity in order to achieve their goals in a constrained software environment. They can put in practice different local actions in order to inter- act with other agents or with the environment to accommodate their needs. Many agents, especially cognitive ones, are autonomous and operate in a decentralized manner. <font color=purple>@TAG modeling</font>

> It is important to look at three relevant issues that may arise in the application of the DT in large open systems. <font color=purple>@TAG modeling; inter-operability</font>
> - 1) Knowledge of the physical world: It is a daunting task to determine and to describe the models, laws and effects of the real world in an LO. A deeper com- prehension of the physical environments in which the PO will operate can be difficult to realize and to represent in a virtual environment.<font color=purple>@TAG modeling</font>
> - 2) Large systems and products may need to represent a considerable number of parts and their dynamic behavior. Their descriptions and status changes could introduce a higher level of complexity.
> - 3) Siloing/programming: If proprietary and closed interfaces are used, it will be extremely difficult to create ecosystems of DTs capable of working together and being interoperable.

> Characterizing DT
> - Representativeness and Contextualization. Modeling of the DT is still a difficult task; however, practical methodologies are emerging [
> - Reflection
> - Replication. This is the general ability to replicate an object into a different environment. Each replica can be tailored to the needs of the requesting application. Replicas can also cooperate to share data and information about the PO quickly and efficiently. 
> - Entanglement. This communication relationship is termed here entanglement because it refers to the instantaneous exchange of information between two closely related entities... The exchange of information between PO and the LO should be timely, that is, in such a way that the time between the changes of states of the PO is negligible with respect to the needs and intended usage of the LO by applications or users. <font color=purple>@TAG synchronization frequency; real-time optimization</font>
> - Persistency. While all of these mechanisms ensure the high persistency of objects and memory in large distributed systems, they do introduce the issues of managing different copies and their consistency. <font color=purple>@TAG synchronization frequency; real-time optimization</font> (Case in the Section V-A, virtual sensors)
> - Memorization. <font color=green>@RQ The DT concept brings with it an important issue: how much of the complex context in which the PO is immersed should be considered by the digital copy? What are the relevant data to be stored? If the object (e.g., the cloverleaf) is going to be used for a specific goal (feeding some animals), how much should it be contextualized with respect to the envisaged application of the DT? Should the entire context of a PO be recreated and represented? In principle, the DT should keep a set of all the meaningful data together with their location and time indication.</font>
> - Composability. Supporting component integration and communication. The efforts related to virtualization also offer mechanisms and technologies for supporting the composability property of the DT: microservices [149] and containers [150] are possible candidates for supporting the integration and composition of several LOs. Simulation theory [152] and agent-based simulation technologies [72], [153] for large systems also play a key role in representing the behavior of a large system composed of different DTs... Some middleware platforms for DT are developed [31], [156] and are aiming at composability.
> - Accountability/Manageability. Auto Digital Twin maintenance.
> - Augmentation. it could be functionally augmented, that is, new functions and features could be implemented in the LO. New features are software-based and take the form of innovative and more intelligent functions enabled by APIs or by the analysis of data sets related to the PO....The possibility of defining platform mechanisms to support the creation of services is also discussed in [177].
> - Ownership. Their replication can create a set of LOs that refer to the physical one, but they not necessarily share the same ownership.
> - Servitization. A permanent linkage between the customer and the producer is then established by means of the ownership of the servitized product. Servitization is a great possibility for transforming existing and future products into services appealing to customers. In the long term, servitization could lead to a new kind of economy no longer based on the ownership of things, but based on a pay per usage philosophy.
> - Predictability

> Typical scenarios for the usage of the DT
> - Design and consolidation of products, that is, where the DT is used to help in the design and the production phases of complex products and then used as a means to collect and check the operation of the product in order to identify variations or unexpected behavior.
> - Prediction and simulation of the behavior of an aggregated set of DTs in order to understand, con- trol, govern, and orchestrate the behavior of a complex system. This is supported by the collection of historical data that show the past behavior of the PO.
> - Servitization of a physical product and its augmentation in terms of new functions and interaction with the customers.

> This requires a good set of modeling capabilities as well as the ability to fully understand the constraints and limitation of the POs and the environment in which they operate. The object, or a set of objects, and the environment in which they will operate should be modeled in an autonomous fashion. <font color=purple>@TAG modeling</font>

> The most tangible value of a large DT implementation may reside in the possibility to observe, analyze, and understand real-world interactions and impacts on differ- ent objects at a very granular level.

> Following this analogy, DT may not be the right choice if the problem at hand has a very procedural solution, or if it can be solved in a functional way.

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

## [Survey](#content)
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

5. **Optimization problems for machine learning: A survey**. EJOR, 2021. [paper](https://doi.org/10.1016/j.ejor.2020.08.045). *Claudio Gambella, Bissan Ghaddar, Joe Naoum-Sawaya*. 

6. **Machine learning for combinatorial optimization: A methodological tour d’horizon**. EJOR, 2020. [paper](https://doi.org/10.1016/j.ejor.2020.07.063). *Yoshua Bengio, Andrea Lodi, Antoine Prouvost*

> Challenges
> - Data generation. Collecting data (for example instances of optimization problems) is a subtle task. In other cases, i.e., when we are not targeting a specific application for which we would have historical data, how can we proactively train a policy for problems that we do not yet know of? 

7. **Parallel computational optimization in operations research: A new integrative framework, literature review and research directions**. EJOR, 2020. [paper](https://doi.org/10.1016/j.ejor.2019.11.033). *Guido Schryen*.

8. **Distributed simulation: state-of-the-art and potential for operational research**. EJOR, 2019. [paper](https://doi.org/10.1016/j.ejor.2018.04.032). *Simon J. E. Taylor*.

9. **Reviewing the role of stakeholders in Operational Research: A stakeholder theory perspective**. EJOR, 2017. [paper](http://dx.doi.org/10.1016/j.ejor.2017.03.079). *Vincent de Gooyert, Etiënne Rouwette, Hans van Kranenburg, Edward Freeman*.

10. **Hybrid simulation modelling in operational research: A state-of-the-art review**. EJOR, 2018. [paper](https://doi.org/10.1016/j.ejor.2018.10.025). *Sally C. Brailsford , Tillal Eldabi , Martin Kunc , Navonil Mustafee , Andres F. Osorio*. 

11. **The characteristics of problem structuring methods: A literature review**. EJOR, 2019. [paper](https://doi.org/10.1016/j.ejor.2018.05.003). *Chris M. Smith, Duncan Shaw*

12. **Algorithm runtime prediction: Methods & evaluation**. Artificial Intelligence, 2014. [paper](http://dx.doi.org/10.1016/j.artint.2013.10.003). *Frank Hutter , Lin Xu, Holger H. Hoos, Kevin Leyton-Brown*.

## [Building digital models](#content)

### [Synchronization frequency](#content)
1. **An Introduction to Event-triggered and Self-triggered Control**. IEEE 51st IEEE Conference on Decision and Control (CDC), 2012. [paper](https://ieeexplore.ieee.org/document/6425820). *W.P.M.H. Heemels, K.H. Johansson, P. Tabuada*

> It is desirable in these systems to limit the sensor and control computation and/or communication to instances when the system needs attention. However, classical sampled-data control is based on performing sensing and actuation periodically rather than when the system needs attention.

2. **Challenges of Real-Time Decision Support**. In book Supporting Real Time Decision-Making, 2011. [paper](https://www.springer.com/gp/book/9781441974051). *Daniel J. Power*

>  Many strategic decisions do not need real-time data, but decision makers may benefit from improved rich media, real-time communications. Choosing when and how to deploy real-time decision support is an important decision that creates opportunities and challenges for managers and organization stakeholders. <font color=purple>@TAG synchronization frequency</font>

> When response time or delay in retrieving data impacts decision-making timeliness and effectiveness, managers are faced with a trade-off between technological expenditures, decision quality, and decision risk.

>  Real time also means ‘near real time’ in practice because there is always some latency between (a) the actual state change, (b) the reflection of that state change in data in one or more systems of record and (c) the availability of the changed data to decision makers. Real time is not the same for every decision task. ((d) the availability of the best decisions, (e) the reflection of that best decisions in actuators (e) the actual state change given the decisions)

### [Integration of Data](#content)

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



## [Solving problems in Real-time](#content)

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
> - Type 2 (Control Symbiotic Simulation System) – Here the output will directly affect the physical system through an actuator.
> - Type 3 (Open Loop Symbiotic Simulation System) – No direct feedback mechanism exists.

4. **Combining symbiotic simulation systems with enterprise data storage systems for real-time decision-making**. Enterprise Information Systems, 2021. [paper](https://doi.org/10.1080/17517575.2020.1777587). *B. S. Onggo, Canan G. Corlu, Angel A. Juan , Thomas Monks, Rocio de la Torre*. 

> A symbiotic simulation system (S3) enables interactions between a physical system and its computational model representation. To support operational decisions, an S3 uses real-time data from the physical system, which is gathered via sensors and saved in an enterprise data storage system (EDSS).

> Open research challenges
> - to integrate its different technologies, i.e., data acquisition, analytics, and machine learning.
> - standardization and inter-operability
> - scalability issues
> - security and data-privacy issues
> - methodological challenges <font color=green>@RQ (i)how to deal with highly dynamic physical systems; (ii) the need for suitable algorithms (e.g. optimization, machine learning) in a short-term decision-making environment; and (iii) how to create simulation models that are also adaptive in order to reflect changes in the physical system.</font>

### [Online Problems](#content)

1. **Online Optimization—An Introduction**. INFORMS TutORials in Operations Research, 2010. [paper](https://doi.org/10.1287/educ.1100.0072). *Patrick Jaillet, Michael R. Wagner.*

> An online problem is one where the problem data are revealed incrementally. 
> - In the sequential model, when a request is revealed, a decision by the online algorithm must be made before the next request is revealed. 
> - In the dynamic model, the requests are revealed dynamically over time, irrespective of the actions of the online algorithm. The time at which a request is revealed is (usually) denoted as the request’s release date.

2. **Online Algorithms for Multilevel Aggregation**. OR, 2020. [paper](https://doi.org/10.1287/opre.2019.1847). 

> In practice, however, packet aggregation decisions must be done on the fly, in real time. This gives rise to the online version of TCP-AP, in which an online algorithm receives information about messages as they are released over time. At each time step, this algorithm needs to decide whether to transmit the packet with pending messages or not, without any information about future message releases.

3. **The Myopic Property in Decision Models**. Decision Analysis, 2019. [paper](https://doi.org/10.1287/deca.2018.0384). *Manel Baucells, Rakesh K. Sarin*

> the optimal decision strategy is obtained by considering the impact of the current decision on all future decisions... Instead, he may think of small chunks of the problem in isolation. It is intuitively obvious that such myopic strategy generally produces suboptimal choices (Rabin and Weizsacker 2009)...We examine decision situations and utility functions for which solving a sequence of problems in isolation is globally optimal.

4. **The Bayesian Prophet: A Low-Regret Framework for Online Decision Making**. Management Science 67(3):1368-1391. https://doi.org/10.1287/mnsc.2020.3624
Alberto Vera, Siddhartha Banerjee (2021) 

> Broadly speaking, an online decision-making problem is defined by a current state and a set of actions, which together determine the next state as well as generate rewards. In Markov decision processes (MDPs), the rewards and state transitions are also affected by some random shock. Optimal policies for such problems are known only in some special cases when the underlying problem is sufficientlysimpleand knowledgeofthe generative model sufficiently detailed. For many problems of of interest, an MDP approach is infeasible for two reasons: (1) insufficiently detailed models of the generative process of the randomness and (2) the complexity of computing the optimal policy (the so-called “curse of dimensionality”). These shortcomings have inspired a long line of work on approximate dynamic programming. 

5. **Solving Myopia in Real-time Decision-making using Petri nets Models’ Knowledge for Service-oriented Manufacturing Systems**. IFAC Proceedings Volumes, 2010. [paper](https://doi.org/10.3182/20100701-2-PT-4011.00026). *Paulo Leitão, Joel Alves1, Ana I. Pereira*

> This paper introduces a novel approach to the real-time decision-making in service-oriented manufacturing systems, addressing the myopia problem usually presented in such systems. 

6. **Generalized Online Routing: New Competitive Ratios, Resource Augmentation, and Asymptotic Analyses**. Operations Research, 2008. [paper](https://doi.org/10.1287/opre.1070.0450). *Patrick Jaillet, Michael R. Wagner*.

### [Simulation optmization](#content)
1. **Optimization via Simulation Over Discrete Decision Variables.** In INFORMS TutORials in Operations Research, 2010. [paper](https://doi.org/10.1287/educ.1100.0069). *Barry L. Nelson*

2. **History of seeking better solutions, AKA simulation optimization**. Proceedings of the 2017 Winter Simulation Conference, 2017. [paper](http://simulation.su/uploads/files/default/2017-fu-henderson.pdf). *Michael C. Fu, Shane G. Henderson*

3. **An Adaptive Hyperbox Algorithm for High-Dimensional Discrete Optimization via Simulation Problems**. NFORMS Journal on Computing, 2013. [paper](https://doi.org/10.1287/ijoc.1110.0481). *Jie Xu, Barry L. Nelson, L. Jeff Hong*

4. **Faster Kriging: Facing High-Dimensional Simulators**. OR, 2020. [paper](https://doi.org/10.1287/opre.2019.1860). *Xuefei Lu, Alessandro Rudi, Emanuele Borgonovo, Lorenzo Rosasco*.

> Kriging is one of the most widely used emulation methods in simulation. How- ever, memory and time requirements potentially hinder its application to data sets generated by high-dimensional simulators. We borrow from the machine learning literature to propose a new algorithmic implementation of kriging that, while preserving prediction accuracy, notably reduces time and memory requirements. The theoretical and computational foundations of the algorithm are provided. The work then reports results of extensive numerical experiments to compare the performance of the proposed algorithm against current kriging implementations, on simulators of increasing dimensionality. Findings show notable savings in time and memory requirements that allow one to handle inputs across more that 10,000 dimensions.

5. **Rapid Discrete Optimization via Simulation with Gaussian Markov Random Fields**. INFORMS Journal on Computing, 2020. [paper](https://doi.org/10.1287/ijoc.2020.0971). *Mark Semelhago, Barry L. Nelson, Eunhye Song, Andreas Wächter*

> In our setting, the output is stochastic, and the number of feasible solutions is huge, but individual replications of a solution may be relatively cheap compared with a deterministic computer experiment. In combination, the computational overhead for inference is no longer negligible compared with the simulation cost.

> Our primary contribution is to greatly extend the reach of GMRF-based optimization by dramatically reducing the computational cost of inference.


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


### [Multi-fidelity approaches](#content)

1. **Survey of multi-fidelity methods in uncertainty propagation, inference, and optimization**. SIAM REVIEW, 2019. [paper](https://epubs.siam.org/doi/pdf/10.1137/16M1082469). *Benjamin Peherstorfer, Karen Willcox, Max Gunzburger*

> This work surveys multi-fidelity methods that accelerate the solution of outer-loop applications by combining high-fidelity and low-fidelity model evaluations, where the low-fidelity evaluations arise from an explicit low-fidelity model (e.g., a simplified physics approximation, a reduced model, a data-fit surrogate) that approximates the same output quantity as the high-fidelity model.

2. **Multi-fidelity simulation optimization for airline disruption management**. Proceedings of the 2018 Winter Simulation Conference, 2018. [paper](https://ieeexplore.ieee.org/document/8632329). *Luke Rhodes-Leader, David J. Worthington, Barry L. Nelson, Bhakti Stephan Onggo*. <font color=purple>@TAG real-time optimization; synchronization fidelity</font>

> This paper presents a method for the aircraft recovery problem that uses multi-fidelity modeling including a trust region simulation optimization algorithm to mitigate the computational costs of using high-fidelity simulations with its benefits for providing good estimates of the true performance.

> <font color=green>@RQ The contribution of this paper is a method to balance the need to use a high-fidelity simulation model to estimate the performance of a recovery option with the computational difficulties associated with simulation in this context. These difficulties include a large and complicated solution space and short computation time constraints.</font>

> In each case, 2000 simulation replications were allowed for the optimisation procedure, with $nd = 5$ replications at each design point, and 20 replications used for the acceptance tests. (The solution times are not reported.)

> Future work will include considering how the repeated nature of the problem could be exploited to improve both the models and the optimization process in a symbiotic manner.

3. **Analytics with digital-twinning: A decision support system for maintaining a resilient port**. Decision Support Systems, 2021. [paper](https://doi.org/10.1016/j.dss.2021.113496). *Chenhao Zhou, Jie Xu, Elise Miller-Hooks, Weiwen Zhou, Chun-Hung Chen, Loo
Hay Lee, Ek Peng Chew, Haobin Li*. <font color=purple>@TAG real-time optimization; synchronization fidelity</font>

> Because digital twin runs are time-consuming, there are important <font color=green>trade-offs between making enough runs for accurate estimates and computation time</font>. For real-world size applications, especially when used to support real-time operations, efficient run designs with good statistical accuracy are needed. It is likely that with insufficient runs to guarantee statistical accuracy the DSS will select a sub-optimal c for a given scenario and, simultaneously, develop an incorrect (reduced) resilience assessment. To tackle this computational challenge, the proposed DSS integrates a state-of-the-art simulation-optimization method known as optimal computing budget allocation (OCBA) (Chen and Lee [12,13]) to determine the number of simulations to be executed for each candidate recovery action under a given simulation budget.

### [Parallel computing](#content)
1. **Fully Sequential Procedures for Large-Scale Ranking-and-Selection Problems in Parallel Computing Environments**. OR, 2015. [paper](http://dx.doi.org/10.1287/opre.2015.1413). *Jun Luo, L. Jeff Hong, Barry L. Nelson, Yang Wu*

> In this paper, we propose two types of fully sequential procedures that can be used in parallel computing environments. We call them vector-filling procedures and asymptotic parallel selection procedures, respectively. Extensive numerical experiments show that the proposed procedures can take advantage of multiple parallel processors and solve large-scale R&S problems.

2. **Knockout-Tournament Procedures for Large-Scale Ranking and Selection in Parallel Computing Environments**. Working paper, 2020. [paper](https://www.researchgate.net/publication/339200267_Knockout-Tournament_Procedures_for_Large-Scale_Ranking_and_Selection_in_Parallel_Computing_Environments). *Ying Zhong, L. Jeff Hong*

> When using parallel computing environments, we argue that the existing stage-wise procedures and fully-sequential procedures are both inefficient, and we need a new framework that takes a holistic view at the total computation time, including the time spent on simulation, comparison, and communication. Stage-wise procedures were first proposed to handle physical experiments, and fully-sequential procedures were more suitable to handle computer experiments generated in a single processor. Using them directly in parallel computing environments for large-scale problems will cause either too many simulation observations or too many comparisons or too many communications among the processors. In this paper, we propose new R&S procedures that consider the total computation time and work well in parallel computing environments, especially commercial clouds.

> We show that no matter whether the variances of the alternatives are known or not, our procedures can theoretically achieve the lowest growth rate on the expected total sample size with respect to the number of alternatives and thus are optimal in rate. 

3. **Speeding Up Paulson’s Procedure for Large-Scale Problems Using Parallel Computing**. INFORMS Journal on Computing, 2021. [paper](https://doi.org/10.1287/ijoc.2020.1054)

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


### [Applications](#content)
1. **A Real-Time Multiobjective Optimization Algorithm for Discovering Driving Strategies**. TS, 2018. [paper](https://doi.org/10.1287/trsc.2018.0872). *Erik Dovgan, Matjaž Gams, Bogdan Filipič*. 

> This paper presents a real-time multiobjective optimization algorithm for discovering driving strategies that uses a black-box driving simulator to search for driving strategies on a given route and minimizes the traveling time and the fuel consumption.

> During the driving prediction, the computational time is checked several times. When the computational time is going to exceed the available computational time, the driving prediction stops, that is, the algorithm jumps to Line 27 and continues with the selection of the best control action for the next step. The computational time available for the selection of the control action for the next step is equal to the traveling time of the current step.

> A particular challenge would be the deployment of the algorithm in a real-life vehicle and its evaluation on a real route, where real-life neighboring vehicles and unexpected events have to be considered.

2. **Industrial IoT integrated with Simulation – A Digital Twin approach to support real-time decision making**. Proceedings of the International Conference on Industrial Engineering and Operations Management, 2019. [paper](http://ieomsociety.org/pilsen2019/papers/225.pdf)

> The suggested approach involves a Manufacturing Executing System (MES) producing a production schedule, an IoT Platform composed by a message broker and a real-time database, a Simulator including simulation software and a wrapper, and a user application serving as an interface between the user and the IoT Platform and Simulator integrated system. 

3. **Online Vehicle Routing: The Edge of Optimization in Large-Scale Applications**. OR, 2018. [paper](https://doi.org/10.1287/opre.2018.1763). *Dimitris Bertsimas, Patrick Jaillet, Sébastien Martin*.

> Challenges. With the emergence of ride-sharing companies that offer transportation on demand at a large scale and the increasing availability of corresponding demand data sets, new challenges arise to develop routing optimization algorithms that can solve massive problems in real time. 

> In this paper, we develop an optimization framework, coupled with a novel and generalizable backbone algorithm, that allows us to dispatch in real time thousands of taxis serving more than 25,000 customers per hour.

> With the recent interest in real-time ride sharing, several large-scale online decision systems for taxi scheduling have been proposed and implemented although these applications focus more on managing large-scale decision systems than optimizing vehicle actions. 

> Several strategies have been proposed for dynamic vehicle routing... Unfortunately, these exact algorithms rarely scale past a few dozens or hundreds of customers and vehicles, depending on the application. We use such formulations in this paper although applying them on problems with tens of thousands of customers and thousands of vehicles.

> A classical way to solve these static vehicle-routing problems at a larger scale is the use of heuristics... Unfortunately, these heuristics are usually special purposed and have to be adapted to each particular new problem... In this paper, we were not able to successfully apply any of these algorithms because of the size of our problem and the very small time available for computations.

4. **Challenges of Real-Time Decision Support**. In book Supporting Real Time Decision-Making, 2011. [paper](https://www.springer.com/gp/book/9781441974051). *Daniel J. Power*

> When evaluating implementation of these systems, managers need to consider and respond to three categories of continuing challenges: (1) technical, (2) organizational and (3) social/psychological.

>  Many strategic decisions do not need real-time data, but decision makers may benefit from improved rich media, real-time communications. Choosing when and how to deploy real-time decision support is an important decision that creates opportunities and challenges for managers and organization stakeholders. <font color=purple>@TAG synchronization frequency</font>

> When response time or delay in retrieving data impacts decision-making timeliness and effectiveness, managers are faced with a trade-off between technological expenditures, decision quality, and decision risk.

>  Real time also means "near real time" in practice because there is always some latency between (a) the actual state change, (b) the reflection of that state change in data in one or more systems of record and (c) the availability of the changed data to decision makers. Real time is not the same for every decision task.

5. **6 Best Practices for Real-Time Analytics**, Gartner, 2016. [article](https://www.gartner.com/smarterwithgartner/six-best-practices-for-real-time-analytics/).


6. **Digital Twin Framework and Its Application to Power Grid Online Analysis**. CSEE JOURNAL OF POWER AND ENERGY SYSTEMS, 2019. [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8779809). *Mike Zhou, Jianfeng Yan, Donghao Feng*

> Digital twin (DT) framework is introduced in the context of application for power grid online analysis. In the development process of a new power grid real-time online analysis system, an online analysis digital twin (OADT) has been implemented to realize the new online analysis architecture. 

> A high-performance parallel computing approach has been implemented on the top of the virtual models.

7. **Data-Driven Appointment-Scheduling Under Uncertainty: The Case of an Infusion Unit in a Cancer Center.**. Management Science, 2020. [paper](https://doi.org/10.1287/mnsc.2018.3218). *Avishai Mandelbaum, Petar Momčilović, Nikolaos Trichakis, Sarah Kadish, Ryan Leib, Craig A. Bunnell*

> In reality, there exists a significant discrepancy between the planned and actual operations. .. This mismatch can be traced back to the aforementioned assumptions of deterministic service times and punctuality - assumptions routinely made in appointment scheduling implementations, which are capable of handling large-scale operations that involve hundreds of servers and hundreds of customers.

> It (Actual Durations of Infusion Treatments Scheduled for Two Hours) was compiled using high-resolution data from a real-time locating system (RTLS) deployed at DFCI.

> RTLS data from the eight clinical floors were “synchronized” with appointment book data, as well as data from the in-house pharmacy. Having access to all these logs enables us to accurately determine not only locations of patients but also the activities in which they are engaged.


### [Inter-operability](#content)

1. **Learning to Approximate Industrial Problems by Operations Research Classic Problems**. OR, 2021. [paper](https://doi.org/10.1287/opre.2020.2094). *Axel Parmentier* <font color=purple>@TAG inter-operability</font>

> Challenges: Practitioners of operations research often consider difficult variants of well-known optimization problems and struggle to find a good algorithm for their variants although decades of research have produced highly efficient algorithms for the well-known problems. 

> Methods: We introduce a machine learning for operations research paradigm to build efficient heuristics for such variants: use a machine learning predictor to turn an instance of the variant into an instance of the well-known problem, then solve the instance of the well-known problem, and finally retrieve a solution of the variant from the solution of the well-known problem. This paradigm requires learning the predictor that transforms an instance of the variant into an instance of the well-known problem. We introduce a structured learning methodology to learn that predictor.

2. **A Model-Driven Approach to Interoperability Between Simulation and Optimization for Production and Logistics Systems**. NIST, 2021. [paper](https://doi.org/10.6028/NIST.IR.8326). *Timothy Sprock*
