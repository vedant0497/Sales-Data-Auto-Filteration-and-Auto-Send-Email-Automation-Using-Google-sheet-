# Sales-Data-Auto-Filteration-and-Auto-Send-Email-Automation-Using-Google-sheet-
![Photos](https://github.com/vedant0497/Sales-Data-Auto-Filteration-and-Auto-Send-Email-Automation-Using-Google-sheet-/blob/main/Screenshot%202025-12-22%20221616.png)
![Photos](https://github.com/vedant0497/Sales-Data-Auto-Filteration-and-Auto-Send-Email-Automation-Using-Google-sheet-/blob/main/Screenshot%202025-12-22%20223008.png)
![Photos](https://github.com/vedant0497/Sales-Data-Auto-Filteration-and-Auto-Send-Email-Automation-Using-Google-sheet-/blob/main/Screenshot%202025-12-22%20223043.png)
![Photos](https://github.com/vedant0497/Sales-Data-Auto-Filteration-and-Auto-Send-Email-Automation-Using-Google-sheet-/blob/main/Screenshot%202025-12-22%20223136.png)
![Photos](https://github.com/vedant0497/Sales-Data-Auto-Filteration-and-Auto-Send-Email-Automation-Using-Google-sheet-/blob/main/Screenshot%202025-12-23%20172535.png)
📊 Salesman-Wise Automated Sales Report

Google Apps Script | Google Sheets Automation

📝 Overview

This project automates salesman-wise sales reporting using Google Apps Script and Google Sheets.
It reads a master sales dataset, filters records for each salesman, generates individual reports, shares them automatically via email, and cleans up temporary files.

This solution is designed to reduce manual work, improve accuracy, and demonstrate real-world automation using Google Workspace.

✨ Key Features

📥 Reads sales data from a master Google Sheet

🔍 Filters data salesman-wise

📄 Creates a separate Google Sheet report for each salesman

📤 Automatically shares reports with edit access

📧 Sends email notifications with the report link

🧹 Deletes temporary files after sharing

⚡ Fully automated with a single script execution

🗂️ Spreadsheet Structure
Sheet1 – Sales Data
Column	Description
Sale Date	Date of sale
Region	Sales region
State	State name
City	City name
Product	Product category
Quantity	Units sold
Salesman	Salesman name
Age	Salesman age
Price per Unit	Unit price
Sales Amount	Total sales value
Sheet2 – Salesman List
Column	Description
Salesman Name	Salesman full name
Email ID	Salesman email address
🛠️ Technologies Used

Google Apps Script (JavaScript)

Google Sheets

Google Drive API

Gmail Service (MailApp)

⚙️ How the Script Works

Reads all sales data from Sheet1

Reads salesman names and email IDs from Sheet2

Filters sales data for each salesman

Creates a temporary Google Sheet report

Writes filtered data into the report

Shares the report with the salesman via email

Sends an automated email notification

Deletes the temporary spreadsheet after sharing

▶️ Setup & Usage

Open Google Sheets

Go to Extensions → Apps Script

Paste the project code

Ensure sheet names match the script

Run the function:

sendSalesmanWiseData()


Grant required permissions

📌 Use Cases

Sales reporting automation

Business analytics workflows

Admin & MIS reporting

Google Apps Script learning projects

🙏 Acknowledgment

Special thanks to my guardian and mentor Vikash Sir for his guidance, motivation, and continuous support.
His mentorship helped me build this project with real-world business logic and automation best practices.
