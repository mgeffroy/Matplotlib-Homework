# Matplotlib-Homework
## Matplotlib Homework for the Data Analysis Bootcamp: Pandas, Pandas, Pandas!. 
## Information: 
This repository contains the code for the analysis of the CSV files of a screening that looks for potential treatments for squamous cell carcinoma (SCC), using the information of 249 mice.  
### Pymaceuticals 
This repository contains the following: 
- ***main_pymaceuticals.ipynb:*** Notebook document made to analyze the results of the SCC experiment. The first part has an brief analysis of the obtained results and the data presented in this notebook. There are statistical summaries, boxplots, bar and pie charts, scatterplots and correlation and regression analysis throughout the notebook.  At the first part there is a brief analysis of the data presented. 
- ***Data***
  - ***Mouse_metadata.csv:*** Csv file that contains the information about the mice in the trial. It has the data for mouse ID sex, age, weight, drug regimen and sex. 
  - ***Study_results.csv:*** Csv file that contains the information regarding the procedures and results of the clinical trials. It has the information for each mice, the timepoint, tumor volume and metastasic sites. 
   
## Main Findings of the Analysis 
### Pymaceuticals Analysis 
- Concerning the sex of the mice, the distribution was almost even, due to the population being composed by 50.74% of male mice and 49.26% of females.

![image](https://user-images.githubusercontent.com/79372976/122690184-a45dd800-d1ed-11eb-8c63-1be5fdb4f7c7.png)

- At least 9 drug regimens were tested ( and a placebo). Out of these drugs Ramicane seems to be the most effective in reducing tumor growth, having the lowest mean, median, variance and standard deviation. It is followed closely by Capmulin. This can be seen in the drug summary table and also, in the boxplot. As well both drugs were both the ones that had the highest amount of essays (timepoints). 

![image](https://user-images.githubusercontent.com/79372976/122690210-ca837800-d1ed-11eb-8f43-26c97edd42e4.png)

- The tumor growth for capomulin in two mice has slightly different behaviours, but still there is an increase in tumor volume, that is followed by a decrease in tumor volume. The first mouse that was taken as an example first had and increased tumor growth until day following by a drop on day 20. The second mouse had a slight increase, but this happened only for around 7 days, and then decreased constantly until the end of the experiment. 

![image](https://user-images.githubusercontent.com/79372976/122690326-82188a00-d1ee-11eb-8613-d247429dc981.png)

![image](https://user-images.githubusercontent.com/79372976/122690268-17674e80-d1ee-11eb-8f03-295b4a7dc2f1.png)



- The correlation and regression tells us there is a strong positive relationship between tumor volume and mouse weight ( the heavier the mouse, the bigger tumor volume). The correlation between both factors is 0.84.

![image](https://user-images.githubusercontent.com/79372976/122690284-382fa400-d1ee-11eb-83a8-f6ddcd846cce.png)

