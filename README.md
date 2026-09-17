# 📊 Instagram Social Media Analytics Dashboard

## About the Project

The **Instagram Social Media Analytics Dashboard** is a Power BI project created to analyze Instagram post performance and understand audience engagement, reach, impressions, content performance, and follower growth.

## Why We Chose This Project

Social media is an important digital marketing channel, but posting content alone does not show whether a campaign is successful. Data analytics can help identify which content receives more engagement, how far posts reach the audience, and how performance changes over time.

We chose this project to apply data analytics to a **real-world digital marketing problem** and demonstrate the complete workflow of:

**Data Cleaning → Data Analysis → KPI Calculation → Visualization → Business Insights**

## Dataset

The project uses an Instagram Analytics dataset containing approximately **30,000 post records**.

The dataset includes information such as:

- Post ID
- Account Type
- Follower Count
- Media Type
- Content Category
- Traffic Source
- Post Date and Time
- Likes
- Comments
- Shares
- Saves
- Reach
- Impressions
- Engagement Rate
- Followers Gained
- Hashtag Count
- Caption Length
- Performance Category

The dataset was cleaned and prepared using **Python, Pandas, and NumPy** before being used in Power BI.

## Dashboard

The Power BI dashboard contains four main KPI cards:

### Total Posts
Shows the total number of Instagram posts available in the selected data.

### Total Reach
Shows the total number of users reached by the posts.

### Total Impressions
Shows the total number of times the posts were displayed.

### Engagement Rate
Shows the overall engagement generated compared with total reach.

## Dashboard Charts

### 1. Engagement by Media Type

This chart compares total engagement across different media types such as images, reels, and carousels.

It helps identify which type of content generates more audience interaction.

### 2. Engagement by Content Category

This chart compares engagement across different content categories such as Fashion, Food, Technology, Music, and others.

It helps identify which content categories receive higher engagement.

### 3. Reach & Impressions Over Time

This chart shows how **reach and impressions change over time**.

It helps identify periods of higher or lower audience exposure and content visibility.

### 4. Reach by Traffic Source

This chart shows how total reach is distributed across different traffic sources.

It helps understand where audience exposure is coming from.

## Interactive Filters

The dashboard includes filters for:

- Media Type
- Content Category
- Traffic Source
- Post Date

These filters allow users to interact with the dashboard and analyze specific parts of the dataset.

## Tools Used

- **Python**
- **Pandas**
- **NumPy**
- **Power BI**
- **DAX**
- **Excel**

## Project Workflow

```text
Instagram Dataset
       ↓
Data Cleaning using Python & Pandas
       ↓
Feature Engineering
       ↓
KPI Calculation
       ↓
Power BI
       ↓
Interactive Dashboard
       ↓
Business Insights
```
## Note

The dataset does not contain a Clicks column, so Click-Through Rate (CTR) was not calculated. The dashboard focuses only on metrics available in the dataset.

## Conclusion

This project demonstrates how social media data can be transformed into an interactive business intelligence dashboard. It provides a clear view of engagement, reach, impressions, content performance, traffic sources, and audience growth to support data-driven digital marketing analysis.
