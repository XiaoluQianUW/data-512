# data-512-a2: Bias in the Data

In this assignment, I performed two analysis using

The goal of this assignment is to construct, analyze, and publish a dataset of monthly traffic on English Wikipedia from January 1 2008 through August 30 2020. The work process and analysis can be found in this well-documented [jupyter notebook](data_512_a2.ipynb).


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


* [jupyter notebook](data_512_a2.ipynb): This jupyter notebook shows all the work and analysis in the end.



## License
The license for my code is under [MIT LICENSE](LICENSE).
The term of the use of the United Nations Population Dynamic data is [here](http://creativecommons.org/licenses/by/3.0/igo/).
