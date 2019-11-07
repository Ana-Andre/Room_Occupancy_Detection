<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Room Occupancy Detection

Ana André, Data Squad 21
Lisbon, 30.09.2019

## Content
- [Project Description](#project-description)
- [Motivation](#motivation)
- [Dataset](#dataset)
- [Workflow](#workflow)
- [Links](#links)


<a name="project-description"></a>
## Project Description

The scope of this project was to predict whether a room in an office building is occupied or not, using sensor records for temperature, humidity, light, and carbon dioxide levels inside the room. This information can then be integrated in the HVAC control systems and used to improve their algorithm and performance, promoting the building's energy efficiency and sustainability.

I developed this project as an Ironhack's data analytics bootcamp student. The aim of the project was to choose a topic and implement a solution using a supervised machine learning algorithm. For more details about the context and/or the requirements to meet, please check folder [0_Context](https://github.com/Ana-Andre/Room_Occupancy_Detection/tree/master/0_Context).

To analyze the data, I used Python libraries such as Pandas, Numpy, Matplotlib and Seaborn. For the prediction, I built a classifier with Scikit-Learn library.


<a name="motivation"></a>
## Motivation

Energy efficiency in buildings has been a hot topic for quite a while now both for sustainability and cost reasons.
Literature states that the accurate determination of room occupancy detection can lead to energy savings up to 30 to 40 % which can mean a lot in terms of money and CO2 emitions.
So designing smart buildings, buildings able to adjust to user's needs in real time, is the path we want to follow.


<a name="dataset"></a>
## Dataset

I got the [dataset](https://archive.ics.uci.edu/ml/datasets/Occupancy+Detection+#/) from the University of California's repository for machine learning.
It results from an experiment that monotorized 4 environmental measures over time:
- temperature
- humidity
- light
- CO2 concentration.
20560 instances for each feature.
There is also a label feature to specify the room occupation (1 for occupied, 0 for non-occupied).


<a name="workflow"></a>
## Workflow

1. Collect the data
2. Explore the data
3. Train and test the models
4. Evaluate the models
5. Feature selection
6. Conclusions

<a name="links"></a>
## Links

[Repository](https://github.com/Ana-Andre/Room_Occupancy_Detection)  
[Presentation](https://bit.ly/2orZj8z)  
[Trello](https://trello.com/b/2WM1FlgO/project-6)  
[Dataset](https://archive.ics.uci.edu/ml/datasets/Occupancy+Detection+#)