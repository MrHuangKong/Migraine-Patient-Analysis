# Capital University - Data Science Individual Study Capstone Project
### Nicolas Huang
### Dr. Leigh Johnson
### 1/24/2023 - 4/30/2023

## Senior Study Capstone Project Details

### Learning Outcomes
- Demonstrate the ability to program in a higher-level language (write functions, utilize control flow in Python or R).
- Demonstrate algorithmic thinking and problem-solving skills.
- Acquire, manage, and manipulate data, including joining data from different sources and formats, restructuring data for analysis.
- Develop skills to build and assess data-based models.
- Identify patterns in data, draw inferences and conclusions, and effectively communicate insights.

### Project Overview
This project explores the **impact of the neurologic disease migraine** on patients, analyzing anonymized health survey data obtained from **Missouri University**, funded by the **National Headache Foundation**. The data is used under the guidelines provided in the associated research paper, available via [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S235234092201006X).

The analysis focuses on **Exploratory Data Analysis (EDA)**, which provided insights into the demographic characteristics of migraine sufferers, common comorbid conditions, and their satisfaction with current treatments.

### Key Findings
- **Prevalence of Migraine:** Migraine is a **neurological disorder** affecting roughly 12% of the U.S. population, yet remains misunderstood by both the public and healthcare providers.
- **Comorbid Conditions:** Many sufferers report conditions such as **hemiplegia, depression, and syncope** alongside their migraines.
- **Impact on Quality of Life:** Participants reported that migraines have a significant impact on their daily activities and overall quality of life.
- **Demographic Disparities:** A chi-square goodness-of-fit test revealed insignificant differences between the sample and U.S. population. However, **females were disproportionately affected**, with approximately **83.92%** of participants identifying as female.
- **Treatment Satisfaction:** Participants expressed neutral feelings about their current treatments, indicating room for improvement in migraine management.
  
These findings emphasize the complexity of migraines as a **multifaceted disorder** and highlight the need for increased awareness and better treatment strategies.

### Data Analysis Methods
1. **Data Cleaning & Preparation:**
   - Removed unnecessary columns and handled missing values.
   - Separated data into individual components such as demographics, medications, and comorbid conditions.

2. **Exploratory Data Analysis (EDA):**
   - Visualized demographic data using bar plots and pie charts to highlight race, sex, and age distributions.
   - Explored the relationship between migraine severity and comorbid conditions.
   - Analyzed medication usage and effectiveness, including **Triptans**, **NSAIDs**, and **Beta-Blockers**.

3. **Statistical Analysis:**
   - Performed **Chi-Square Goodness of Fit** tests to compare the sample's racial demographic against U.S. population data from the 2018 census.
   - The test failed to reject the null hypothesis, indicating the sample is representative of the broader population.

### Tools & Technologies
- **Python:** Data manipulation, statistical analysis, and visualization
- **Pandas:** Data management and cleaning
- **Matplotlib:** Data visualization (bar charts, pie charts)
- **Scipy & Statistic Models:** Statistical analysis (chi-square tests)
- **GNU General Public License v3.0:** Licensing framework for this project

### Project Structure
- **Data Cleaning:** Code to clean and preprocess survey data.
- **EDA:** Visualizations of demographic, comorbid conditions, and treatment effectiveness.
- **Statistical Analysis:** Chi-square tests and comparisons to U.S. population data.
- **Visualizations & Conclusions:** Key findings and visual representations of the migraine dataset.

### Project Presentation
This project was presented at the **Capital University Science Symposium** as a research poster titled _Exploring the Impact of the Neurologic Disease Migraine and Treatment Efficacy_. The presentation highlighted the demographic analysis, comorbid conditions, and the significant impact migraines have on individuals' quality of life.

### Want to Clone this Repository? 
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/capstone-migraine-analysis.git
