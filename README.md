# Invoice-Data-Simplified

The project is a powerful tool designed to streamline the processing of scanned invoice PDF images. By harnessing the capabilities of this tool, users can transform complex, paper-based invoices into structured, JSON-formatted data, significantly simplifying the task of understanding and managing invoice information. This solution is ideal for users looking to expedite and optimize their invoice data comprehension, making it an invaluable resource for seamless further processing.




Key Features:
Scanned Invoice Processing: The project is tailored to work with scanned invoice PDF images. It uses advanced optical character recognition (OCR) technology to extract text and data from these images.
JSON Output: The tool's output is structured in JSON format, which is a universally recognized and easily parsable data format. This structured data simplifies the extraction of specific invoice details and their integration into various systems or applications.
Efficient Data Comprehension: The project's primary goal is to make invoice data easily comprehensible. It organizes data into logical structures, ensuring that users can quickly access and interpret important invoice details.
Seamless Further Processing: The JSON-formatted data generated by the tool is perfect for seamless further processing. Users can integrate this data into their financial systems, databases, or reporting tools with ease.





Benefits:
Time Savings: By automating the extraction and structuring of invoice data, this tool saves users significant amounts of time compared to manual data entry and processing.
Accuracy: The tool's OCR capabilities and data structuring ensure high accuracy in data extraction, reducing the risk of errors commonly associated with manual data input.
Compatibility: The JSON format allows for easy integration with a wide range of software applications, making it a versatile choice for different use cases.
Efficiency: Users can efficiently manage and analyze invoice data, enabling better financial decision-making and reporting.
Use Cases:
Accounting and Finance: This project is especially beneficial for professionals working in accounting and finance, as it simplifies the management of invoice data.
Business Automation: It can be integrated into automated business processes to ensure the efficient handling of invoices and financial transactions.
Data Analytics: The structured data can be analyzed for insights and trends, aiding in financial analysis and planning.




Instructions:
To run the code successfully, you need to install the following libraries:
import pytesseract
from pdf2image import convert_from_path
from tabula import read_pdf
import pandas as pd
import os
import re
import requests
import json

Some of the above libraries may already be installed on your PC. To install the remaining libraries, use the pip command in your command prompt. For example, run pip install library-name to install each library.
Additionally, in your code, make sure to specify the poppler_path variable.
When you run the code, it will prompt you to enter the file path of the input file. After entering the path and pressing the Enter key, the code will generate an output in JSON format. The output file will be saved in the same directory as the input file, and it will have the same name as the input file.
