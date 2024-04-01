#sapling 

[[Vault/Economics|Economics]] [[data]] [[DataforIndia Prep]] 

### Sample Design 

- **Objective:** NFHS-5 aimed to produce indicators at the district and state/union territory (UT) levels.
- **Sample Size and Coverage:**
    - Covered 707 districts, 28 states, and 8 union territories.
    - Utilized a uniform sample design representative at the national, state/UT, and district levels.
- **Stratification:** // **Selection Process:**
    - Rural areas: Villages selected as Primary Sampling Units (PSUs) based on literacy rate of women age 6+ years.
	    - Urban areas: Census Enumeration Blocks (CEBs) selected as PSUs based on percentage of SC/ST population.
    - Within PSUs, households selected using equal probability systematic selection.
- **Sample Representation:**
    - 30,456 PSUs selected across the country, with 30,198 completing fieldwork.
    - A stratified two-stage sample design utilizing 2011 census data as the sampling frame.
- **State Module Implementation:**
    - Sexual behavior, husband’s background, women’s work, HIV/AIDS knowledge, attitudes, behavior, and domestic violence data collected at the state level.
    - A subsample of 15% of households selected from the district sample for the state module.
- **Household Selection for State Module:**
    - Every alternate selected household in 30% of randomly selected clusters interviewed for state module.
- **Subsampling and Segmentation:**
    - Villages with fewer than 40 households linked to nearest PSU.
    - Selected PSUs with estimated 300+ households segmented into segments of 100-150 households.
    - Two segments randomly selected for survey using systematic sampling.
- **Data Quality Measures:**
    - Complete household mapping and listing conducted prior to main survey.
    - Detailed description of sampling design, weight computation, estimation of standard errors, and data quality enhancement strategies provided in Volume II of national report.


#### Sample Weighting
- Not all areas or households have an equal chance of being chosen for the survey. Some areas might have more households, while others might have fewer. Similarly, some households might be easier to reach or more likely to respond than others.

- To ensure that the survey results accurately represent the entire population, weights are assigned to each household. These weights are calculated based on the probability of selecting each household.

- Essentially, households with a lower probability of being selected are given higher weights in the analysis to ensure that they have a proportional representation in the final results. 

- This process corrects for any biases in the sample and ensures that the survey findings are truly reflective of the entire population. By giving higher weights to households that are less likely to be chosen, the survey corrects for any underrepresentation of certain groups. 

- For example, if rural areas are less likely to be sampled but represent a large portion of the population, households from rural areas will receive higher weights to ensure their representation in the survey results.

#### Types of Sample Weights in NFHS-5:
- Household Weight:
	- - This weight is assigned to each household in the survey.
	- It's calculated based on the household's probability of being selected for the survey and the household's response rate.
- **State-Level Household Weight (shv005)**:
	- Similar to hv005 but used specifically for estimating state-level household indicators and district-level indicators within selected states.
	- Essentially, it's a version of hv005 adjusted for state-level analysis.
- **Individual Weight for Women (v005)**:
	- This weight is assigned to each woman surveyed within a household.
	- Calculated by multiplying the household weight (hv005) by the individual woman's response rate.
	- Used for estimating women's indicators at different levels, similar to household weight but at an individual level.
- **State-Level Individual Weight for Women (sv005)**:
	- Similar to v005 but used specifically for estimating state-level individual indicators and district-level indicators within selected states.
- **Individual Weight for Men (mv005)**:
	- Similar to v005 but used for men surveyed within households.
	- Calculated using the household weight for the men's subsample and the individual men's response rate.
- **State-Level Individual Weight for Men (smv005)**:
    - Similar to mv005 but used specifically for estimating state-level individual indicators and district-level indicators within selected states.
- **Domestic Violence Weight (d005)**:
    - This weight is specifically adjusted for the domestic violence module.
    - Calculated based on the individual weight for women (v005) adjusted for within-household selection probabilities and non-response for the domestic violence module.
    - Used for estimating women's indicators related to domestic violence at various levels.
- **State-Level Domestic Violence Weight (sd005)**:
    - Similar to d005 but used specifically for estimating state-level domestic violence indicators.