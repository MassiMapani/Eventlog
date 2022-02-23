# Eventlog
This project takes the path of a text file that contains logs and calculates the time taken for an event to finish. It is not a complete solution and just provides the skeleton/file structure for the project

## Prerequisites
- IDE (using Visual Studio and/or IntelliJ Webstorm for MacOS)
- Java 8 (Oracle Java SE jdk-8u311-windows-x64 or jdk-8u311-linux-x64.rpm for macos) Please make use of the [documentation](https://docs.oracle.com/javase/8/docs/) 

    Please run the following to check your version of Java is installed correctly
    
        ``` $ java -version
        
            $ java version "1.8.0_121"
        ```

- Gradle 7.4
- Git Bash is recommended not essential
- Maven 3.3+ require JDK 1.7 and above which can be downloaded from [here](https://maven.apache.org/download.cgi)
- Some decent Java and gradle knowledge base is assumed

### Notes
If your Operating system is windows 7 or later; please enable 'Developer Mode' in the following path: 

Settings -> Update & Security -> For developers -> Developer Mode (Enable in slider)

Ensure to enable Linux through the control panel with the following steps 

Control Panel -> Programs -> Turn windows feature on or off -> Checkbox for 'Windows Subsystem for Linux' 

This will allow you to use most linux commands from terminal/Command Prompt or Git Bash on windows instead of using a Virtual Machine to make use of Linux functions

#### Windows

Environment Variables can be accessed and set from the Control Panel, including the path for Java. If you experience an error 'Java' is not recognized as an internal or external command, please follow steps 1 - 11 from answer in the following [link](https://stackoverflow.com/questions/15796855/java-is-not-recognized-as-an-internal-or-external-command)

### Running Project
 Once all necessary software is installed and the repository is cloned, run the following command

 ```  gradle build  ```

 This will build the project. Once complete, use the following command

 ```  gradlew tasks  ```
 
This will provide the list of tasks present for a cache build. From this point on, coding for the logic provided in the Report can be done.
