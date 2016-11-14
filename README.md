# sample-mvn

### Building WAR file

1. Install Maven (tested with 3.2.3)

2. Run maven package goal:

```
cd <project root>
mvn package
```

this will generate a WAR file in `<project root>/target/samplemvn-0.0.1.war`

### Deploying WAR to Tomcat

Copy the WAR file into `<tomcat root>/webapps` and restart tomcat.
