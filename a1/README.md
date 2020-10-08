This project collects data from the wikimedia api endpoint. The data is more for educational pirposes. Using this data is bound by the license terms of wikimedia https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions 

Data is collected from two endpoints provided by wikimedia. 
Legacy documentation: https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts
New endpoint documentation: https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews

There are 5 json files in the repo which is the data downloaded from wikimedia endpoint. 
This will produce a final csv file with following columns 
pageviews_desktop_views - Number of page views in month where access type is desktop.
pageviews_mobile_views -  Number of page views in month where access type is mobile.
pageview_all_views - Sum of pageviews_desktop_views pageviews_desktop_views columns for the month.
 
pagecounts_desktop_views  - Number of page views in month where access type is desktop from legacy endpoint.
pagecounts_mobile_views  - Number of page views in month where access type is mobiole from legacy endpoint.
pagecount_all_views - Sum of pagecounts_desktop_views pagecounts_mobile_views columns for the month.

year - year in format YYYY for which the data is collected.
month - Month of the year MM for which data is collected.

