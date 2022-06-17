# An Analysis of Kickstarter Campaigns
Identifying Successful Trends for a Proposed 12,000 Theater Kickstarter Theater Campaign
6/16/2022


Overview:

Kickstarter is an American based Public Benefit Corporation that is unique because it is a crowdfunding platform that helps artists finance their creative projects. Between 2008 and 2013 the platform has provided $775 million for more than 48,000 projects (Canadian Radio Broadcasting Commission, 2013). As stated on the Kickstarter website the goal is, "We [Kickstarter] don't want world elites and entertainment executives to define our culture, we want creative people--even those who've never made anything before to take the wheel. We help creators connect directly to their communities, putting power where it belongs." (Kickstarter.com, 2022). With this focus in mind, their is a breadth of data created by Kickstarter that can be analyzed to see the patterns of successfully funded projects. This is important as it determines the scale/how elaborate projects should be and what dollar amount to expect from crowdfunding.


Purpose:

An artistic project that was proposed was a $12,000 theater-play event with the question of being "how much financing should the owner of the project expect to recieve from a Kickstarter campaign?" An analysis of kickstarter campaigns was conducted with much consideration to previous theater events, from wolrdwide to specific regions (notably the U.S. and U.K). The indicator that was consider significant, and dependent, was "outcome", decidedly how many were Kickstarter campaign outcomes were "successful" vs. "failed" vs. canceled. Further analysis went into what was the Kickstarter campaign's initial dollar goal against what was the dollar amount pledged. Lastly, seasonality was considedered. Trends in the data did occur for "successful" campaign's with respect to goal dollar amount and seasonality. The data for this analysis was provided by UC-Davis and occurs between 2009 and 2017 (UC Davis, 2022). 


Analysis:

Analysis of the Kickstarter data was conducted by Microsoft Excel with tutorial material from (UC Davis). Tools used were data tab sorts, conditional formatting, excel functions, pivot tables, and graphs from pivot tables. "Headscratcher moment" was formatting the pivot table to provide Launch Date in months instead of years or quarters. Trick is to format privot table in the PivotChart Fields -- Axis, removing both year and quarter which leaves only months (See Pivot Table Formatting Before and After Below, Figure 1 and Figure 2). Other "moment of confusion" was why summary table of successful vs. failed vs. canceled campaigns did not add up to the amount of entries in the original table, reason: need to add in the greater than equals sign and less than equals sign as many Kickstarter goals were rounded figures (i.e. goal was set at 10,000 not 9995", see figure 3.)


Figure 1: Before formatting Axis (Categories) in Pivot Chart Fields for Pivot Chart


![PivotTableFormattingBefore](https://user-images.githubusercontent.com/105992109/174227543-24b1ae04-61a2-4cab-ae12-e79a9242b13d.png)


Figure 2: After formatting Axis (Categories) in Pivot Chart Fields for Pivot Chart


![PivotTableFormattingAfter](https://user-images.githubusercontent.com/105992109/174227559-0e1ad914-6585-431d-adf0-d9a1e33a1ab8.png)


Figure 3: In the excel formula the greater than equals sign is key to set the parameters right for the summary table


![ImportanceOfGreaterThanEqualsSign](https://user-images.githubusercontent.com/105992109/174236703-f97376d7-008d-4d0d-80b2-4bb49c3caed9.png)



Results

  * Significance of Goals 
  1. Theater events in the U.S. reach their target goal on kickstarter  57.5% of the time (See Kickstarter Data Workbook: Category Statistics Tab)
  2. Plays in the U.S. reach their targe goal 61.4% of the time (See Kickstarter Data Workbook: Subcategory Statistics Tab)
  3. The 5 plays that most are most similar in scope to the one being proposed asked for an average of 2100 GBP (range 1000-4000 GBP) with a successful pledge amount being 2384 GBP (range 1168-4137 GBP). However these were based in Great Britain (See Kickstarter Data Workbook: Edinburg Research Tab). 
  4.  In the U.S. theater events were successful when asking for a median of $3000 that recieved a median pledge of $3168 (See Kickstarter Data Workbook: Descriptive Statistics Tab). 
  5.  Theater events that failed asked for a median of $5,000, only recieving a median pledge amount of $103. (See Kickstarter Data Workbook: Descriptive Statistics Tab)
  6.  A breakedown of successful play outcomes, with no region specified, by dollar increments shows: 76% success for plays asking for less than 1,000, 73% success for plays asking between $1,000 and $4,999 and 55% success for plays asking between $5,000 and $9,999. All with Kickstarter campaign sample sizes greater than 100 (See Kickstarter Data Workbook: Outcomes Based on Goals Tab).

  * Significance of Launch Date
  6. The time of year that successful campaigns occur is late spring, early summer -- April thru July (62.8%, 66.9%, 65.4%, 63.0%) (See Kickstarter Data Workbook: Outcome Based on Launch Date Tab).
  7. This late spring-early summer period also has a higher volume of campaigns (113, 116, 153, 138) with the yearly average by month being 116 (See Kickstarter Data Workbook: Outcome Based on Launch Date Tab).
  

Results/Data Visualization:

![CountOfKickstarterOutcomesUSByTheaterArtForm](https://user-images.githubusercontent.com/105992109/173254512-5adcd83f-67bd-4eb7-ae77-c8713f1cbe8b.png)

Graph 1: Proportion of theater Kickstarter campaign outcomes in the U.S.



Table 1: The five theater plays from Great Britain, with a quick summary, that are the most similar to the one being proposed with their kickstarter results i.e. goal and pledge amount.

![SimilarTheaterPlayGreatBritain](https://user-images.githubusercontent.com/105992109/173254568-3b9288d6-1420-41cf-b0dc-a4dc3d295301.png)



Table 2: The distribution of U.S. theater Kickstarter campaign's successful vs. failed outcomes with goal and pledged money.

![USTheaterKickstarterCampaignDistributionSuccessfulVFailed](https://user-images.githubusercontent.com/105992109/173254589-a6718006-3fd7-429e-9fcf-9b47c8c27273.png)


![SeasonalityOfTheaterKickstarterCampainOutcomesByMonthUS](https://user-images.githubusercontent.com/105992109/173254541-00bec573-98f5-4996-b915-bbf596c42b98.png)

Graph 2: Seasonality of theater Kickstarter campaign outcomes by month in the U.S

Discussion:
From the analysis conducted, the recommendation for a theatrical play Kickstarter campaign, to be successful, is to conduct it between April and July. It was during this time period where most campaigns were successful and did not seem to compete directly against eachother for a limited amount of funding as the number of campaigns peaked during that time period as well. 

It would also behoove the host of the proposed campaign to ask for a donation amount in the range of $2500 - $3000. The reason for this is the $2500 amount is what similar plays suceeded on in Great Britain (once the currency was converted from Pounds Sterling to Dollars) and the $3000 was the median of what succeded in the U.S. The trend towards a failing campaign occurs quickly in the distribution as failing campaigns asked for a median of $5000. Hence, a proposed theatrical play with a budget of 12,000 should not try to obtain all of this through Kickstarter. Future Kickstarter campaigns with the theater-play art form and a budget of 12,000 should only expect to obtain about 20-25% of their budget through Kickstarter.   

The dataset provided is limited by the fact it is not recent. Trends in the last 5 years could not be discerned as the dataset ends in 2017. Hence their could be a change in seasonality, what category and subcategory correspond to successful campaigns and if crowdfunding generates more or less cash than the the time period analyzed. Data was also limited by not providing the artist or studio that sponsored the project. Certain entities might be more popular or reckognizable and thus are funded based on brand recognition.

If a deeper analysis was to be conducted identify donation amounts and number of donors is a good place to start. This is because if a grass-roots advertising campaign was to be used in concert with the Kickstarter campaign it would identify the expected amount of money provided by a donor. Should the Kickstarter campaign manager try to get several big donations or many small donations to achieve the financial goal. Based on this, the manager would have an idea of what events to go to to generate support and financial backing for the proposed theatrical play. 

Another aspect that deserves further analysis is if there are key words, or phrases, in the blurb that correlates with successful campaigns. Certain themes might capture the Zeitgeist of the time period and it reflects by being demanded through funding.

References

Canadian Radio Broadcasting Commission, 2013. The Canadian Press. "Kickstarter Crowdfunding Site Officially Launches in Canada". Posted Sep 10, 2013. Accessed June 16, 2022.  https://www.cbc.ca/news/business/kickstarter-crowdfunding-site-officially-launches-in-canada-1.1703774

Kickstarter.com, 2022. Kickstarter, PBC. "Our Mission is to Help Bring Creative Projects to Life". Copywrite 2022. Accessed June 16, 2022. https://www.kickstarter.com/about

UC Davis, 2022. Course: "Bootcamp: UCD-VIRT-DATA-PT-06-2022-U-B-TTH". Module 1: Kickstarting with Excel. Accessed June 1, 2022. https://courses.bootcampspot.com/courses/2512/pages/1-dot-1-3-download-the-kickstarter-data?module_item_id=635736  
