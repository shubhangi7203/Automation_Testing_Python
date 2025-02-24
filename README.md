# Automation_Testing_Python
Automation Testing By Using Python
Selenium Playground Table Search Demo Test 

This Python script automates the search functionality in the Selenium Playground Table Search Demo. It searches for "New York" and validates that the search results return 5 entries out of 24 total entries. 

Approach: 

Navigate to the Selenium Playground Table Search Demo. 

Interact with the search box by entering the term "New York". 

Validate that 5 entries are displayed because of the search. 

Requirements: 

Python 3.x 

Selenium 4.x 

Edge WebDriver (msedgedriver.exe) 

Installation: 

Install Python Dependencies: If you haven't installed Selenium yet, you can install it using pip: 

bash pip installs selenium 

Download Edge WebDriver: 

Ensure that your version of msedgedriver.exe matches your Microsoft Edge version. 

Download it from Microsoft Edge Driver. 

Update the path in qa_selenium_test.py to point to the downloaded msedgedriver.exe. 

Run the Script: Execute the Python script by running: 

python qa_selenium_test.py 

Expected Output: After running the script, you should see a message indicating whether the test passed or failed. If the search results show 5 entries, the test passes. 

Troubleshooting: 

Ensure that Microsoft Edge is installed on your machine. 

Ensure that the Edge WebDriver version is compatible with your version of Microsoft Edge. 

If you encounter any issues with the WebDriver path, double-check the file location. 

 

 
