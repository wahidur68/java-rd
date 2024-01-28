## Commands

### Command for Generating target folder along with Jacoco code coverage report
mvn clean install
### Command to run sonar in docker
docker run --name sonar -p 9000:9000 sonarqube:lts-community
### command to generate Sonar Report
mvn sonar:sonar
### Download Jenlkins from this URL
https://updates.jenkins.io/download/war/

## Description About Tools

### Jacoco
**Type:**
- Code Coverage Library for Java

**Function:** 
- Jacoco instruments your Java code during compilation, tracking which lines of code are executed when you run your tests. This information is then used to calculate code coverage, a metric that shows how much of your code is actually tested.

**Benefits:**
- Identifies untested code areas, helping you focus your testing efforts.

**Limitations:**
- Limited to Java and requires specific integration with other tools.

### SonarQube
**Type:**
- Code Quality Platform

**Function:** 
- SonarQube analyzes your code base across various dimensions, including code coverage, code smells (anti-patterns), potential bugs, code complexity, and security vulnerabilities. It provides visualizations and reports to help you understand the overall quality of your code and identify areas for improvement.

**Benefits:**
- Improves code quality and maintainability, reduces bugs, and promotes secure coding practices.

**Limitations:** 
- Requires initial setup and configuration, learning curve for interpreting reports.

### Jenkins:

**Type:**
- Continuous Integration (CI) and Continuous Delivery (CD) Server

**Function:**
- Jenkins automates your software development lifecycle, including building, testing, and deploying your code. It can integrate with Jacoco and SonarQube to run code coverage analysis and quality checks automatically with each code change or commit.

**Benefits:**
- Increases development speed and agility, reduces manual work, and helps ensure consistent quality across releases.

**Limitations:**
- Requires expertise to configure and maintain, can become complex for large projects.