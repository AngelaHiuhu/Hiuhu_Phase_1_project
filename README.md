TABLE OF CONTENTS
1. INTRODUCTION
2. BUSINESS UNDERSTANDING
3. DATA UNDERSTANDING AND ANALYSIS
4. CONCLUSION

1.INTRODUCTION
This analysis will describe airline risk assessment.

2. BUSINESS UNDERSTANDING
You are diversifying your business by entering new markets, and your primary interest is in buying and running aircraft for individual and commercial use. However, you are unaware of the possible hazards associated with aviation. It is your responsibility to ascertain which planes pose the least risk to the corporation when it launches this new venture. The next step is to turn your research into useful knowledge that the head of the new aviation division may utilize to inform his or her decision on which aircraft to buy.

3. DATA UNDERSTANDING AND ANALYSIS
SOURCE OF DATA
The National Transportation Safety Board supplied the data that we are utilizing for our research, which covers civil aircraft accidents and specific events in US and foreign waterways from 1962 to 2023.
https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses

DESCRIPTION OF DATA
We can get to see a brief description of some descriptive statistics of numerical columns in our data

Number.of.Engines	Total.Fatal.Injuries	Total.Serious.Injuries	Total.Minor.Injuries	Total.Uninjured
count	82805.000000	77488.000000	76379.000000	76956.000000	82977.000000
mean	1.146585	0.647855	0.279881	0.357061	5.325440
std	0.446510	5.485960	1.544084	2.235625	27.913634
min	0.000000	0.000000	0.000000	0.000000	0.000000
25%	1.000000	0.000000	0.000000	0.000000	0.000000
50%	1.000000	0.000000	0.000000	0.000000	1.000000
75%	1.000000	0.000000	0.000000	0.000000	2.000000
max	8.000000	349.000000	161.000000	380.000000	699.000000

as well as the columns in our dataset:

Event.Id', 'Investigation.Type', 'Accident.Number', 'Event.Date',
       'Location', 'Country', 'Latitude', 'Longitude', 'Airport.Code',
       'Airport.Name', 'Injury.Severity', 'Aircraft.damage',
       'Aircraft.Category', 'Registration.Number', 'Make', 'Model',
       'Amateur.Built', 'Number.of.Engines', 'Engine.Type', 'FAR.Description',
       'Schedule', 'Purpose.of.flight', 'Air.carrier', 'Total.Fatal.Injuries',
       'Total.Serious.Injuries', 'Total.Minor.Injuries', 'Total.Uninjured',
       'Weather.Condition', 'Broad.phase.of.flight', 'Report.Status',
       'Publication.Date'],
      dtype='object')

VISUALIZATIONS
C:\Users\USER\Desktop\Aircraft_images\output.png
This distribution of total minor injuries against Engine type.

C:\Users\USER\Desktop\Aircraft_images\output3.png
This visualization shows of total minor injuries against make column

C:\Users\USER\Desktop\Aircraft_images\output_1.png
This visualization shows total fatal injuries against number of engines

CONCLUSIONS
* As observed above we notice that the distribution of total fatal, total minor, total serious injuries and total uninjured are skewed. This means that the distribution of data is not normally distributed.
* The aircrafts Cessna, Piper, Boeing have the highest Total fatal injuries respectively.
* Aircarfts with the following engine types have the highest total fatal injuries: Reciprocating, Turbofan and turbo prop engines have the highest total fatal injuries while also having the highest number of minor injuries both in descending order.# Hiuhu_Phase_1_project
