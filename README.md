# Calculate-Client-Security-Hash

This project is conducted within ACME Systems Inc., Finance and Accounting Department. The Objective of this process automation is to

-Deliver fast processing
-Reduce redundant activities
Improve overall performance and reliability
### Process Description
- Step.1 Open ACME System 1 Web Application
- Step.2 Log in to the application with the required username and password
- Step.3 Access the work items menu in the dashboard
- Step.4 For each activity of type WI5 perform the following steps
- Step.5 Open the details page and retrieve the Client Information Details
- Step.6 Open SHA 1 Online webpage
- Step.7 Enter ClientID-ClientName-ClientCountry details
- Step.8 Retrieve Client Security Hash value
- Step.9 Go back to Client Information Details and update with hash value as a comment and set the status value to "Completed"
- Step.10 Continue with the next activity with type WI5
### Note
- Orchestrator Asset is used to store Credentials
- Robotic Enterprise Framework is used(REFramework)

### Instructions

Compress your Calculate Client Security Hash workflow and upload it below. Your results will be displayed as soon as your workflow is processed. Evaluation criteria: Number of correct items divided by the total number of processed items.

Do not reset the test data if the results of your evaluation on one of the assignments are still pending!

When registering on http://www.acme-test.com, make sure you use the SAME email address you used to create the Academy account!

All users need to install UiPath Studio (the Trial or the Community version) before the course

Evaluating the assignments in the UiPath Academy 2.0 is an automatic process, checking the results of the robot running on your system. The assignment should be submitted after all items are completed by the robot, while NOT resetting the test data until getting the grade. The grade consists of the number of correct items divided by the total number of items. Grading can take a few minutes.

The criteria for a correct processed item is based on the instructions in the provided PDD and is the following:

Status Completed
comment contains correct security hash - Pay close attention to the formula ([ClientID]-[ClientName]-[ClientCountry] - Example: AD38755-Austin Villacorta-Italy) with no spaces between the dashes and without the brackets.
If you have failed this assignment, no worries - you can try again. You must click the Results tab on this page, then go to Feedback. You have to click the arrow next to the submitted date and you will see the Upload a File button available. If your assignment is passed, you cannot reupload the file.
