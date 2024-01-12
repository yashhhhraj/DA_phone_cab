# Cohort based Analysis and Insight Generation

This project consists of two datasets and relevant analysis.

## Dataset 1

Columns: <br>
&emsp;    userid: int<br>
&emsp;    Average Screen Time (mins): int	<br>
&emsp;    Average Spent on App (INR): int	<br>
&emsp;    Left Review: Bool	<br>
&emsp;    Ratings: int	<br>
&emsp;    New Password Request: int	<br>
&emsp;    Last Visited Minutes: int	<br>
&emsp;    Status: str<br>


Cohorts:<br>
&emsp;    1: Engagement Cohort<br>
&emsp;    2: Monetary Cohort<br>
&emsp;    3: Satisfaction Cohort<br>
&emsp;    4: Activity Cohort<br>
&emsp;    5: User Interaction Cohort<br>

Findings/Insights:<br>
&emsp;    1: Correlation Matrix ( incl Heatmap)<br>
&emsp;    2: Spending vs. Screen Time Scatter Plot<br>
&emsp;    3: Descriptive Statitics for High Engagement Cohort<br>
&emsp;    4: Descriptive Statistics for Low Engagement & High Ratings Cohort<br>
&emsp;    5: Distribution of ratings to understand the overall satisfaction levels<br>


## Dataset 2

Columns: <br>
&emsp;    START_DATE: datetime<br>
&emsp;    END_DATE: datetime	<br>
&emsp;    CATEGORY: str	<br>
&emsp;    START: str	<br>
&emsp;    STOP: str	<br>
&emsp;    MILES: int	<br>
&emsp;    PURPOSE: str<br>

Trends:<br>
&emsp;    1: Top 5 routes taken<br>
&emsp;    2: Top 5 trip purposes<br>
&emsp;    3: Miles vs Trip Duration and Purpose<br>

Action Points: Provided in the notebook along with trends.
