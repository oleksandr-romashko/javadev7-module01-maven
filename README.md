# Java Developer - Module 1 - Homework

## Task for Module 1

_Note: current repository is a solution using Maven:_

Create two projects - Maven and Gradle. Each project should:

* be packaged into an executable FatJar .jar file named `myname.jar` when running the `mvn package` and `gradle jar` commands for Maven and Gradle projects respectively
* when run by the `java -jar myname.jar` command, it should display your first and last name in English as JSON object in the console, separately first name and last name. For example `{"name": "Igor", "lastName": "Petrenko"}`. To generate a JSON string, use any third-party library from Maven Central (for example, GSON)
* each project must be located in a separate public github repository
* the project must have a correctly configured .gitignore file
* for the Gradle project, you must also configure the Wrapper (the Wrapper files must also be uploaded to Github)

The result of the homework is two links to github, to Maven and Gradle projects, respectively.

## Solution

1) Generate fat Jar using Maven installed on your machine, use command `mvn clean package` or using provided Maven wrapper `./mvnw clean package` (`mvnw clean package` in Windows). File `myname.jar` is generated and located in `target` directory.
2) From `target` directory, run ` java -jar ./myname.jar` to run the program and print name.