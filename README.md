# Titanic-Data-Analysis-and-Prediction

#Table of Content
- [Project Overview](#Overview)
- [Project Structrue](#Project-Structure)
- [Visualizations](#Visualization)
- [Predictions](#Predictions)
- [Reccomendation](#reccomendations)

## Overview

The Titanic Data Analysis project aims to uncover insights into the demographics and characteristics of passengers aboard the Titanic. The analysis covers aspects such as survival rates, passenger classes, gender distribution, and also predicted the survival rate of all passengers on board.

## Data Source

titanic data: the primary data used for this analysis and prediction is the "titanic.csv" file, containing details information on both survival and non-survival passengers

## Tools

* Python - For data cleaning, analysis and prediction
* Power BI - preparing dashboard for report

## Project Structure

- **Jupyter Notebooks**: The project is organized into Jupyter notebooks for a clear and reproducible analysis.
- **Data Cleaning**: The dataset underwent thorough cleaning to handle missing values and ensure data quality.
- **Exploratory Data Analysis (EDA)**: EDA techniques were applied to understand the distribution of variables and identify patterns.
- **Visualization**: Matplotlib and Seaborn were utilized to create visualizations that enhance the interpretation of the data.
- **Statistical Analysis**: Basic statistical analyses were performed to derive meaningful insights.

## Data Cleaning
In the initial data preparation phase, I performed the following functios
1. Data loading and inspections
2. Handling missing values
3. Data cleaning and formatting

## EDA - Exploratory Data Analysis
EDA incolve exploring survival data to answer key questions:
1. What is the total surviving rate to death rate
2. what is the surviving rate to gender
3. Does Pclass affected the survival rate?
4. Does their geographical area affect the survivin rate

## Visualization

 Matplotlib and Seaborn were utilized to create visualizations that enhance the interpretation of the data.

* I then included dashboard from Power BI, below is the dashboard created
[TITANIC DASHBOARD.pdf](https://github.com/JohnEvansOkyere/Titanic-Data-Analysis/files/13792224/TITANIC.DASHBOARD.pdf)


## Predictions

Create and train a logistic regression model on the training data
Use the trained model to make predictions on the test data
Assess the model's performance using relevant metrics like accuracy, confusion matrix, and classification report.

## Key Findings

1. ### Survival vs. Deceased:

The majority of passengers did not survive; the deceased rate is higher than the survival rate.

2. ### Gender-Based Survival:

- Female passengers have a higher survival rate, while the deceased rate is higher among males.
- Suggests a potential trend of prioritizing saving females first during the disaster.

3. ### Class-Based Survival:

- First-class passengers had the highest survival rate.
- Third-class passengers had the highest deceased rate.
- Implies that socio-economic status influenced survival, with the rich having a higher chance of survival.
4. ### Age Insights:

The age range varies from 0.42 to 80.0 years.

5. ### Impact of Family Relations:

Passengers without a spouse or sibling had both higher survival and deceased rates.

6. ### Family Composition:

Passengers with no spouse or sibling, and those with parents alone or children alone, had the highest survival and deceased rates.
7. ### Embarkation Point Influence:

Passengers embarking from Southampton (S) had a higher survival rate than those from Cherbourg (C) and Queenstown (Q).
Suggests a correlation between embarkation point, passenger class, and survival rates.

## Reccomendation

1. ### Gender-Aware Evacuation Protocols:

Consider implementing gender-aware evacuation protocols, acknowledging the observed higher survival rate among females. Training and awareness programs can emphasize the importance of prioritizing vulnerable groups during emergency situations.

2. ### Enhanced Safety Measures for Males:

Recognize the higher deceased rate among males and consider enhancing safety measures, evacuation strategies, or emergency response plans that specifically address the needs and challenges faced by male passengers.

3. ### Age-Sensitive Evacuation Plans:

Develop age-sensitive evacuation plans, recognizing the diverse age range of passengers. Consider special assistance or provisions for the elderly and young passengers during emergency situations.

4. ### Family-Centric Support Systems:

Implement family-centric support systems during emergencies. Recognizing the impact of family relations on survival rates, providing support for passengers without a spouse or sibling, and those with specific family compositions can enhance overall safety.

5. ### Education and Training Programs:

Offer education and training programs on emergency preparedness and survival strategies. Empower passengers with knowledge on how to respond to emergencies, regardless of socio-economic status or demographic factors.

6. ### Embarkation Point Awareness:

Increase awareness regarding survival rate variations based on embarkation points. Consider providing additional safety resources or information to passengers embarking from locations with historically lower survival rates.

7. ### Public Awareness Campaigns:

Conduct public awareness campaigns on the importance of safety and preparedness during travel. Encourage passengers to be proactive in familiarizing themselves with emergency procedures and understanding safety measures on board.

8. ### Collaboration with Industry Experts:

Collaborate with industry experts and organizations to continuously refine safety standards and emergency response protocols. Engage in discussions and partnerships that contribute to the overall improvement of safety in the transportation sector.

## Dependencies

- Python 3
- Jupyter Notebooks
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Acknowledgments
- ChatGPT
- LinkedIN


## Contact

For questions or collaboration opportunities, feel free to reach out:

- 📧 Email: [okyerevansjohn@gmail.com)
- 
- 💼 LinkedIn: https://www.linkedin.com/feed/

Happy analyzing! 🚢📊
