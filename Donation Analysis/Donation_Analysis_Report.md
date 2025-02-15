# Project: Donations Analysis 

## Table of Contents  
1. [Introduction](#introduction)
2. [Project Aim](#projectaim)
3. [Project Description](#project-description)
4. [Data Acquisition and Preparation](#data-acquisition-and-preparation)
5. [Data Cleaning and Transformation](#data-cleaning-and-transformation)
6. [Data Analysis and Visualization](#data-analysis-and-visualization)
7. [Interpretation of Data](#interpretation-of-data)
   * [Top 5 Donors by Donation Amount and Donor Potential](#a-top-5-donors-by-donation-amount-and-donor-potential) 
   * [Donation Per Demographic Class](#b-donation-per-demographic-class)
   * [Donation Per Year](#c-donation-per-year)
   * [Donation by State](#d-donation-by-state)
   * [Top 10 Cities by Donation](#e-top-10-cities-by-donation)
8. [Recommendations](#recommendations)
   * [Targeted Donor Engagement](#a-targeted-donor-engagement)
   * [Geographic Focus](#b-geographic-focus)
   * [Yearly Trends and Campaign Timing](#c-yearly-trends-and-campaign-timing)
   * [Demographic-Specific Campaigns](#d-demographic-specific-campaigns)
   * [Donor Retention and Recognition](#e-donor-retention-and-recognition)
   * [Enhancing Donation Channels](#f-enhancing-donation-channels)
   * [Community Involvement and Awareness](#g-community-involvement-and-awareness)

## Introduction
This donation analysis report aims to provide a comprehensive overview of an organization's fundraising efforts, donor engagement, and donation patterns. By analyzing the data collected from various fundraising campaigns and donor interactions, this report seeks to identify key trends, strengths, and areas for improvement in donation strategies. Understanding these elements will enable organizations to optimize their fundraising efforts, enhance donor relationships, and ultimately increase the overall effectiveness of their philanthropic initiatives. Through this analysis, I aim to gain valuable insights that will inform organizations' future strategies and ensure the sustainability and growth of their mission.

## Project Aim
This project evaluates donation patterns and donor behaviors to optimize future campaigns and maximize contributions. It also identifies states with many donors which can be crucial for strategic planning and targeted fundraising efforts. 

## Project Description
The Donation Analysis project aims to evaluate donation patterns, donor behaviors, and fundraising effectiveness to optimize future campaigns and maximize contributions. It involves analyzing data on donation amounts, frequency, and donor demographics. Using statistical tools and data visualization, the analysis identifies key trends, successful strategies, and areas for improvement. The report provides actionable insights and recommendations to enhance donor engagement, target potential high-value donors, and improve overall fundraising efficiency. Tableau Desktop is used to complete the data analysis. 

I will derive the following insights from this data such as trends, patterns, and any anomalies that will help propose informed recommendations such as:
*	Donation amounts by donor potential.
*	Donation trends over time to see if there are any seasonal patterns or significant changes in donation behavior.
*	Understanding which demographic groups contribute the most and least. 
*	What are the high-value donors and how understanding their characteristics can help in targeting future fundraising efforts?
*	Determine which regions or cities have the highest and lowest donation rates.
*	Identify the year of maximum donations.
  
Here is what I did:
## Data Acquisition and Preparation
The data were obtained from the Tableau website. MeriSKILL provided data. I downloaded the dataset as a .csv file and uploaded it in Tableau Prep for cleaning and transformation purposes. This dataset had 9 columns in total and was recorded for the years *2013* to *2017*.
*	Donor Potential: Classification of donor potential (e.g., High, Medium, Low, Not Specified).
*	Donor Name: Name of the donor.
*	Demographic: Socioeconomic classification (e.g., Middle Class, Upper-Middle Class).
*	Region: Geographic region.
*	State or Province: State or province of the donor.
*	City: City of the donor.
*	Postal Code: Postal code of the donor.
*	Donation Date: Date of the donation.
*	Donation Amount: Amount donated

## Data Cleaning and Transformation
To clean the data, I used *Tableau Prep* as follows: 
*	Uploaded the downloaded dataset by connecting to the data. 
*	Renamed fields for consistency, filtered blanks, removed duplicates, combined data per categories, and edited values accordingly. 
*	Using Group Values by Manual Selection, I changed “Med” under the Donation Potential field to “Medium”. I did the same for Hi and High and Lo and Low.
*	Aggregated data where necessary and created an output of my cleaned data. 
*	Profiled and explored my data before analysis to know what to expect from the analysis.
*	Lastly, I output the cleaned data as a .hyper file. 

## Data Analysis and Visualization
The analysis was performed in Tableau Desktop. To do so,  
*	I Launched Tableau Desktop and connected the cleaned data. 
*	I created charts in several sheets such as Bar charts, a Line chart, a pie chart, a Map, a side-by-side bar chart, and Stacked Bar charts.
*	After creating all the charts, I combined them in a dashboard as shown in the following Figure.
*	All the charts were assembled and made interactive through the use of filters to display Donor potential, Demographics, and years of donations. 

<figure>
  <img src="https://github.com/Songonge/Tableau-Projects/blob/main/Donation%20Analysis/Donation%20Analysis%20Dashboard.png" width=100% height=100% alt="alt text">
  <figcaption>Figure: Donation Analysis Dashboard</figcaption>
</figure>
<br/><br/> 

## Interpretation of Data
The Donation Analysis dashboard provides a comprehensive overview of donation patterns across different dimensions. Here’s a detailed interpretation:

#### a. Top 5 Donors by Donation Amount and Donor Potential
*	**High Potential Donors**: Kim Weiss is the top donor in this category, followed by Caroline Mor, Eleanor Swain, Bonnie Matt, and Herbert Hold. These donors have shown the most consistent and significant increase in donations over the years (2013-2017).
*	**Medium Potential Donors**: Kim Weiss is again the top donor, followed by Eleanor Swain and Bonnie Matt. 
*	**Low Potential Donors**: Kim Weiss remains significant, with contributions from Caroline Mor, Eleanor Swain, Bonnie Matt, and Herbert Hold.

#### b. Donation Per Demographic Class
*	**Middle Class**: Largest contributing class, 47.9%. Significant contributions across high, medium, and low potentials.
*	**Upper Class**: Moderate contributions, 35.4%. 
*	**Upper-Middle Class**: Lowest contributions among the three, 16.7% but still significant.

#### c. Donation Per Year
*	2015: Highest (peak year) total donations.
*	2017: Noticeable drop from previous years.

#### d. Donation by State
*	Florida: Top state for donations and leading state in terms of donation amounts.
*	North Carolina, Georgia, Virginia: Follow closely.

#### e. Top 10 Cities by Donation
*	Miami: The city with the highest donation.
*	Atlanta, Charlotte: Other significant contributors.

## Recommendations
#### a. Targeted Donor Engagement
* High Potential Donors:
  * Kim Weiss has shown consistently high contributions across different potentials. Personalized engagement strategies and recognition programs can ensure sustained support.
  * Other high-potential donors like Caroline Mor and Eleanor Swain should be engaged with personalized communication, exclusive updates, and events.

* Middle Class Donors:
  * Given that the middle class is the largest contributing demographic, tailor campaigns to address their interests and showcase the impact of their donations.
  * Create middle-class donor clubs or societies that offer special benefits and recognition.

#### b. Geographic Focus
* Top Donor States:
  * Florida, North Carolina, and Georgia are leading states in terms of donations. Focus on these areas with local events, targeted campaigns, and partnerships with regional organizations to further boost donations.

* Cities with High Donations:
  * Miami, Atlanta, and Charlotte are key cities. Organize exclusive events, donor appreciation ceremonies, and community involvement projects in these cities.

#### c. Yearly Trends and Campaign Timing
* Strategize Around Peaks:
  * Since 2015 was a peak year, analyze the factors that contributed to this spike and try to replicate those strategies. Consider what events, campaigns, or economic conditions might have influenced donations.
  * Plan major fundraising campaigns around historically successful times of the year.

#### d. Demographic-Specific Campaigns
* Upper and Upper-Middle-Class Donors:
  * Although their numbers are smaller, they still contribute significantly. Develop high-end fundraising events, like galas or exclusive tours, to appeal to these donors.
  * Offer tailored giving options such as legacy donations, endowments, or major gift programs.

#### e. Donor Retention and Recognition
* Retention Programs:
  * Develop robust donor retention programs, including regular updates on how their donations are being used, success stories, and personalized thank you messages.
  * Recognize long-term donors with loyalty programs, awards, and special mentions in annual reports.

#### f. Enhancing Donation Channels
* Online and Mobile Giving:
  * Enhance online donation platforms to be user-friendly and secure, accommodating various payment methods.
  * Implement mobile giving options and text-to-donate campaigns to capture donations from tech-savvy and younger donors.

#### g. Community Involvement and Awareness
* Increase Community Engagement:
  * Host community events to raise awareness about the organization’s mission and projects. This can increase grassroots support and small to medium-sized donations.
  * Partner with local businesses and influencers to promote fundraising campaigns and events.

By focusing on these recommendations, the organization can maximize its fundraising potential, build stronger relationships with donors, and ensure sustainable support for its initiatives.


<br/>


**Thank you for taking the time to read this report!**

**Please reach out for any updates.**

### Author
[Edwige Songong](https://github.com/Songonge)
