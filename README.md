# AUTOMATED-REPORT-GENERATION

*COMPANY*: CODTECH IT SOLUTIONS 

*NAME*: SHREYKUMAR SANDIPKUMAR PATEL

*INTERN ID*: CT04DL1307

*DOMAIN*: PYTHON PROGAMMING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION*:
              Task 2: Automated Report Generation Using Python and FPDF
In Task 2 of the internship project, I was tasked with creating an automated reporting system using Python. The goal was to read data from a file, analyze it, and generate a structured and readable report in PDF format using libraries like FPDF. This task mirrors real-world scenarios where businesses need quick, repeatable, and professional-looking reports generated from raw data.

Project Overview
To begin with, I created a simulated dataset that resembled a basic sales record. It included information such as the date of transaction, product sold, and the revenue generated for that product. I used the pandas library to construct this dataset as a DataFrame, which allowed for easy manipulation and storage. The dataset was then saved as a CSV file named sales_data.csv, mimicking how businesses often store daily records.

Data Analysis
Once the CSV was created, I read it back into the program using pandas.read_csv(). I performed a few basic analytics on the revenue data to summarize performance over the five-day period. Specifically, I calculated:

Total Revenue

Average Revenue

Maximum and Minimum Revenue

Top-performing Product

PDF Report Creation
For the reporting part, I used the FPDF library to generate a clean and readable PDF. After importing the library and initializing a PDF object, I formatted the report by setting fonts, creating headings, and aligning text.

The report included:

A title (“Sales Report”) centered at the top of the page

A summary of key metrics including total, average, min, and max revenue

The name of the top-performing product based on revenue
These metrics are commonly used in sales and financial reports to give an instant overview of business performance and identify trends or anomalies.

![sales report pdf](https://github.com/user-attachments/assets/bc78b169-e31b-4010-b577-22e2561f222e)
