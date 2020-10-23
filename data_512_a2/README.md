# data-512-a2: Bias in the Data

In this assignment, I performed two analysis using datasets for toxicity as well as aggression. In the first analysis, I compared the demographic information about the crowflower workers who labeled the toxicity data and aggression data with the demographic information of the general population I obtained from the United Nation's data. Workers who labeled for toxicity data and aggression data shows the same skewed demographic information. The demographic profile of the crowdflower workers do not match that of the general population well at all. We see that there are twice as much male crowdflower workers than females. We also see that there are a lot more younger people over 18-year-old among workers than the proportion of this age group in the general population. Such bias in the demographic data of the workers is very obvious.

In the seconnd analysis, I tried to answer the question : Are female-identified labelers more or less likely to label comments as aggressive than male-identified labelers? Under the assumption that workers are randomly selected to do the annotations for toxicity data and the aggression data, we see that suprising, female-identified labelers are equally likely to label comments as aggressive than male-identified labelers. Based on the results of the conditional probability we have,female-identified labelers are equally likely to label comments as aggressive than male-identified labelers. Thus gender disproportion does not contribute to the bias in the data. We do not need to worry about that. However, I believe the age-group, ecucation level as well as language demographic profile of workers would make a difference. If more time is granted, furthur analysis on the age-group should be done.

The work process and analysis can be found in this well-documented [jupyter notebook](data_512_a2.ipynb).

## Data Source

Wulczyn, Ellery; Thain, Nithum; Dixon, Lucas (2016): Wikipedia Detox. figshare. [doi.org/10.6084/m9.figshare.4054689](doi.org/10.6084/m9.figshare.4054689) The data set contains comments from 2001-2016 that were scored on their level of toxicity and aggression by approximately 10 different crowdworkers.

The Toxicity dataset can be downloaded from [The toxicity Figshare dataset](https://figshare.com/articles/Wikipedia_Talk_Labels_Personal_Attacks/4054689),and the aggression dataset can be downloaded from [aggression Figshare dataset](https://figshare.com/articles/dataset/Wikipedia_Talk_Labels_Aggression/4267550). The schema can be found in the [dataset docummentation page](https://meta.wikimedia.org/wiki/Research:Detox/Data_Release).

The term of the use of the United Nations Population Dynamic data is [here](http://creativecommons.org/licenses/by/3.0/igo/).

## License
The license for my code is under [MIT LICENSE](LICENSE).
