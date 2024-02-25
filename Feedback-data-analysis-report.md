# Intel Unnati Machine Learning Course Feedback Analysis Report

## Problem Statement

The Intel Unnati Machine Learning Course Feedback Analysis Report aims to provide insights into various aspects of the course, such as faculty performance, content quality, and relevance to industry scenarios, based on student feedback. However, there is a need for a more targeted analysis focusing on segmentation of course participants to understand satisfaction levels across different groups.

### Challenges

1. **Segmentation of Participants**: Identifying meaningful segments within the course participants based on satisfaction levels, considering factors such as demographic information, educational background, and prior experience in machine learning.

2. **Satisfaction Measurement**: Developing appropriate metrics or indicators to measure satisfaction levels among course participants accurately.

3. **Interpretation of Segmentation Results**: Interpreting the segmentation results to derive actionable insights for improving the course and addressing specific needs of different participant segments.

### Objectives

1. **Segmentation Analysis**: Conduct a segmentation analysis to categorize course participants into distinct groups based on their satisfaction levels.

2. **Satisfaction Measurement**: Define and measure satisfaction levels using relevant metrics or indicators derived from the feedback data.

3. **Segment-specific Analysis**: Perform an in-depth analysis of each participant segment to understand their unique characteristics, needs, and areas of improvement.

4. **Actionable Insights Generation**: Derive actionable insights from the segmentation analysis to improve course delivery, content quality, and overall participant satisfaction.

### Significance

This study of the segmentation of Intel Certification course participants over satisfaction levels will provide valuable insights into the diverse needs and preferences of participants. By understanding the factors influencing satisfaction among different segments, Intel Unnati can tailor its course offerings and delivery methods to better meet the expectations and requirements of its participants, ultimately enhancing the overall learning experience and outcomes.


## Introduction

This detailed report analyses the student feedback for the Intel Unnati Machine Learning course. The feedback assesses the faculty-led sessions, gauging the course content's quality, delivery methods, faculty expertise, session organization, and relevance to real-world industry scenarios.

## Methodology

### Exploratory Data Analysis Approach :

- **Frequency Calculation**: We determined the occurrence of each unique value in the dataset, specifically focusing on the "Resource Person" and "Name" columns.
  
- **Percentage Calculation**: Converting the frequency counts into percentages allowed us to analyze the relative contribution of each resource person and participant.

- **Rounding**: The calculated percentages were rounded to improve readability and presentation.

Analyzing the distribution of feedback data across resource persons and participants is relevant as it sheds light on the engagement levels and participation patterns within the course. Understanding how feedback data is distributed facilitates the generation of insights into trends, preferences, and potential areas for improvement. It helps in identifying effective resource persons and active participants.

### Machine Learning Approach

K-means clustering was chosen as the ML technique to segment participants based on their satisfaction levels. The Elbow Method was used to determine the optimal number of clusters, and GridSearchCV was employed to fine-tune the hyperparameters of the K-means algorithm. The model was trained on features related to satisfaction levels (Content Quality, Effectiveness, Expertise, Relevance, Overall Organization), and participants were segmented into clusters based on their feedback.

The analysis utilizes both exploratory data analysis (EDA) and machine learning techniques. EDA involves summarizing the main characteristics of the dataset using visual methods to understand the distribution and relationships within the data. The machine learning aspect employs K-means clustering, an unsupervised learning algorithm, to segment the participants based on their feedback scores. This method is chosen due to its effectiveness in identifying distinct groups or clusters within the data without prior labeling.

## Exploratory Data Analysis (EDA)

The exploratory analysis revealed the following:

Faculty-wise distribution of data: The participants' responses were distributed across four different faculty members with Mrs. Akshara Sasidharan and Mrs. Veena A Kumar having the majority of the responses.

Branch-wise distribution: The boxplots per branch showed how the ratings varied across different departments, indicating the perceived content quality by branch.

Feedback was collected from students post-session and covers various dimensions of the teaching effectiveness and course content quality. The data was meticulously cleaned and preprocessed to ensure a high-quality analysis.

### Percentage analysis of Resource_person wise distribution of data

| Resource Person         | Percentage |
|-------------------------|------------|
| Mrs. Akshara Sasidharan | 28.99      |
| Mrs. Veena A Kumar      | 26.57      |
| Mrs. Gayathri J L       | 14.98      |
| Mr. Arun Sebastian      | 14.98      |
| Dr. Anju Pratap         | 14.49      |

### Percentage analysis of Name wise distribution of data

| Name                       | Percentage |
|----------------------------|------------|
| Rizia Sara Prabin          | 3.86       |
| Sidharth V Menon           | 3.86       |
| Aaron James Koshy          | 3.38       |
| Rahul Biju                 | 3.38       |
| Abna Ev                    | 3.38       |
| Allen John Manoj           | 3.38       |
| Christo Joseph Sajan       | 3.38       |
| Jobinjoy Ponnappal         | 3.38       |
| Varsha S Panicker          | 3.38       |
| Nandana A                  | 3.38       |
| Rahul Krishnan             | 3.38       |
| Anjana Vinod               | 3.38       |
| Kevin Kizhakekuttu Thomas  | 3.38       |
| Lara Marium Jacob          | 3.38       |
| Abia Abraham               | 3.38       |
| Shalin Ann Thomas          | 3.38       |
| Jobin Pius                 | 3.38       |
| Sebin Sebastian            | 2.90       |
| Aaron Thomas Blessen       | 2.90       |
| Sani Anna Varghese         | 2.90       |
| Bhagya Sureshkumar         | 2.90       |
| Leya Kurian                | 2.90       |
| Jobin Tom                  | 2.90       |
| Anaswara Biju              | 2.42       |
| Muhamed Adil               | 2.42       |
| Aiswarya Arun              | 2.42       |
| Mathews Reji               | 1.93       |
| Marianna Martin            | 1.93       |
| Riya Sara Shibu            | 1.93       |
| Riya Sara Shibu            | 1.45       |
| MATHEWS REJI               | 1.45       |
| Sarang kj                  | 1.45       |
| Lisbeth Ajith              | 1.45       |
| Aiswarya Arun              | 0.97       |
| Muhamed Adil               | 0.97       |
| Marianna Martin            | 0.97       |
| Lisbeth Ajith              | 0.48       |
| Anaswara Biju              | 0.48       |
| Lisbeth                    | 0.48       |
| Jobin Tom                  | 0.48       |
| Aaron Thomas Blessen       | 0.48       |


### Faculty Performance Analysis

The feedback distribution was analyzed to measure the performance and impact of each faculty member involved in the course.

### Faculty-wise Distribution of Data

The pie chart provides a holistic depiction of the distribution of resource persons by displaying the proportion of each resource person in relation to the entire dataset. Each segment of the pie denotes a resource person, with the size of the segment indicating their relative frequency.

![image](https://drive.google.com/uc?id=1M9RdXYzxno0il0nGVGBfA-Ba4va0wq3I)

The bar chart and pie chart show the count and percentage distribution of sessions conducted by each resource person.

### Summary of Responses

Boxplots showed the spread and central tendency of the satisfaction ratings across different aspects such as effectiveness, expertise, relevance, and overall organization, segmented by resource person and branch. This helped identify any outliers or anomalies in the feedback.

### Content Quality by Resource Person

![image](https://drive.google.com/uc?id=1ogs3o8rbW5_K4qqUaHl6F6CRodQsvoGe)

Boxplot showing the distribution of content quality ratings for each resource person.

### Effectiveness by Resource Person

![image](https://drive.google.com/uc?id=1jfXpgEQj2wYNgv_tYamURpuH2ESGwIdj)

 Boxplot indicating the effectiveness of training methods and delivery style by each resource person.

### Expertise by Resource Person

![image](https://drive.google.com/uc?id=1hKicp2j6nrUeNFTRCNnj6EGSMjFb-_X0)

Boxplot representing the expertise levels of resource persons as rated by students.

### Relevance to Industry by Resource Person

![image](https://drive.google.com/uc?id=1THyo7w35kWwPpBpUHv39zN2mG5hDscv8)

Boxplot depicting the relevance of session content to real-world industry scenarios.

### Session Organization by Resource Person

![image](https://drive.google.com/uc?id=1zEmXmiJky11bkAkJRpQRQKPFXH32PBhX)

Boxplot illustrating the overall organization of sessions by each resource person.

### Branch-wise Content Quality

![image](https://drive.google.com/uc?id=1jzlIP0_9up9NiQjweLvSWxUxkQKlCgIb)

Boxplot showing the content quality ratings across different branches.

## Machine Learning Model to study segmentation: K-means clustering

### Cluster Analysis

K-means clustering was employed to identify patterns within the student feedback, determining distinct groups based on their satisfaction and perception.

### Elbow Method

The Elbow Method is a technique used in machine learning for determining the optimal number of clusters in a dataset when performing clustering algorithms like K-means. It involves plotting the explained variation as a function of the number of clusters and observing the "elbow point," where the rate of decrease in variation sharply decreases. This point is considered the optimal number of clusters, as adding more clusters beyond this point does not significantly decrease the variation explained by the model.

![image](https://drive.google.com/uc?id=1uuk76Zw9KNEasvR8gjp9_AXj8uRD2Dny)

The Elbow Method graph used to determine the optimal number of clusters.

### K-means Clustering Visualization

![image](https://drive.google.com/uc?id=1TeXW08tC632Vbg5kZnNmzOFnrKUPkKOt)

Scatter plot visualizing the clusters based on effectiveness and expertise ratings.

### Visualizing the clustering using first two features

This visualization provides a graphical representation of the clusters formed by the K-means algorithm
![image](https://drive.google.com/uc?id=1DW0J6OekgQwsErVOms00OORRgZXmmoOJ)

## Conclusions

In-depth analysis of the feedback data yielded several actionable insights:

- The quality of content and delivery by Mrs. Akshara Sasidharan and Mrs. Veena A Kumar was particularly well-received.
- Certain sessions, while rated high in content quality, indicated a need for improvement in delivery effectiveness.
- The overall feedback was positive, with most students finding the course relevant and applicable to industry scenarios.

## Recommendations

Based on the insights, the following recommendations are made:

- Encourage peer learning sessions to maintain high content quality.
- Provide additional training for faculty on interactive delivery methods.
- Continue to align course content with industry requirements for maximum relevance.
