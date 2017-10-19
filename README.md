# data-512-a1
Data512 HW1
## Goal
The goal of this project is to construct, analyze and publish a dataset of monthly traffic on English Wikipedia from July 1 2008 through September 30 2017. The project should fully reproducible by others.
## Link to API documentation
1. The legacy Pagecounts API: `https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts`
2. The Pageviews API: `https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews`
3. Wekimedia REST API: `https://www.mediawiki.org/wiki/REST_API`
4. Wekimedia REST API endpoint: `https://wikimedia.org/api/rest_v1/#!/Pagecounts_data_(legacy)/get_metrics_legacy_pagecounts_aggregate_project_access_site_granularity_start_end`

## Data file description
### There are eight fields in the final data file (en-wikipedia_traffic_200801-201709.csv):
#### year:
The values of this field are in four-digit format (YYYY)
#### month:
The values of this field are in two-digit format (MM)
#### pagecount_all_views：
The values of this field are numbers 
#### pagecount_desktop_views:

#### pagecount_mobile_views:

#### pageview_all_views：
#### pageview_desktop_views：
#### pageview_mobile_views：

## Special considerations of data
