<div align="center">
    <h1>Unlocking Happiness</h1>
</div>

<div align="center">
    <h2>Data Insights On What<br>
    Really Matters In Life</h2>
</div>

<div align="center">
    <img src="ENTER PHOTO HERE" alt="" width="500"/>
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
    - [Social Isolation](#social-isolation)
    - [Mental Health Ratings](#mental-health-ratings)
    - [Satisfaction with Remote Work](#satisfaction-with-remote-work)
- [Summary](#summary)
- [Recommendation](#recommendation)

  
  
  
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

1. Does work location (remote, hybrid, on-site), serve as a positive driving force towards increasing people’s well being and life satisfaction?  

2. Can machine learning help us understand which variables have the highest impact to a greater quality of life?


By exploring these questions, we aim to deepen our understanding of the factors that influence individual happiness and uncover new strategies to enhance overall quality of life.

[Back to Top](#top)

---

## Resources

The following dataset was used for this analysis:

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
    <img src="ENTER PHOTO HERE" alt="" width="500"/>
</div>


The data revealed that Iceland, Denmark, and Sweden rank as the top three countries in terms of happiness. This finding led us to wonder: What factors contribute to higher happiness levels in these countries, and how can we measure overall well-being in a meaningful way? Given that work is a central part of daily life, we hypothesized that different work environments could have a significant impact on overall happiness. With this insight, we decided to broaden our focus and look at how various work-related factors influence well-being.


[Back to Top](#top)

## Looking At The Bigger Picture

Building on the initial findings, we developed a Tableau dashboard to examine four key factors that may impact happiness across different work settings: sleep quality, stress levels, feelings of isolation, and mental health ratings. By analyzing these metrics, we aim to uncover data-driven insights into how work environments shape overall well-being. This broader perspective provides a foundation for deeper exploration into how specific work conditions can enhance or detract from life satisfaction.

<div align="center">
    <img src="ENTER PHOTO HERE" alt="" width="500"/>
</div>

[ADD A SHORT SUMMARY OF DASHBOARD HERE]

[Back to Top](#top)

## Machine Learning Models

Machine learning models are computer programs created to recognize patterns in data and make predictions. These models are developed using machine learning algorithms, trained on data that may be labeled, unlabeled, or a mix of both. For this project, two primary types of machine learning models are used: Supervised and Unsupervised Learning. Below is an example illustrating how a machine learning model works.

<div align="center">
    <img src="ENTER PHOTO HERE" alt="" width="500"/>
</div>

[Back to Top](#top)

## Unsupervised Learning

Unsupervised learning is a type of machine learning where the model is trained on data without predefined labels or categories. Unlike supervised learning, which requires labeled data to learn from which we will coverin the next section, unsupervised learning algorithms identify patterns, structures, and relationships within the data on their own. This approach is often used for tasks like clustering, where similar data points are grouped together, and dimensionality reduction, which simplifies data while retaining essential information. Unsupervised learning helps uncover hidden insights, enabling us to make sense of complex data and discover meaningful groupings without needing prior knowledge of the categories.

<div align="center">
    <h3>Unsupervised Learning Illustration</h3>
</div>

<div align="center">
    <img src="ENTER PHOTO HERE" alt="" width="500"/>
</div>

### Clustering and PCA Models

<div align="center">
    <img src="ENTER PHOTO HERE" alt="" width="500"/>
</div>

[Back to Top](#top)

## Supervised Learning

Supervised learning is a type of machine learning where the model is trained on a labeled dataset, meaning each data point is paired with an output label. The model learns by identifying patterns and relationships between the input data and the corresponding labels, allowing it to make predictions on new, unseen data. Supervised learning is commonly used for tasks such as classification, where data is categorized into predefined groups, and regression, where continuous outcomes are predicted. By learning from labeled examples, supervised learning algorithms can accurately predict outcomes, making them valuable for applications like spam detection, image recognition, and financial forecasting.

<div align="center">
    <h3>Supervised Learning Illustration</h3>
</div>

<div align="center">
    <img src="ENTER PHOTO HERE" alt="" width="500"/>
</div>



### Decision Tree Model

In this analysis, we used a decision tree model to predict different stress levels based on various work settings. A decision tree is a supervised learning algorithm commonly used for classification and regression tasks. It operates by splitting data into branches according to feature values, creating a tree-like structure where each node represents a decision rule, and each branch leads to a specific outcome. Starting from the root node, the model divides the data at each level based on the feature that best separates it, using metrics like Gini impurity or information gain. Decision trees are highly interpretable and visually intuitive, making them valuable for understanding decision-making processes in areas such as customer segmentation, medical diagnosis, and loan approval predictions.


<div align="center">
    <img src="ENTER PHOTO HERE" alt="" width="500"/>
</div>

The decision tree model provided valuable insights into factors influencing stress levels in various work settings, achieving a high accuracy of 94% with strong performance across all stress categories. Age, Years of Experience, and Number of Virtual Meetings emerged as the top predictors, indicating that both individual characteristics and virtual interactions strongly impact workplace stress. Additionally, Job Role and Region showed that occupational and geographic contexts matter. Factors like Company Support for Remote Work, Work-Life Balance Rating, physical activity, and mental health conditions also contributed to the model, highlighting the importance of supportive work environments and a balanced work-life dynamic. These findings suggest that tailored support and policies promoting work-life balance could effectively reduce workplace stress and improve employee well-being.


[Back to Top](#top)

### Random Forest Model

In this analysis, we used a random forest model to predict different stress levels based on various work-related factors. A random forest is a supervised learning algorithm that builds multiple decision trees and combines their predictions to improve accuracy and reduce overfitting. Each tree in the forest makes an independent prediction, and the final output is determined by aggregating these predictions, often through a majority vote for classification tasks. This approach increases the model's robustness and accuracy by minimizing the impact of any single decision tree’s errors. Random forests are especially useful for handling complex data with many features and interactions, making them a powerful tool for understanding which factors, such as age, work-life balance, and company support, are most influential in predicting stress levels.

<div align="center">
    <img src="ENTER PHOTO HERE" alt="" width="500"/>
</div>

The analysis of stress predictors using both the random forest and decision tree models provided valuable insights, with some noteworthy comparisons between the two. The random forest model achieved a slightly higher accuracy of 97.6% compared to the decision tree model’s 94%, indicating that the ensemble method of combining multiple decision trees improved predictive accuracy and reduced overfitting. Both models identified Age, Years of Experience, and Number of Virtual Meetings as the top factors influencing stress levels, reinforcing these variables as critical indicators across different modeling approaches.

Both models emphasize the importance of individual demographics, virtual meeting load, and organizational support in influencing stress. Still, the random forest’s robustness in handling complex interactions among variables provides a more comprehensive understanding, while the decision tree model offers a straightforward view of primary predictors. Together, these models offer a balanced perspective, with the random forest model providing depth and the decision tree model providing clarity in identifying stress-influencing factors.

[Back to Top](#top)

### Partial Dependence Plots

Given that both the random forest and decision tree models identified age, years of experience, and number of virtual meetings as the most significant predictors of stress, we sought to explore further how different stress levels are influenced by each of these features independently.

To achieve this, we leveraged partial dependence plots (PDPs) to gain a deeper understanding of how specific features impact stress levels across various work settings. Partial dependence plots are a tool in machine learning that visualize the relationship between one or more predictor variables and the predicted outcome, while keeping all other variables constant. By isolating the effect of individual features—such as age, number of virtual meetings, or work-life balance rating—PDPs allow us to see how changes in these variables affect predicted stress levels.

PDPs are particularly valuable for interpreting complex models, like random forests, where it can be challenging to discern how each feature contributes to the prediction. By showing the average effect of a single feature on the outcome, partial dependence plots make it easier to pinpoint which factors tend to increase or decrease stress and to what degree. This insight supports targeted strategies to reduce stress by focusing on the most impactful aspects of work conditions.

<div align="center">
    <img src="ENTER PHOTO HERE" alt="" width="500"/>
</div>


The partial dependence plots for high stress level predictions reveal interesting insights into how specific features impact stress. Age shows a gradual increase in partial dependence as it approaches the mid-50s, suggesting that older employees may experience slightly higher stress levels. Years of Experience also exhibits an upward trend, indicating that individuals with more experience tend to have higher stress, possibly due to increased responsibilities or expectations. The Number of Virtual Meetings feature shows fluctuating partial dependence, with moderate levels of virtual meetings correlating with higher stress, while lower and higher extremes tend to show a decrease. These findings suggest that age, experience, and virtual meeting frequency all play nuanced roles in influencing stress, with mid-levels of experience and moderate virtual meeting load potentially contributing most to elevated stress levels. Understanding these patterns can inform targeted interventions to support employees at different stages in their careers and manage virtual work demands.

[Back to Top](#top)


## Tableau
<div align="center">
    <img src="ENTER PHOTO HERE" alt="" width="500"/>
</div>

[Back to Top](#top)

### Social Isolation
<div align="center">
    <img src="ENTER PHOTO HERE" alt="" width="500"/>
</div>

[Back to Top](#top)


### Mental Health Ratings
<div align="center">
    <img src="ENTER PHOTO HERE" alt="" width="500"/>
</div>

[Back to Top](#top)

### Satisfaction with Remote Work


## Summary


## Recommendation

