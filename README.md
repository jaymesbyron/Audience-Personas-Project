<h1>Audience Personas - Data Analysis Capstone</h1>

This analysis is part of a larger group capstone project using a mock telecommunication company's campaign reporting data. The project's goal was to:

1. Analyze, clean, and manipulate the data
2. Identify top performing audiences, creative messaging, locations, and inventory to develop budget allocation strategies for stakeholders.
3. Produce marketing personas based on analysis.

My assigned role on the project was the Audience Analyst. I manipulated the data with Google Sheets and Tableau to create 3 personas based on my findings, using KPI's such as CPA, CVR, and CPC to inform their creation. 

Alt-text is available for each image in this repository.



<h2>Ask</h2>

- Who are the people represented in this dataset?
- What do these people do for a living? Where do they live? What are their goals and aspirations?
- Where should stakeholders allocate the budget to best market to these groups?



<h2>Prepare</h2>

- The original campaign reporting dataset can be found [here](https://docs.google.com/spreadsheets/d/1-FgnAIrco1xcsaOtO_vaYJiXm3iTrWrnA1baqnrPHDM/edit?usp=sharing).
- Dataset was created for educational purposes for COOP Career's Fall 2024 data analytics capstone.
- Efforts to clean this data were made as a team.



<h2>Process</h2>

- Cleaned data using functions in Google Sheets, including VLOOKUP.
- Replaced "Â»" character with ">" and separated data into columns.
- Aggregated records into fields with more specific names, enhancing legibility of the data by 50%.
- Created a database of KPI tables in Tableau, increasing understanding of costs and rates analysis by 25%.



<h2>Analyze</h2>

<h3>Insight 1</h3>

After analyzing recurring audience segments and their KPI's, I narrowed it down to the segments below. These audiences represent the lowest costs (per acquisition, per click, and per 1,000 views) and the highest rates of clicks and conversions:

![Five highlight table charts showing the top 10 audience segments in CPA (cost per acquisition), the CPC (cost per click), the CPM (cost per one thousand views), the CTR (click through rate), and the CVR (conversion rate) from this dataset.](https://github.com/user-attachments/assets/fba9b7d4-5405-4351-8551-7a40d9cd2809)


<sub>*Charts created in Tableau.</sub>

<h3>Insight 2</h3>

From there, I extracted the top performing segments from each KPI category and came up with the top 10 audiences. Across categories (food, sports, travel, financial, automotive, and interests), these were the top 10 repeat audience segments:

![Screenshot of a table from Google Sheets. The top 10 performing audiences are listed as follow: Porsche, Financial Planning and Management, Loans Credit Lending, Basketball, Skin Care, Accounting Auditing, Holiday Seasonal Events, Cruises, Banking, and Agri-tourism. The other four columns list the creative messaging, the ad exchange used, the website, and the kind of device used to serve the ad.](https://github.com/user-attachments/assets/e8d2dd9a-aa11-4c53-acf1-723c33d81730)



<h2>Share</h2>

My analysis culminated into the following 3 personas:

<h3 align="center">
  Audience Persona #1
</h3>

![Photo of a well-dressed middle-aged gentleman on the righthand side. On the lefthand side, text reads, "Audience Persona #1. George, 56. Demographics: Owns his own home in Little Rock as a married father of two. Works as a loan officer making $100,000 annual. Behavioral Identifiers: He enjoys luxury purchases like cars and keeping up-to-date on the latest investment news. He’s looking towards early retirement with a stable financial history. Savings are important to him, managing his personal brokerage accounts."](https://github.com/user-attachments/assets/488d33cd-b22d-447a-b505-5977b403311e)

<h3 align="center">
  Audience Persona #2
</h3>

![Photo of a professional woman on the righthand side. On the lefthand side, text reads, "Audience Persona #2. Raya, 32. Demographics: Rents luxury apartment in Manhattan with one roommate. Works as a property manager, making $85,000 annual. Behavioral Identifiers: In-the-know regarding online trends in fashion, skincare, and makeup. Living in a city, she’s looking for vacation spots that are the opposite of her everyday. Cruises, agritourism. Follows holiday seasonal sales events.](https://github.com/user-attachments/assets/a7ff94d0-7644-404f-aefa-3fb8a2478b3f)

<h3 align="center">
  Audience Persona #3
</h3>

![Photo of a casual young man on the righthand side. On the lefthand side, text reads, "Audience Persona #3. Brian, 27. Demographics: Rents an apartment in Chicago. Looking to own his own home. Works in financial consulting, making $120,000 annual. Behavioral Identifiers: He aspires to own luxury cars like a Porsche. Loves sports, plays in basketball team with buddies, and goes out to see games. Wants to eat better, but prefers the speed of fast food like Five Guys.](https://github.com/user-attachments/assets/bc7276a4-9e50-43ef-a40d-7e3b26f5e74f)

<sub>*Location data was the purview of another teammate. Highest conversions came from Arkansas, New York, and Illinois.</sub>


<h2>Act</h2>

<h3>Results</h3>

1. Top three performing audiences are Porsche, Financial Planning and Management, and Loans (Credit and Lending).
2. Top categories are Financial, Sports, and Automotive
     - Low cost, high conversion
4. Bottom performing categories include Pontiac, Makeup and Cosmetics, and Individual Sports.
     - Makeup and Cosmetics is high cost, high conversion
     - Individual Sports is high cost, low conversion
5. There's untapped potential in the Agritourism category with it occurring at least twice in the top 10 KPIs (CPC, CPM), but bottom performing in CVR.
     - What is it about this market that has high interest but low conversion?

<h3>Recommendations</h3>

Strategies for marketing to these personas include: 

1. Financial Planning and Management: market to a younger audience of older Gen Z/Young Millenials to accommodate the economic and financial challenges faced by this group.
2. Porsche: market to a middle aged male audience - mens' mid-life crises, and young men who want to appear cool and favorable to women.
3. Loans: market to middle aged consumers who had time to build credit and are more likely to be approved for loans.
4. Agritourism: market to a younger audience as the trendy new thing. Market to older audience as something fun and new to do with retirement, compare them to the trendy, young folks doing it.
