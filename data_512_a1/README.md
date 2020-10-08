# data-512-a1: Data Curation

In this assignment, I combine data about Wikipedia page traffic from two different Wikimedia REST API endpoints into a single dataset, perform some simple data processing steps on the data, and then analyze that data.

The goal of this assignment is to construct, analyze, and publish a dataset of monthly traffic on English Wikipedia from January 1 2008 through August 30 2020. The work process and analysis can be found in this well-documented [jupyter notebook](data_512_a1.ipynb). I observed the difference between the two APIs in which data from the Pageview API (solid lines )excludes spiders/crawlers, while data from the Pagecounts API (dashed lines) does not. Because of the change of the metrics, we see a drop in total pageviews using the Pageview API since July 2015. Since 2018, I also see the amount of pageviews assicoated with mobile users exceeds the amount of pageviews with destop users.

## API Documentation
Here are the documentations for both APIs used in this assignment:
- Legacy API: [Documentation](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts)
- Pageviews API: [Documentation](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews)

## File Directory
* [csv](csv): This folder contains the final processed data of the merged datasets on page view counts obtained from the two APIs. It contains the following information of the traffic:

| Column | Description | 
| ------ | ------ |
| year | YYYY | 
| month | MM | 
|pagecount_all_views| Total number of page views from the Legacy API|
|pagecount_desktop_views | Number of page views from desktop users of Legacy API|
|pagecount_mobile_views	| Number of page page views from mobile users of Legacy API|
|pageview_all_views| Total number of page views from the Pageviews API|
|pageview_desktop_views| Number of page views from desktop users of the Pageviews API|
|pageview_mobile_views| Number of page views from mobile users of the Pageviews API|

* [json](json): In this folder, I collect data for all months where data is available and then save the raw results into 5 separate JSON source data files.
* [jupyter notebook](data_512_a1.ipynb): This jupyter notebook shows all the work and analysis in the end. 
* [graph](en-wikipedia_traffic_200712-202008-fig): This is the time series graph of the analysis of the pageview traffic for each APIs and their types.

## Visualization
Here I visualize the traffic metrics from the two APIs as a time series graph:

![Page Views on English Wikipedia (x 1,000,000)](/en-wikipedia_traffic_200801-202008.png)



