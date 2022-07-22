Maven

1. Build  Project 
   1. Parent Project: run command `mvn clean install` 
   2. Build child projects Admin/Web
      1. Please navigate into respective child project, for example if we want to build `Admin`, we will navigate into admin 
      by `cd admin` and run the clean build `mvn clean install`. Similarly we can do this for `Web` module.
2. Run Unit tests
   1. Parent Project: run command `mvn test`
   2. For child projects such as admin/web, please navigate into their respective repo and run the above command.
3. To Deploy the application to Tomcat via Cargo containers run command `mvn cargo:deploy` and to undeploy `mvn cargo:undeploy`

Gradle: 
1. Build Project
   1. Parent Project: run command `gradle clean build`. If `gradlew` is installed: 
      1. For Linux/Mac Users `./gradlew clean build`
      2. for Windows Users `.\gradlew clean build`
   2. Build Child Projects: To build child projects `Admin` or `Web` please cd into the respective module and execute the command in `1.i`
2. Run unit tests
   1. Parent Project: `gradle test` or if graldew is installed `.\gradlew test` for windows and `./gradlew test` for mac/linux
   2. Child Projects: `Admin` or `Web` please navigate to respective modules are run the above gradle test command.