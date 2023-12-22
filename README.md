# Switch to "mainBranch" to view code

Deployment Instructions:
Prerequisites:
1. Download Java version 17
2. Download the Zip file, unpack it, and import it into Eclipse
3. Download the latest version of MySQL and MySQL Workbench version 8.0.31
4. Download MYSQL connector Jar and ensure it is in the build path of your project

Tomcat Local Host Server Installation:
1. Installing Apache Tomcat
a. Mac: Install Homebrew
b. Install Tomcat through Homebrew
2. Link Tomcat to Eclipse (Lab 1 instructions)

Spring Boot Installation:
1. Go to Eclipse
2. Click on help in the upper menu bar
3. Select Eclipse Marketplace
4. Search for Spring Tools 4
5. Click Download

Running Application Process:
1. Open MySQL Workbench and create a new schema titled StudySC.
2. Run the following script:
DROP DATABASE StudySC;
CREATE DATABASE IF NOT EXISTS StudySC;
USE StudySC;
3. Update the SQL passwords in the following files to your MySQL password:
SchedulePageREST.java, UserProfilePageREST.java, UserService.java,
applications.properties
4. After the local database is connected go and open the project in Eclipse. To run the
project, right click on the project name, select Run As, and select Spring Boot App.
5. Spring Boot will automatically generate necessary tables for the database.
