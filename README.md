# 2019 UK General Election Predictions 

Simple multilevel regression and post stratification to predict the outcome of the 2019 UK general election 

## Data

Data comes from the following sources:
* Census data from the [Office of National Statistics](https://www.ons.gov.uk/datasets/create)
* Survey data from the [British Election Study](https://www.britishelectionstudy.com/data)


## Repo Structure
```
├── README.md  
├── data
│   ├── transformed    <- Final, canonical data for modeling
|   ├── interim        <- Intermediate data that has been transformed
│   └── raw            <- Original, raw data 
└── code 
```


## Resources
Additional resources I used to complete this project:
* [MRP: what it is and why it may, or may not, be right at the next general election](https://theweekinpolls.substack.com/p/mrp-what-it-is-and-why-it-may-or)
* [Cookie cutter data science template](https://github.com/drivendata/cookiecutter-data-science)