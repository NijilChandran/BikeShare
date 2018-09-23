# BikeShare 
A webapp on AWS - Linear regression to predict number of bikes that will be rented based on day /time of the year.

Steps for Deploying to aws with elasticbeanstalk:

1) Download /clone the code
2) from the location of application.py 
 
 	$ eb init -i (follow along the prompt for creating a unique <projectname>, awskeypair if you want to ssh)   
 
	 $ eb create <projectname>
 
 	$ eb open <projectname>
 
 After completion don't forget to terminate.
 
 	$ eb terminate <projectname>

Assumptions:
 You have an aws account. awscli and awsebcli are installed. 
 
 Based on book Monetizing Machine Learning by Amunategui, Manuel, Roopaei, Mehdi 
https://www.apress.com/us/book/9781484238721
