# data-512-a1: Data Curation

In this assignment, I combine data about Wikipedia page traffic from two different Wikimedia REST API endpoints into a single dataset, perform some simple data processing steps on the data, and then analyze that data.

The goal of this assignment is to construct, analyze, and publish a dataset of monthly traffic on English Wikipedia from January 1 2008 through August 30 2020. The work process and analysis can be found in this well-documented [jupyter notebook] (data_512_a1.ipynb). I observed the difference between the two APIs in which data from the Pageview API (solid lines )excludes spiders/crawlers, while data from the Pagecounts API (dashed lines) does not. Because of the change of the metrics, we see a drop in total pageviews using the Pageview API since July 2015. Since 2018, I also see the amount of pageviews assicoated with mobile users exceeds the amount of pageviews with destop users.

## API Documentation
Here are the documentations for both APIs used in this assignment:
- Legacy API: [Documentation](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts)
- Pageviews API: [Documentation](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews)

