# ServiceNow Leave Management System

## 📌 Project Overview

The **ServiceNow Leave Management System** is a ServiceNow-based application designed to simplify and automate employee leave requests. It allows leave requests to be submitted, validated, approved, or rejected through an automated workflow.

The project uses **ServiceNow Flow Designer, Client Scripts, custom tables, and dashboards** to improve the leave management process.

## 🎯 Problem Statement

Managing employee leave requests manually can lead to delays, errors, and difficulties tracking request statuses. This project provides a centralized system to manage leave requests and automate the approval process.

## 🚀 Objectives

- Create and manage employee leave requests.
- Validate leave start and end dates.
- Automate leave approval and rejection.
- Track Pending, Approved, and Rejected requests.
- Display leave request statistics through a dashboard.

## 🛠️ Technologies Used

- **Platform:** ServiceNow
- **Application Development:** Scoped Application
- **Workflow Automation:** Flow Designer
- **Validation:** Client Scripts
- **Data Management:** Custom Tables and Fields
- **Visualization:** Reports and Platform Analytics Dashboard

## ✨ Key Features

- **Leave Request Management:** Store employee leave details in a custom table.
- **Date Validation:** Prevent users from selecting an end date earlier than the start date.
- **Automated Approval Workflow:** Route leave requests for approval using Flow Designer.
- **Approval and Rejection:** Automatically update the request status based on the approval outcome.
- **Email Notification Configuration:** Email actions are configured for approval outcomes. Actual email delivery has not been verified because outbound email is disabled in the developer instance.
- **Analytics Dashboard:** Visualize total, pending, approved, and rejected leave requests.
- **Reports:** Generate reports based on leave request status.

## 🔄 Workflow

1. An employee submits a leave request.
2. The system validates the leave dates.
3. Flow Designer triggers the approval workflow.
4. The request is sent to the configured approver.
5. The approver approves or rejects the request.
6. The leave request status is updated automatically.
7. Request statistics are displayed on the dashboard.

## 📊 Dashboard

The **Leave Management Dashboard** provides an overview of leave requests using scorecards and a pie chart.

It includes:

- Total Leave Requests
- Pending Leave Requests
- Approved Leave Requests
- Rejected Leave Requests
- Leave Requests by Status

## 🧪 Testing

The following scenarios were tested:

- Submitting a leave request with valid dates.
- Preventing an invalid date range.
- Processing an approved leave request.
- Processing a rejected leave request.
- Verifying automatic status updates.
- Checking dashboard reports and visualizations.

## 📸 Project Documentation

A PDF document containing screenshots of the ServiceNow Leave Management System is included in this repository.

The document showcases:
- Leave Request Form and Records
- Flow Designer Approval Workflow
- Leave Approval and Rejection
- Reports and Analytics Dashboard

Please refer to the PDF for a visual walkthrough of the project implementation and its features.

## 📚 Skills Demonstrated

- ServiceNow Application Development
- Scoped Application Configuration
- Flow Designer
- Client Script Development
- Workflow Automation
- Custom Table and Field Configuration
- Reports and Dashboards
- Testing and Troubleshooting

## 🔮 Future Enhancements

- Configure and verify email delivery.
- Add leave balance tracking.
- Implement role-based access for employees, managers, and administrators.
- Add leave history and advanced reporting.
- Integrate with employee records for improved data management.

## 👨‍💻 Author

**Deepak S**
B.E. Computer Science and Engineering Student

## 📄 License

This project is intended for educational and portfolio purposes.
