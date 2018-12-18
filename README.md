# RESTful APIs Automation test using Rest Assured 
## Pre-requisite
1. Java above 1.8.
2. Maven version above 3.0.
3. Api should be running on local machine on localhost i.e. `http://localhost:51544`
## How to install & Run using command prompt
1. Please extract the project at your desired path.
2. Go to `src/test/resources/application.properties` file and update configurations. 
	* Update `{host URL}/v1/orders` in application.properties file ,i.e. where api is hosted  e.g. {host URL}=`localhost:51544`
  #Please Enter `present` and `future` to run test cases for Order place in Present and future
##How to install & Run using command prompt
1.  Please extract the project at your desired path.
2.  Open the command prompt and go to the project path.
3.  Run the command "mvn clean install test"
4.  All the automated test cases will be executed.

Note: Test cases are available in TestCases.xls for your reference.

