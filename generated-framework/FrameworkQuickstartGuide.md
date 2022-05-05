# Quickstart Instructions
   

## Selenium & Rest Assured
NOTE: Full in depth guide can be found in src/test/java/selenium/Documentation/README.md
### Installation/Setup
1.	Extract the zip file delivered with this email
2.	Open cmd or terminal, navigate to your unzipped framework
3.	Run - “mvn validate”
### Run commands
* 	Run all the tests - “mvn clean verify -Denvironment=default”
* 	Run specific test by tag - “mvn clean verify -Dcucumber.filter.tags=”UITest” -Denvironment=default”
* 	Run all but ignore specific tests by tag - “mvn clean verify -Dcucumber.filter.tags=”not UITest” -Denvironment=default”      