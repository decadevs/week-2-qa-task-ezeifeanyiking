# QA SOLUTION TO WEEK TWO TASK
1. ## What is test coverage and why is it very important in testing?
### Test Coverage?
Test coverage is synonymous to exhaustive testing. It is a metric for how thorough testing is. 
Example: If there are 10 requirements and 100 tests created and if 90 tests are executed then test coverage is 90%.
### Importance of test coverage?
- Defect prevention at early stages of project life cycle
- It creates additional test cases to increase coverage
- Better ROI will be achieved by reduction in UAT defects and production defects
- It helps in finding areas of a program not exercised by a set of test cases
- Time, Cost and Scope will be in control
-  Testing life will become smooth by managing the Risk based testing approach
- It helps in determining a quantitative measure of code coverage, which indirectly measures the quality of the application or product.

2. ## What is the difference between the testing technique and types of testing?
### Software testing?
: Software Testing Type is a classification of different testing activities into categories, each having, a defined test objective, test strategy, and test deliverables. The goal of having a testing type is to validate the Application Under Test(AUT) for the defined Test Objective.
### b.	Software techniques?
: Software Testing Techniques help you design better test cases. Since exhaustive testing is not possible; Manual Testing Techniques help reduce the number of test cases to be executed while increasing test coverage. They help identify test conditions that are otherwise difficult to recognize.

3. ## Discuss each type of testing and discuss the sub-testing types associated with each type of testing.
: We have 2 main types of testing. Functional Testing & Non-functional testing.
###	FUNCTIONAL TESTING: (i.e.: Manual and Automation Testing)
1.	Unit Testing
2.	Integration Testing
3.	Interface Testing
4.	Regression Testing
5.	User Acceptance Testing
6.	System Testing

### NON-FUNCTIONAL TESTING:
1.	Documentation Testing
2.	Installation Testing
3.	Reliability Testing 
4.	Security Testing
5.	Performance Testing: - Load Testing, .Stress Testing, Endurance Testing, .Spike Testing

### UNIT TESTING
A unit is the smallest testable part of any software. It usually has one or a few inputs and usually just a single output.
This is a level of software testing where individual units or components of a software are tested and the purpose is to validate each unit of the software performs as designed. 
It is normally performed by the software developers and in rare cases, independent software testers.

### INTEGRATION TESTING 
This is a level of software testing where individual units are combined and tested as a group to expose faults in the interaction between integrated units.
It is usually performed by the software developers and in rare cases, independent software testers.
### SYSTEM TESTING
This is the third level of software testing after Acceptance Testing and Integration Testing and it is usually performed by independent testers.
This is a level of software testing where a complete and integrated software is tested to evaluate if the system meets the specified requirements. 
An analogy of system testing.
When manufacturing a ball point pen, all the parts are produced separately and unit tested separately, so when two or more units are ready, they are assembled and integration testing is performed. Now when the complete pen is integrated, the system testing is performed.
### INTERFACE TESTING
When a software is developed, it has several components e.g.: server, database e.tc. The connection that integrates and facilitates the connection between these components is called “Interface”.
It verifies that communication between the systems is done correctly if all supported hardware and software has been tested.    

### Interface Life Cycle has 3 Phases of Interface Testing
1.	Configuration and Development: Once the interface is configured and the development starts, the configurations need to be verified as per the requirements.
2.	Validation: Once the development is completed, the interface needs to be verified and validated. (This can be done as part of unit testing also).
3.	Maintenance: Once the software is ready, deployed and working, the interface needs to be monitored for its performance and any new changes introduced due to the changes made.

### Benefits of Unit Testing
1.	It is required to check if server execution is proper.
2.	Error Handling:
3.	It is used to check the result when a connect to the server is reset.
4.	Security Aspect.
5.	It is used to check the impact of network failure on the communication between the components.

### Approaches to interface testing
1.	Define Requirement
2.	Expected Output
3.	Start Small
4.	Try Automating
5.	Start & Stop points

### REGRESSION TESTING
Regression testing verifies that recent code changes haven't altered or destroyed the already existing functionality of a system. 
#### Techniques for regression testing:
1.	Retest All: Here, the entire test case in the test suite is re-executed to ensure that there are no bugs that are introduced as a result of a change in the code.
2.	Regression Test Selection: Here, test cases are selected from the test suite to be executed, not all.
3.	Test Case Prioritization: Test cases with high priority are executed first, before the ones with medium and low priority. 
4.	Hybrid: This is a combination of “Regression test selection” and “Test case prioritization” 

### Test Plan Template:
1.	Document History: Consists of the record of the first draft and all the updated ones. 
2.	References: This refence column keeps a track of all the reference documents used/required while creating a test plan.   
3.	Test Plan: Consist of all the introduction and details involved in the testing. 

### ACCEPTANCE TESTING:
Here, the system is tested for acceptability. To evaluate the systems compliance with the business requirements and access whether it is acceptable for delivery. (Usually, the management sales, customer support, end users and customers performs this kind of testing). 

### Approach to Acceptance Testing (Acceptance Testing Tasks)
1.	Test Plan: Here, we prepare, review, rework and form the baseline.
2.	Test Cases/Checklist: Here, we prepare, review, rework and form the baseline.
3.	Acceptance Test: Here, we perform the acceptance testing.

### Types of Acceptance Testing
1.	User Acceptance: Whether the product is working for the user correctly for the usage.
2.	Business Acceptance: Whether the product meets the business goals or not.
3.	Contract Acceptance: This is a contract the specifies that once the project goes live, within the pre-determined period, the acceptance test must be performed and it should pass all the acceptance use cases.
4.	Operational Acceptance: This is to assess the operational readiness of the product and it is a non-functional testing.
5.	Alpha Testing: This is to assess the product in the development or testing environment by a specialized testers team usually called alpha testers.
6.	Beta Testing: This is to assess the product by exposing it to the real end users usually called the beta testers/beta users in their environment. 

### NON-FUNCTIONAL TESTING:
1.	DOCUMENTATION TESTING: It helps to estimate testing effort required and test coverage. (Software documentation includes; test plane, test case and requirements).
There are 4 main focus areas when testing documentation: 
- Instructions 
- Examples
- Messages
- Samples
2.	INSTALLATION TESTING: A type of QA work in the software industry that converges on what customers will need to do to install and setup the new software successfully. (The testing process may involve full, partial or upgrades install or uninstall processes).

3.	PERFORMANCE TESTING: software testing technique that determines how the stability, speed, scalability, and responsiveness of an application holds up under a given workload. 

### Types of performance testing: 
- Load Testing: A type of performance testing conducted to check the performance of a system at increasing workload.
- Stress Testing: Conducted to evaluate the behavior of a system at or beyond the limits of its anticipated workload.
- Endurance Testing: Conducted to evaluate the behavior of a system when a significant workload is given continuously.
- Spike Testing: Conducted to evaluate the behavior of a system when the load is suddenly and substantially increased. 

### Tips for performance testing:
- Establish test environment: as close to the production environment as possible. 
- Isolate: the test environment from the QA or UAT environment.
- Find the perfect tool: though no perfect tool for performance testing. Research and decide on the tool that best fits your purpose.
- Conduct multiple test: do not rely on the results of just one test, you should conduct multiple tests to arrive at an average number. 

### RELIABILITY TESTING: Software reliability is the probability that software will work properly in a specified environment and for a given amount of time.

### Types of reliability testing:
- Feature Test: Here, each function in the software should be executed at least once and the interaction between two or more functions should be reduced. Also, each function should undergo proper execution or functional tests.
- Regression Test: Whenever any new functionality is added or old functionalities is removed in an application, it undergoes a regression test to make sure with introduction of new functionality no new bugs are introduced.
- Load Test: Checks whether the application is supporting the required load without getting breakdown. (To get the break point of an application, the load is gradually increased until the application gets hung).

### SECURITY TESTING: 
This involves:
- The Network Security: which involves looking for vulnerabilities in the network infrastructure.  
- System Security: && Client-Server Security:
 which ensures that the client can-not be manipulated and the server code and its technologies are robust enough to fend off any intrusion.

### Security testing techniques:
1.	Access to application: This is implemented by roles and rights management.
2.	Data Protection: Now there are three aspects of data security:  
- a user can view or utilize only the data which he/she is supposed to use. 
- talks about how data is stored in the database. 
- Proper security measures must be adopted when the flow of sensitive or business critical data occurs.
3.	Brute Force Attacks: Mostly done by some software tools. The concept is that by using a valid user ID the software attempts to guess the associated password by trying to log in again and again.
4.	SQL Injection and XSS: Here, input fields of the website field length should be defined small enough to restrict input of any script.
5.	Service Access Points: When there is a large number of the target audience, the access points should be open enough to facilitate all users, accommodating enough to fulfil all users requests and secure enough to cope with any security trial. 
6.	Session Management: You can check for session expiry of the particular idle time, session termination of the maximum lifetime, session termination of the logout, check, check for session cookie scope etc. 
7.	Error Handling: Error codes are returned with a detailed message. These messages should not contain any critical information that can be used for hacking purpose.
8.	Specific Risky Functionalities: Payment and File Uploads.

### Create a folder in google drive with name Testing Types Task (Done)
- Inside the folder, create more folders with name of the type of bug that can be found on the site.
- Go to link AcademyBugs.com
- Click find bugs.
- On the site, there are only 25 bugs. You will perform exploratory testing where you will test every functionality on the site and find all defects (features that do not work as expected).
- For each bug you find take a screen shot of the bug report and save it under the related folder.
- When done, take a screen shot of bug number found and save to folder.
- Submit the google drive link, do not restrict user, set link to everyone with link.
- This will teach you how to classify bugs under testing types and the kind of defects to look out for in an application

Solution link: 
[Solution to number 4](https://drive.google.com/drive/folders/1tk6Ki9IxgW-lep8c7rOmF7TpPz3fDrnW?usp=sharing)

### What is testing technique, discuss the type of testing techniques and give 2 examples of each.

### TEST CASE DESIGN TECHNIQUES IN SOFTWARE TESTING
: Test case design technique is also called black box design technique.
This is a technique used while writing test cases in other to have a better test case coverage.
A test case with no substantial coverage is of no use.

### TYPES OF TEST CASE DESIGN TECHNIQUES:
1.	Error Guessing: Here, you try to guess the error by entering negative values. (There are no rules to go about it. Just be creative).

**For example1**: suppose you had an input field which should receive a numeric value and not less than 10 numbers, you can approach the error guessing technique by saying, “what will be the result if”:
- The mobile no. is left blank?
- Any character other than a numeric value is entered?
c.	Less than 10 numerical values are entered?
For example2: 

2.	Boundary Value Analysis: Boundary value analysis is a software testing technique in which tests are designed to include representatives of boundary values in a range. The idea comes from the boundary. (This is testing the boundaries between partition). 

**For example1**: Say you have an online order pizza app that accepts numeric values:
Pizza values 1 to 10 is considered valid. (Here, a success message is shown).
While value 11 to 99 is considered invalid. (Here, an error message is shown: “Only 10 Pizza can be ordered”).
#### Here is the test condition
- Any Number greater than 10 entered in the Order Pizza field (let say 11) is considered invalid.
- Any Number less than 1 that is 0 or below, then it is considered invalid.
- Numbers 1 to 10 are considered valid
- Any 3 Digit Number say -100 is invalid.

Boundary Value Analysis- in Boundary Value Analysis, you test boundaries between equivalence partitions.

[Boundary Value Analysis](https://drive.google.com/drive/folders/1gO7Nbp48SEc4eMNuM_DvYB2oLOkAvJb_?usp=sharing)

Here, we will check the values at the partitions like 0, 1, 10, 11 and so on. As you may observe, you test values at both valid and invalid boundaries. Boundary Value Analysis is also called range checking.

3.	Decision Table Techniques: An approach where the different input combinations and their corresponding system behavior (Output) are captured in a tabular form (can we say using truth table).
Here, we check for multiple conditions, combinations and rule criteria. Here we check for multiple inputs. Here, the conditions are taken as an input and actions are taken as an output
4.	State Transition Techniques: Any system where you get a different output for the same input, depending on what has happened before, is a finite state system. 
For example: if you request to withdraw $100 from a bank ATM, you may be given cash. Later when you make the same request you could be refused money (because your balance is insufficient). This later refusal is because the state of your bank account has changed from having sufficient funds to insufficient funds. And the transaction that caused your account to change its state was probably the earlier withdrawal.
5.	Equivalence Partitioning: Equivalence partitioning or equivalence class partitioning (ECP) is a software testing technique that divides the input data of a software unit into partitions of equivalent data from which test cases can be derived.

For example1: Say you have an online order pizza app that accepts numeric values:
Pizza values 1 to 10 is considered valid. (Here, a success message is shown).
While value 11 to 99 is considered invalid. (Here, an error message is shown: “Only 10 Pizza can be ordered”).
#### Here is the test condition
- Any Number greater than 10 entered in the Order Pizza field (let say 11) is considered invalid.
- Any Number less than 1 that is 0 or below, then it is considered invalid.
- Numbers 1 to 10 are considered valid
- Any 3 Digit Number say -100 is invalid.
We cannot test all the possible values because if done, will be time consuming.
Using equivalence partitioning hypothesis where we divide the possible values of tickets into groups or sets as shown below.

[Equivalence partitioning technique](https://drive.google.com/drive/folders/1PoRhwQLKBHbRUXEGQ1aOjH1PpAFr0m-H?usp=sharing)

The divided sets are called Equivalence Partitions or Equivalence Classes. Then we pick only one value from each partition for testing. The hypothesis behind this technique is that if one condition/value in a partition passes all others will also pass. Likewise, if one condition in a partition fails, all other conditions in that partition will fail.

### 6. Using the login form specification requirements, identify all testing techniques that can be used to design test case for this login form. Also Implement the identified techniques and document your solution. 
Image link - https://drive.google.com/file/d/1_3kr18fUMzPnYDybKCabDJ0gZ6SrVInk/view?usp=sharing

## Solution: 
#### Email must be a valid email format:
- Here, we use Error guessing by trying to enter negative and positive values.
#### Email characters cannot be less that 15 characters but not greater than 200 characters:
- Here, we use Equivalence partitioning by dividing the input data of a software unit into partitions of equivalent data from which test cases can be derived.
#### Password should contain at least 8 characters and at most 20 characters:
- Here, we user boundary value analysis where tests are designed to include representatives of boundary values in a range.
#### Password must contain at least one character, one number and one capital letter:

- Here, we use decision table technique where the different input combinations and their corresponding system behavior (Output) are captured in a tabular form.

[Decision table technique](https://drive.google.com/drive/folders/1Pkap8INJPz7kxK3dD617pXY9srNiPYJA?usp=sharing)

#### The Login button should be enabled if the user has entered all the valid required fields (email & password).
- Here, we use state transitioning technique where you get a different output for the same input, depending on what has happened before.

#### Only a registered user can login:
- Here, we use error guessing. 
#### All invalid inputs should throw the correct error, tester should suggest the type of error, while valid input should show the correct output.:
- Here, the type of error would be type error.

### 7. Design a decision table for Upload image Scenario. 
#### Requirements:
- you can upload only .jpeg format, 
ii.	file size must be less than 32kb, 
- Resolution must be only 137*177
- No. of Test Cases: 2**(No. of requirements = 3) = 8
### Solution: 
[Decision table technique](https://drive.google.com/drive/folders/1eymlmx99HND41jeNnPARJw14Z8eehx90?usp=sharing)
### 10. An organization gives you a new mailing application they just designed to identify its strengths and weaknesses with respect to the standard in the market.
- what testing technique would you apply and give a detailed description of what you will do when applying this technique.

**Solution**: I will apply state transition technique.

[State transition technique](https://drive.google.com/drive/folders/106JPor4YUgNvMfN8tF_-mDUwqL3cWBg7?usp=sharing)