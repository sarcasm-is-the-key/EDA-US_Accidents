# EDA-US_Accidents
Exploratory Data Analysis on  , 3 million dataset of US_Accidents(2016-2019).

Link of used DataSet:
https://www.kaggle.com/sobhanmoosavi/us-accidents

Contains Data for 49 States of US

Missing relevant Data for: New York.

Process Included:

1. Data Processing & Cleaning.

2. Filling or removing missing datasets as required.

3. Exploratory Analysis & Visualisation
General Analysis on Columns:

City,
Start Time,
Start lat, End lat
Temperature,
Weather Conditions,
Wind_Speed,
States

4. Asking & Answering of important questions.

5. Insights Drawn from dataset.

Insights:

No. of Rows = 2906610 & Columns = 47
Column Types are distributed as : bool(13), float64(13), int64(1), object(20)

By columns:

Cities:


There are only 7.3 k reported accidents for New York City

Looks like most of thr data for NYC is missing or accidents aren't reported.

Most cities have less than 2000 accidents

More than 10k accidents per city have very less no of cities(Density close to 0). i.e, most cities have less than 2000 accidents

No. of cities with accidents more than 1k = 513

No. of cities with accident less than 1k = 11,276

Total no. of cities = 11,790

1306 cities have less than or equal to 1 accident

5005 cities have less than or equal to 10 accidents

the No. of accidents per city decreases exponentially


Start_Time:

A high percentage of accidents are between 6a.m to 10 a.m(probably people are in hurry to get to work)

Maximum no of accidents are at 8 a.m

The next time for higher percentage of accidents is b/w 3:00 pm to 6:00 pm

No. of Accidents starts decreasing from 6:00 pm.

The no of accidents on week days are almost constant but it gets decreased at weekends.

On Weekends, the peak of percent of accidents is higher during afternoon(1 pm - 2p.m) unlike for weekdays.

The data for months show that: The wintery months have more trends for accidents. Do you think its relevant?

Looks like many data for 2016 is missing, and also for 2017.

Other than that, for moths in a year, trend is more like constant.

Start_Lat & Start_Lng:

More No. of accidents are seen to be occuring at coastal areas than on midland

Population of coastal areas are more than mid land maybe

The heat map is drawn by taking 1% of the total data, which is relevant to show details.


Temperature:

Temperature curve is normally distributed between -40 to 40 deg celcius

Looks like the maximum no. of accidents are at the temperature between 15-20 deg celcius or 60-80 Degree F which is kinda normal temperature.

The Temperature doesn't affect the happening of accidents as shown by the data.


Wind_Speed:

It can be seen that no of accidents are not much dependent on windspeed

Though there are some accidents at higher wind speeds, which can be cause as people might be affected by winds and got engaged in accidents.


States:

The most number of accidents are in the State(Top 5) :

California

Florida

Texas

New York

North Carolina Texas has more population than Florida, but the number of accidents show opposite trend.

States having more than 50k accidents are only 18

States having less than 50k accidents are 31

