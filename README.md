# spliwiseapp
Splitwise application 
Splitwise is a useful website dedicated to helping groups of people split up bills. Multiple users can log on, create a bill, add expenses to the bill, indicate who has already paid what, and choose how different things should be split up. It's a useful tool, and a complex piece of machinery!
Add bills and checks, split the costs, and pay back you friends for outings, dinner groceries, or the movies. AllSet! keeps track of who owes what and divides up the bill for you!


## Installation steps:
 
To install json-server use following command
``` 
npm install -g json-server
```
Steps to launch an application:

The easiest way to get started is to clone repository
```
$ git clone https://github.com/devnigam24/Splitwise.git
 ```
                    	OR
Download the zip file from above repository and Unzip it.
 
Open another command prompt terminal and change to directory where ‘Splitwise’ project is located. Go to ‘splitwise-app’ folder. To generate node-modules run following command.
```
npm install
bower install 
 ```
Open another command prompt terminal and change to directory where ‘Splitwise’ project is located. Go to ‘serverSide’ folder where you have the db.json file. To start json-server use following command.
``` 
json-server --port=3009 --watch db.json
After this command runs successful, open “http://localhost:3009/”
```
Open a new command prompt terminal and change directory ‘serverSide’ of project folder. To start Node server use following command.
```
node nodeServer.js
```
Open a new command prompt terminal and change directory ‘splitwise-app’ of project folder. To start Node server use following command
``` 
ember server --proxy http://localhost:3000
```
