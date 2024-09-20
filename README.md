
# 🤖 LinkedIn Automation

Welcome to **LinkedIn-Automation**, a Python-based script that automates the process of connecting with recruiters on LinkedIn. By leveraging Selenium and Pandas, this tool simplifies the task of sending personalized connection requests to multiple recruiters in one go.

## ✨ Features
- Automates LinkedIn connection requests.
- Sends personalized messages to recruiters.
- Reads recruiter information from a CSV file containing their names and LinkedIn profile URLs.
- Automatically logs in to LinkedIn and sends connection requests.

## 📋 Requirements
To run this project, ensure you have the following installed on your system:

- **Python** (Version 3.0 or higher)
- **pandas** library
- **selenium** library
- **BeautifulSoup** library
- **Chrome WebDriver** (compatible with your Chrome browser version)

## 🚀 Usage

### 1. Clone the Repository
Start by cloning this repository to your local machine:
```bash
git clone https://github.com/yourusername/LinkedIn-Automation.git
```

### 2. Install Dependencies
Install the required libraries by running:
```bash
python -m pip install -U pip
pip install -r requirements.txt
```

### 3. Prepare Recruiter Information
Make sure to place the Excel file containing the recruiters' LinkedIn information (named `linkedinrecruiters.xlsx`) in the same directory as your code files. The file should include recruiters' names and profile URLs.

### 4. Modify Configuration
Open the `automate_recruiter.py` file and update the following variables:

- **`excel_file_path`**: Path to your Excel file with recruiter info.
- **`linkedin_username`**: Your LinkedIn username or email.
- **`linkedin_password`**: Your LinkedIn password.

### 5. Run the Script
Execute the script to automate the connection requests:
```bash
python automate_recruiter.py
```

### 6. Monitor Progress
Follow the console output to monitor the progress and catch any potential errors during execution. The script will automatically log in to your LinkedIn account, visit each recruiter’s profile, and send a connection request with a personalized message.

> **Note:** Ensure you have the appropriate version of **Chrome WebDriver** matching your Chrome browser version. You can download it from the [ChromeDriver Downloads page](https://sites.google.com/chromium.org/driver/downloads).

## 🤝 Contributing
Contributions are welcome! Feel free to fork this repository and submit pull requests. For major changes, please open an issue to discuss the proposed changes first.

## 📄 License
This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).
