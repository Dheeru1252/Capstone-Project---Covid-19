# Capstone-Project-Covid-19


# Problem Statement:
Given data about COVID-19 patients, write code to visualize the impact and
analyze the trend of rate of infection and recovery as well as make predictions
about the number of cases expected a week in future based on the current
trends.


# Dataset:
CSV and Excel files containing data about the number of COVID-19 confirmed
deaths and recovered patients both around the world and in india.

# Task to be done:
● Use pandas to accumulate data from multiple data files.
● Use plotly (visualization library) to create interactive visualizations.
● Use Facebook prophet library to make time series models.
● Visualize the prediction by


1. Introduction:
   
Coronavirus disease 2019 (COVID-19) is a contagious disease caused by the virus SARS-CoV-2. The first known case was identified in Wuhan , China, in December 2019. The disease quickly spread worldwide, resulting in the COVID-19 pandemic.

The symptoms of COVID‑19 are variable but often include fever, cough, headache, fatigue, breathing difficulties, loss of smell, and loss of taste. Symptoms may begin one to fourteen days after exposure to the virus.

At least a third of people who are infected do not develop noticeable symptoms. Of those who develop symptoms noticeable enough to be classified as patients, most (81%) develop mild to moderate symptoms (up to mild pneumonia), while 14% develop severe symptoms (dyspnea, hypoxia, or more than 50% lung involvement on imaging), and 5% develop critical symptoms (respiratory failure, shock, or multiorgan dysfunction). Older people are at a higher risk of developing severe symptoms. Some people continue to experience a range of effects (long COVID) for years after infection, and damage to organs has been observed. Multi-year studies are underway to further investigate the long-term effects of the disease.


2. Loading libraries and Dataset:
   
   Pandas
   Matplotlib
   Seaborn
   Sklearn
   Plotly
   Prophet


3. Interpreting the Dataset:

   - First five records..
  
     ![image](https://github.com/Dheeru1252/Capstone-Project---Covid-19/assets/115200521/52243b70-f586-4fff-9c9b-405edbe5231e)

4. EDA - Exploratry Data Analysis:

   - in EDA we are doing the first investigation aboout the datasets, like missing values, duplicated values etc.
  
     - Null values in datasets.
       
      ![image](https://github.com/Dheeru1252/Capstone-Project---Covid-19/assets/115200521/b99f0183-611a-40d7-b8ee-df5e3304ab2b)

    - Duplicated Values in datasets.

      ![image](https://github.com/Dheeru1252/Capstone-Project---Covid-19/assets/115200521/b4b666cd-d581-4269-970c-0bdaf8aac0ec)

5. Visualizing the Data:

    - How Covid Spread.. by Graph Confirmed cases around the world

       ![image](https://github.com/Dheeru1252/Capstone-Project---Covid-19/assets/115200521/dd7f4052-940c-4d69-980b-0ed9980ba1cb)

    - Top 10 Countries having Active cases.
  
       ![image](https://github.com/Dheeru1252/Capstone-Project---Covid-19/assets/115200521/451ba94f-cbec-4004-963e-165bdb6d1117)

    -  Top 10 Countries having confirmed Cases.
  
       ![image](https://github.com/Dheeru1252/Capstone-Project---Covid-19/assets/115200521/16557795-ded6-471f-bc8b-e3494897b4fb)

    -  Top 10 Countries having recovered Cases.
  
       ![image](https://github.com/Dheeru1252/Capstone-Project---Covid-19/assets/115200521/6281b23f-0cbd-4c33-83ca-37b6b5a4cceb)

    -  Combined veiw into graph to see the confirmed covid case.
  
       ![image](https://github.com/Dheeru1252/Capstone-Project---Covid-19/assets/115200521/56d71a14-6f23-4e9d-a6d0-bccf7cee316b)


    -  Combined veiw into graph to see the confirmed covid case.
  
       ![image](https://github.com/Dheeru1252/Capstone-Project---Covid-19/assets/115200521/b74376d0-7358-4db5-920f-5405d6722799)

    -  Combined veiw into graph to see the deaths covid case.
  
       ![image](https://github.com/Dheeru1252/Capstone-Project---Covid-19/assets/115200521/6f0364d8-1cf7-40b3-b215-0dd1e772596e)

    -  Combined veiw into graph to see the recovered covid case.
  
       ![image](https://github.com/Dheeru1252/Capstone-Project---Covid-19/assets/115200521/fbe9c97a-4ccd-4ba2-ad97-f73e4ce65e4a)

  6. Modelling - Predictive Modeling:

     # Forcasting the Confirmed Covid19 Cases for 7 days from 2020-07-28 to 2020-08-03


      ![image](https://github.com/Dheeru1252/Capstone-Project---Covid-19/assets/115200521/e69a5457-4313-4421-be6e-e5a4b865be0d)

 
       # Plotting the forcaseted data

      ![image](https://github.com/Dheeru1252/Capstone-Project---Covid-19/assets/115200521/b792ff97-34ee-4bc7-8b6b-fbdc19af6cdb)

     # Ploting the Forcasting Data of Yearly and Weekly Trends 7 days with orignal Confirmed Covide 19 Cases.

      ![image](https://github.com/Dheeru1252/Capstone-Project---Covid-19/assets/115200521/2b1b3957-ff3c-445b-8a26-5e675790d206)

     # Forcasting the Active Covid19 Cases for 7 days from 2020-07-28 to 2020-08-03

     # Predicting the forcast cases for next 7 days of Active Covid19 Cases.

       ![image](https://github.com/Dheeru1252/Capstone-Project---Covid-19/assets/115200521/9aa05cb3-be4b-456c-ad2d-62d1bfbb2a5d)

     # Ploting the Forcast 7 days with orignal Active Covide 19 Cases.

       ![image](https://github.com/Dheeru1252/Capstone-Project---Covid-19/assets/115200521/aa77f47d-0bab-47c1-ac35-549ce91346ec)

     # Ploting the Forcast Data of Yearly and Weekly Trends 7 days with orignal Active Covide 19 Cases.

      ![image](https://github.com/Dheeru1252/Capstone-Project---Covid-19/assets/115200521/81fb315b-d058-4c28-858a-4546ebc3293f)

     # Forcasting the Deaths Covid19 Cases for 7 days from 2020-07-28 to 2020-08-03

       -  Predicting the forcast cases for next 7 days of Deaths Covid19 Cases.

       ![image](https://github.com/Dheeru1252/Capstone-Project---Covid-19/assets/115200521/81212c61-2e62-45b0-9cfa-2eadf5e6b6d9)

       -  Ploting the Forcast 7 days with orinal Deaths Covide 19 Cases.

       ![image](https://github.com/Dheeru1252/Capstone-Project---Covid-19/assets/115200521/ff8f0b68-8f02-4481-b4e6-c1ebb0839099)

       -  Ploting the Forcast Data of Yearly and Weekly Trends 7 days with orignal Deaths Covide 19 Cases.

       ![image](https://github.com/Dheeru1252/Capstone-Project---Covid-19/assets/115200521/58b174b0-5224-46ae-8627-005a51737099)

       # Forcasting the Recovered Covid19 Cases for 7 days from 2020-07-28 to 2020-08-03
      
       -  Predicting the forcast cases for next 7 days of Recovered Covid19 Cases.

       ![image](https://github.com/Dheeru1252/Capstone-Project---Covid-19/assets/115200521/e874d79c-ae51-4b75-85b5-edabe4b51ec2)

       -  Ploting the Forcast 7 days with orinal Recovered Covide 19 Cases.

       ![image](https://github.com/Dheeru1252/Capstone-Project---Covid-19/assets/115200521/98b1bf45-6045-4e00-91f8-fbe4fdfeaf2e)

       -  Ploting the Forcast Data of Yearly and Weekly Trends 7 days with orignal Recovered Covide 19 Cases.

       ![image](https://github.com/Dheeru1252/Capstone-Project---Covid-19/assets/115200521/f6648553-432b-4a7d-a647-4a0a7130aeda)


       7. Conclusion:

       #After perfoming the future perdiction for 7 day's I have got that the covid 19 cases for Active, Recovered, Confirmed and Deaths cases
       will be increasing as the as the period is increasing until we have any medicine to stop or prevent these pendiemic.

   
