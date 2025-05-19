

# PROJECT H1 HEALTH INSURANCE

* H1 Health insurance is a comprehensive data analysis tool designed to streamline data exploration, analysis, and visualisation. The tool supports multiple data formats and provides an intuitive interface for novice and expert data scientists.
* This project analyses healthcare insurance data to uncover how personal attributes and geographic factors impact insurance costs. By developing predictive models, the goal is to estimate healthcare expenses and generate data-driven insights to support more accurate forecasting of insurance charges.


# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
The dataset provides information on personal characteristics (including age, gender, BMI, family size, and smoking status) and geographic factors, examining their effect on medical insurance charges. It serves as a resource for analysing the impact of these variables on insurance costs and for building predictive tools to estimate healthcare expenses.


## Business Requirements
Deliver insights and predictive reports to estimate healthcare insurance costs based on individual and geographic characteristics.


## Hypothesis and how to validate?
Descriptive Statistics: Show fundamental statistics such as average insurance charges by age, gender, and region.

Correlation Analysis: Visualise the strength and direction of relationships between various attributes and insurance charges.

Predictive Analysis: Build and display models to forecast insurance expenses.

Geographic Analysis: Illustrate how regional differences impact insurance costs.


## Project Plan
* Set up the project dashboard and tasks 
* Extract: Load data from the provided CSV file.
* Transform: Clean the data, handle missing values, encode categorical variables, and create new features such as body mass index (BMI) categories.
* Load: Store the transformed data in a format suitable for analysis (e.g., a cleaned DataFrame).
* Visualise data as per business requirements.
* Create project documentation as required.
* Proofread and review all elements of the projects before loading/sharing them.
* Push the final version within the given timeframe.

## The rationale to map the business requirements to the Data Visualisations
* Descriptive statistics like averages, medians, and standard deviations can reveal important insights into how different groups (age, gender, region) are impacted by insurance charges. Visualisations like bar charts can show average charges across different age groups, genders, or regions.
* Correlation Analysis: Visualise Correlations between different attributes and Insurance Charges: Visualisations such as heatmaps can display correlation matrices, making it easy to spot strong relationships. Correlation analysis helps identify which variables have the strongest positive or negative relationships with insurance charges.
* Predictive Analysis: Develop and Visualise Predictive Reports for Estimating Insurance Costs. Predictive models such as regression or machine learning algorithms can be used to estimate insurance costs based on multiple features. Visualisations like scatter plots with regression lines can show predicted versus actual insurance charges.


## Analysis techniques used
* Data analysis methods used: Descriptive analysis, Correlation analysis, Predictive analysis and Geographical analysis.
* Structure of the data analysis techniques. 
    *Data Exploration: Understand the dataset, detect issues early
    *Data Cleaning & Preprocessing: Ensure reliable, accurate analysis and modelling
    *Descriptive Statistics: Identify basic patterns and segment-wise trends
    *Correlation Analysis: Discover key influencers of insurance charges
    *Predictive Modelling: Estimate insurance costs and enable forecasting
    *Geographic Analysis: Explore regional impact on costs and support targeted decision-making

* The data is very limited, and in a real-life scenario, I will try to acquire more information, such as: current health condition and medical history, other lifestyle attributes than smoking, such as: drinking, drugs, active/sedentary, etc. Lack of Time-series Data: The dataset does not include time-series information (e.g., insurance charges over time), limiting our ability to perform longitudinal analyses or trend forecasting.
    * Approach: The analysis is adapted to fit the scope of the dataset, focusing on relationships between personal attributes and insurance charges, and using appropriate visualisations to provide actionable insights. Instead of time-series data, I focused on analysing the relationships between features (such as BMI, age, and smoking habits) and insurance charges at a single point in time. These steps ensured that the business requirements were still met, despite the data limitations. For predictive modelling, I built models based on personal and geographic features, without incorporating time-dependent changes.
* Generative AI tools like CoPilot and ChatGPT have been used for code smart suggestions/error correction as well as optimising and text rephrasing and formatting for documentation.   

## Ethical considerations
* The data has already been anonymised and there are no privacy risks to be considered. As the BMI is the only health-related attribute, and is limited to yes or no on smoking habits, the results can be potentially biased.
* There are no legal challenges in processing the data. A disclaimer regarding limited data and potential bias, it is still recommended.


## Unfixed Bugs
* Syntax is the most common error, and generative AI is quite helpful in VS Code, generating suggestions and predictive commands.

## Development Roadmap
* Being the first project, the major challenge is to deliver all KPIs timely, and as required.


## Main Data Analysis Libraries
* Pandas- Purpose: Data loading, cleaning, and manipulation.
* NumPy- Purpose: Numerical operations and array handling.
* Matplotlib & Seaborn, Plotly- Purpose: Data visualisation to explore relationships between variables.


## Credits 

* Code Institute https://learn.codeinstitute.net/ and GitHub: https://github.com/Code-Institute-Solutions/da-README-template, https://github.com/Code-Institute-Org/data-analytics-template
* CoPilot for code correction and predictive suggestions
* ChatGPT for text rephrasing and visualisation optimisation: egz but not limited to: compiling sets of multiple charts.

### Content 

- The data set is from https://www.kaggle.com/datasets/willianoliveiragibin/healthcare-insurance 
- Instructions and project templates are from: Code Institute https://learn.codeinstitute.net/ and GitHub: https://github.com/Code-Institute-Solutions/da-README-template, https://github.com/Code-Institute-Org/data-analytics-template
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)


## Acknowledgements (optional)
* Really appreciated the support and guidance from my tutors, coordinators and colleagues. Thank you!
