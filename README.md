# DS.v3.2.1.5

# **Mental Health Condition Prevalence Analysis**

## **Description:**
This project performs an exploratory data analysis (EDA) on the prevalence of various mental health conditions, including ADHD, Anxiety, Depression, and PTSD, in randomly selected samples. The dataset contains responses related to the impact of mental health on work productivity and its discussion with employers and coworkers. Using Python libraries like Pandas, Matplotlib, and SQLite, the project explores the distribution of these conditions and visualizes the prevalence rates along with their confidence intervals.

## **Position statement for this sprint project:**
In this project, I assume the role of a Data Scientist for a new app initiative aimed at supporting and improving the livelihood of individuals who have faced and struggled with mental health challenges in workplace environments. As the app is still in its early stages, my team lead has assigned me the task of identifying target users and evaluating whether this is the right direction for the app’s development.

Since the app is currently in the research phase, one of the key requirements from the development team is to keep expenses low as posible during the early stages. To achieve this, we are utilizing freely available data from old surveys in which one of our stakeholders participated while living in the U.S.

## **EDA Objectives**

* Analyze the Kaggle dataset: Examine its structure, completeness, and key trends.

* Assess sample size and demographics: Understand respondent distribution and sociodemographic characteristics.

* Identify potential biases: Check for demographic or methodological biases affecting data reliability.

* Report mental health prevalence: Calculate rates for at least three conditions with confidence intervals.

* Evaluate experience with mental health problems: Determine how many respondents have faced mental health issues.

* Explore any family mental health history: Assess the presence of mental health conditions in respondents’ families.

* Analyze workplace mental health communication: Identify openness and stigma in professional settings. Give statistical insight about posible hesitation in workplace. 

* Provide structured feedback: Summarize key insights and dataset limitations.

* Test the hypothesis: "There is a need for a mental health app that assists individuals facing mental health challenges."

* Suggest future improvements: Recommend refinements for further research and data collection.


## **Tools:**
SQLite: Programming language used to querying and extracting data from the database.
Python: Programming language used for analysis.
Jupyter Notebook: The environment where the EDA is conducted.
Pandas: For data manipulation and analysis.
Matplotlib: For creating data visualizations and plots.

## **Database:**

Mental_health dataset from Kaggle is used in this analysis contains responses from a survey on mental health in the workplace. It includes tables:

* Answers
* Questions
* Survey


## **Installation/Setup Instructions:**
1. Clone this repository or download the notebook file.
2. Install the required libraries (if needed): pip install pandas numpy sqlite3 matplotlib
3. Ensure the database file mental_health.sqlite is located in the correct directory.
4. Open terminal and run: jupyter notebook
5. Open the notebook EDA.ipynb and execute the cells to run the analysis.


## **Usage:**
The notebook is organized into several sections:

* Data Collection and Querying: The data is fetched using SQL queries from the SQLite database to retrieve user responses for mental health conditions.

* Prevalence Calculation: The prevalence rate of each mental health condition is calculated for each sample and represented as a percentage.

* Confidence Interval Calculation: Confidence intervals for each condition's prevalence rate are computed and visualized.

* Data Visualization: Prevalence rates for ADHD, Anxiety, Depression, and PTSD are visualized across three samples, with error bars representing the confidence intervals.

* Insights and Recommendations: The final analysis offers key insights into how mental health affects productivity and recommendations for workplace improvements.


## **Results of EDA:**

* The dataset is messy, with significant missing information and unclear survey targeting, requiring clarification.

* A negative correlation was found between the number of questions and enrollment, suggesting shorter surveys may improve engagement.

* The dataset is biased toward white males around 30 years old and heavily skewed toward the U.S., requiring more diverse representation and individual country analysis for global accuracy.

* One-third of participants have experienced mental health issues, and half have a family history of mental health problems, suggesting a focus on the tech industry and family subscriptions.

* The app should primarily target depression and anxiety, with secondary focus on ADHD, PTSD, OCD, and BPD to maximize engagement and support for broader mental health issues.

* The data is consistent across random subsets, confirming that conditions like depression and anxiety are not overrepresented due to sampling bias.

* 83% of respondents avoid questions about work productivity, suggesting anxiety around discussing mental health at work, which calls for sensitive app design and further research into workplace trends.


## **Suggestions for Further Improvement:**

* Reach out to the survey creators for clarification on the dataset structure, coded responses, and survey targeting to gain better insights.

* Review coded responses and explore additional survey questions to uncover missed patterns and provide more context for the analysis.

* If possible, explore other mental health datasets to expand the scope and improve the accuracy of the analysis with more structured numerical data.

* With more data and time, apply advanced statistical methods like predictive modeling and hypothesis testing to gain deeper insights into mental health trends and user behavior.

* Conduct targeted surveys in the tech industry to gather real-time data and address gaps in the current dataset, provided the budget allows.