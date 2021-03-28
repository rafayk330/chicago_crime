# **CRIME IN CHICAGO**
## **PROJECT SYNOPSIS**
> This project analyzes the crime scenario in the city of Chicago. The project analyzes datasets shared by the governmnet of Chicago online, and then comes up with interesting findings through which, important recommendations may be obtained.
___
## **TOOLS USED**
This project uses MySQL queries only. However, the queries have been used in conjunction with Python on Jupyter Notebooks. Hence, the tools may be listed as follows:
- MySQL (database)
- Python 3.8 (programming)
- Jupypter Notebook (IDE)
___

## **DATASET DESCRIPTION**
### ***1. Census Data - Selected socioeconomic indicators in Chicago, 2008-2012***
This dataset contains a selection of six socioeconomic indicators of public health significance and a “hardship index,” by Chicago community area, for the years 2008 – 2012. The indicators are the percent of occupied housing units with more than one person per room (i.e., crowded housing); the percent of households living below the federal poverty level; the percent of persons in the labor force over the age of 16 years that are unemployed; the percent of persons over the age of 25 years without a high school diploma; the percent of the population under 18 or over 64 years of age (i.e., dependency); and per capita income. Indicators for Chicago as a whole are provided in the final row of the table. See the full dataset description for more information at: https://data.cityofchicago.org/api/views/fwb8-6aw5/files/A5KBlegGR2nWI1jgP6pjJl32CTPwPbkl9KU3FxlZk-A?download=true&filename=P:\EPI\OEPHI\MATERIALS\REFERENCES\ECONOMIC_INDICATORS\Dataset_Description_socioeconomic_indicators_2012_FOR_PORTAL_ONLY.pdf
### ***2. Chicago Public Schools - Progress Report Cards (2011-2012)***
This dataset shows all school level performance data used to create CPS School Report Cards for the 2011-2012 school year. 
https://data.cityofchicago.org/api/assets/B6741303-EA32-467D-9E33-5CE949ACCDD8
### ***3. Crimes - 2001 to Present***
This dataset reflects reported incidents of crime (with the exception of murders where data exists for each victim) that occurred in the City of Chicago from 2001 to present, minus the most recent seven days. Data is extracted from the Chicago Police Department's CLEAR (Citizen Law Enforcement Analysis and Reporting) system. In order to protect the privacy of crime victims, addresses are shown at the block level only and specific locations are not identified. Should you have questions about this dataset, you may contact the Research & Development Division of the Chicago Police Department at PSITAdministration@ChicagoPolice.org. Disclaimer: These crimes may be based upon preliminary information supplied to the Police Department by the reporting parties that have not been verified. The preliminary crime classifications may be changed at a later date based upon additional investigation and there is always the possibility of mechanical or human error. Therefore, the Chicago Police Department does not guarantee (either expressed or implied) the accuracy, completeness, timeliness, or correct sequencing of the information and the information should not be used for comparison purposes over time. The Chicago Police Department will not be responsible for any error or omission, or for the use of, or the results obtained from the use of this information. All data visualizations on maps should be considered approximate and attempts to derive specific addresses are strictly prohibited. The Chicago Police Department is not responsible for the content of any off-site pages that are referenced by or that reference this web page other than an official City of Chicago or Chicago Police Department web page. The user specifically acknowledges that the Chicago Police Department is not responsible for any defamatory, offensive, misleading, or illegal conduct of other users, links, or third parties and that the risk of injury from the foregoing rests entirely with the user. The unauthorized use of the words "Chicago Police Department," "Chicago Police," or any colorable imitation of these words or the unauthorized use of the Chicago Police Department logo is unlawful. This web page does not, in any way, authorize such use. Data are updated daily. To access a list of Chicago Police Department - Illinois Uniform Crime Reporting (IUCR) codes, go to http://data.cityofchicago.org/Public-Safety/Chicago-Police-Department-Illinois-Uniform-Crime-R/c7ck-438e
___
## **METHODOLOGY**
### **Step-01: Downloading the Libraries and Modules**
The important libraries and modules may be downloaded first. The following modules are important to (a) establish a connection between MySQL and Pandas on Jupyter Notebook, and (b) run queries using the same IDE:
1. download_pandoc
2. pandas
3. mysql.conncector
4. create_engine
### **Step-02: Load the MySQL Extension**
Load the extension by providing the necessary credentials.
### **Step-03: Display the Tables Stored in the Database**
In order to verify and validate a successful upload, display the database tables.
___
## **ANALYSIS**
### ***Total Number of Recorded Crimes***
![MySQL Query](1.jpg "Total Number of Recorded Crimes in Chicago")
### ***Top Rows from the CRIME Table***
![MySQL Query](2.jpg "First 10 Rows from CRIME")
### ***Crimes Involving an Arrest***
![MySQL Query](3.jpg "CRIMES = ARREST")
### ***Crimes at a Gas Station***
![MySQL Query](4.jpg "Crimes at a Gas Station")
### ***Community Areas***
![MySQL Query](5.jpg "Community Areas")
### ***Schools that are "Healthy-School" Certified***
![MySQL Query](6.jpg "Schools that are "Healthy-School" Certified")
### ***Average School Safety Score***
![MySQL Query](7.jpg "Average School Safety Score")
### ***Top Five Community Areas***
![MySQL Query](8.jpg "Top Five Community Areas")
### ***Community Area With the Least Value of Safety Score of Schools***
![MySQL Query](9.jpg "Community Area With the Least Value of Safety Score of Schools")
### ***Per-Capita Income Using Sub-Queries***
![MySQL Query](10.jpg "Per-Capita Income Using Sub-Queries")
___
## **SUMMARY AND REFLECTION**
This project tests some of the basic concepts of MySQL and integrates the engine startup of MySQL using an IDE. It may not be considered as a proper data analysis capstone project. However, it may, nevertheless, be considered adequate as a learninng resource for those interested in exploring further the wide variety of advanced topics in SQL.
> All rights related to the published dataset are reserved with the issuing authorities of the same (Government of Chicago).

> The projecct may be used only as a learning resource; no part of the same must be copied for any other usage whatsover.