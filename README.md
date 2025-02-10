# Data-Analytics-and-Visualization
This repository contains the R script and dataset used for Data Analytics and Visualization Assignments. The script performs various data processing and statistical analysis tasks on various datasets each mentioned below.

# Assignment 1: 


**Description:**
    This repository contains the R script and dataset used for Data Analytics and Visualization Assignment 1. The script performs various data processing and statistical analysis tasks on the State Wise Udyam Registration Details dataset.
  
**Dataset**
The dataset to be used is from the Ministry of Micro, Small & Medium Enterprises (MSME) Udyam Registration, which includes data from the Udyam Assist Platform (UAP). The dataset is available at the following links: The dataset includes six key fields:
**Micro**

**Small**

**Medium**

**Total Udyam**

**IMEs (UAP)**

**Total MSMEs**

The Datasets can be found using the below links:

 https://dashboard.msme.gov.in/Udyam_Statewise.aspx
 
 https://www.data.gov.in/catalog/udyam-registration-msme-registration

**Features & Functionality**

The script performs the following steps:

**1. Data Import and Preprocessing**

  i. Reads the dataset from a CSV file.

  ii. Displays the raw data.
  
  iii. Removes the last row (Total) to avoid skewing the analysis.
  
  iv. Converts numeric columns to integer format after removing commas.

**2. Descriptive Statistics Calculation**
  
  i. Computes Mean, Median, Variance, and Standard Deviation for each numerical column.
  
  ii. Displays summary statistics in a structured table format.

**3. Correlation Analysis**
  
  i. Computes correlation between each field and every other field.
  
  ii. Generates and prints a Correlation Matrix to understand interdependencies.

**How to Run the Code**

**1. Clone the repository:**

        git clone <repository-url>

**2. Open the R environment or RStudio.**

**3. Load the necessary package:**

        library(dplyr)

**4. Run the script in R.**
