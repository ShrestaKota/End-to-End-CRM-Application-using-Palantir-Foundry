# End-to-End-CRM-Application-using-Palantir-Foundry
# 📊 CRM Application in Palantir Foundry

## Overview
This project demonstrates the end-to-end development of a CRM (Customer Relationship Management) application using **Palantir Foundry**. The goal was to transform messy input data into a clean, interactive CRM dashboard that allows users to explore people and company details and gain insights into company revenue across industries.

---

## 📁 Project Structure

### 1. **Data Cleaning & Pipeline Development**
- Loaded two raw Excel datasets: `People` and `Company`.
- Cleaned inconsistent fields such as phone numbers, company names, and extra suffixes (`Inc.`, `LLC`, etc.).
- Used transforms like:
  - `Regex Replace`
  - `String Before Delimiter`
  - `Explode Array`
  - `Trim Whitespaces`
- Joined datasets using an **Outer Join** on company name to retain all information.
- Generated unique `ID` values using a **Window transformation**.
- Output published as a clean dataset `Sk_DataSet`.

📸 _Pipeline Screenshot_  
![image](https://github.com/user-attachments/assets/c9723183-3748-4f8a-a491-43df34293a51)


---

### 2. **Ontology Modeling**
- Created ontology object `Sk Data Set` using the final cleaned dataset.
- Assigned action types: `Create`, `Edit`, and `Delete`.
- Enabled data modification, aligning with real-world CRM use cases.

📸 _Ontology View_  
![image](https://github.com/user-attachments/assets/e12b19b0-629d-4f80-9dd7-f0f0617bf5af)
 
![image](https://github.com/user-attachments/assets/d7fd742a-3e84-4ec0-81ca-3ea7da201db5)


---

### 3. **Workshop Dashboard**
- Built a **Foundry Workshop dashboard** named `Shresta_CRM`.
- Filters for: Name, Company, Email, Phone Number, Industry
- Chart: **Company vs Revenue** grouped by industry segments.
- Table: All person–company records displayed with full details.

📸 _CRM Dashboard_  
![image](https://github.com/user-attachments/assets/3ea074ec-2e8d-45e0-aed2-18c38abca49c)


---

## 🧠 Key Features
- 🔍 Data Cleaning & Standardization with Regex
- 🔗 Entity Linking via Joins
- 🧱 Ontology-driven object modeling
- 📈 Visual dashboard for real-time exploration
- 🪄 Full interactivity with Workshop filters

---

## 📝 Author

**Shresta Kota**  
[LinkedIn](https://www.linkedin.com/in/shresta-kota-1879241a4) • [Email](mailto:shrestakota9441@gmail.com)

---

