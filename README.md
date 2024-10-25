# 🎬 Netflix Analytics: A Visual Breakdown of Ratings, Genres, and Global Reach 🍿

## Overview 📝
This project is a dynamic and interactive **Power BI dashboard** designed to analyze Netflix's **Movies and TV Shows** data. The goal is to provide insights into Netflix’s content across various dimensions, such as **ratings**, **genres**, **votes**, and **geographical distribution**. The dashboard allows users to explore Netflix's vast content library with visually appealing charts and interactivity.
### Dashboard Preview:
![Dashboard](https://github.com/KeshavaYada/Netflix-Dashboard/blob/main/Bubble%20chart.png)

## Features 🔥

1. **Dynamic Filtering Using Cards** 🎥📺
   - The dashboard includes two **cards** (Movies and TV Shows) that filter the entire dashboard when clicked. This helps users break down the analysis for movies and TV shows separately, providing a clear view of content across each category.

2. **Waterfall Chart for Rating Distribution** 📊
   - A **waterfall chart** displays the **number of titles** across different **rating groups** (e.g., 9+, 8-9, etc.), showing the distribution of content by rating. This visual dynamically adjusts based on whether Movies or TV Shows are selected, making it easy to see rating patterns.

3. **Title Information Table** 📝
   - A detailed **table** presents important information for each Netflix title:
     - **Title Name**
     - **Image** (poster or thumbnail)
     - **Average Rating**
     - **Votes**
   - The table allows for easy sorting and exploration, offering detailed insights into individual Netflix titles.

4. **Geographical Distribution (Bubble Map)** 🌍
   - A **bubble map** shows the global distribution of Netflix content, with the **size of the bubble** representing metrics like:
     - **Average Rating**
     - **Number of Titles**
     - **Total Votes**
     - **Votes per Title**
   - Users can toggle between these metrics, enabling a detailed view of how Netflix content is distributed and rated across various countries.

5. **Stacked Bar Chart for Genres** 🎭
   - The **stacked bar chart** visualizes the **number of titles per genre** alongside the **average rating** for each genre, providing insights into the popularity and performance of each genre on Netflix.

6. **Country-wise Detailed List** 🌍
   - A **country list table** presents:
     - **Number of Titles**
     - **Average Rating**
     - **Total Votes**
     - **Votes per Title**
   - This detailed breakdown offers a global perspective on how Netflix content is spread across different countries and how it performs in terms of ratings and votes.

7. **KPI Indicators for Key Stats** 📈
   - **KPI cards** at the top of the dashboard highlight key metrics:
     - **Total Number of Titles** (Movies and TV Shows).
     - **Total Votes**.
     - **Average Ratings**.
   - These KPIs provide a quick summary of the most important metrics across the dataset.

## Advanced Features 🚀

- **Dynamic Interactions**: The visuals on the dashboard are all interconnected. Selecting any filter or metric updates the entire dashboard to reflect the filtered data, making the dashboard highly interactive.
  
- **Toggleable Metrics**: The **bubble map** offers users the ability to toggle between different metrics (e.g., number of titles, votes, average rating, and votes per title) for a comprehensive analysis.

- **Netflix-Branded Aesthetic**: The dashboard uses a dark theme with **red accents** to align with Netflix’s visual identity, creating a branded and visually appealing experience.
- **Conditional Color Grading with DAX** 🎨:
   - I implemented **color grading** using **DAX** expressions to dynamically change the **font color** and **background color** based on the **average rating** of each title.
   - **High ratings** are shown with **intense red colors**, while lower ratings are represented with lighter shades. This gives an immediate visual cue of the content's quality.
   - The use of **conditional formatting** ensures that users can quickly spot highly rated content at a glance by the **color intensity** of the background and text.

## Insights 💡

1. **Popular Genres**:
   - Genres like **Comedy** and **Action** have the highest average ratings and the most titles. This suggests that Netflix viewers prefer these genres for both quantity and quality content.

2. **Country Insights**:
   - The **United States** and **United Kingdom** have the most Netflix titles. However, countries like **South Korea** and **Japan** stand out for high average ratings, indicating that while they have fewer titles, they produce high-quality content.

3. **Rating Distribution**:
   - The **waterfall chart** highlights that most Netflix titles fall in the **6-8 rating range**, with fewer titles in the 9+ or below 5 categories.

## Project Outcomes 💡

- The dashboard provides Netflix users, analysts, and content creators with valuable insights into Netflix’s global content library.
- It helps identify **content trends**, **geographical insights**, and **popular genres**, aiding in better content strategies and decision-making.

## Files 📁

- **Netflix-Dashboard.pbix**: The Power BI file containing the dashboard.
- **Dataset - Netflix-Listings.xlsx**: The dataset used for the analysis.
- **Image.png**: A screenshot of the final dashboard, providing a visual representation of the project.

## How to Use the Dashboard 🖥️

1. **Download the Files**: Clone or download the repository and open the **Netflix-Dashboard.pbix** file in **Power BI Desktop**.
2. **Interactivity**: Use the filters and cards on the dashboard to interact with the visuals. Explore different genres, ratings, and countries by selecting elements on the dashboard.
3. **Customize**: The dashboard is fully customizable. You can upload new datasets or change visuals based on your preferences.

## Future Enhancements 🚀

1. **Advanced Filters**: Adding more filters for deeper analysis, such as **year of release**, **director**, or **cast**.
2. **Custom Tooltips**: Enhancing the dashboard with detailed tooltips for each title, showing more information on hover.
3. **Integration with External APIs**: Adding real-time data integration with platforms like **IMDb** to show updated ratings and user reviews.



---

### Example of Bubble Map:
![Bubble Map](https://github.com/KeshavaYada/Netflix-Dashboard/blob/main/Bubble%20chart.png)

---

## Conclusion 🏁

This Power BI dashboard offers a comprehensive look into Netflix’s content library, providing key insights into genres, ratings, and geographical distributions. It is a valuable tool for both viewers and Netflix stakeholders looking to gain data-driven insights into the platform’s content performance.

