Leave Management System (Salesforce)

📌 Project Overview

The Leave Management System is a Salesforce-based application designed for IT companies to streamline employee leave requests.
Employees can request leaves, and managers can approve or reject them. The system also provides reports and dashboards for HR to monitor leave trends.

🚀 Features

Employee Records: Maintain employee details (Name, Email, Department).

Leave Requests: Employees can request Sick, Casual, or Earned leave.

Automation:

Short leaves (≤2 days) auto-approved.

Long leaves require manager approval.

Validation: Prevents invalid date ranges (End Date before Start Date).

Apex Trigger: Prevents overlapping leave requests for the same employee.

Reports & Dashboards:

Leaves by Employee (Bar Chart)

Leaves by Type (Pie Chart)

Leave Overview Dashboard

🛠️ Technology Stack

Platform: Salesforce

Automation: Flow, Validation Rules

Development: Apex Trigger + Test Class

UI: Standard Salesforce UI

Reports: Salesforce Reports & Dashboards

📂 Project Structure

Employee__c → Custom Object for employees

Leave_Request__c → Custom Object for leave requests

Apex Classes → Trigger & Handler for duplicate prevention

Reports & Dashboard → Visual analytics

🎯 How to Use

Clone/download this repository.

Import metadata (Objects, Flows, Triggers) into your Salesforce Developer Org.

Use Employee tab to add employees.

Use Leave Request tab to create leave requests.

View reports & dashboards for insights.

🔮 Future Enhancements

Approval process with Manager notifications.

LWC-based Leave Request form.

Integration with external HR systems (Workday, PeopleSoft).

👩‍💻 Author

Developed by Prasanth as part of Salesforce Developer project submission.

Demo Video : https://drive.google.com/file/d/1d0Zyu95DCglOFFSHAJDw8wIbB3OiW_lw/view?usp=drivesdk
