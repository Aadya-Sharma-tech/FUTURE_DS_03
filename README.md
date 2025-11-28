# FUTURE_DS_03
The College Event Feedback Analysis project focuses on extracting insights from student feedback collected after participating in various campus events such as workshops, seminars, and competitions. The dataset consists of numerical ratings and text-based comments gathered through a single Google Forms CSV file.

## Project Objectives 

**Analyze student ratings across multiple evaluation parameters such as:**

  - Clarity of explanations

  - Subject knowledge

  - Use of presentations

  - Doubt-solving ability

  - Course structuring

  - Assignment difficulty

  - Recommendation for the course/event

**Identify top-performing events based on overall satisfaction.**

**Perform text analysis (NLP) on student comments to extract:**

  - Common keywords

  - Frequent complaints

  - Sentiment scores

**Generate visual insights such as:**

  - Word clouds

  - Rating distributions

  - Correlation heatmaps

  - Event/department-wise comparisons

**Prepare a dashboard-ready dataset for Power BI visualization.**

## Workflow Summary
**1. Data Cleaning**

  - Removed redundant “Unnamed” index column

  - Standardized column names

  - Handled missing values

  - Verified data types and converted rating columns to numeric

**2. Exploratory Data Analysis (EDA)**

  - Identified rating patterns across students

  - Compared events and departments

  - Visualized distributions, boxplots, and heatmaps

  - Highlighted the top-rated and lowest-rated areas

**3. Text Feedback Processing**

  - Cleaned the comments column (removed NaN, converted to string)

  - Generated a word cloud to show frequently used terms

  - Extracted common complaint themes

  - Applied VADER Sentiment Analysis to measure positivity/negativity

**4. Insights Generated**

  - Which events received the highest and lowest overall ratings

  - Which departments conducted the most impactful events

  - Which areas (presentation use, structuring, doubts solving) need improvement

  - Sentiment trends from textual comments

  - Correlation relationships between rating parameters
