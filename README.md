# Bike-Sharing-Des-Moines2
**Overview**: We are asked to perform a bike trip analysis using the NYC CitiBike Share data to show details on how it works and how this could apply to Des Moines. 
During the class modules, we had performed multiple analysis and visualization using Tableau showing the total number of bike trips in August 2019, user type (short term customer
and annual subscriber) breakdown, peak riding hours, top starting and ending location, etc. We have to perform additional analyses to provide details as to how the bike sharing business could work in Des Moines.

## Requirements and Details of the Analysis

1. We are to use Pandas to change the "tripduration" column from an integer to a datetime datatype of the CitiBike 201908 data we already downloaded for the module.

<img width="795" alt="citibike df" src="https://user-images.githubusercontent.com/98235755/172276667-76de88b4-2075-4879-aa9c-75b477097c81.png">



<img width="783" alt="citibike TD reformat" src="https://user-images.githubusercontent.com/98235755/172276644-80042b3f-043a-4fb8-bc14-57c217a2b0b4.png">


2. Using the converted datatype, we are to create a set of visualizations to:

    a.  Show the length of time that bikes are checked out for all riders and genders
    
    
    b.  Show the number of bike trips for all riders and genders for each hour of each day of the week


    c.  Show the number of bike trips for each type of user and gender for each day of the week.
    

   **Refer to the [Tableau Bike Sharing - Des Moines Story](https://public.tableau.com/app/profile/dianne.malabanan/viz/BikeSharing-DesMoines/BikeShareDesMoinesSotry?publish=yes) to see the dashboards that were created for this analysis**


## Results and Summary


1. Eventhough the data is from NYC CitiBike Share, the analysis result provided some good details to demographic and other pertinent information that could be applicable to Des Moines and provide us some baseline on user demographic for target marketing perhaps.

2. Gender: The data profile indicated that out of the 2.34mil recorded rides from the data, 65% were male bikers. 

<img width="407" alt="Screen Shot 2022-06-06 at 9 51 46 PM" src="https://user-images.githubusercontent.com/98235755/172278591-7b63474a-0021-4dc4-9646-0829611c31de.png">

3. Checkout Times: Data indicated that users generally checked out bikes for less than an hour and that male users checked them out more than women's.

<img width="884" alt="Screen Shot 2022-06-06 at 9 33 58 PM" src="https://user-images.githubusercontent.com/98235755/172276782-2495b41a-6ca8-4dc7-8fc8-3610ecc7d0be.png">


<img width="872" alt="Screen Shot 2022-06-06 at 9 34 56 PM" src="https://user-images.githubusercontent.com/98235755/172276852-8d9173d6-bdaf-4ff1-bb18-9c215caba4de.png">


4. Bike Trips by day/hour and by gender: The most trips happened on Thursdays around 6 pm with almost 45k trips. Of which, 30k were trips by male bikers


<img width="560" alt="Screen Shot 2022-06-06 at 9 36 11 PM" src="https://user-images.githubusercontent.com/98235755/172277005-d56f9b6e-661a-4a0d-a41a-a70db28e2933.png">


<img width="1139" alt="Screen Shot 2022-06-06 at 9 36 31 PM" src="https://user-images.githubusercontent.com/98235755/172277026-830498b7-7db7-4bbb-b1bf-b03f582b4770.png">

5. Bike trips by User type and gender by day: It showed that Thursday had the most male subcribers trips with 259k trips.

<img width="349" alt="Screen Shot 2022-06-06 at 9 37 23 PM" src="https://user-images.githubusercontent.com/98235755/172277070-29029830-86a4-4c78-bcc1-2b0e8fcd7e68.png">

6. Trips by age group: By adding a calculated field to group the bikers by age group, I was able to identify that bikers in their 30s have done the most trips. Addtionally, a good chunk of subscribers were in their 30s. To my surprise though, the second highest bike trips were done by people in their 50s.


<img width="490" alt="Screen Shot 2022-06-06 at 10 02 43 PM" src="https://user-images.githubusercontent.com/98235755/172279832-a1629a5d-5de2-48f4-bd12-e81efaf067c8.png">

<img width="490" alt="Screen Shot 2022-06-06 at 10 02 43 PM" src="https://user-images.githubusercontent.com/98235755/172279930-100b5938-39eb-44f9-83e9-14001a03a274.png">


   **Refer to the [Tableau Bike Sharing - Des Moines Story](https://public.tableau.com/app/profile/dianne.malabanan/viz/BikeSharing-DesMoines/BikeShareDesMoinesSotry?publish=yes) to see the dashboards that were created for this analysis**

7. I think this dataset was a good basis of what to expect the demographics to be. If the business is to be established in Des Moines, I would be interested to see if there are any public data to see totals of tourists and bike sales around the area with demographic breakdowns. 


