# Maven-standalone-app
This is my first standalone application project structure build using Maven

PREREQUISITES:
Java Development Kit (JDK) version 17 or later (download from https://www.oracle.com/java/technologies/downloads/)
Maven version 3.8.6 or later (download from https://maven.apache.org/download.cgi)

STEPS:
1. Open your terminal from the folder where you have to create the project folder structure.
2. Enter the following bash code
   mvn archetype:generate \
  -DgroupId=com.yourcompany \  # Replace with your company's group ID
  -DartifactId=your-application-name \  # Replace with your application's name
  -DarchetypeArtifactId=maven-archetype-quickstart \
  -DinteractiveMode=false
3. This will create an .jar folder which can be deployed on any application hosting platform. 

PROJECT STRUCTURE:
The project is organized as follows:

src/main/java: Contains the source code for your application logic.
src/main/resources: Stores configuration files or other resources needed by the application.
src/test/java: Holds unit tests for your application code.
pom.xml: Defines the project configuration, dependencies, and build lifecycle.
target: This directory is generated during the build process and contains the compiled class files and the final JAR file (my-awesome-app.jar) for running the application.

CONTRIBUTING:
We welcome contributions to improve this project! If you'd like to contribute, please follow these guidelines:

Fork the repository on GitHub.
Clone your forked repository to your local machine.
Make changes to the code.
Write unit tests for your changes.
Commit your changes and push them to your forked repository.
Create a pull request from your forked repository to the main branch of this repository.
