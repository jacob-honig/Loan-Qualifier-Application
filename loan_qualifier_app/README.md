# Project Title
Loan Qualification App

The purpose of this application is to allow users to seamlessly filter through a list of banks and their loan qualifications, using the user's financial information, and to download a list of banks which the user qualifies for a loan from. 

This application is an assignment included in the fintech bootcamp curriculum by Trilogy Education Services. 


---

## Technologies

Describe the technologies required to use your project such as programming languages, libraries, frameworks, and operating systems. Be sure to include the specific versions of any critical dependencies that you have used in the stable version of your project.
This application was written using Python and WindowsOS. There are three main modules of the application

This application was made using Python (v3.7.0) and WindowsOS (v20H2) as well as the following Python libraries: 
    sys, fire, questionary, pathlib, csv

There are three main modules that make up this app.

The utils module, a subdirectory located in the qualifier folder, includes two files. The first file, calculators.py, provides the functions needed to modify the user's financial information into the financial metrics used by lenders to screen applicants. The second file, fileio.py, provides the functions needed to load csv data and save data into a csv file.

The filters module, a subdirectory located in the qualifier folder, includes multiple python files and each file provides a function needed to filter through one financial metric on the daily rate sheet.

The final module, app.py, is located in the main loan_qualifer_app folder. This module pulls functions from the other modules and integrates them with the main usability functions provided in this file. 


---

## Installation Guide

In this section, you should include detailed installation notes containing code blocks and screenshots.

Filters Module
![Filter_Image_1](https://user-images.githubusercontent.com/63683699/148701510-0c3b4818-6f35-4f9b-843b-6056411e4d8d.jpg)
![Filter_Image_2](https://user-images.githubusercontent.com/63683699/148701513-a58685b1-330c-4c99-a0db-43d0b290082f.jpg)
![Filter_Image_3](https://user-images.githubusercontent.com/63683699/148701514-03e66d8e-0e77-4a23-a506-54510b5b169f.jpg)
![Filter_Image_4](https://user-images.githubusercontent.com/63683699/148701516-30586f31-5e8f-4235-b41d-267bfbe9e090.jpg)

Utils Module
![Utils_Image_1](https://user-images.githubusercontent.com/63683699/148701530-9fac2de0-04fb-4d96-abe5-19f76ca69445.jpg)
![Utils_Image_2](https://user-images.githubusercontent.com/63683699/148701532-ace5290a-b48f-4948-b0a0-75e218b532b4.jpg)

App Module
![App_Image_1](https://user-images.githubusercontent.com/63683699/148701537-2e156729-09c6-4e6e-b07d-37e6e68d29bb.jpg)
![App_Image_2](https://user-images.githubusercontent.com/63683699/148701543-3b3ec9a9-b45b-40cc-975b-7c0210da6563.jpg)
![App_Image_3](https://user-images.githubusercontent.com/63683699/148701546-62339d93-4f49-4a05-9cc5-0afc1ee0729f.jpg)


---

## Usage

This section should include screenshots, code blocks, or animations explaining how to use your project.

1. Open terminal, navigate to the loan_qualifier_app directory, and run the app.py using python

2. Enter the path to the daily rate sheet

3. Enter your financial information

4. Specify whether or not you would like to save the qualifying loans to a csv file

5. Enter the desired output path


---

## Contributors
Jacob Honig
jacobdhonig@gmail.com
www.linkedin.com/jacob-honig/

---

## License

This repository is copyrighted using the MIT License. 
