# 📞 Customer Call List – Data Cleaning Project

This project focuses on cleaning and preparing a customer call list for further use in marketing or customer outreach. The dataset contained unstructured and inconsistent data such as missing values, unwanted characters, and formatting issues, which were resolved using Python and regular expressions.

---

## 📁 Dataset Overview

- **Source:** Excel file (`Customer Call List.xlsx`)
- **Content:** Names, Phone Numbers, Addresses, and Contact Preferences
- **Issues Handled:**  
  - Duplicate rows  
  - Inconsistent formatting in names and phone numbers  
  - Unstructured address field  
  - Placeholder and irrelevant data  
  - Cleaning up "Do Not Contact" flags

---

## 🎯 Objectives

- Remove duplicate and non-useful records
- Standardize text fields (names, contact preferences)
- Format phone numbers into a consistent structure
- Split the full address into structured fields
- Filter out customers who should not be contacted

---

## 🧰 Tools & Libraries Used

- **Python**
  - `pandas` – Data wrangling and cleaning
  - `re` – Regular expressions for text and phone number cleaning
  - `numpy` – Handling missing values

---

## 🔧 Key Cleaning Steps

- Dropped duplicate records and unnecessary columns
- Trimmed special characters from `Last_Name` field
- Used regular expressions to clean and format `Phone_Number` into `XXX-XXX-XXXX`
- Split `Address` column into `Street_Address`, `State`, and `Zip_Code`
- Standardized `Do_Not_Contact` column to "Y" and "N"
- Filtered out records marked as "Do Not Contact" or with missing flags
- Reset index after cleaning

---

## 📊 Result

The final cleaned dataset is ready for use in outbound marketing or analysis, containing only valid, contactable customers with structured and normalized fields.

---

## 📬 Contact

**Eichi Thu**  
🌐 [Portfolio Website](https://eichitportfolio.framer.website)  
📧 eichithu@email.com  
📍 Thailand  
