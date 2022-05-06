Coverage: 34%
# IMS Week 5 Project

An application that functions as an IMS (Inventory Management System) so that an end user can keep a record of customers, items and orders.
It is designed to be run through a CLI (Command Line Interface). 

JIRA: https://rayyana.atlassian.net/jira/software/projects/W5P/boards/2 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

You will need Java and MySQL in order to run this application and use the associated database. 
You will need to download the Java Installer, as well as the MySQL installer to install Java-16 and the latest version of MySQL.
You will also need JUnit to run the tests, Maven to create a build of the application and Eclipse to manage any code.


### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

Run the Installer for the applications and install the file in Program Files in your Home Directory. 
Press the Windows button and type "path" into the search field, then select "Edit the system environment variables".
Click on Environment Variables and then create a NEW system variable. 
Call the variable 'JAVA_HOME', 'MYSQL_HOME' etc. depending on the application, and point it towards the corresponding folder. 
Now EDIT the 'path' system variable to include a reference to the /bin (binary files) folder in our JAVA_HOME. 
Create a new variable called %MYSQL_HOME%\bin or append %JAVA_HOME%\bin to the path variable. 
Click OK recursively until all system windows are closed.



## Running the tests

Explain how to run the automated tests for this system. Break down into which tests and what they do

To run the tests, open the project folder in Eclipse, and navigate to a class in the src/test/java.
Select Run As JUnit Test when you have found the class you wish to test.  
This will run the tests to make sure the app is working, and will let you know if any test is failing.

### Unit Tests 

Explain what these tests test, why and how to run them

The unit tests are assessing whether or not the created code is able to produce the expected result when given a know input. 
If the code doesn't give us the expected output, we know something has gone wrong that needs fixing. 


### Integration Tests 
Explain what these tests test, why and how to run them

Integration Testing is usually the next step after unit testing, once the functionality of the individual components is confirmed.
We verify that the functionality of the combined methods and modules. The approach to do this varies. 
It is used to assess whether components can successfully rely on each other to carry out a function.

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Maven is used to package the application into a fat.jar (a usable format)
To deploy the application in a live system, open a Command-Line in the target directory. 
Enter -mvn clean and then -mvn package.
Go into the target directory and enter 'java -jar maven' along with the name of the file. 
The application should open in a command-line, ready to be used.




## Built With

* [Maven](https://maven.apache.org/) - Dependency Management

## Versioning

We use [SemVer](http://semver.org/) for versioning.

## Authors

* **Chris Perrins** - *Initial work* - [christophperrins](https://github.com/christophperrins)

## License

This project is licensed under the MIT license - see the [LICENSE.md](LICENSE.md) file for details 

*For help in [Choosing a license](https://choosealicense.com/)*

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
