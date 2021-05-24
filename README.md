# EclecticIQ-QA-Lead

[![Java CI with Maven](https://github.com/executeautomation/SeleniumWithCucucumber/actions/workflows/maven_new.yml/badge.svg?branch=master)](https://github.com/executeautomation/SeleniumWithCucucumber/actions/workflows/maven_new.yml)

~~~~
# Important
Make sure you have JAVA 8 or above installed to run this test
~~~~

### Technologies
    Jave
    Selenium
    Cucumber
    log4j2
    Maven

### Default properties
    Default.properties file can be found in the root directoy.
        Make sure you confirgure the webdriver path as for your OS(Windows/Mac).
        Define the browser type(CHROME/FIREFOX) as for your requirment. One browser can run at a once.
        Browser mode can be set to headless.

### Run Test
    To run all the test and generate report in target directory(cucumber-report-html)
        Run 'install' maven Intellij IDEA plugin or if maven is install locally run the below commond in the terminal by going to the root directory.
        'mvn clean install'

### Logs
Will be created under the **logs** directory

### Reports

######Overview
![img.png](img.png)

######Feature view with scenario and steps
![img_1.png](img_1.png)

######Example fail scenario
![img_2.png](img_2.png)
    