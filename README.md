# LinkedIn-Automation
This repository contains a Python script that can be used to automate the process of connecting with recruiters on LinkedIn. The script first imports the pandas and selenium libraries. It then reads a CSV file containing the names and LinkedIn profile links of the recruiters that you want to connect with. For each recruiter, the script opens their LinkedIn profile in a web browser, clicks the "Connect" button, and sends a personalized message.

# Requirements
To run the code in this repository, you need to have the following installed:

* Python (version 3.0 or higher)
* pandas library
* selenium library
* BeautifulSoup library
* Chrome WebDriver (compatible with your Chrome browser version)

# Usage
1. Clone the repository to your local machine or download the code files.

2. Install the required dependencies by running the following command:
```bash
python -m pip install -U pip
pip install -r requirements.txt
```
3. Place the Excel file containing the LinkedIn recruiter information (named 'linkedinrecruiters.xlsx') in the same directory as the code files.

4. Open the code file 'automate_recruiter.py' and modify the following variables according to your setup:

* excel_file_path: Specify the file path of the Excel file.
* linkedin_username: Provide your LinkedIn username.
* linkedin_password: Provide your LinkedIn password.
5. Run the code file using the following command:
```bash
python automate_recruiter.py
```
6. The code will automate the login process, visit each recruiter's LinkedIn profile, and send connection requests with custom messages.

7. You can monitor the progress and any errors through the console output.

Note: Make sure to use the appropriate Chrome WebDriver version that matches your Chrome browser version. You can download the WebDriver from the ChromeDriver Downloads page.
