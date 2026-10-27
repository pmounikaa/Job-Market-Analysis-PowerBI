# Data Science Job Market Analysis (Power BI)

An analysis of 742 Data Science job postings, presented as three interactive Power BI dashboards. The project shows where the jobs are, what they pay, which companies and industries are hiring, and which skills employers ask for, with suggestions a hiring company could act on.

## Tasks and Findings

| # | Task | Finding |
|---|---|---|
| 1 | Get the data | Dataset of 742 job postings and 42 columns loaded into Power BI |
| 2 | States with the most jobs | New York has the most postings (59), followed by Illinois and Massachusetts |
| 3 | Average minimum and maximum salaries by state | Salaries vary by state, but the differences are small |
| 4 | Average salary by state | Georgia has the highest average salary, not New York |
| 5 | Top 5 industries with the most Data Science postings | Media, Software, Financial Services, Consulting, Insurance (IT Services ties for 5th with 74 postings) |
| 6 | Companies with the most job openings | Adobe has the most, followed by IBM and Uber |
| 7 | Job titles with the most jobs | Senior Machine Learning Engineer, then Senior Data Scientist, BI Analyst and BI Developer |
| 8 | Salary of the most common job titles | Senior Machine Learning Engineer, Senior Data Scientist and Analytics Manager are among the highest paid |
| 9 | Skills required for each job title | Python is the most requested skill; requirements change by job title |
| 10 | Relation between average salary and education | Average salary ranges from about $82K to $103K across education groups |
| 11 | Insights from all features | See Key Insights below and the full report |
| 12 | Visualise in Power BI and suggest to the company | Three dashboards and a set of recommendations, shown below |

## Dashboards

### 1. Job Market Overview
Job postings by state, industry, company and job title.

![Job Market Overview](Dashboard%201%20-%20Job%20Market%20Overview.png)

### 2. Salary Analysis
Average salary by state (with a map), job title and education level, plus average minimum and maximum salaries by state.

![Salary Analysis](Dashboard%202%20-%20Salary%20Analysis.png)

### 3. Skills Analysis
How many times each skill is required for each job title.

![Skills Analysis](Dashboard%203%20-%20Skills%20Analysis.png)

Each dashboard has slicers for industry, location, job title, company and degree, so the numbers can be viewed for a chosen group.

## Key Insights

- New York has the most postings, but Georgia has the highest average salary, so the state with the most jobs is not the one that pays the most.
- Data Science roles are available across several industries, with Software and Media among the leaders.
- A few companies, led by Adobe, IBM and Uber, have the most openings.
- Senior Machine Learning Engineer is the most common job title and is also among the highest paid.
- The overall average salary is about $98.4K, and it differs by state, job title and education level.
- Python is the most requested skill, and the skills employers ask for change by job title.

## Recommendations

- Focus recruitment on locations with consistently higher job demand.
- Prioritise hiring for frequently posted roles such as Senior Machine Learning Engineer and Senior Data Scientist.
- Set salary offers by job title, seniority, location and market demand, not by one average figure.
- Offer role-specific training to cover skill gaps, and review skill requirements and salary ranges regularly.

## Dataset

- 742 job postings and 42 columns
- Fields include Job Title, Company, Location, Industry, Degree, Lower Salary, Upper Salary and Average Salary (in thousands of USD)
- Skills are stored in a separate table linked to the main table, with a Skills column and a Required column

## Approach

1. Loaded the data into Power BI and linked the skills table to the main jobs table.
2. Wrote DAX measures for the dashboard cards: Top State, Top Company, Most Common Job Title, Highest Average Salary State, Highest Average Salary Job Title and Most Requested Skill.
3. Built the charts, salary map, skills table and slicers.
4. Wrote up the findings and recommendations in a report and a presentation.

## Limitations

- Some postings have education listed as "Not Specified" or blank, so the education comparison is only a rough guide.
- State averages are based on the postings available for each state, so states with fewer postings may not be representative.
- This is a snapshot of one dataset, not a full picture of the job market.

## Files in This Repository

| File | Description |
|---|---|
| `Job Market Analysis Report.pdf` | Full write-up with insights and recommendations |
| `Job Market Analysis PPT.pptx` | Presentation version |
| `Dashboard 1, 2, 3 (.png)` | Dashboard screenshots |

## Tools

Microsoft Power BI, DAX
