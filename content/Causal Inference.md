#sapling
[[statistics]] [[data]] [[Book Notes/Data Analysis for Social Science]]


- Definition: 
	- Causation **indicates that one event is the result of the occurrence of the other event**; i.e. there is a causal relationship between the two events. This is also referred to as cause and effect.
	- It means reasonable evidence that an [[independent variable]] "X" causes a change or occurrence in another dependent variable "Y."
- [[Independent Variable]]: 
	- Independent variable is the cause. It is stand alone and does not change by the other variables you are trying to measure
- [[Dependent Variable]]: 
	- The dependent variable is the effect. 
	- It is what u are measuring for in the experiment. 
	- Its value depends on changes in the independent variable.
- Individual Causal Effects
- Average Causal Effects
	- [[RCTs]]
		- In a Randomized Controlled Trial or RCTs, researchers decide randomly on who recieves the treatment
		- Hypothetically it is like throwing a coin and if it lands heads then that personis given treatment and if tails then not given treatment 
		- In practice its not a coin but some program used that assigns 1 or 0 to each individual. Individuals who are assigned a 1 are given the treatment and individuals who are assigned a 0 are not given the treatment
		- [[Treatment Group]] consists of individuals who received the treatment (observations for which *Xi = 1*)
		- [[Control Group]] consists of individuals who did not received the treatment (observations for which *Xi = 0*)
	- Average Treatment effect (ATE):
		- The goal of an RCt is to estimate the average causal effect of a treatment on an outcome by comparing the average outcomes between the treatment and control groups. 
		- ie. ![[Pasted image 20231202140055.png]]
		- The "difference-in-means estimator" is introduced, indicating that if groups were comparable before treatment, the estimated average treatment effect can be calculated by taking the difference in average outcomes between the treatment and control groups.
		- ![[Pasted image 20231202140330.png]]
	- [[Counterfactual]]: 
		- In causal inference, the counterfactual is the outcome that would have occurred for a specific individual or group in the absence of the treatment. Since we can't observe both the treatment and its absence for the same individual, the counterfactual is a hypothetical or unobserved scenario.
		- For an individual who takes the blood pressure drug, the counterfactual is the hypothetical scenario of what their blood pressure would have been if they had not taken the drug. It's essentially the "what if" scenario that allows us to attribute changes to the treatment.
	- 
		