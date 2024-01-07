# Python-Data-Analysis-COVID19

> This project is based on Coursera project course. For full information, please visit this [link](https://www.coursera.org/projects/covid19-data-analysis-using-python). 
> In this analysis, I examined the COVID-19 death dataset for 2020. My exploration included several key outputs:
> Top 5 countries with the highest death rates: This identified the nations most severely impacted by the pandemic in terms of mortality.
> Average death rate: This provided a general sense of the global fatality rate for COVID-19.
> Countries with the highest and lowest death rates: This highlighted both the extreme ends of the mortality spectrum.
> Furthermore, I combined the 2020 death rate data with the 2019 world happiness dataset. This allowed me to conduct a linear regression analysis, investigating the potential relationship between COVID-19 death rates and factors associated with national happiness.

> For your information, I used Jupyter Lab program to run this file. Alternatively, you can use Visual Code Studio and install the Jupyter Lab extensions. 

## Implementation

1. Find the following statistic results: 
* Top five countries with the highest death rate: <br>
![VSCodium_YG1vECAZEc](https://github.com/Kwangsa19/Python-Data-Analysis-Covid19/assets/135963482/8c95c0db-e3d7-4a52-914e-b0b8c3221fdd)

* Average death rate: <br>
![VSCodium_sitQD2Z8Ki](https://github.com/Kwangsa19/Python-Data-Analysis-Covid19/assets/135963482/06bfb346-4c17-43c0-8ea1-321814cb97ff)

* The highest death rate: <br>
![VSCodium_NEp3sQIcDF](https://github.com/Kwangsa19/Python-Data-Analysis-Covid19/assets/135963482/a092b7e0-dc84-49ed-b615-b3decb76b37d)

* The lowest death rate: <br>
![VSCodium_B9OH4F4tyk](https://github.com/Kwangsa19/Python-Data-Analysis-Covid19/assets/135963482/8efd833a-c08c-4774-a167-dde8d16fbb6d)

* The death time series: <br>
![death time series](https://github.com/Kwangsa19/Python-Data-Analysis-Covid19/assets/135963482/d846a4c7-47f6-467e-b5a6-5688249f34d2)

* Death across all countries: <br>
![all of them](https://github.com/Kwangsa19/Python-Data-Analysis-Covid19/assets/135963482/b2d04a73-f28c-45f6-a7af-a1c6f2ff0796)

2. Conduct a linear regression analysis, investigating the potential relationship between COVID-19 death rates and factors associated with national happiness.
   In addition, to determine the correlation:
   - If R^2 is close to 1, it suggests a strong correlation.
   - If R^2 is around 0.5, it suggests a moderate correlation.
   - If R^2 is close to 0, it indicates a weak correlation.
   
* The correlation betwen GDP per capita against the death rate (Weak correlation): <br>
![3](https://github.com/Kwangsa19/Python-Data-Analysis-Covid19/assets/135963482/a44f88c6-36c1-4fa4-afa9-8469e1fa571c)

* The correlation betwen Social support against the death rate (Weak correlation): <br>
![6](https://github.com/Kwangsa19/Python-Data-Analysis-Covid19/assets/135963482/44564966-4606-4786-a8f2-14d2d2c450ee)

* The correlation betwen Healthy Life Expectancy against the death rate (Weak correlation): <br>
![9](https://github.com/Kwangsa19/Python-Data-Analysis-Covid19/assets/135963482/022fd5f3-799d-48c4-9d08-30612b92d84e)

* The correlation betwen Freedom to make choices against the death rate (Weak correlation): <br>
![12](https://github.com/Kwangsa19/Python-Data-Analysis-Covid19/assets/135963482/c252b5c8-b3c1-4d86-915d-6c25baf09957)

## Future Works
* Fix the death across all countries chart as it looks messy on X-axis.
* Build an interface that can allow us to do the computation as required and needed.
* Add testing/normalization test for processing raw data too. 
