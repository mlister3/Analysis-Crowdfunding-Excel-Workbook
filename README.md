# Croudfunding Project Sample Analysis in Excel

> using Excel to visualize crowdfunding data and analyze success rates in different catagories and years.

## Step 1

> New columns and initial visualizations.

| Sub Step | Description |
|--------------|---------------|
| Outcome | use conditional formatting to visualize outcome of a project. ie success, fail, cancelled, etc |
| Percent Funded | create a column to show a percentage ratio of pledged to goal. Visualize rate of success though conditional formatting |
| Average Donation | create a column to calculate average donation per backer |
| Category and Sub-Category | use split function to make two columns; one with category only, one with sub-category only |

## Step 2

> Pivot tables and stats

| Sub Step | Description |
|--------------|---------------|
| Category | create pivot table that counted outcomes per category |
| Sub-category | create pivot table that counted outcomes per sub-category with parent category and country filters |
| Timelines | convert Unix timestamps of launch and deadline into normal dates. stored dates in new columns |
| Launch date outcomes | create pivot table that counts outcome based on date created with parent category and years filters |

*see CrowdfundingReport.md for analysis and questions about query.*

## Step 3

> Outcomes based on goals

| Sub Step | Description |
|--------------|---------------|
| Columns | create * `Goal`  * `Number Successful`  * `Number Failed`  * `Number Canceled`  * `Total Projects`  * `Percentage Successful`  * `Percentage Failed`  * `Percentage Canceled` columns |
| Organization | create rows to categorize project samples based on goals set in ~5000 dollar increments |
| Data Population and Analysis | using 'COUNTIFS()' formula to populate columns with sample data. create line chart to visualize relationship |
| Evaluation of statistics | calculate   * The mean number of backers  * The median number of backers  * The minimum number of backers  * The maximum number of backers  * The variance of the number of backers  * The standard deviation of the number of backers * to determine which statistic most meaningfully summarizes sample |
| Varience | evaluate differences in varience between outcomes and infer a relationship |

*see CrowdfundingReport.md for analysis and questions about query.*

## Rubric

[Unit 1 Rubric - Excel Homework: Charting Crowdfunding](https://docs.google.com/document/d/1gIVky_5CZi-b4w07RLBYZyXgbbhMRemvpcT1V6EGkvw/edit?usp=sharing)

## Employer-Ready Criteria

Students who are marked as employer ready gain access to our employer referral program, additional workshops, and other resources. Work with your Career Director to become employer ready. At a minimum, you must have:

- A clear, concise, and compelling resume. Submit via your learning platform for review.
- A polished GitHub profile:
  - 3 to 6 pinned repositories ([instructions here](https://docs.github.com/en/enterprise/2.13/user/articles/pinning-items-to-your-profile))
  - Professional titles, i.e. not "Homework #1"
  - Thorough README.md files for each repository
  - Clean code

## References

Dataset created by Trilogy Education Services, LLC.

- - -

© 2021 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
