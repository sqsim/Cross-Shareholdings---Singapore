1)Folder : raw_data
==============================================
a)File:2018_stocklist_updated.csv 

This file have all the details for each listed company in 2018
such as name,sector,investmen type ,etc.
Information taken from web scraping

b)File:STI Top 30.xlsx

This file is manually copied from the SGX
===============================================

2)Folder : PDF Scraping
===============================================
The notebook is numbered in execution order
Notebook:
a)PDF Scrape
Is the scraping of shareholders in a table from the PDF

b)Semi-Manual Extraction
If unable to locate the page and extract in PDF Scrape,use this to extract.
if unable to extract only manual method is left

c)Data Cleaning
Clean extracted data base on a case by case basis,
need to alter code to fit each case

d)Standard naming of cleaned csv
Standardised the naming convention of the stakeholders in the csv

e)Standard naming of cleaned csv
Standardised the naming convention of the listed companies in the 
file 2018_stocklist_updated.csv 

f)Create Cross Shareholdings matrix
Create Cross Shareholdings matrix with direct and indirect shares

Folder:
a)cleaned_shareholder(direct shares)
csv files that are cleaned and can be used to create the matrix

b)indirect shares
This csv files are manually created after looking at the PDF,
as some of the shareholders mask their ownership.

c)pdf_files
all the pdf_files

d)uncleaned_csv
raw files after pdf extraction
===============================================

3)Folder : Graphing
===============================================
Notebook:
a)NetworkX Listed Companies
Analysis and plotting of the final graph

Folder:
a)merge_data(the matrix)
The Final Graph Data

b)figures and indicators
All the saved figures and analysis


