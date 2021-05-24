## [Content](#content)
<table>
<tr><td colspan="2"><a href="#related-research-papers-in-or">3. Related research papers in OR</a></td></tr>
<tr><td colspan="2">&emsp;<a href="#managing-dts">3.x Managing DTs</a></td></tr>
<tr>
	<td>&emsp;&emsp;<a href=#inter-operability>x.x.x inter-operability</a></td>
	<td>&emsp;&emsp;<a href=#privacy-and-ownership>x.x.x Privacy and ownership</a></td>
</tr>
<tr>
	<td>&emsp;&emsp;<a href=#stakeholder-management>x.x.x stakeholder management</a></td>
</tr>
</table>

[Back to homepage](../papers4dtor.md)

## [Managing DTs](#content)

9. **Reviewing the role of stakeholders in Operational Research: A stakeholder theory perspective**. EJOR, 2017. [paper](http://dx.doi.org/10.1016/j.ejor.2017.03.079). *Vincent de Gooyert, Etiënne Rouwette, Hans van Kranenburg, Edward Freeman*.

<font color=purple>@TAG ownership; stakeholder management</font>

### [Inter-operability](#content)

1. **Learning to Approximate Industrial Problems by Operations Research Classic Problems**. OR, 2021. [paper](https://doi.org/10.1287/opre.2020.2094). *Axel Parmentier* <font color=purple>@TAG inter-operability</font>

> Challenges: Practitioners of operations research often consider difficult variants of well-known optimization problems and struggle to find a good algorithm for their variants although decades of research have produced highly efficient algorithms for the well-known problems. 

> Methods: We introduce a machine learning for operations research paradigm to build efficient heuristics for such variants: use a machine learning predictor to turn an instance of the variant into an instance of the well-known problem, then solve the instance of the well-known problem, and finally retrieve a solution of the variant from the solution of the well-known problem. This paradigm requires learning the predictor that transforms an instance of the variant into an instance of the well-known problem. We introduce a structured learning methodology to learn that predictor.

2. **A Model-Driven Approach to Interoperability Between Simulation and Optimization for Production and Logistics Systems**. NIST, 2021. [paper](https://doi.org/10.6028/NIST.IR.8326). *Timothy Sprock*

### [Privacy and ownership](#content)
> Minor comment of R3. As an example of the breadth of opportunity for INFORMS professionals, see the article (Milberg, Smith, and Burke 2000) on data privacy in the INFORMS journal Organizational Science and the article (Jia, Jin, and Wagman 2021) in Marketing Science.

1. **Information Privacy: Corporate Management and National Regulation**. Organization Science, 2000. [paper](https://doi.org/10.1287/orsc.11.1.35.12567). *Sandra J. Milberg, H. Jeff Smith, Sandra J. Burke*

> Almost all developed countries have grappled with the trade-offs between open access to information—which enables economic efficiency—and an individual’s right to privacy. Consistent with these trade-offs, many recent incidents suggest that regulatory approaches to information privacy, corporate management of personal data, and consumer reactions are becoming tightly interwoven around the world. To provide some insights into these relationships, we develop a conceptual model and test it with a cross-cultural sample from 19 different countries.

> Findings: a country’s regulatory approach to the corporate management of information privacy is affected by its cultural values and by individuals’ information privacy concerns.

2. **The Short-Run Effects of the General Data Protection Regulation on Technology Venture Investment**. Marketing Science, 2021. [paper](https://doi.org/10.1287/mksc.2020.1271). *Jian Jia, Ginger Zhe Jin, Liad Wagman*

> The General Data Protection Regulation (GDPR) was enacted in the European Union in April 2016 and went into effect in May 2018. We study its impact on investment in new and emerging technology firms. Our findings indicate negative post-GDPR effects after its 2018 rollout on European ventures relative to their counterparts in the United States and the rest of the world, and considerably lesser effects after its 2016 enactment and before implementation. The negative effects manifest in the number of and amounts raised in financing deals, and are particularly pronounced for newer, data-related, and business- to-consumer ventures.

> There appear to be at least two broad categories for how the GDPR can affect business. The first includes costs related to adjusting a firm’s business model such that it meets regulatory requirements. The second includes potential reductions in longer-term profitability because of costs related to maintaining different systems, higher fines, or the inability to extract the same amount of value as in the pre-GDPR regime.

> This study presents an analysis of the impact of the GDPR on new technology venture investment in the EU.

> B2B deals, in comparison, did not significantly change after the GDPR’s enactment but decreased by 10.8% following its rollout. The difference between B2C and B2B ventures is potentially because consumer-facing products have more expo- sure to the regulation, particularly to its requirements concerning individual users (e.g., opt-in or legitimate interest, data management, control, and processing violations, with potential fines per violation).

### [V&V and trust issue]

1. **Verification and validation of simulation models**. Journal of Simulation, 2013. [paper](https://doi.org/10.1057/jos.2012.20). *RG Sargent*

> Model verification is defined as ‘ensuring that the computer program of the computerized model and its implementation are correct’. 

> Model validation is defined as the ‘substantiation that a model within its domain of applicability possesses a satisfactory range of accuracy consistent with the intended application of the model’.

> Model credibility is concerned with developing in (potential) users the confidence they require in order to use a model and in the information derived from that model.

> It is often too costly and time-consuming to determine that a model is absolutely valid over the complete domain of its intended applicability. Instead, tests and evaluations are conducted until sufficient confidence is obtained that a model is considered valid for its intended application.

![](../image/confidence-of-model-validity.png)

> Three basic decision-making process: model development team itself, users, independent team

> Two paradigms (simple, complex)

> Validation techniques: animation, comparison to other models, data relationship correctness, degenerate tests, event validity, extreme condition test, face validity (individual knowledgeable), historical data validation, internal validity, multi-stage validation, operational graphics, parameter variability-sensitivity analysis, philosophy of science methods, predictive validation, structured walkthrough, trace, turing test, 

> Data validity. 
> - it is usually difficult, time-consuming, and costly to obtain appropriate, accurate, and sufficient data, and data problems are often the reason that attempts to validate a model fail. 
> - Data are primarily used for three purposes: for building the conceptual model, for validating the model, and for performing experiments with the validated model

> Conceptual model validation:  (1) the theories and assumptions underlying the conceptual model are correct and (2) the model’s representation of the problem entity and the model’s structure, logic, and mathematical and causal relationships are ‘reasonable’ for the intended purpose of the model.
> - A conceptual model may be a single model or an overall model with submodels.

> Computerized model verification

> Operational validity: determining whether the simulation model’s output behavior has the accuracy required for the model’s intended purpose over the domain of the model’s intended applicability.
> - explore model behavior: qualitatively or quantitatively
> - comparisons of output behavior：hypothesis test; confidence intervals (it is often not possible in practice to use either one of these two approaches because (a) the statistical assumptions required cannot be satisfied or only with great difficulty (assumptions usually required are data independence and normality) and/or (b) there is an insufficient quantity of system data available, which causes the statistical results to be ‘meaningless’); graph

2. **Optimal Prescriptive Trees**. INFORMS Journal on Optimization， 2019. [paper](https://doi.org/10.1287/ijoo.2018.0005). *Dimitris Bertsimas, Jack Dunn, Nishanth Mundru*.

> The proliferation in volume, quality, and accessibility of highly granular data has enabled decision makers in various domains to seek customized decisions at the individual level.

> In this paper, we consider the problem of prescribing the best option from among a set of predefined treatments to a given sample (patient or customer depending on context) as a function of the sample’s features. 

> Our method relies on iterative splitting of the feature space and can handle the case of more than two treatment options.

> Three key challenges to designing personalized prescriptions for each sample as a function of their observed features.
> - counterfactual outcomes 
> - bias inherent in observational data.
> - interpretable

> Optimal Prescriptive Tress
> - a decision tree that, in each leaf, prescribes a common treatment for all samples that are assigned to that leaf of the tree
> - in each leaf, we fit a linear regression model for each treatment using only the samples in that leaf that received the corresponding treatment. 
