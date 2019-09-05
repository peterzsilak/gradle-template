# "Template" for API testing project

## Todo
Update the "template" project name in the following files:
- README.md
- settings.gradle
- logback.xml
- application.properties

and the project package name.

## Technologies
- Gradle
- Spring Boot / Spring Boot Test
    - Hamcrest and AssertJ 
    - JUnit 4.12 excluded
- Junit 5

# Running

```gradle clean test```

Without any parameters the project will run with "dev" profile. 
But you can specify another target environment ( dev | tst | prd ) with the "springProfiles" param.

```gradle clean test -PspringProfiles=dev```