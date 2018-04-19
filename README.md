# List of Technologies and Tools used in this framework:

1)Selenium Webdriver
2)Cucumber
3)Java Scripting
4)Maven
5)Application page was designed in Page Object Model and Page Factory for Object repository
6)AutoIT


# List of Test Scenarios written in this framework:

1)A new user registration(Test is incomplete because of captcha, captcha error validated)
2)Field validations for mobile number
3)Field validations for an email address
4)Field validations for Password
5)Password confirmation validation

# About the Framework:
•	Authentication password: In order to authenticate automation process, I have used another tool called AutoIT.Using AutoIT I have written a small script to handle the Windows authentication which is located in the 'util' folder under 'src/test/resources'. During the execution of test cases this 'AutoITscript.exe' gets called and executed and then the application test follows.

•	Cucumber Feature File: I have used Cucumber to implement BDD. Created Feature file(Registration.feature) under 'features' folder

•	Step Defs: Step definitions for cucumber files are written in 'RegistrationStepDefs.java' file.

•	POM & Page Factory: Registration page in the application is defined as a class. All the web elements and actions related to this page are defined in this class.

•	Runner File: In order to execute the test scripts we need to provide the tags in this file. We can use either scenario level tag or a feature level tag which are defined in the feature file. Also in this file, we will provide the glue for features, step defs and any plugins for the framework.

•	Base Page: In this page, we can define reusable actions that will be used across the framework.

•	Reports & Screenshots: After execution of the test scripts we can get the reports from target folder and can be viewed in a web browser. I have designed screenshots to be saved in the target folder and also for failure scenarios a screenshot along with the current URL is embedded in the report for reference.

#  If time permits:
   # Framework related improvements:
        •	Multi-browser compatibility
        •	Implementation of logging
        •	Database verification

   # Tests that can be implemented:
        •	Verification of all links and their navigations on the Registration page
        •	Menu navigation to different pages
        •	Detailed field validation of every mandatory input field
        •	Mandatory field test
        •	Duplicate user registration


