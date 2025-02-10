Healthcare Billing SQL Project

Overview
    This project provides a structured SQL database for managing healthcare billing, including patient records, procedures, claims, and payments. The database enables efficient revenue cycle management by supporting data retrieval, analysis, and automation.
Features
    •	Patient Management: Store patient details including insurance information.
    •	Appointment Scheduling: Track patient visits, providers, and procedures.
    •	Billing & Claims: Record claim submissions and monitor statuses.
    •	Data Analysis: Generate reports to identify trends and optimize billing.
    •	Stored Procedures & Triggers: Automate key billing operations.
Database Schema
    The project includes the following tables:
    •	Patient
    •	Provider
    •	ProcedureCode
    •	Appointment
    •	Claim
Views, Stored Procedures, and Triggers
    •	View: PatientBilling (Summarizes patient billing information)
    •	Stored Procedure: GetPatientClaims(IN patientID INT) (Fetches all claims for a patient)
    •	Trigger: BeforeClaimInsert (Prevents negative payment amounts)
Usage
    Running the SQL Script
    1.	Create the HealthcareBilling database.
    2.	Run the SQL script to set up tables, insert sample data, and define views, stored procedures, and triggers.
    3.	Use SQL queries to retrieve and analyze billing data.
Future Enhancements
    •	Integration with an EHR system
    •	Advanced machine learning for claim denial predictions
    •	More detailed reports and analytics

