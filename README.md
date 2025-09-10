# Disease-Predictor-application-

Disease Predictor Application is an AI-based tool that analyzes user health data—such as symptoms, demographics, lifestyle, and medical history—to predict the risk of various diseases. It provides quick, data-driven insights to support early detection, preventive care, and better decision-making while ensuring data privacy and security.

A Java application that helps diagnose diseases based on selected symptoms. This project uses a MySQL database to store symptoms and diseases and their relationships.

Features

Select symptoms from a list.
Click "Diagnose" to get a list of possible diseases based on selected symptoms.
View detailed descriptions of the diseases.

Requirements

Java
MySQL Database
MySQL JDBC Driver
Setup

Set Up the Database

Create a MySQL database named DiseasePredictor.
Run the provided SQL script (resources/db_code.sql) to set up the necessary tables and sample data.
Configure Database Connection

Update the connectToDB() method in Main.java with your MySQL database credentials.
Compile and Run

Compile and run the Main.java file
Usage
Launch the Application

Run the application using the command above.
The GUI will open, displaying a list of symptoms.
Diagnose

Select the symptoms you are experiencing.
Click the "Diagnose" button to see possible diseases and their descriptions
