# China's Wage Premium: A Comparison of Urban Areas and Rural Areas
The goal of this project is to investigate China's urban wage premium with a special focus on its provincial capitals. My goal is to determine if there exist urban/provincial capital agglomeration effects in China that contribute to the wage premium accounting for the cost of living and the unobservable ability bias of workers. I also want to see the wage gap between male and female in the urban, rural setting if time is allowed.

## Abstract
Traditionally, people living in the urban areas tend to earn more compared to those who live in the rural areas. Such bias in income exists for multiply possible reasons. The main research question I have is: What makes workers in urban area makes more money than those living in the rural area capitals? Previous theories for the explanation includes ability bias of workers living in urban areas, higher living costs in urban areas, and urban agglomeration effect. After controlling for all potential confounding variables, there does not exist urban wage premium; higher wages in urban areas is likely to explain by the higher cost of living, high-skilled jobs, being male in large cities.

## Data
I will be using data from the China Health and Nutrition Survey (CHNS) https://www.cpc.unc.edu/projects/china, a nationally representative sample of Chinese population running from 1997 to 2015. The sample data for the analysis can be found in [data](data) folder. The main analysis and code is in [here](final_report.ipynb).

## Results
Using OLS regression models, I investigate whether there is an urban wage premium in China. I account for the cost of living using the average housing price in addition to other observable individual characteristics. In my results, I find that there is no evidence for urban wage premium. Wage premium is entirely caused by other factors such as higher costs of living in urbanized settings, being male, having a white-collar job, having more years of education. I find a negative but not significant urban premium. The urban wage premium is mostly compensated for other factors such as the cost of living.

These results should be interpreted with caution. Regional price indexes are hard to find for China, therefore using housing prices can only approximate differences in the overall costs of living between urban and rural areas. As better data become available, better accounting for individual heterogeneity and regional differences in costs of living may be an interesting area of further research.

## License
This project is under the [MIT License](LICENSE).
