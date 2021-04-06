# Liquibase tutorial

Simple spring boot application to test the use of Liquibase. 
The idea is to run the app where the liquibase data will be imported. It uses a h2 database in memory and 
executes the files located at resources/db/changelog directory. 

Once the app is running, to verify the changes, go to
```bash
/h2-console
```
To access just provide the credentials located at application.properties. 
To see what has been changed, select table changelog.

## Installation

Use maven simple build
```bash
mvn clean install
```

To run the project use:
```bash
mvn spring-boot:run
```

