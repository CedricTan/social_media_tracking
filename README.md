# Social Media Tracking

## Attempting to create a simple python tool to track follower counts across social media platforms

Temporary Solution will involve a scraping tool - Beautiful Soup along with Requests

Will move onto more difficult usage of code from API requests to utilise JSON which will be more concise and scalable

This will remove all concerns of changing UIs for the scraping tool in the future - thanks to Maxime for guidance

Integrating use of APIs from:
* Facebook &#x2611; with Scraping Functionality
* Twitter &#x2611;
* Twitch &#x2611;
* Youtube &#x2611;
* Instagram &#x2611; with Scraping Functionality


2019-04-17: 
* Main stumbling block atm is requesting for access for Facebook APIs - they also own instagram.
* Youtube has a simple json and urllib request system that I used courtesy of HowCode

2019-04-29
* Twitch also uses no SDK, simply the Requests library for simplicity. Wrote a few lines to authenticate with Twitch and is working perfectly.
* Dataframe has been updated, still conceptualising how to enter inputs most effectively.
* Currently approaching it in a class format i.e. each line in the excel will be entered influencer by influencer since each class has all objects such as tags/followers/totalfollowers

2019-05-13
* Dataframe works and has all adaptive functionality
* Decided to use scraping features for Facebook and Instagram as the solution since Graph API takes too much time
* Further, Facebook API's may be closing down as a result of issues of conflict so a workaround solution is required
* If the scraping formula changes, we can work around that as well but it seems to be consistently working
* Functionality across all platforms is working fine at this moment
* **Next Steps:**
  - Create writing functionality into Excel
  - Hard-code in user names and influencer names
  - Start testing and troubleshooting when writing into Excel



