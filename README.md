BizCardX: Extracting Business Card Data with OCR

BizCardX is a Python application created with Streamlit, EasyOCR, OpenCV, regex functions, and a MySQL database. It enables users to extract information from business cards and store it in a MySQL database for further analysis. The primary purpose of BizCardX is to automate the extraction of essential details from business card images, including names, designations, company information, and contact details, using Optical Character Recognition (OCR) provided by EasyOCR.

About EasyOCR
EasyOCR is a Python package that simplifies Optical Character Recognition (OCR). It allows developers to extract text effortlessly from images and scanned documents. In this project, EasyOCR is used for text extraction from business cards.

Features of EasyOCR
Easy installation with a single pip command.
Minimal dependencies, making it easy to set up.
Importing the library with a single import statement.
Simple two-line code for OCR, initializing the Reader class and performing OCR on an image.
Project Overview
BizCardX is a user-friendly tool for extracting information from business cards. It employs OCR technology to recognize text on business cards and uses regular expressions for classification. Users can access the extracted information through a Streamlit-based graphical user interface. The application guides users in uploading business card images, extracting data, and presenting it in an organized manner. Users can easily add this data to the database and perform operations like reading, updating, and deleting.

Libraries/Modules Used
Pandas (for creating a DataFrame with scraped data)
mysql.connector (for data storage and retrieval)
Streamlit (for creating the graphical user interface)
EasyOCR (for text extraction from images)
Features
Extracts text information from business card images using EasyOCR.
Utilizes OpenCV for image preprocessing, including resizing, cropping, and enhancement.
Uses regular expressions (RegEx) for parsing and extracting specific fields such as names, designations, contact details, and more.
Stores extracted information in a MySQL database for easy retrieval and analysis.
Provides a user-friendly interface built with Streamlit for uploading images, extracting information, and viewing/updating the database.
Workflow
To use BizCardX Data Extraction:

Install required libraries: Streamlit, mysql.connector, pandas, and EasyOCR using pip install.

Start the app with menu options: HOME, UPLOAD & EXTRACT, MODIFY.

Upload a business card to extract its text using EasyOCR.

Classified data is displayed and can be edited if needed.

Click "Upload to Database" to store the data in the MySQL database.

Use the MODIFY menu to access and perform Read, Update, and Delete operations on the uploaded data in the SQL Database.

Note
Ensure that you provide the necessary connection details (host, user, password, database name) in the code to establish a connection with the MySQL database.
