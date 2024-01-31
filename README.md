# Core Spring and Spring Boot Lab Projects

Labs for the Core Spring and Spring Boot courses

To import these labs into your IDE, import the parent pom `lab/pom.xml` as Maven projects or `lab/build.gradle` as Gradle projects.

**Lab Setup**


Once you have downloaded the file, unzip it under a directory of your choice. The unzipped directory core-spring-labfiles/lab contains the lab projects.

**Install Required Software:**

Java 11:

	Oracle Java 11 - https://jdk.java.net/java-se-ri/11-MR2
	Open JDK Installations - https://www.oracle.com/java/technologies/downloads/#java11

REST client

	curl or - https://curl.se/download.html
	Postman - https://www.postman.com/downloads/


**Build the Projects**

Build the projects under core-spring-labfiles/lab directory. 
This will download and install required dependencies to local repository.

Windows:

	mvnw clean install

MacOSX or Linux:

	chmod 755 mvnw
	./mvnw clean install

If you experience any build failure, check firewalls or proxy settings in the <Home-Directory>/.m2/settings.xml file.



**Choose an IDE**

	Spring Tools 4 (STS)
	JetBrains IntelliJ

The Spring Tools 4 (STS) is a free IDE built on the Eclipse Platform with additional plugins to support Spring, Aspect Oriented Programming and the Tanzu Application Service deployment platform.


**Import Projects Into Your IDE**

Import the projects in core-spring-labfiles/lab into your IDE. You can import them as either Maven or Gradle projects.

For STS, you can perform "Import" from the lab directory, which will import the projects underneath it.

For IntelliJ, you can perform "Import Projects" via the parent pom.xml or build.gradle, and IntelliJ will automatically set them up as a multi-module project.

Verify that the projects are imported correctly.

**Review the Using TODO Tasks article.**

Troubleshooting
After importing the lab projects, your IDE may report errors, typically related to project dependencies. You can resolve these issues using the following techniques:

For STS:
Select all projects, right-click, Maven, Update Projects.
Clean all selected projects
Close & Open all projects


**Configure TODOs in IntelliJ**

In the IntelliJ IDE, the TODO tasks can be enabled in a couple of steps.

Locate the TODO panel button in the lower left corner of the IDE work area and click it. Alternatively, use the shortcut Alt+6 or ⌘+6 on Mac.

Locate the Group By Modules button on the left menu of the TODO area and click it. Alternatively, click Alt+M or ⌘+M* on the Mac.

From here, you can locate the module for the current lab you are working on and expand that and the files below the module you expanded to see all the related TODO steps for that module.

Guidelines to using TODOs as Quick Instructions
Each TODO will have a header referenced in the lab instructions. If you wish to review the associated detailed instructions, you may find on the associated lab instruction page on the course site.

It is critical to follow the TODO steps in the order they appear. Do not jump ahead to later TODOs in the same file or some features of the lab won’t work as described.

