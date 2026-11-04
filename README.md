# stack-overflow-developer-survey-analysis

Exploratory analysis of the Stack Overflow Developer Survey to find patterns in developer salaries, Python popularity and remote work.

**Tools:** Python (pandas), Jupyter Notebook
**Dataset:** 49,191 respondents, 172 columns (`survey_results_public.csv`, `survey_results_schema.csv`).

## Key Tasks
- Analyzed missing values across 126 survey questions
- Calculated central tendency measures for work experience
- Measured the share of remote workers and Python users
- Compared Python developer salaries by country
- Explored Python popularity across age groups
- Identified top industries among high-paid remote specialists

## Key Findings
- **37.54%** of respondents use Python, most often developers aged 18-24 (**40%**)
- **10,931** respondents work remotely
- High-paid remote specialists (above the 75th percentile, **$120,596**) work mainly in software development, fintech and healthcare
- Median work experience is **10 years**, while the mean is **13.4**, so very experienced developers pull the average up
- No respondent answered all 126 questions, so missing values had to be handled question by question

## Limitations
- Some countries at the top of the salary ranking have only one or two respondents, so their figures are not representative
- The highest reported salaries (up to $50M per year) are most likely input errors and should be filtered in further analysis
