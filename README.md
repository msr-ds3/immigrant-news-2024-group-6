# Replication of "Anti-Immigrant Rhetoric and ICE Reporting Interest: Evidence from a Large-Scale Study of Web Search Data"

Replications and extensions of [this article](https://www.cambridge.org/core/journals/british-journal-of-political-science/article/abs/antiimmigrant-rhetoric-and-ice-reporting-interest-evidence-from-a-largescale-study-of-web-search-data/AF982680AEC49AE65CACFD73352A44AD) on the relationship between media cues and public interest in reporting suspected unauthorized immigrants to Immigration and Customs Enforcement (ICE). The study uses Google Trends and Bing search data, combined with automated content analysis of cable news transcripts.

Replicated figures 2-4, and tables 3-4 using both 2024 Google Trends data and the original data used in the research paper.

## Replication
1. Install `tidyverse`, `dbplyr`, and `lubridate` R libraries
2. Run the code from the `final_report.Rmd` R Markdown file
3. Otherwise, use [this link](https://htmlpreview.github.io/?https://github.com/msr-ds3/immigrant-news-2024-group-6/blob/main/final_report.html) to view the results of the replication without running the code

## Data from the paper

The data to entirely reproduce the results paper is available in this repository. For convenience for the user, tidy data for data scientists and faculty is available in the `data` directory. For instance, for the data scientists:

- `google_trend_search.csv` contains google search data for reporting, crime, and welfare topics from 2024
- `google_trends_crime.csv` contains the original google search data for crime used in the paper
- `google_trends_report.csv` contains the original google search data for reporting used in the paper
- `google_trends_welfare.csv` contains the original google search data for welfare used in the paper
- `gt_report_daily.csv` contains daily google search data for reporting used for Table 4
- `gtopic_model_lite.Rdata` contains the topic model used for figures 3-4 and table 4