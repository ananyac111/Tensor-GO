# Tensor-GO
Description:
Your task is to develop a system that allows users to log in using Google OAuth, view the details of due
invoices in a SaaS platform, and automate the process of sending past-due invoice reminders and
follow-up sequences. The system should integrate with Zapier to trigger automation actions. This
assignment assesses your ability to integrate third-party services, implement OAuth authentication, and
design a microservices architecture.

Requirements:

Backend Microservice (Node.js):

Implement a Node.js backend microservice that provides the following API endpoints:
● User authentication: Enable users to log in using Google OAuth.
● Invoice details: Allow users to view details of their due invoices, including the invoice amount, due
date, and recipient information.
● Integration with Zapier: Create endpoints to trigger automation actions in response to past-due
invoices.
● Integrate with Zapier to automate past-due invoice reminders and follow-up sequences. Set up
workflows in Zapier to send email reminders and follow-up notifications based on past-due
invoice data.

Frontend (React):

Develop a React frontend that includes the following features:
● Google OAuth integration: Implement a user interface for users to log in using their Google
accounts.
● Invoice details: Display a list of due invoices with relevant details.
● Trigger automation: Provide a button or option for users to manually trigger the automation
process using Zapier.
