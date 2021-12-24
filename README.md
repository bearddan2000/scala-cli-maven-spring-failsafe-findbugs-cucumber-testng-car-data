# scala-cli-maven-spring-failsafe-findbugs-cucumber-testng-car-data

## Description
Analyze source code for potential bugs.
A POC for spring app using testng
and cucumber framework with failsafe and
surefire-findbugs plugins.

## Tech stack
- scala
- maven
	- findbugs
  - spring
  - testng
  - failsafe
  - surefire
  - cucumber

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- findbugs report at bin/target/findbugs

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code concept](https://stackoverflow.com/questions/67847818/maven-junit-5-cucumber-not-running-tests)
- [Parameter Type code base](https://thepracticaldeveloper.com/cucumber-guide-3-step-definitions-state/)
