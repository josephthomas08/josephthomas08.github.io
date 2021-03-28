# Plotly Deploy
Belly button analysis 


## PROJECT OVERVIEW

Plotly data analysis of Belly buttons is a research project where bacterial samples of number of volunteers were taken to identfy which sample is ideal to produce synthetic beef.
The intent of the research is to use the samples taken from the belly buttons of the volunteers to match with the right bacteria from which lab beef could be produced.


The bacterial samples have been accumulated on the web page in order to provide ease of access to each volunteer to possibly see the Top 10 bacterial types found in their belly buttons. Once the specific bacteria is identified to make synthetic beef then the volunteers can check their own Top 10 bacterias whether they match with the identified bacteria. Volunteers can select their :


##### 1. 'ID' number from drop down menu under "Test Subject Id No:". 
##### 2.Once ID is selected, the relevant bacterial cultures in bar and bubble charts are displayed. 
##### 3.The volunteers can also see their "Belly Button washing frequency" on the guage chart.

## 1. Deliverable 1 

#### 1. Code is written to create the arrays when a sample is selected from the dropdown menu 

Code as drafted in the charts.js file in the repositary. 
#### 2. Code is written to create the trace object in the buildCharts() function, and it contains the following: 

Code as drafted in the charts.js file in the repositary. 
##### 2.1. The y values are the otu_ids in descending order
##### 2.2.The x values are the sample_values in descending order
##### 2.3.The hover text is the otu_labels in descending order.
#### 2. Code is written to create the layout array in the buildCharts() function that creates a title for the chart 


Code as drafted in the charts.js file in the repositary. 


#### 3. When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard, and the bar chart has the following: (10 pt)
##### 3.1The top 10 sample_values are sorted in descending order
##### 3.2 The top 10 sample_values as values
##### 3.3 The otu_ids as the labels

Images provided below shows 3.1, 3.2, 3.3 for ID 940 and few other IDs -ID958, .


<img width="1652" alt="Screen Shot 2021-03-21 at 1 54 44 PM" src="https://user-images.githubusercontent.com/75267605/111915983-3fa8ab00-8a4f-11eb-8b7e-3924878c21c6.png">




<img width="1670" alt="Screen Shot 2021-03-21 at 2 11 52 PM" src="https://user-images.githubusercontent.com/75267605/111916026-754d9400-8a4f-11eb-962a-9305cf48fef1.png">




<img width="1647" alt="Screen Shot 2021-03-21 at 1 55 16 PM" src="https://user-images.githubusercontent.com/75267605/111915952-15ef8400-8a4f-11eb-95cb-bd7e4762d971.png">





<img width="1655" alt="Screen Shot 2021-03-21 at 1 55 46 PM" src="https://user-images.githubusercontent.com/75267605/111915908-e17bc800-8a4e-11eb-8584-3a507eef7518.png">



## 2. Deliverable 2 


####  2.1 The code for the trace object in the buildCharts(); function does the following:
##### 2.1.1 Sets the otu_ids as the x-axis values
##### 2.1.2 Sets the sample_values as the y-axis values
##### 2.1.3 Sets the otu_labels as the hover-text values
##### 2.1.4 Sets the sample_values as the marker size
##### 2.1.5 Sets the otu_ids as the marker colors



<img width="1140" alt="Screen Shot 2021-03-21 at 2 28 28 PM" src="https://user-images.githubusercontent.com/75267605/111917943-f0677800-8a58-11eb-8552-16b09a69d724.png">




####  2.2 The code for the layout in the buildCharts(); function does the following: 
##### 2.2.1 Creates a title
##### 2.2.2 Creates a label for the x-axis
##### 2.2.3 The text for a bubble is shown when hovered over
##### 2.2.4 When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard. All three charts should also be working according to their requirements when a sample is selected from the dropdown menu 




<img width="1672" alt="Screen Shot 2021-03-21 at 3 13 12 PM" src="https://user-images.githubusercontent.com/75267605/111917963-0f660a00-8a59-11eb-8679-3cd6df819275.png">




<img width="1597" alt="Screen Shot 2021-03-21 at 3 12 38 PM" src="https://user-images.githubusercontent.com/75267605/111917959-06753880-8a59-11eb-99aa-97be13d44f23.png">







## 3. Deliverable 3 Requirements


#### 3.1The code to build the gauge chart does the following: 
##### 3.1.1 Creates a title for the chart.
##### 3.1.2 Creates the ranges for the gauge in increments of two, with a different color for each increment.
##### 3.1.3 Adds the washing frequency value on the gauge chart.
##### 3.1.4 The indicator shows the level for the washing frequency on the gauge.
##### 3.1.5 The gauge is added to the dashboard.
##### 3.1.6  The gauge fits in the margin of the <div> element.
 

  
<img width="711" alt="Screen Shot 2021-03-21 at 3 45 40 PM" src="https://user-images.githubusercontent.com/75267605/111920878-daad7f00-8a67-11eb-992b-8c7bdd3630b1.png">





 <img width="1664" alt="Screen Shot 2021-03-21 at 3 47 20 PM" src="https://user-images.githubusercontent.com/75267605/111920897-f4e75d00-8a67-11eb-8842-7c2d84579eb3.png">


  
  
#### 3.2 When the webpage loads, the bar and bubble chart are working according to the requirements in Deliverable 1 and 2, respectively, and the gauge chart is working according to the requirements listed for this Deliverable 


<img width="1666" alt="Screen Shot 2021-03-21 at 3 56 00 PM" src="https://user-images.githubusercontent.com/75267605/111920906-0af51d80-8a68-11eb-9ef7-4bca82ba6425.png">





## 4. Deliverable 4 

#### 4.1The webpage has three customizations. 


Yes as advised three customization for the layouts was done and visible the charts.js 


#### 4.2 When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard, and all three charts should be working according to the requirements when a sample is selected from the dropdown menu 


<img width="1098" alt="Screen Shot 2021-03-21 at 5 13 07 PM" src="https://user-images.githubusercontent.com/75267605/111921024-bf8f3f00-8a68-11eb-9db1-f2fd44e7f89c.png">





<img width="1142" alt="Screen Shot 2021-03-21 at 5 00 44 PM" src="https://user-images.githubusercontent.com/75267605/111920953-590a2100-8a68-11eb-8c1a-05bd2f797274.png">





<img width="1165" alt="Screen Shot 2021-03-21 at 5 01 13 PM" src="https://user-images.githubusercontent.com/75267605/111920999-9ec6e980-8a68-11eb-87b4-4e72566bd2c0.png">









