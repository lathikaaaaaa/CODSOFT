Data Visualization Projects

This repository contains three data visualization projects designed to analyze and present Twitter engagement metrics in Power BI. Each project incorporates specific criteria and interactivity features to provide meaningful insights.

---

Projects Overview

1. Proportional Clicks Pie Chart
Objective: Build a pie chart representing the proportion of total clicks (URL clicks, user profile clicks, and hashtag clicks) for tweets with more than 500 impressions.

Key Features:
- Displays the proportion of different types of clicks.
- Drill-down functionality to view specific types of clicks for individual tweets.

Use Case: This visualization helps analyze the distribution of clicks among different types of interactions for highly viewed tweets.

---

2. Clustered Bar Chart for Clicks by Tweet Category
Objective: Create a clustered bar chart that breaks down the sum of URL clicks, user profile clicks, and hashtag clicks by tweet category.

Key Features:
- Displays data for tweets with media, links, or hashtags.
- Only includes tweets that:
  - Have at least one of these interaction types.
  - Are posted during 3 PM to 5 PM IST.
  - Have an even-numbered tweet date.
  - Contain more than 40 words.
- Hides the visualization outside the specified time window.

Use Case: This visualization highlights the performance of tweets categorized by type while adhering to strict filters, ensuring focused analysis.

---

3. Dual-Axis Chart for Media Views and Engagements
Objective: Create a dual-axis chart showing media views and media engagements by the day of the week for the last quarter.

Key Features:
- Highlights days with significant spikes in media interactions.
- Includes tweets that:
  - Are posted during 3 PM to 5 PM IST.
  - Have an even number of impressions.
  - Have an odd-numbered tweet date.
  - Contain fewer than 30 words.
- Hides the visualization outside the specified time window.

Use Case: This chart provides insights into weekly trends in media interactions, helping identify high-performing days.

---

How to Use

1. Clone this repository:
   git clone https://github.com/your-username/repository-name.git
2. Navigate to the desired project folder and open the Power BI file (.pbix).
3. Review the specific criteria and filters applied to the visualizations.

---

Tools Used

- Power BI: For creating interactive dashboards and visualizations.
- DAX (Data Analysis Expressions): For implementing advanced calculations and filters.
