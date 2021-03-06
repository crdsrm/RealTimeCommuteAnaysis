## RealTimeCommuteAnaysis
Data engineering project on analysis about time spent by student in commute 

###Project Description and scope:

* The main idea is to track the students data travelling from home to school and from school to home and get an idea how much times is spent travelling. 
* Analytics we had in mind are showing the average time a student speding for travelling. 
* Average commute time for a particular school in a specific town. 
* Show the analytics in D3.js visualizations. 
* Real time tracking of student on google maps.

####Technology stack:

* Apache storm.
* Apache Kafka,Zookeeper.
* flask server.
* D3.js.
* MongoDb.
* python data generator.
* keen.io(Templates for showing data analytics)

###Current project status:

* Successfully created data generator and managed the data using kafka, Zoo keeper. In the end finished the data cleanup using Apache storm.
* Successfully calculated students average time spent in travelling for 5 different schools in one particular county.
* Successfully calculated average commute time for a specific school based on the number of students. 
* Successfully show the analytics using D3.js visualzation. 

###Future scope:

* Real time tracking of student on google maps. 
* This can be extend to office, any other location and give suggestions on the data collected. 
* Notifications if the student leaves school during school hours. 
* Dashboard for parents to track the time wasted in travelling. 
* Suggestions based on the collected data for the mode of transport for specific day. 

###Project Contribution:

#####[Upendra Sabnis](https://github.com/upensabnis/RealTimeCommuteAnaysis):

* Generated Data using java and handled the data using Apache kafka, Zookeeper.
* Cleaned and calcuated the analytics in Apache Storm.
* Finally Stored the data in MongoDB for data visualization.

#####[Piyush Patel](https://github.com/pipa0979/RealTimeCommuteAnaysis):

* Created Data Generator using python.
* Calculated analytics Euclidean Geomentry to find the distance between co-ordinates based on metrics like transport mode, time and coordinate locations.

#####[Dheeraj Chinni Ranga](https://github.com/crdsrm/RealTimeCommuteAnaysis):

* Created flask server to handle request from Html page. 
* Successfully retreived data from MongoDb and sent to Javascript(Most difficult part).
* Created D3 visualizations based on Json files received from flask.

