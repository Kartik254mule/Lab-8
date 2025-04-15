Theory
Software Testing
It is the process of evaluating and verifying that a software product or application does what it is supposed to do.

Verification and Validation
Verification: Are we building the product right?

Validation: Are we building the right product?

Standards for Software Test Documentation
Test plans, test cases, test logs, test summary reports, etc.

Testing Frameworks
JUnit (Java), PyTest (Python), Selenium (Web Testing), etc.

Need for Software Testing
To detect bugs early, improve system reliability, and ensure user satisfaction.

Test Cases and Test Suite
Test Case: A single scenario to test specific functionality.

Test Suite: A collection of related test cases.

Types of Software Testing
Unit Testing

Example: Test registerDonor() function to ensure donor registration is stored correctly.

Integration Testing

Example: Verify interaction between Schedule Donation and Update Inventory modules.

System Testing

Example: Test the entire system by simulating a complete workflow: Donor registers → schedules donation → blood is added to inventory → recipient requests blood → admin approves.

Sample Unit Test Case (Blood Donation System)

Test Case ID	TC_BD_001
Test Case Name	Donor Registration
Module	Donor Management
Input	Name, Age, Blood Group, Contact Details
Expected Output	"Registration Successful" message and record in database
Actual Output	As expected
Status	Pass


![17447128460236681171077236339472](https://github.com/user-attachments/assets/36bcb214-a71e-4405-afdb-69bca62d1dae)
