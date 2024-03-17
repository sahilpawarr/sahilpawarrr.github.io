#fruit  

Following are notes I made while preparing for a Research Associate role at J-PAL, back in December of 2023. Although I couldn't get the job, it did help me get till the final interview for 3 projects. So the idea of making this publicly available is the sliver of hope that these notes help atleast one person get into JPAL. 

Please note that this is not an EXHAUSTIVE list and neither can I guarantee that this answers all the questions. What I can say is that these notes will give you a strong footing in understandindg randomisation, [[RCTs]], [[causal inference]] and just [[Development Economics]] in general. 

----
##### Why J-PAL/Why development sector?
- Passion for using research to address social challenges and improve lives.
- Drawn to J-PAL for its commitment to rigorous evidence and randomized evaluations.
- Impressed by J-PAL's global impact and contribution to effective poverty reduction policies
- Aligned with J-PAL's dedication to research excellence and methodological rigor.
- Excited about being part of a collaborative culture where different perspectives come together to tackle complex global issues.
- Eager to contribute to cutting-edge research that translates into actionable solutions.
- Values J-PAL's emphasis on continuous learning and professional development.
- Sees J-PAL as an ideal place to make a meaningful impact on poverty alleviation
##### What is an RCT?
- A Randomized Controlled Trial (RCT) is a type of scientific experiment designed to evaluate the effectiveness of a new intervention or treatment.
-  In an RCT, participants are randomly assigned to either a treatment group, which receives the intervention, or a control group, which does not. 
- The random assignment helps ensure that any observed differences in outcomes can be attributed to the intervention rather than pre-existing characteristics.


#### How will you describe randomized control trials to someone?
Imagine you have two groups of people, and you want to find out if eating apples makes people healthier. Instead of just giving apples to the people who already seem healthy, we randomly pick some people to eat apples, and others not to. This way, we can be more certain that any differences we see afterward are because of the apples and not because of other reasons. It's like giving everyone a fair chance, and that's what we call a Randomized Controlled Trial (RCT).
OR
Imagine you're testing a new way to improve student learning. Instead of just applying the method to a single school and comparing the results, you randomly pick some schools to try the new approach (the treatment group) and leave others as they are (the control group). By doing this randomly, you ensure that any differences in the outcomes between the two groups are likely due to the new method, not other factors. This helps us confidently say whether the improvement is a result of our new approach or just a coincidence.

#### How is piloting different from the main survey?
- Piloting is a smaller-scale, preliminary phase conducted before the main survey to test and refine the survey instrument or questionnaire. Its primary purpose is to identify and address any issues related to clarity, wording, or potential bias in the questions. During piloting, the survey is administered to a small sample of participants, allowing researchers to gather feedback on the survey's effectiveness.
- In contrast, the main survey is the full-scale data collection conducted with the target population. It involves a larger sample size and aims to collect comprehensive and representative data for analysis. The main survey incorporates the insights gained from the pilot phase, ensuring that the finalized survey instrument is well-designed and capable of yielding reliable and valid results.

#### Internal vs external validity
- Internal Validity:  degree which accurately measures the relationship between cause and effect without interference from external factors. It reflects the confidence that changes observed in the dependent variable are genuinely due to the independent variable being studied.
- External validity is basically generalisability of the experiment to test if findings of the experiment can be used outside the settings/environment in which the project was conducted
- 

|                     |                                                                                                                 |                                                                                                         |
| ------------------- | --------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| Aspect              | Internal Validity                                                                                               | External Validity                                                                                       |
| Definition          | The degree to which an experiment accurately measures what it intends to measure without confounding variables. | The extent to which study results can be generalized to other populations, settings, or conditions.     |
| Concern             | Focuses on the soundness of the experimental design and control of variables within the study.                  | Concerned with the broader applicability of study findings beyond the specific study context.           |
| Control             | Emphasizes rigorous control over potential confounding factors to establish causal relationships.               | Explores the generalizability of results to diverse populations, settings, or situations.               |
| Main Questions      | "Is there a causal relationship between the independent and dependent variables within the study?"              | "Can the study's findings be applied or extended to other populations or contexts?"                     |
| Methods to Improve  | Randomization, control groups, blinding, and careful experimental design.                                       | Use of diverse samples, consideration of different settings, and ecological validity.                   |
| Threats to Validity | Selection bias, maturation, history, and other internal factors affecting the study's internal structure.       | Population validity, ecological validity, and other factors influencing the study's external relevance. |

#### Explain the differences between internal and external validity and their importance in impact evaluations.

- Internal validity refers to the extent to which a study accurately identifies causal relationships between the independent variable (e.g., an intervention) and the dependent variable (e.g., outcomes). It ensures that observed changes can be attributed to the intervention rather than confounding factors. Randomized controlled trials (RCTs) are designed to maximize internal validity through random assignment.
- External validity, on the other hand, addresses the generalizability of study findings beyond the specific sample and context of the research. While internal validity establishes causation within the study, external validity examines whether those findings can be applied to different populations, settings, or conditions.
- Both internal and external validity are crucial in impact evaluations. Internal validity ensures the reliability of causal inferences within the study, building confidence in the intervention's effectiveness. External validity enhances the relevance of research findings for broader policymaking and implementation, acknowledging that the context of the study may differ from other situations.
- Balancing these two aspects is essential for robust impact evaluations. While a study with high internal validity ensures confidence in causal claims, considerations for external validity broaden the implications of those claims to diverse real-world scenarios.

##### Can you explain the concept of a counterfactual in the context of randomized controlled trials (RCTs)?

##### How would you ensure that the treatment and control groups in an RCT are comparable at the baseline, considering potential confounding variables?
- In an RCT, ensuring comparability at the baseline involves the random assignment of participants to either the treatment or control group. 
- This process is crucial because it helps eliminate the influence of potential confounding variables.  
- Randomization ensures that, on average, both groups are similar at the outset, providing a solid foundation for making causal inferences. 
- Techniques such as stratified randomization or matching may be employed to further enhance comparability by accounting for specific characteristics or variables.
- In designing an RCT, how do you determine the appropriate level of randomization – at the individual, cluster, or some other level?


##### Can you provide an example of a potential confounding variable in an RCT, and how you might address it during the study design phase?
- For our textbooks intervention example, potential confounding variables could be say the inherent skill of the students before they got the books, if one student is brighter than the other etc, could be their socio economic conditions as well. can be mitigated by randomisation selections while distributing in two groups. 
- Randomization ensures that, on average, these potential confounding variables are evenly distributed between the treatment and control groups. This even distribution helps create comparable groups, enhancing the internal validity of the study.


#### You said randomization remove confounding variables on average, how does this happen exactly
- When we say randomization removes confounding variables on average, we mean that by randomly assigning individuals to either the treatment or control group, we create a situation where, on average, the distribution of both known and unknown confounding factors is similar between the two groups. 
- Let me break it down: Suppose there are various characteristics or factors that could influence the outcomes of our study, such as students' inherent skills, socioeconomic conditions, or other variables we may not even be aware of. 
- Through randomization, each individual has an equal chance of being in either group, and over a large sample size, these characteristics should, on average, be evenly distributed between the treatment and control groups. 
- This ensures that any potential confounding factors are equally likely to occur in both groups, and their effects balance out when we compare the outcomes. 
- In simpler terms, randomization creates a fair and unbiased comparison, making the treatment and control groups comparable and allowing us to attribute any observed differences in outcomes to the intervention itself rather than pre-existing differences between the groups.

#### What are some common threats to internal validity in an RCT, and how would you minimize their impact on the study?
- Some common threats to internal validity in an RCT include selection bias, attrition, and contamination. 
	- **Selection bias** occurs when there are systematic differences between the treatment and control groups at the baseline. In our textbooks intervention example, this could happen if certain schools or students are more likely to receive the textbooks, leading to an imbalance in baseline characteristics.
		- To minimize selection bias, randomization is crucial. By randomly assigning schools or students to the treatment and control groups, we ensure that, on average, any potential confounding variables are equally distributed between the two groups. This helps create comparable groups and strengthens the internal validity of the study.
	- **Attrition** poses a threat if there are differential dropout rates between the treatment and control groups. If, for instance, students who receive textbooks are more likely to drop out, it could affect the study's internal validity. To address this, we could implement strategies such as incentives, follow-up protocols, or intent-to-treat analysis, which includes all participants regardless of their level of participation.
	- **Contamination** occurs when elements of the intervention spill over to the control group or vice versa. In our example, this could happen if students from the control group gain access to textbooks. To mitigate contamination, we might consider implementing a cluster-randomized design, where entire schools are randomized rather than individual students. This reduces the risk of students from different groups interacting and influencing each other.

#### In the absence of randomization, what challenges might you face in establishing a causal relationship between an intervention and its outcomes in an impact evaluation?
- Challenges such as selection bias, attrition, confounding variables and contamination.
- In the absence of randomization, establishing a causal relationship between an intervention and its outcomes becomes challenging due to the presence of confounding variables. 
- Confounding variables are external factors that may influence both the intervention and the outcomes, making it difficult to attribute observed effects solely to the intervention.
- Without randomization, there's a risk of selection bias, where certain characteristics or conditions may systematically differ between the treatment and control groups. This can lead to inaccurate causal inferences. Additionally, factors such as participant self-selection or the influence of external events over time may further complicate the analysis.

#### Can you provide an example of a situation where cluster randomization would be more appropriate than individual randomization in an RCT?
- Imagine we're implementing a textbook intervention in schools. If the intervention involves entire schools receiving new teaching methods and sharing a common environment, cluster randomization would be more suitable. This helps prevent the risk of students within the same school influencing each other's outcomes.


#### In the analysis phase of an RCT, how would you deal with issues related to non-compliance with the assigned treatment?

#### Explain why RCTs are considered as the gold standard in economic research practices
- Firstly, they provide a robust method for establishing causal relationships between interventions and outcomes. The random assignment of participants ensures that any observed effects can be attributed to the intervention itself, reducing selection bias and confounding variables.
- Secondly, RCTs offer a high level of internal validity by controlling for potential threats to the study's integrity. This rigorous experimental design allows researchers to make more confident and reliable causal inferences.
- Additionally, the randomization process helps create comparable treatment and control groups, contributing to the generalizability of results. This, in turn, enhances external validity, making findings applicable to broader contexts.


#### How might you address ethical considerations in the design and implementation of an RCT, particularly when working with vulnerable populations?
#### Discuss the potential impact of selection bias in an RCT and how you would guard against it during the study design.
- To address this issue, one commonly used approach is stratified randomization. In this method, the randomization process is conducted separately within different strata or groups defined by certain characteristics that are known to be potential sources of variation. For instance, if we're testing an educational intervention, we might stratify by school size or students' initial academic performance.
- This ensures that each stratum has a more balanced representation of participants with similar characteristics, reducing the likelihood of significant imbalances. By doing so, we enhance the internal validity of the study, as it becomes less likely that observed differences in outcomes are due to pre-existing imbalances rather than the intervention itself.
- However, it's important to note that even with stratified randomization, small sample sizes can still pose challenges.

#### How do you decide on the appropriate duration for an RCT, and what considerations would influence the study's timeline?
- In the context of randomization, how might you deal with baseline imbalances that occur by chance in a small sample size? 
- To address this issue, one commonly used approach is stratified randomization. In this method, the randomization process is conducted separately within different strata or groups defined by certain characteristics that are known to be potential sources of variation. For instance, if we're testing an educational intervention, we might stratify by school size or students' initial academic performance.
- This ensures that each stratum has a more balanced representation of participants with similar characteristics, reducing the likelihood of significant imbalances. By doing so, we enhance the internal validity of the study, as it becomes less likely that observed differences in outcomes are due to pre-existing imbalances rather than the intervention itself.

##### In the context of a real-world example, how might you convey the significance of randomization to someone not well-versed in research methodology?
- Imagine you're a chef testing a new recipe for a delicious chocolate cake. To ensure the validity of your taste test, you decide to invite 100 people to participate. Now, if you simply assign the first 50 people who show up to Group A and the next 50 to Group B, there could be some unintentional bias. Maybe the first 50 people are all chocoholics, and the next 50 prefer vanilla. This could lead to misleading results because the groups are not balanced in terms of their preferences.
- To avoid this bias, you decide to use randomization. Instead of assigning people based on their arrival order, you randomly select individuals from the pool and assign them either to Group A (receives the new chocolate cake recipe) or Group B (receives the old chocolate cake recipe). This ensures that each group is a representative sample of the entire population of taste testers


##### Can you outline your career goals for the next few years and how they align with your interest in research and development?

##### In the context of your future plans, how do you envision contributing to the field of impact evaluation?
#### How would you handle issues related to attrition or dropout rates in the course of an ongoing RCT, and how might they impact the study's internal validity?

#### If you were tasked with conducting an RCT to evaluate the impact of a new teaching method in schools, how would you go about determining the sample size?

If you were tasked with evaluating the impact of a government-sponsored nutrition scheme for school children, what specific parameters would you consider in your randomized evaluation design?

How would you approach determining the sample size for a randomized evaluation, especially in the context of a nutrition scheme for school children?

Reflecting on your background, how have your past work experiences nurtured your skills and prepared you for a role in impact evaluation?

Can you share an example from your academic or professional journey that significantly contributed to your readiness for this role?

What are some critical considerations you would keep in mind when designing a research study, particularly in the context of impact evaluations?

In your opinion, what makes a research design robust, especially when dealing with interventions in low-income settings?

Beyond the commitment to evidence-based research, can you elaborate on what specifically draws you to the development sector?


If you were to explain the concept of Randomized Controlled Trials (RCTs) to someone unfamiliar with research, how would you do it differently based on their background or perspective?

.

Can you provide an example from your past experiences where you had to ensure the quality and reliability of data during a research project?

In data cleaning and management, what specific steps do you take to maintain data quality and ensure accurate analysis?

Reflecting on your experiences, how has feedback from piloting influenced the success of a subsequent main survey?

Can you share an instance where insights gained from piloting significantly impacted the effectiveness of the final survey instrument?
Certain questions could be confusing to respondents
Removed bias from questionable formulation

If you were handed a survey instrument that had already been designed, how would you approach assessing its quality and reliability before deployment?

Beyond its role in establishing comparability, can you discuss other reasons why randomization is crucial in impact evaluations?

In a hypothetical scenario where randomization wasn't feasible, how might you address the challenges of establishing causation and minimizing bias?

