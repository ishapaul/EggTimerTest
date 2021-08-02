# EggTimerTest
This Automation project validates the Countdown Functionality of the eggtimer website based on the input time fed by the user. Validation incudes whether the countdown is successful and remaining time decreases in 1 second decrements.

# Highlights
1.Page Object Model used for designing the object repositories and tests
2.Parameterization and Sequence of Execution using TestNg Annotations
3.BDD layer added with Cucumber Feature File and Step Definitions
4.Tests can be run using TestNg XML file after importing project

# Improvements
BDD Approach could be enhanced using Cucumber Step Definitions 

# Tools
1.Maven
2.Cucumber-JVM
3.TestNG
4.Selenium Webdriver

# Dependencies
In order to utilise this project you need to have the following installed locally:
Maven 3
Chrome and Chromedriver (Tests use Chrome by default, can be changed in TestNGRunner.xml)
Java SE 16.0.2

# Usage

To run the tests using TestNg, import the project to an IDE(e.g. Eclipse)-> Right click on the TestNGRunner.xml -> Run as TestNGSuite

To run the tests using maven, navigate to EggTimerTest directory and run:

mvn clean install







