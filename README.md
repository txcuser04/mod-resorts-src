# ModResorts Demo Application

## About
This version of the application has been migrated from IBM WebSphere Application Server 9. It contains all the changes needed for the application to run on Liberty.
Additionally, the application has been upgraded from Java 8 to Java 21.

## Building and Running
Application can be build with standard Maven lifecycle commands:

```
mvn clean package
```

The Liberty maven plugin is added to the pom.xml to facilitate running of the application in your development environment.

## Dependencies
Application has dependencies on a DB2 database and IBM MQ queue manager as described in the server.xml, but these are not currently used.

VS Code experiment