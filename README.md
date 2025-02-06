# Project 2024-25
Title - Detecting Data Leaks via SQL Injection 
This project focuses on preventing unauthorized access to admin data by detecting SQL injection attacks using the Support Vector Machine (SVM) algorithm. The system monitors database interactions and identifies suspicious queries that attempt to insert unauthorized data. Upon detection of an SQL injection attempt, an alert message is sent to notify the concerned individual.

Features:
SQL Injection Detection: Identifies malicious attempts to modify or access unauthorized database records.
Machine Learning Model: Uses the SVM algorithm to classify and detect suspicious SQL queries.
Real-time Alerts: Sends a notification when an injection attempt is detected.
Security Enhancement: Provides an additional layer of protection for admin data.
Technologies Used:
Python
Machine Learning (SVM)
SQL Database
Flask/Django (if applicable)
Twilio/Email API (for alerts, if used)
How It Works:
Monitors database queries in real time.
Uses an SVM-based classifier to detect SQL injection patterns.
If an injection is detected, the system blocks the query and sends an alert.
Logs the attack attempt for further analysis.
