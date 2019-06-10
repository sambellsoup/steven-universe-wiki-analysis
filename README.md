# steven-universe-wiki-analysis
beginnings of an analysis of the Fandom Steven Universe Wiki and other sources

This project involves a rudimentary scraping of Tumblr, Google Trends, and the Steven Universe wiki on Fandom to statistically explore and test the interactions of fans with the Internet.

Unfortunately, Cartoon Network has a habit of drastically shifting the scheduled air times of some of their programming. We are interested in the question of whether or not the erratic scheduling of this show has affected its viewership, and the social media presence of the fans talking about their viewership.

Specifically, we wish to examine: 
 - Tumblr posting frequency on #stevenuniverse against the air dates of new episodes
 - Viewership per season (according to Nielsen ratings)
 - Google Trends interest against Nielsen ratings
 - Schedule hiatus length against Nielsen ratings
 
We scrape episode data from Wikipedia and the Steven Universe wiki, along with blog posts from Tumblr and tracking data from Google Trends, to undertake this analysis. Once the data is clean and manually updated, four hypothesis tests are executed:
 - chi-squared goodness-of-fit for Tumblr posting frequency "near" vs "far" from air dates
 - ANOVA for Nielsen ratings by season
 - 2-sample t-test and parametric linear regression for Google Trends vs Nielsen ratings
 - parametric linear regression for viewership vs schedule hiatus length
 

Future exploration possibilities:
 - Other hashtags on Tumblr, Twitter, Facebook, other social media platforms
 - Social media posting, viewership against which characters / fusions appear in new episodes
 - Correlation between music in episodes and social media interaction
 - Wiki comment threads: sentiment analysis against length of time as a wiki poster, content of current episode under discussion

