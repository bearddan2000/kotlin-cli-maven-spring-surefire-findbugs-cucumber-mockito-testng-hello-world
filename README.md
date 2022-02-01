# kotlin-cli-maven-spring-surefire-findbugs-cucumber-mockito-testng-hello-world

## Description
A POC for spring app using testng, cucumber, mockito,
and findbugs framework with surefire plugins.

Findbugs analyze source code for potential bugs.

This is a simple and trivial way to start:
  - kotlin
    - springframework
    - cucumber test runner for testng
  - cucumber
    - parameterized scenario
  - mockito
    - integration of testng
    - injection

## Tech stack
- kotlin
- maven
	- mockito
  - spring
  - testng
  - cucumber
  - surefire
  - findbugs

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Code concept](https://github.com/eugenp/tutorials/tree/master/testing-modules/testng)
