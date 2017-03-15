# Capstone Proposal Haotian Zhang

## Project Track
__Track 1 - Data Mining and Analysis System for Cloudacl__

## Project Objective:

* Building a data pipeline with the functionalities including but not limited to data processing, data storage and data visualization.

* Extracting data features and making recommendations based on the results

## Project Introduction:
Cloudacl is the leading provider of security and infrastructure service
that make the Internet safer through integrated Web content filtering. It provides
plugin for Chrome, Firefox, and mobile app for android and iPhone. Every
browser request will go through our cloud service and will be classified according
to customized policy. Our cloud service capture every browsing request including
ip, timestamp, url and category of the url.

## Team Members:
Chen Zhiting

Haotian Zhang

Song Yu

Sun Yang

Tianyang Lin

## Data Format:
Web Log

### Sample Data:
~~~~
179.39.12.146 - - [05/Mar/2017:00:00:00 +0000] "GET /axis2/services/WebFilteringService/getCategoryByUrl?app=chrome_antiporn&ver=0.19.7.1&url=https%3A//openload.co/stream/6fF2Dk85Wqw%7E1488758111%7E179.39.0.0%7E99LJRJZj%3Fmime%3Dtrue&cat=unknown HTTP/1.1" 200 134 "-" "Mozilla/5.0 (Windows NT 6.3) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/56.0.2924.87 Safari/537.36"
~~~~

## Draft Proposal

Functionalities:

1. Basic data processing and visualization

The project can realize functions such as:
- Group by IP address, seeing what are the websites a certain user likes to visit.
- Group by URL, seeing what are the most popular URLs.
- Group by time, seeing at which time slot enjoys most Internet surfers. 

A user can see the data he wants to see by customizing his filtering or aggregation preferences.

2. Further data mining

(1) Locality Sensitive Hashing
Find similar users.
Find similar URLs.

(2) Recommendation
Recommend URLs to users that he or she potentially has interest in

(3) Advertising
By figuring out the hehavior of the user IP according to the web visiting history, we can come out with web advertising strategies.


## Timeline:

1. Week 1 (Mar 19) - Brainstorming and making plans to the project.
	* Interpret data format
	* Research industrial performance for the expected data system
	* Find suitable techniques to extract valuable data
	* Explore possible services and technical stacks for the project
	* Distribute tasks to team members
  
2. Week 2 (Mar 26) - Building Data Management System
	* Build data pipelines, including message queue, data storage and data processing models
	* Ensure the system meet industrial performance requirements and industry practices
 
3. Week 3 (Apr 2) - Improvement and Customization
	* Develop data set processes for data modeling, mining and production
	* Create custom software components (e.g. specialized UDFs) and analytics applications
	* Employ data visualization to data reports
  
4. Week 4 (Apr 7) - Finishing project
	* Collect performance report
	* Create project doc
	* Make slides for presentation
