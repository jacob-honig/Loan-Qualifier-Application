# Loan-Qualifier-Application
An application used to filter through a csv file containing banks and their loan qualifications to see which banks the user qualifies for a loan from.

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

---

## Usage

This section should include screenshots, code blocks, or animations explaining how to use your project.

1. Open terminal, navigate to the loan_qualifier_app directory, and run the app.py using python

![Step_1](https://user-images.githubusercontent.com/63683699/148700963-789aa26a-9306-4379-8f20-8b63d7144a4b.jpg)

2. Enter the path to the daily rate sheet

![Step_2](https://user-images.githubusercontent.com/63683699/148700968-d4f6cd64-06e5-49c6-b627-a62c7a2286e8.jpg)

3. Enter your financial information

![Step_3](https://user-images.githubusercontent.com/63683699/148700980-51c42be9-a863-4046-8997-0e290bb9900f.jpg)

4. Specify whether or not you would like to save the qualifying loans to a csv file

![Step_4](https://user-images.githubusercontent.com/63683699/148700988-2b9c2a23-13e5-4aef-b445-f1bdf4ec8611.jpg)

5. Enter the desired output path

![Step_5](https://user-images.githubusercontent.com/63683699/148700996-00216436-13a9-4934-9915-a1e4c27136b9.jpg)


---

## Contributors
Jacob Honig
jacobdhonig@gmail.com
www.linkedin.com/jacob-honig/

---

## License

This repository is copyrighted using the MIT License. 
