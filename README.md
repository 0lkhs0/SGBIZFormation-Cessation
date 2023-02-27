# SG Business Formation & Cessation

An analysis of the impact of the Covid-19 pandemic on the formation and cessation of business entities in Singapore, with the goal of gaining valuable insights into the economic effects of the pandemic on the country's business landscape.

## About the Project
This project is a data analysis of the formation and cessation of business entities in Singapore by industry, from January 1990 to December 2022. The goal of the project was to identify trends in the data and provide insights into the performance of different industries over time. The project involved data cleaning, transformation, and visualization using Python and its data analysis libraries such as Pandas, Matplotlib, and Seaborn. Through this analysis, we were able to identify industries that have seen significant growth or decline in recent years and gain a better understanding of the business market in Singapore after covid.

## Questions to Answer

1. Based on the formation and cessation rate of businesses across different industries in Singapore which industries have the highest and lowest rates?
2. Which industries have seen the most growth and which have faced the most challenges post-Covid-19 pandemic in Singapore?
3. Which types of businesses are most vulnerable to failure? 
4. Which industries are in high demand for new business formation and evaluate their success rate in terms of survival post-establishment?

## Data
Datasets obtained from Singstats (https://www.singstat.gov.sg/find-data/search-by-theme/industry/formation-and-cessation-of-business-entities/latest-data)
<br></br>
It comprises of monthly formation and cessation values of business entities in Singapore from January 1990 to Decemeber 2022. The data is split into 397 months, across 15 different industries:
1. Manufacturing
2. Construction
3. Wholesale Trade
4. Retail Trade
5. Transportation & Storage
6. Accommodation
7. Food & Beverage Services
8. Information & Communications
9. Finance & Insurance
10. Real Estate
11. Professional Services
12. Administrative & Support Services
13. Education, Health & Social Services
14. Arts, Entertainment, Recreation & Other Services
15. Others

## Results


<br></br>
<!-- <p align=center>
  Total Number of Formation and Cessation of Businesses <br></br>
  <img width ="800" alt="[Total]" src="https://user-images.githubusercontent.com/104280044/213170565-7cfc06d7-2d29-40c8-adba-8670ee41f665.png">
</p>

<p align=center>
  Industry: Accommodation <br></br>
  <img width ="800" alt="[Accommodation]" src="https://user-images.githubusercontent.com/104280044/213147202-6bb0a89a-8abe-4904-ad76-c7158baaceed.png">
</p>

<p align=center>
  Industry: Manufacturing <br></br>
  <img width ='800' alt='[Manufacturing]' src='https://user-images.githubusercontent.com/104280044/213149665-4d1b099a-a786-4e09-8a9c-3d27763e2106.png'>
  </p>
  
<p align=center>
  Industry: Construction <br></br>
  <img width ='800' alt='[Construction]' src='https://user-images.githubusercontent.com/104280044/213151562-7ff250f8-32e9-4976-8b6d-3187d4347472.png'>
  </p>
  
<p align=center>
  Industry: Wholesale Trade <br></br>
  <img width ='800' alt='[Wholesale Trade]' src='https://user-images.githubusercontent.com/104280044/213152285-a8d6d901-34b5-43d2-8568-789474bd241f.png'>
  </p>
  
<p align=center>
  Industry: Information & Communications <br></br>
  <img width='800' alt='[Information & Communications]' src='https://user-images.githubusercontent.com/104280044/213156171-b230d029-60f9-4b46-951b-4b9f612dbb41.png'>
  </p>
  
<p align=center>
  Industry: Retail Trade <br></br>
  <img width='800' alt='[Retail Trade]' src='https://user-images.githubusercontent.com/104280044/213156339-7aebfcce-4ecc-4ea6-a692-b1254161eea6.png'>     </p> 
  
<p align=center>
  Industry: Food & Beverages Services <br></br>
  <img width='800' alt='Food & Beverages' src='https://user-images.githubusercontent.com/104280044/213156202-3c33977f-7616-45ce-aa37-0aab670a2fbc.png'>
  </p>
  
<p align=center>
  Industry: Transportation & Storage <br></br>
  <img width='800' alt='[Transportation & Storage]' src='https://user-images.githubusercontent.com/104280044/213156254-66d5b224-4517-4ff0-8c09-b3bbd85a3cae.png'>
  </p>
                                                          
<p align=center>
  Industry: Arts, Entertainment, Recreation & Other Services <br></br>
  <img width='800' alt='[Arts, Entertainment, Recreation & Other Services]' src='https://user-images.githubusercontent.com/104280044/213156432-5e4262b7-8a77-4e68-9150-06d375201731.png'>
  </p>  
  
<p align=center>
  Industry: Education, Health & Social Services <br></br>
  <img width='800' alt='[Education, Health & Social Services]' src='https://user-images.githubusercontent.com/104280044/213156435-591540b5-682f-4e4e-9fea-c68806d195e0.png'>
  </p>  
  
<p align=center>
  Industry: Administrative & Support Services <br></br>
  <img width='800' alt='[Administrative & Support Services]' src='https://user-images.githubusercontent.com/104280044/213156438-a898faef-514a-455d-a5c2-09d2cb4edb50.png'>
  </p>
  
<p align=center>
  Industry: Professional Services <br></br>
  <img width='800' alt='[Professional Services]' src='https://user-images.githubusercontent.com/104280044/213156442-7e4309f8-ebba-4ffa-af20-5fa195b96ee3.png'>
  </p>  
  
<p align=center>
  Industry: Real Estate <br></br>
  <img width='800' alt='[Real Estate]' src='https://user-images.githubusercontent.com/104280044/213156447-1f6d2a21-1670-4b4b-902e-c904d3c7fc34.png'>
  </p>  
  
<p align=center>
  Industry: Finance & Insurance <br></br>
  <img width='800' alt='[Finance & Insurance]' src='https://user-images.githubusercontent.com/104280044/213156449-fc0f0504-aa7b-4650-b081-0d774edd195e.png'>                       
  </p>  
  
<p align=center>
  Industry: Others <br></br>
   <img width='800' alt=['Others'] src='https://user-images.githubusercontent.com/104280044/213170047-3cf84836-a714-4644-a2b9-0ad474a34875.png'>
  </p>   -->
  
## Post Covid Analysis

### Based on the formation and cessation rate of businesses across different industries in Singapore, which industries have the highest and lowest rates?
<p align=center>
<img width ='800' alt=['Time series formation-cessation rate'] src='https://user-images.githubusercontent.com/104280044/221544636-f86ea883-af1a-41bf-8b7f-7a87edcd3cff.png'>
 </p>

<p align = center>
<img width ='800' alt['Average rate'] src='https://user-images.githubusercontent.com/104280044/221539965-2cf2a649-1b09-4a70-811c-90da135ff729.png'>
  </p>
The rate is maximum for the industry:  Professional Services <br>
The rate is minimum for the industry:  Accommodation

Industries like: Information & Communications, Education, Health & Social Services, Retail Trade, Arts, Entertainment, Recreation & Other Services, Transportation & Storage, Food & Beverage Services have potential for growth. <br></br>
Their cessation formation rate is in the middle as we can observe.


### Which industries have seen the most growth and which have faced the most challenges post-Covid-19 pandemic in Singapore?

<p align=center>
   <img width ='800' alt['Growth'] src='https://user-images.githubusercontent.com/104280044/221546743-5772d22e-f1c3-4331-945b-b6d30f04b756.png'>
  <img width ='800' alt['Growth'] src='https://user-images.githubusercontent.com/104280044/221546373-c89c536d-be23-4ca0-92aa-874a6039e6a0.png'>
  </p>
  
The industry with the most growth during the pandemic is Finance & Insurance. <br></br>
The industry which took the hardest hit is Transportation & Storage.

### Which types of businesses are most vulnerable to failure?
<p align=center>
  <img width ='800' alt['ts'] src='https://user-images.githubusercontent.com/104280044/221547261-1355c273-1a38-49d2-af27-3fc150dc6d8d.png'>
  <img width ='800' alt['ts'] src='https://user-images.githubusercontent.com/104280044/221547442-1f7700f5-9125-4020-b323-fa69abf47cd0.png'>
  </p>
Wholesale trade the average cessation value is the highest, also the cessation rates are the most across the entire period. Retail trade follows similar pattern, We can conclude this using bar chart and line chart.

### Which industries are in high demand for new business formation and evaluate their success rate in terms of survival post-establishment?
| Industry | Success Rate |
| --- | --- |
| Finance & Insurance                              |50.176820|
|Information & Communications                        |41.105687|
|Education, Health & Social Services                 |39.721610|
|Professional Services                               |38.374956|
|Administrative & Support Services                   |23.279183|
|Food & Beverage Services                            |21.825709|
|Arts, Entertainment, Recreation & Other Services    |21.333087|
|Wholesale Trade                                     |16.897559|
|Transportation & Storage                            |15.652792|
|Construction                                        |14.586423|
|Retail Trade                                        |9.251670|
|Manufacturing                                        |7.332252|
|Others                                               |6.050093|
|Real Estate                                          |5.346710|
|Accommodation                                            |-inf|

<br></br>
Aggreate formation-cessation rate
<br></br>

| Industry | Aggreate formation-cessation rate|
| --- | --- |
|Wholesale Trade                                     |764.810606|
|Professional Services                               |541.770202|
|Retail Trade                                        |419.929293|
|Information & Communications                        |297.805556|
|Finance & Insurance                                 |283.260101|
|Construction                                        |257.467172|
|Arts, Entertainment, Recreation & Other Services    |245.113636|
|Transportation & Storage                            |226.535354|
|Administrative & Support Services                   |196.679293|
|Food & Beverage Services                            |194.040404|
|Manufacturing                                       |186.613636|
|Education, Health & Social Services                 |183.497475|
|Real Estate                                         | 66.921717|
|Others                                               |21.578283|
|Accommodation                                         |6.068182|

<p align=center>
  <img width='800' alr=['success rate'] src='https://user-images.githubusercontent.com/104280044/221553398-4f484dd2-8da2-4e67-be99-27205fb42f05.png'>
  </p>
Wholesale trade, retail trade, professional services are in high demand.
Success rates can be observed.

## Modelling 
Modelling with decision tree regressor and xgboost
<p>
<img width="800" alt="Screenshot 2023-02-27 at 11 40 49 PM" src="https://user-images.githubusercontent.com/104280044/221609465-80b4a30e-013d-4062-ab42-44664c7ea005.png">

<img width="685" alt="Screenshot 2023-02-27 at 11 41 26 PM" src="https://user-images.githubusercontent.com/104280044/221609610-f5e2cbe6-2a59-4b41-96c9-03bb51291eac.png">

<img width="770" alt="Screenshot 2023-02-27 at 11 41 45 PM" src="https://user-images.githubusercontent.com/104280044/221609687-12079e4c-b321-4993-ac93-f2edcd24850e.png">
<img width="614" alt="Screenshot 2023-02-27 at 11 42 02 PM" src="https://user-images.githubusercontent.com/104280044/221609757-2641d94e-7c68-4c0e-9c01-99bc2fb6dbcb.png">
<img width="760" alt="Screenshot 2023-02-27 at 11 42 12 PM" src="https://user-images.githubusercontent.com/104280044/221609816-2e154248-84fd-4f23-a8a6-eaae618c2d97.png">
  </p>
  
  
 ## Limitations
 Modelling is not accurate as the impact of external factors in Singapore and globally will affect the business environment.
 The dataset does not comprise of existing business entities before 1990.
 
