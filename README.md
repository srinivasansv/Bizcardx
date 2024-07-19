# BizCardX: Extracting Business Card Data with OCR

## Project Overview

**BizCardX** is a Streamlit application designed to streamline the process of extracting and managing information from business cards. By leveraging OCR technology through easyOCR, this application allows users to upload images of business cards and automatically extract relevant information such as company name, cardholder name, designation, mobile number, email address, website URL, area, city, state, and pin code. The extracted information is then displayed in a user-friendly GUI and can be stored in a database for easy retrieval and management.

## Technologies Used

- Python
- Streamlit
- easyOCR
- SQLite or MySQL

## Problem Statement

Develop a Streamlit application that enables users to:
1. Upload an image of a business card.
2. Extract information from the card using easyOCR.
3. Display the extracted information in a clean and organized GUI.
4. Save the extracted information and the business card image into a database.
5. Read, update, and delete data through the Streamlit UI.

## Approach

### 1. Install Required Packages

Ensure you have the following installed:
- Python
- Streamlit
- easyOCR
- SQLite or MySQL

### 2. Design the User Interface

Create a simple and intuitive UI using Streamlit with widgets like file uploaders, buttons, and text boxes to guide users through the process.

### 3. Implement Image Processing and OCR

Use easyOCR to extract information from the uploaded business card images. Enhance image quality using techniques like resizing, cropping, and thresholding before passing it to the OCR engine.

### 4. Display Extracted Information

Present the extracted information in a clean and organized manner in the Streamlit GUI using tables, text boxes, and labels.

### 5. Implement Database Integration

Store the extracted information along with the uploaded business card image in a database (SQLite or MySQL). Perform CRUD operations through SQL queries and Streamlit UI.

### 6. Test the Application

Test the application thoroughly to ensure functionality. Run the application locally using the command:
streamlit run app.py
where app.py is your Streamlit application file.

### 7. Improve the Application
Continuously enhance the application by adding new features, optimizing the code, and fixing bugs. Consider adding user authentication and authorization for improved security.

### Results
The resulting application will:

* Allow users to upload business card images and extract relevant information using easyOCR.
* Display the extracted information in a user-friendly GUI.
* Enable users to save the extracted information and business card images in a database.
* Provide functionalities to read, update, and delete data through the Streamlit UI.

### Skills Required
* Image Processing
* OCR (Optical Character Recognition)
* GUI Development
* Database Management

### Getting Started
###Prerequisites
* Python 3.6 or higher
* Streamlit
* easyOCR
* SQLite or MySQL
