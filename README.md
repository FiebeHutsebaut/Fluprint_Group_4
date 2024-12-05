In dit kleur heb ik het report al eens ingevuld voor het eerste deel (univariate, uitgevoerd door Janne) 

 

**Introduction** 

Briefly explain the background, the research question of the analysis (what is the problem for which you formulated a hypothesis) and the dataset. 

Influenza has a devastating societal impact, causing up to 650,000 deaths every year worldwide. Vaccination is only partially effective, especially among young children and the elderly. Understanding the factors that influence vaccine response is crucial for improving vaccine efficacy. In this analysis, we investigate whether the level of IFNG (Interferon-gamma) is associated with the vaccine response using the FluPRINT dataset. 

**Methodology** 

Describe the (statistical) methods used for the analysis. Create a Github directory where you provide an annotated markdown (Rmarkdown and/or jupyter notebook) with your code. 

We used the FluPRINT dataset, which contains data from clinical studies on influenza vaccination. The dataset includes measurements of various biological markers and responses to vaccines. For this analysis, we focused on the IFNG levels and vaccine response. 

**Statistical methods:**

Directional Hypotheses: 

Null Hypothesis (H0): Higher levels of IFNG do not result in a stronger vaccine response. 

Alternative Hypothesis (H1): Higher levels of IFNG result in a stronger vaccine response. 

Wilcoxon Rank Sum Test: Since the data is not normally distributed, we performed a Wilcoxon rank sum test to compare IFNG levels between low and high vaccine responders. 

Visualization: We created a boxplot to visualize the distribution of IFNG levels between low and high vaccine responders. 


**Results**

Present the key findings of your analysis clearly. Create publication proof graphs to help visualize the results.  

Based on the Wilcoxon rank sum test results, we have a p-value of 0.01371. This suggests that there is a significant difference in IFNG levels between low and high vaccine responders. 




 
