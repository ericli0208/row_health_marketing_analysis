# Row Health Marketing Insights
## About Row Health
**Founded in 2016, Row Health is a medical insurance company serving thousands of customers throughout the United States**. **In 2019, they launched a new set of marketing campaign categories** spanning topics like wellness tips, the affordability of their plans, and preventative care. Their customers can sign up for 4 different plans - bronze, silver, gold, and platinum - each with different premiums and claim coverage rates. 

Now that they’ve hired a new data team and are strategizing their marketing budget for 2024, the company would like to build more understanding of the effectiveness of these campaign categories and how they relate to signups and subsequent patient claims. The budget is allocated to drive two primary objectives: 1) to increase the number of customer signups, and 2) to raise awareness of Row Health’s brand across the country.

## Data Structure
The dataset consisted of three tables, including information about campaigns, signups and user demographics, as well as claims filed by customers and related claim information.

![image](https://github.com/user-attachments/assets/473eb4fb-705b-49fd-b9a4-a40b6e654a84)

## Objectives
The goal of this analysis is to investigate the performance of marketing campaigns at Row Health in order to surface recommendations on marketing budget allocation across future campaign categories. **As a data analyst at Row Health, your focus is on building visualizations** to enable the marketing team to self-serve insights and regular-cadence reporting. 

### Analyst Steps
- **Requirements gathering:** Meet with the stakeholder to clarify metric definitions, dimensions, and timelines
- **Create a template:** Create a proof-of-concept dashboard to anchor the stakeholder on how the dashboard will look, and iterate before building the dashboard.
- **Iterate on dashboard:** Create a first draft of the dashboard and continue to iterate with stakeholder based on visualization and formatting preferences

## Metrics and Dimensions
After meeting with the Marketing team to clarify metric definitions, dimensions, and timelines, we've identified the following key metrics and dimensions:

### North Star Metrics
- **Signup Rate:** The percent of people who see a campaign and subsequently sign up for a Row Health plan.
- **Cost Per Signup:** The average dollars spent in order to acquire a signup from each campaign.
- **Click Through Rate:** The percent of people who see a campaign and click on the associated link. 
  
### Key Dimensions
- **Campaign Category**
- **Time**
- **Plan Type**
- **State**
- **Campaign Type**

## Insights Summary

### Signup Rate
- Across all campaign categories, Health For All campaigns had the best-performing signup rate (2.1%) and the second-highest number of signups (3.5K).
- In the Health For All campaign, the Health Awareness campaign type has the highest sign up rate across all other campaign types (3.72%).
- The campaign category with the highest number of signups - #HealthyLiving - had a relatively low signup rate at under 0.3%. 
- Sign up volumes rose tremendously across all campaigns at the start of 2020Q2, after which they dipped back down into normal levels, suggesting a peak in demand for medical insurance during the pandemic. 
- The silver plan was the most widely sought-after health plan with the highest signup rate (0.17%) and 14k signups out of the 16k total. The platinum plan performed the worst, with only 12 signups across 5 years. 

### Cost per Signup
- Across all campaign categories, Golden Years Security had the highest cost per signup ($176) as well as the lowest number of signups (23).
- #CoverageMatters performed the best, with the lowest cost per signup ($0.65) and over 3.5k signups overall.
- The covid-awareness campaign types for the Compare Health Coverage and #CoverageMatters campaigns had significantly higher customer acquisition costs (CACs) than average ($2.2k and $1.3k respectively).
- Within the two campaign categories with highest cost per signup, info-based campaign types (like offers and policy info) drove high costs per signup.

### Click Through Rate
- Across categories, Health For All, Benefit Updates, and Summer Wellness Tips performed 2-3 times better than the overall CTR average at 25%, 22%, and 18%, respectively.
- Within Health For All and Benefit Updates campaigns, the product promotion campaign type did not perform well (0% & 7%), but was the highest performer for Summer Wellness Tips (26%).
- Family Coverage Plan had over 1.1 million total impressions but no clicks, which requires further investigation to determine whether there is missing data or issues with the campaign. 

## Recommendations
- **Health for All**: Reallocate budget from Golden Years Security, which has high cost per acquisition, to Health for All campaigns. The second category outperforms across all key metrics, yet we have invested a relatively low amount ($20K) on them.
- **Health Awareness**: Within Health for All campaigns, focus on health awareness-type marketing, and less on product promotion-type campaigns, which had low signup rate and CTR.
- **COVID Campaigns**: Investigate the cause of abnormally high cost per signup for COVID-based campaigns, which had 2 signups that costed over $1K, compared to an average signup cost of $2.2. Consider removing these campaigns altogether.
- **#HealthyLiving**: Decrease investment in this campaign category, which has the highest spend ($46K) but mediocre signup rates compared to Health for All campaigns.

## Dashboard
Row Health's interactive dashboard can be found in Tableau Public [here](https://public.tableau.com/app/profile/ericli0208/viz/RowHealth_17335647652660/Dashboard1). This dashboard enables users to filter by plan, campaign type, and state, and focuses on trends and values in marketing metrics, signup metrics, and claim metrics.

![Dashboard 1](https://github.com/user-attachments/assets/6cc937fa-55f6-4a55-950e-531e5183dd6c)

