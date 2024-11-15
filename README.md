<div align="center">
    <h1>Unlocking Happiness</h1>
</div>

<div align="center">
    <img src="https://github.com/thecolombian/Project-4/blob/tai/IMAGES/intro_pic.jpg" alt="intro_pic" width="700"/>
</div>

<div align="center">
    <h2>Data Insights On What Really Matters In Life</h2>
</div>

<div align="center">
    <h3><b>Team Members:</b></h3>
    <h4>
      Eduardo Gonzalez<br>
      Jenny Jaurequi<br>
      Mariem Diaz<br>
      Jorge Reyes<br>
      Tai Reagan
    </h4>
</div>


---
<a name="top"></a>
# Table of Contents

<details>
    <summary>Click to expand</summary>
  
  
- [Project Description](#project-description)
- [Objective](#objective)
- [Resources](#resources)
- [Project Outline](#project-outline)
- [Where Are All The Happy People At?](#where-are-all-the-happy-people-at)
- [Looking At The Bigger Picture](#looking-at-the-bigger-picture)
- [Machine Learning Models](#machine-learning-models)
    - [Unsupervised Learning](#unsupervised-learning)
         - [Clustering and PCA Models](#clustering-and-pca-models)  
    - [Supervised Learning](#supervised-learning)
        - [Decision Tree Model](#decision-tree-model)
        - [Random Forest Model](#random-forest-model)
        - [Partial Dependence Plots](#partial-dependence-plots)          
- [Tableau](#tableau)
    - [Mental Health and Satisfaction with Remote Work](#mental-health-and-satisfaction-with-remote-work)
    - [Social Isolation](#social-isolation)
- [Summary](#summary)
- [Recommendations](#recommendations)

  
  
  
  </details>
  
---

## Project Description

In today’s rapidly evolving work landscape, especially post-pandemic, companies worldwide are encountering new challenges related to employee morale, productivity, and overall well-being. This project seeks to analyze how various work settings and personal factors contribute to employees' life satisfaction and well-being, offering data-driven insights that organizations can use to create a more supportive and productive work environment.

The analysis incorporates a comprehensive dataset that includes key variables influencing individual well-being, such as stress levels, sleep quality, access to mental health resources, physical activity, social isolation, work-life balance, and job satisfaction. While happiness is a multifaceted concept influenced by many factors, this project focuses specifically on workplace conditions to uncover patterns that might explain why certain countries, like Iceland, Denmark, and Sweden, consistently rank among the highest in overall happiness.

To achieve these insights, a range of machine learning techniques—including Decision Trees, Random Forests, supervised and unsupervised learning, and Principal Component Analysis (PCA)—is employed. Supervised models like Decision Trees and Random Forests allow for the prediction of life satisfaction and identification of the most impactful factors, while unsupervised learning and PCA reveal hidden patterns and groupings within the data. These methods highlight key areas where work-related factors influence well-being and allow for a deeper understanding of the links between workplace conditions and overall happiness.

By generating actionable insights, this project aims to equip organizations with strategies to enhance employee satisfaction, well-being, and motivation. Beyond serving as a practical resource for businesses, this analysis also contributes to the broader discourse on work-life balance and employee happiness in the modern workplace. The combination of thorough data analysis and advanced machine learning techniques ensures that these findings are both comprehensive and rooted in robust analytical methods, making them valuable for decision-making in today’s dynamic work environment.

[Back to Top](#top)

---

## Objective

This project aims to address the question, "How do working conditions impact employee well-being and life satisfaction in countries with higher happiness ratings?" To answer this, the analysis will delve into related sub-questions to provide a comprehensive understanding of the factors influencing employee satisfaction.

**1.** Does work location (remote, hybrid, on-site), serve as a positive driving force towards increasing people’s well being and life satisfaction?  

**2.** Can machine learning help us understand which variables have the highest impact to a greater quality of life?


By exploring these questions, we aim to deepen our understanding of the factors that influence individual happiness and uncover new strategies to enhance overall quality of life.

[Back to Top](#top)

---

## Resources

**The following dataset was used for this analysis:**

### Remote Work & Mental Health

The [Remote Work and Mental Health](https://www.kaggle.com/datasets/waqi786/remote-work-and-mental-health)  dataset on Kaggle offers insights into how remote work influences mental well-being. It includes data on stress levels, work-life balance, and productivity among remote workers.


> [!WARNING]
> Please note that the dataset used in this analysis may contain synthetic data. Synthetic data is artificially generated, often designed to resemble real-world data patterns without originating from actual individuals or events. While synthetic datasets can provide valuable insights and maintain privacy, they may not fully capture the complexities and nuances found in authentic data. Analyses and insights derived from synthetic data should be interpreted with caution, as certain trends, correlations, or relationships may not hold in real-world applications. When applying these findings to real-world scenarios, further validation using authentic data is recommended to ensure accuracy and reliability. We advise stakeholders to consider this limitation when drawing conclusions or making data-driven decisions based on this analysis.

### Our World In Data

The [Happiness and Life Satisfaction](https://ourworldindata.org/happiness-and-life-satisfaction) Data provides a comprehensive analysis of global well-being, focusing on self-reported measures of happiness and life satisfaction. It explores variations across countries and over time, examining factors such as income, health, and social support that influence subjective well-being.

---

[Back to Top](#top)

## Project Outline

1. **Project Ideation:** Define the research questions, objectives, and scope of the project to ensure a clear focus on the impact of work settings on employee well-being.

2. **Data Fetching Integration:** Collect relevant data through data sources, ensuring a comprehensive dataset that includes key indicators of employee work setting and well-being.

3. **Data Analysis:** Clean, preprocess, and analyze the data to uncover patterns, correlations, and insights into factors affecting employee well-being.

4. **Building the ML Model:** Develop machine learning models, such as Decision Trees and Random Forests, to identify influential factors and predict employee satisfaction levels.

5. **Testing:** Evaluate and validate model performance to ensure accuracy and reliability in predicting employee well-being and satisfaction.

6. **Creating Documentation:** Document the project process, methodology, and findings to ensure clarity and reproducibility for future users.

7. **Creating the Presentation:** Summarize the insights, methodology, and results in a presentation format to communicate findings effectively to stakeholders.

[Back to Top](#top)


---

## Where Are All The Happy People At?

To begin our analysis and address the central question—How do working conditions impact employee well-being and life satisfaction in countries with higher happiness ratings?—we started by identifying the countries with the highest overall happiness scores. Using the [Happiness and Life Satisfaction](https://ourworldindata.org/happiness-and-life-satisfaction) dataset, we gained an initial understanding of global happiness distribution and pinpointed where the happiest populations reside.

<div align="center">
    <img src="https://github.com/thecolombian/Project-4/blob/main/IMAGES/happiness_by_country.png" alt="happiness_by_country" width="600"/>
</div>


The data revealed that Iceland, Denmark, and Sweden rank as the top three countries in terms of happiness. This finding led us to wonder: What factors contribute to higher happiness levels in these countries, and how can we measure overall well-being in a meaningful way? Given that work is a central part of daily life, we hypothesized that different work environments could have a significant impact on overall happiness. With this insight, we decided to broaden our focus and look at how various work-related factors influence well-being.


[Back to Top](#top)

## Looking At The Bigger Picture

Building on the initial findings, we developed a Tableau dashboard to examine four key factors that may impact happiness across different work settings: sleep quality, stress levels, feelings of isolation, and mental health ratings. By analyzing these metrics, we aim to uncover data-driven insights into how work environments shape overall well-being. This broader perspective provides a foundation for deeper exploration into how specific work conditions can enhance or detract from life satisfaction.

<div align="center">
    <img src="https://github.com/thecolombian/Project-4/blob/main/IMAGES/dashboard_overview.png" alt="dashboard_overview" width="700"/>
</div>

This dashboard provides a concise, data-driven overview of how work settings—remote, hybrid, and onsite—correlate with employee mental health, stress levels, sleep quality, and social isolation. The findings indicate nuanced relationships between work location and well-being, suggesting that each setting offers distinct advantages and challenges. 

### Overall Trends:
Remote work is associated with higher rates of anxiety, depression, and isolation, while hybrid work shows a more balanced impact, with moderate levels of stress, anxiety, and depression. Onsite work, in contrast, is linked to a higher prevalence of burnout but lower levels of anxiety and depression.

### Specific Insights:

**Anxiety & Depression:** Highest among remote workers, highlighting potential mental health risks associated with social isolation in remote settings.

**Burnout:** Most prevalent in onsite work, suggesting potential challenges related to commute and rigid schedules.

**Stress Levels:** Hybrid work shows the highest levels of medium and high stress, indicating that balancing onsite and remote responsibilities can be demanding.

**Isolation:** Remote workers report the highest isolation, underlining the need for social support systems in remote work arrangements.

**Interpretations:** These patterns suggest that remote work offers flexibility but may increase isolation-related mental health issues, while hybrid work provides a balanced experience but can still be stressful. Onsite work offers social interaction but may lead to burnout.

Overall, these insights reveal the complex ways in which work location affects employee well-being, underscoring the importance of tailored support strategies for each work setting. This analysis serves as a foundation as we dive deeper into these specific variables using machine learning models. 

[Back to Top](#top)

## Machine Learning Models

Machine learning models are computer programs created to recognize patterns in data and make predictions. These models are developed using machine learning algorithms, trained on data that may be labeled, unlabeled, or a mix of both. For this project, two primary types of machine learning models are used: Supervised and Unsupervised Learning. Below is an example illustrating how a machine learning model works.

<div align="center">
    <img src="https://github.com/thecolombian/Project-4/blob/main/IMAGES/machine_learning.jpg" alt="machine_learning" width="700"/>
</div>

[Back to Top](#top)

## Unsupervised Learning

Unsupervised learning is a type of machine learning where the model is trained on data without predefined labels or categories. Unlike supervised learning, which requires labeled data to learn from which we will coverin the next section, unsupervised learning algorithms identify patterns, structures, and relationships within the data on their own. This approach is often used for tasks like clustering, where similar data points are grouped together, and dimensionality reduction, which simplifies data while retaining essential information. Unsupervised learning helps uncover hidden insights, enabling us to make sense of complex data and discover meaningful groupings without needing prior knowledge of the categories.

<div align="center">
    <h3>Unsupervised Learning Illustration</h3>
</div>

<div align="center">
    <img src="https://github.com/thecolombian/Project-4/blob/main/IMAGES/Unsupervised_learning.png" alt="unsupervised_learning" width="700"/>
</div>

## Clustering and PCA Models

This project contains two clustering models aimed at understanding the factors that affect employee sleep quality in remote, hybrid and on site work settings. We used two different approaches to explore the interactions between employee work-life factors and sleep quality. Each model differs in the features analyzed, clustering results, and overall findings.

<div align="center">
    <h2>Model 1: Clustering Without Sleep Quality Feature</h2>
</div>


### Purpose
In this model, we dropped the *Sleep Quality* feature to examine how other factors related to work-life balance, satisfaction, stress, social isolation, and company support interact with each other. This approach allowed us to explore if distinct patterns emerged within these factors independent of direct sleep quality information.

### Steps
1. **Feature Selection and Preprocessing**:
   - Removed columns related to *Sleep Quality*, *Employee ID*, and others irrelevant to clustering.
   - Applied one-hot encoding on categorical features.
   - Scaled the features using `StandardScaler` for uniformity.

2. **Dimensionality Reduction (PCA)**:
   - Reduced the data to 2 principal components for easier visualization.
   
3. **Clustering (KMeans)**:
   - Used the elbow method and silhouette scores to determine an optimal cluster count.
   - **Optimal Clusters**: 3 clusters, chosen based on the elbow curve and silhouette score evaluation.


### Findings
- **Cluster Characteristics**: We identified three clusters, with two clusters showing some overlap while the third was more distinct, suggesting unique factor interactions among that group.
- **Implications**: These clusters might represent different employee groups with varied work-life and mental health experiences, which could indirectly influence sleep quality.
<div align="center">
    <img src="https://github.com/thecolombian/Project-4/blob/main/mariem_project4/Images/sleep_clusters.png" alt="decision_tree_classification_report" width="700"/>
</div>

<div align="center">
    <h2>Model 2: Clustering Including Sleep Quality Feature</h2>
</div>

### Purpose
This model includes the *Sleep Quality* feature to directly investigate how it clusters alongside work-life factors. By adding sleep quality into the model, we aimed to see if its inclusion alters cluster formation and reveals new insights into the relationships between work factors and sleep.

### Steps
1. **Feature Selection and Preprocessing**:
   - Selected features including *Sleep Quality*, work-life factors, and mental health support.
   - Applied one-hot encoding where necessary.
   - Scaled all features using `StandardScaler`.

2. **Dimensionality Reduction (PCA)**:
   - Reduced dimensions to 2 principal components for visualization while preserving feature variance.

3. **Clustering (KMeans)**:
   - Evaluated clusters using the elbow method and silhouette scores, selecting 5 clusters as optimal.

### Findings
- **Cluster Characteristics**: Five clusters were identified, with one group showing significantly lower sleep quality scores and higher stress levels. Other clusters displayed varying levels of work-life balance, satisfaction, and company support.
- **Implications**: These clusters provide actionable insights for addressing specific groups' needs to improve sleep quality and work satisfaction. For instance, the cluster with low sleep quality may benefit from targeted mental health resources.
<div align="center">
    <img src="https://github.com/thecolombian/Project-4/blob/main/Presentation%20Images/happiness_clusters%20copy.png" alt="decision_tree_classification_report" width="700"/>
</div>

[Back to Top](#top)

## Supervised Learning

Supervised learning is a type of machine learning where the model is trained on a labeled dataset, meaning each data point is paired with an output label. The model learns by identifying patterns and relationships between the input data and the corresponding labels, allowing it to make predictions on new, unseen data. Supervised learning is commonly used for tasks such as classification, where data is categorized into predefined groups, and regression, where continuous outcomes are predicted. By learning from labeled examples, supervised learning algorithms can accurately predict outcomes, making them valuable for applications like spam detection, image recognition, and financial forecasting.

<div align="center">
    <h3>Supervised Learning Illustration</h3>
</div>

<div align="center">
    <img src="https://github.com/thecolombian/Project-4/blob/tai/IMAGES/supervised_learning.png" alt="supervised_learning" width="700"/>
</div>



### Decision Tree Model

In this analysis, we employed a decision tree model to predict different stress levels based on various work-related features. A decision tree is a supervised learning algorithm commonly used for classification and regression tasks. It operates by splitting data into branches according to feature values, creating a tree-like structure where each node represents a decision rule, and each branch leads to a specific outcome. Starting from the root node the model evaluates each feature to determine the optimal splits, using metrics like Gini impurity or information gain to guide these decisions. Decision trees are highly interpretable and visually intuitive, making them valuable tools for understanding complex decision-making processes in fields such as customer segmentation, medical diagnosis, and employee well-being.


<div align="center">
    <img src="https://github.com/thecolombian/Project-4/blob/tai/IMAGES/decision_tree_classification_report.png" alt="decision_tree_classification_report" width="700"/>
</div>

The decision tree model provided meaningful insights into factors influencing stress levels, achieving a high overall accuracy of 94%. The classification report shows consistently high precision, recall, and F1-scores across all stress categories, underscoring the model’s reliability in predicting stress outcomes. 


<div align="center">
    <img src="https://github.com/thecolombian/Project-4/blob/tai/IMAGES/feature_importance_decision_tree_graph.png" alt="decision_tree_feature_importance" width="700"/>
</div>

To gain further insights on what variables have the highest importance, the feature importance graph further illustrates the significance of individual features in predicting stress levels. The top predictors—Age, Years of Experience, and Number of Virtual Meetings—reflect the impact of demographic and interaction-related factors. Other influential variables, such as Company Support for Remote Work and Work-Life Balance Rating, underscore the importance of supportive environments and balanced work-life dynamics in managing stress. Together, these findings indicate that a mix of personal, occupational, and organizational factors contribute to stress outcomes, suggesting that tailored support and policies promoting work-life balance could effectively enhance employee well-being.

In summary, the decision tree model demonstrated robust performance and interpretability, offering valuable insights into how various factors affect stress levels. The feature importance graph identified Age, Years of Experience, and Number of Virtual Meetings as the strongest predictors, highlighting the significance of both demographic characteristics and virtual meeting in shaping workplace stress. Additionally, Job Role and Region contributed to the model’s accuracy, demonstrating that occupational and geographic factors also play a role in influencing stress. These findings support the model's utility in identifying key indicators of workplace stress with a high level of predictive performance.

[Back to Top](#top)

### Random Forest Model

In this analysis, we used a random forest model to predict different stress levels based on various work-related factors. A random forest is a supervised learning algorithm that builds multiple decision trees and combines their predictions to improve accuracy and reduce overfitting. Each tree in the forest makes an independent prediction, and the final output is determined by aggregating these predictions, often through a majority vote in classification tasks. This approach increases the model's robustness and accuracy by minimizing the impact of any single decision tree’s errors. Random forests are especially useful for handling complex data with many features and interactions, making them a powerful tool for understanding which factors, such as age, work-life balance, and company support, are most influential in predicting stress levels.


<div align="center">
    <img src="https://github.com/thecolombian/Project-4/blob/tai/IMAGES/Random_Forest_classification_report.png" alt="Random_Forest_classification_report" width="700"/>
</div>

The random forest model achieved an impressive accuracy of 97.6%, outperforming the decision tree model's accuracy of 94%. The classification report demonstrates consistently high precision, recall, and F1-scores across all stress categories, which underscores the model's effectiveness in predicting stress levels accurately. This high accuracy highlights the advantage of using an ensemble approach, as it combines multiple decision trees to improve predictive performance and reduce overfitting.

<div align="center">
    <img src="https://github.com/thecolombian/Project-4/blob/tai/IMAGES/random_forestfeature_importance_graph.png" alt="random_forestfeature_importance_graph" width="700"/>
</div>

The feature importance graph reveals that Age, Years of Experience, and Number of Virtual Meetings are the most significant predictors of stress, aligning with the decision tree model's findings. This consistency reinforces the critical role of demographic characteristics and virtual interactions in shaping workplace stress. Additional variables, such as Company Support for Remote Work and Work-Life Balance Rating, also emerged as influential factors, underscoring the value of supportive work environments and balanced schedules in mitigating stress.

Together, the random forest and decision tree models emphasize the importance of individual demographics, virtual meeting frequency, and organizational support in predicting stress. However, the random forest model’s robustness in handling complex interactions provides a more comprehensive understanding, while the decision tree model offers a clear view of primary predictors. These models collectively offer a balanced perspective, with the random forest model providing depth and the decision tree model offering clarity in identifying key stress-influencing factors.


[Back to Top](#top)

### Partial Dependence Plots

Given that both the random forest and decision tree models identified age, years of experience, and number of virtual meetings as the most significant predictors of stress, we sought to explore further how different stress levels are influenced by each of these features independently.

To achieve this, we leveraged partial dependence plots (PDPs) to gain a deeper understanding of how specific features impact stress levels across various work settings. Partial dependence plots are a tool in machine learning that visualize the relationship between one or more predictor variables and the predicted outcome, while keeping all other variables constant. By isolating the effect of individual features—such as age, number of virtual meetings, or work-life balance rating—PDPs allow us to see how changes in these variables affect predicted stress levels.

PDPs are particularly valuable for interpreting complex models, like random forests, where it can be challenging to discern how each feature contributes to the prediction. By showing the average effect of a single feature on the outcome, partial dependence plots make it easier to pinpoint which factors tend to increase or decrease stress and to what degree. This insight supports targeted strategies to reduce stress by focusing on the most impactful aspects of work conditions.

<div align="center">
    <h3>Partial Dependence Plots For Low Stress Level</h3>
</div>

<div align="center">
    <img src="https://github.com/thecolombian/Project-4/blob/tai/IMAGES/partial_dependence_stress_low_level.png" alt="partial_dependence_stress_low_level" width="800"/>
</div>


The partial dependence plot for low stress levels highlights how certain factors influence employees' likelihood of experiencing reduced stress. Age shows a gradual increase, especially after 50, suggesting older employees may report lower stress. Years of Experience peaks around 10–15 years, indicating employees in this range are more likely to experience low stress. Additionally, fewer Virtual Meetings correlate with lower stress, as shown by a sharp drop in partial dependence at lower values. These findings suggest that age, experience, and virtual meeting frequency play significant roles in predicting low stress levels.


<div align="center">
    <h3>Partial Dependence Plots For Moderate Stress Level</h3>
</div>

<div align="center">
    <img src="https://github.com/thecolombian/Project-4/blob/tai/IMAGES/partial_dependence_stress_medium_level.png" alt="partial_dependence_stress_medium_level" width="800"/>
</div>

The partial dependence plot for medium stress levels reveals key trends in how certain factors impact the likelihood of experiencing moderate stress. Age maintains a relatively stable partial dependence up to around age 50, after which it sharply decreases, suggesting younger employees are more likely to experience moderate stress. Years of Experience shows some fluctuations, with a slight dip in moderate stress likelihood after 15 years, indicating that employees with more experience might have lower medium stress levels. Number of Virtual Meetings demonstrates an upward trend, suggesting that as the number of virtual meetings increases, so does the likelihood of experiencing moderate stress. These findings emphasize the influence of age, experience, and meeting frequency on medium stress levels.


<div align="center">
    <h3>Partial Dependence Plots For High Stress Level</h3>
</div>

<div align="center">
    <img src="https://github.com/thecolombian/Project-4/blob/tai/IMAGES/partial_dependence_stress_high_level.png" alt="partial_dependence_stress_high_level" width="800"/>
</div>


The partial dependence plots for high stress level predictions reveal interesting insights into how specific features impact stress. Age shows a gradual increase in partial dependence as it approaches the mid-50s, suggesting that older employees may experience slightly higher stress levels. Years of Experience also exhibits an upward trend, indicating that individuals with more experience tend to have higher stress, possibly due to increased responsibilities or expectations. The Number of Virtual Meetings feature shows fluctuating partial dependence, with moderate levels of virtual meetings correlating with higher stress, while lower and higher extremes tend to show a decrease. These findings suggest that age, experience, and virtual meeting frequency all play nuanced roles in influencing stress, with mid-levels of experience and moderate virtual meeting load potentially contributing most to elevated stress levels. Understanding these patterns can inform targeted interventions to support employees at different stages in their careers and manage virtual work demands.

<div align="center">
    <h3>Partial Dependence Plots For All Stress Levels </h3>
</div>

<div align="center">
    <img src="https://github.com/thecolombian/Project-4/blob/main/IMAGES/partial_dependence_plots_with_labels.png" alt="partial_dependence_plots_with_labels" width="800"/>
</div>

> [!TIP]
> The Partial Dependence Plots above are organized by stress levels, progressing from low to high. The first row represents the lowest stress level, the middle row indicates moderate stress, and the bottom row displays the highest stress level.

Overall, the PDPs highlight that age and years of experience are influential across all stress levels, with the number of virtual meetings being particularly impactful for moderate and high stress levels. These insights can guide targeted strategies to address stress based on an employee’s age, experience, and virtual meeting load, with the PDP for low stress levels showing the most significant and actionable results for promoting employee well-being.

[Back to Top](#top)


## Tableau

### Mental Health and Satisfaction with Remote Work

<div align="center">
    <img src="https://github.com/thecolombian/Project-4/blob/main/IMAGES/jj-image-1.png" alt="" width="800"/>
</div>

- **Dashboard Access:** You can explore the **Tableau dashboard** [here](https://public.tableau.com/views/health-remote-v3/Dashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

- **Mental Health and Remote Work Satisfaction:** Satisfaction levels are similar between individuals with and without mental health conditions. Notably, those experiencing burnout report higher satisfaction with remote work, possibly due to the flexibility and reduced commuting.

- **Productivity and Work Environment:** Remote and hybrid work setups are associated with increased productivity, whereas onsite work is linked to lower productivity. This trend holds true for individuals with mental health conditions, suggesting that remote work positively impacts productivity regardless of mental health status.

- **Regional Variations in Satisfaction:** Satisfaction with remote work varies by region. In Africa, Asia, Europe, Oceania, and South America, dissatisfaction surpasses satisfaction, while in North America, satisfaction and dissatisfaction are nearly equal, with a slight lean toward dissatisfaction. Regional challenges, like aligning with U.S. time zones, may contribute to lower satisfaction.

- **Sleep Quality Among Remote Workers:** Remote workers report a higher incidence of poor sleep quality, potentially due to irregular hours required to match employers’ time zones. Onsite workers generally report better sleep. Sleep quality appears consistent between those with and without mental health conditions.

[Back to Top](#top)

### Social Isolation

<div align="center">
    <h3> Social Isolation in Relation to Work Hours </h3>
</div>


<div align="center">
    <img src="https://github.com/thecolombian/Project-4/blob/main/social_iso/Soci_iso_images/social_isolation_by_work_hours.png" alt="social_isolation_by_work_hours" width="500"/>
</div>

The dataset used in this project utilized a variable called "Social_Isolation_Rating" which measured subjects reported self rating on how socially isolated they felt. The score for these ratings ranged from 1-5, with 1 acting as not feeling socially isolated, and 5 acting as feeling severly socially isolated. Most variables within the dataset were found to not have any clear connection to this social isolation rating, however of the two variables that displayed a distinct connection to each other was the variable describing the hours worked per week by each reporter. Originally, the variable was continuous, and ranged from low 20s to near 60 hours each week. In order to more clearly illustrate the connection these variables had, a new variable was created called Work_Hours_Category which grouped reporters based on their work week hours: part-time (<35 hours), full-time (35-45 hours), overtime (45-55) hours, and overworked (55+ hours). These categories were created based on a general idea of the amount of hours required to be employed full-time, with the overworked category being based on the general consensus of when a person will begin to experience physical harm from continuing to work. The grouped bar chart above depicts these work hour categories against the social isolation rating that the reporters gave. The chart shows part timers were more likely to report a high social isolation rating, but, as work hours increased into full-time and then overtime hours; those who fell into these work hour categories were more likely to report lower levels of social isolation as they increased their work hours. However, the people who were being overworked all had similar reporting rates of social isolation. This would mean that as people begin to become overworked, the previous trend falls apart, and the group reports similar rates of social isolation for each rating. A possible explanation for this phenomenon may be that due to the cultural norm of people typically being full-time workers, the less someone works the more likely they are to feel isolated due to the fact that their extra free time is spent alone as others are at work. This would then mean that working more naturally causes people to spend more time amongst other people, i.e., thier fellow co-workers. However, overwork overrides the socializing as people are more likely attempting to deal with their physical exhaustion in their own way.


<div align="center">
    <h3> Social Isolation in relation to Work Satisfaction </h3>
</div>

<div align="center">
    <img src="https://github.com/thecolombian/Project-4/blob/main/social_iso/Soci_iso_images/social_isolation_by_satisfaction_w_remote_work.png" alt="social_isolation_by_satisfaction_w_remote_work" width="500"/>
</div>

The second variable to have a connection to the social isolation ratings was Satisfaction_with_Remote_Work. These two variables appeared to have a somewhat negative correlation: those with low levels of social isolation reported to be outright unsatisfied with remote work, whereas people with high levels of social isolation were satisfied with remote work. On the surface level, this seems to be counterintuitive as people who are satisfied with remote work, should not be experiencing many stressors due to their appreciation of the type of work environment they have. The fact that the opposite occurs implies that it may be a result of why someone may prefer remote work, and what type of connection they have with the concept of community. It may be that those with low social isolation levels may be very social people, or at the very least have a strong communal network, and therefore may also desire to have a work environment that reflects this type of socialization. On the other end of the spectrum, the people who report high levels of social isolation may be dealing with introverted characteristics and as a result appreciate work that keeps them removed from close proximity with others. However, a more prudent suggestion may be that these individuals may be satisfied with remote work as it may fit in better with their day to day lives, but still feel isolated due to the nature of being alone during the remote work hours. 

[Back to Top](#top)



## Summary

To conclude, this analysis provides a detailed exploration of the ways in which different work settings influence employee mental health, productivity, and overall well-being. Our findings reveal that hybrid work arrangements often offer a more balanced environment, with lower reported levels of stress and isolation compared to fully remote or onsite work settings. In addition, factors such as sleep quality and productivity appear to be closely tied to work location, with remote workers benefiting from flexibility yet often experiencing poorer sleep due to irregular hours needed for time zone alignment.

The study also underscores the significant role that demographic factors and virtual work dynamics play in workplace stress. Our machine learning models identified age, years of experience, and the frequency of virtual meetings as key contributors to stress levels, suggesting that these factors require careful consideration in managing employee well-being. Regional variations in satisfaction with remote work, especially in relation to time zone challenges, further highlight the importance of context-specific support strategies.

In summary, these insights emphasize the need for targeted approaches to enhance work-life balance and employee satisfaction. By leveraging data-driven insights from machine learning and visualization tools, organizations can create supportive work environments that foster both productivity and personal well-being in an increasingly flexible workplace.

[Back to Top](#top)

## Recommendations

**Address Regional Time Zone Challenges:**
- Provide more resources and training for asynchronous communication to improve satisfaction in regions with significant time zone differences from employers.

**Collect Additional Demographic Data:**
- Include variables such as working hours, housing arrangements, and household responsibilities to better understand influences on satisfaction and productivity among different groups.

**Explore Interactions Between Physical Activity, Sleep Quality, and Stress:** 
- Conduct a deeper analysis into how lifestyle factors like physical activity and sleep quality interact with stress levels. 

**Acquire Real-World Data:**
- Explore methods to gather real-world data instead of relying on simulated data.

[Back to Top](#top)


