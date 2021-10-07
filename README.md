# data-512-a1

The first assignment of DATA 512-MSDS: A1 Data Curation Assignment. 

### Goal
The aim of this project is to track the traffic trend of Wikipedia since 2008 by integrating and analyzing data through the use of the Wikipedia REST API, which includes desktop, mobile, and total views. In addition, this project demonstrates the data processing and analysis process in detail through Jupyter Notebook to ensure that the analysis process can be fully reproducible by others.

### API 
- The Legacy Pagecounts API ([documentation](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts), [endpoint](https://wikimedia.org/api/rest_v1/#/Pagecounts_data_(legacy)/get_metrics_legacy_pagecounts_aggregate_project_access_site_granularity_start_end)) provides access to desktop and mobile traffic data from December 2007 through July 2016.
- The Pageviews API ([documentation](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews), [endpoint](https://wikimedia.org/api/rest_v1/#/Pageviews_data/get_metrics_pageviews_aggregate_project_access_agent_granularity_start_end)) provides access to desktop, mobile web, and mobile app traffic data from July 2015 through last month.

- Term of Use
Please review the Wikimedia Foundation REST API [terms of use](https://www.mediawiki.org/wiki/Wikimedia_REST_API#Terms_and_conditions) for more information.
- license:  [CC-BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) and [GFDL](https://www.gnu.org/licenses/fdl-1.3.html) 

### Data (en-wikipedia_traffic_200712-202109.csv)
166 rows x 7 columns
- Year : from 2017 to 2021
- Month: 1-12
- pagecount_all_views: combine the monthly values for desktop and mobile to create a total traffic counts for each month. 104 values: 200712 - 201607
- pagecount_desktop_views: a total desktop traffic counts for each month. 104 values: 200712 - 201607
- pagecount_mobile_views :a total mobile traffic count for each month. 22 values: 201401-201607
- pageview_all_views: combine the monthly values for desktop and mobile to create a total traffic views for each month. 75 values: 201507-202109
- pageview_desktop_views: a total desktop traffic views for each month. 75 values: 201507-202109
- pageview_mobile_views: combine the monthly values for mobile-app and mobile-web to create a total mobile traffic views for each month. 75 values: 201507-202109



