# SP_Repo

The project predicts the number of cases in the next week. You can keep adding newer data
To the dataset and the AI does quite an accurate job of predicting. At some point, then, 
One can see that the number of cases have reduced significantly or even gone close to 
Zero, indicating that COVID-19 is under control. The AI can predict cases for each county 
in CA. Initially, the project started off to do just that. Along the way, I realized I 
could just use the population of an area and it’s cases history to predict future cases 
for that area, regardless of county info. It would, therefore, work for any area. 

The dataset attached 'COVID_CA_CASES_RAW.csv' is a raw dataset and not available anywhere, 
I spent considerable effort collecting the weekly information from the CA COVID-19 
dedicated website. This dataset consists of number of cases from March - May 17th, 2020 
for each county in CA. Newer data can continue to be added to this dataset and my AI will 
correctly predict the number of cases next week. 

Since the dataset is raw, I have attached python code to do feature engineering as well as 
Create a new dataset which feeds the project as input. After predictions are obtained, I
Have generated another csv which contains the predictions as an added feature. Data 
Visualization and comparisons graphs can be generated from this file. 
