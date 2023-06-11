# Company-Layoff-2023-Dataset-EDA
Detailed Analysis of Company Layoff 2023 Dataset .

As we all are hearing almost every day that tech firms around the globe are fighting the economic slowdown by firing employees . The slow consumer spending, higher interest rates by central banks and strong dollars overseas are hinting towards possible recession and tech firms have mainly resulted laying employees off. This economic slowdown has made Meta recently fire 13% of its workforce, which amounts to more than 11,000 employees.
So amid all this slowdown and companies firing employees I though of analysing this situation of layoffs and luckily i found a data set on Kaggle
https://www.kaggle.com/datasets/swaptr/layoffs-2022 which was apt for this analysis .

I analysed this dataset using python library numpy and pandas , for visualization I used pyplot, seaborn and plotly . After Importing libraries and dataset in jupyter notebook I starting inspecting the data to check if any cleaning I required .
Following is the dataset
![image](https://github.com/rohit951994/Company-Layoff-2023-Dataset-EDA/assets/72706872/d67c0bcb-d745-4c4a-b6da-08fe92407278)

Below are the major findings that were discovered during analysis .

1) After covid in 2020 layoff has been continuously increasing ,except for 2021 where all the economies and companies were reviving from the lockdown .In 2022 the layoff have been 100% higher that 2020 and in 2023 ( only 4 months of data ) is more than double due to global slowdown .
![image](https://github.com/rohit951994/Company-Layoff-2023-Dataset-EDA/assets/72706872/51002d78-a9ed-4d3c-a50c-9c346167d357)

2) Layoffs peaked between Nov 2022 and March 2023 .
![image](https://github.com/rohit951994/Company-Layoff-2023-Dataset-EDA/assets/72706872/f7357233-9be2-4ac9-892c-c332b8d07d13)

3) Top ten companies where maximum layoff happened were from trch industries .
![image](https://github.com/rohit951994/Company-Layoff-2023-Dataset-EDA/assets/72706872/7cb245b6-8472-4c19-92ce-fb56a646557d)

4) In 2022 and 2023 Meta , Google and Amazon has been the top companies with max layoffs .
![image](https://github.com/rohit951994/Company-Layoff-2023-Dataset-EDA/assets/72706872/8a79d603-9a28-4035-a3a8-af822cf37dd0)

5) A large chunk of layoffs happened in United States companies , after that India and the Netherland , Germany , Sweden , Brazil , UK , Canada followed .We saw earlier that max layoffs happened in tech companies and most of the tech companies are located in USA , So this could be a reliable reason for the same.Next we will explore this city wise .
![image](https://github.com/rohit951994/Company-Layoff-2023-Dataset-EDA/assets/72706872/2f9f14f8-1619-4909-b490-56e906c9098c)

6) Bangalore , Gurugram , Mumbai comprise of 90 % of job loses in India .
![image](https://github.com/rohit951994/Company-Layoff-2023-Dataset-EDA/assets/72706872/f084afd5-52b9-446d-8e70-f43e309e5b91)

7) Consumer , Retail Were the top industries most disrupted and having maximum layoffs . After that there is Others, Transportation , Food , finance , healthcare . Amazon ( Retail ) , Google( Consumer ) and Meta( Consumer )
![image](https://github.com/rohit951994/Company-Layoff-2023-Dataset-EDA/assets/72706872/be65c4b4-16cd-4b85-9d04-ec01ba30d996)

8) Further analysis was done on companies where 100 % layoffs happened .That means the companies got shut down . Following are the result of that analysis .
![image](https://github.com/rohit951994/Company-Layoff-2023-Dataset-EDA/assets/72706872/c0cd0870-a985-416c-a623-a2c1b2ee93bd)

![image](https://github.com/rohit951994/Company-Layoff-2023-Dataset-EDA/assets/72706872/41d68423-696b-49e4-b558-98b3fd964899)


Conclusions
After analysing the dataset of layoff following findings can be concluded .

a) Max layoff happened in companies of USA ( SF , New York , Boston and Seattle ) which are main head offices of tech companies giant like Google , Amazon , Meta .

b) After covid in 2020 layoff has been continuously increasing ,except for 2021 where all the economies and companies were reviving from the lockdown . In 2022 the layoff have been 100% higher that 2020 and in 2023 ( only 4 months of data ) is more than double due to global slowdown .

c) Amazon , Google, Meta, Salesforce,Microsoft and Philips are the top companies with maximum number of layoffs .

d) In 2022 and 2023 Meta , Google and Amazon has been the top companies with max layoffs .

e) In India companies where major layoffs happened were in Bangalore , Gurugram , Mumbai .

f) Consumer , Retail Were the top industries most disrupted and having maximum layoffs . After that there is Others, Transportation , Food , finance , healthcare .

With this global slowdown in consumer demand , continuous talks of recession in US and Europe and increasing trend in layoffs all the employee should be on their toes , continuously skilling up themselves and be up to date with the latest technologies in respective field . We all wish that things go back to normalcy and this game of layoffs cools down .


