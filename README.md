# Reddit DataScience Case Study

## Overview
This project collects and analyzes the top 100 posts from the **DataScience subreddit** in 2024, along with their top 3 comments. The goal is to understand the concerns and discussions of data science practitioners and enthusiasts.

## Files
- `notebooks/jupyterFile_case_study_1.ipynb`: Jupyter Notebook containing the code for data collection and analysis.
- `data/sylvester_krampah_casestudy_1.csv`: CSV file containing the collected Reddit data.
- `presentations/sylvester_krampah_casestudy_1.pptx`: Presentation slides summarizing the project.

## Methods
- **Data Collection**: Used the PRAW library to fetch posts and comments from Reddit.
- **Filtering Criteria**: Only posts from 2024 with a score > 50 and titles longer than 5 words were considered.
- **Data Storage**: Saved the data in a CSV file with columns for date, post score, post title, body, and top 3 comments.

## Insights
- Identified common themes in the DataScience subreddit, such as career advice, industry trends, and challenges faced by data scientists.
- Example post: "Friendly reminder not to work too hard. You'll burn out before you know it."

## Business Use Case
### **Use Case: Improving Employee Retention in Data Science Teams**
#### Problem:
Many companies struggle with retaining data science talent due to burnout, lack of career growth opportunities, and misalignment between employee expectations and company goals.

#### Solution:
By analyzing discussions on the DataScience subreddit, companies can gain insights into the **key concerns** of data scientists and take proactive steps to address them. For example:
1. **Burnout Prevention**:
   - Insights from posts like "Friendly reminder not to work too hard. You'll burn out before you know it." highlight the importance of work-life balance.
   - **Actionable Step**: Implement policies like flexible working hours, mental health days, and workload management to reduce burnout.

2. **Career Growth**:
   - Many posts discuss the lack of clear career progression in data science roles.
   - **Actionable Step**: Create structured career paths, mentorship programs, and opportunities for skill development (e.g., certifications, conferences).

3. **Alignment with Industry Trends**:
   - Posts about emerging technologies (e.g., AI, machine learning) and tools (e.g., Python, TensorFlow) can help companies stay updated.
   - **Actionable Step**: Invest in training programs to upskill employees in trending technologies.

4. **Employee Engagement**:
   - Comments like "I lost my job three times in a row, so I think I'm done with data science" reveal frustration with job instability.
   - **Actionable Step**: Foster a supportive work environment, provide job security, and recognize employee contributions.

#### Business Impact:
- **Improved Retention**: Addressing employee concerns can reduce turnover rates, saving recruitment and training costs.
- **Increased Productivity**: Happier employees are more productive and innovative.
- **Competitive Advantage**: Staying aligned with industry trends ensures the company remains competitive in the data science field.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Reddit-DataScience-Case-Study.git
