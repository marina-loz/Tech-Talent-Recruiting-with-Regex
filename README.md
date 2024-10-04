# 📑 HR Tech Talent Extraction: Resume Data Analysis

## 📝 Objective
The goal of this project is to analyze a large dataset of resumes to extract key details such as job titles, technical skills, and educational background using regular expressions. This analysis is aimed at identifying suitable candidates for tech-focused roles within a global HR consultancy.

## ❓ Key Questions
- How can regular expressions help extract job titles, tech skills, and education from resumes?
- How many qualified candidates possess relevant technical skills (Python, SQL, R, Excel)?
- How can this data be cleaned and organized for HR decision-making?

## 📊 Data
- **resumes.csv**: Contains the full text of resumes, with each record having:
  - `ID`: Unique identifier for each resume.
  - `Resume_str`: Full text of the resume.
  - `Category`: Job category indicating field expertise.

## 🧠 Approach
1. **Data Loading**: Loaded resumes.csv into a DataFrame.
2. **Regular Expressions**: Used regex to extract job titles, technical skills (Python, SQL, Excel, R), and educational qualifications (e.g., Bachelor, Master).
3. **Data Cleaning**: Filtered out resumes lacking relevant data for job titles, skills, or education.
4. **Data Organization**: Created a clean DataFrame containing essential columns for candidate identification.

## 📈 Results
- **Extracted Data**: Job titles, technical skills, and education were extracted from the resumes.
- **Filtered Candidates**: Generated a DataFrame of candidates meeting the requirements for tech-focused roles (Python, SQL, Excel, etc.).

## 🚀 Conclusion
The project demonstrates how regular expressions and data preprocessing can be used to extract meaningful information from resumes, aiding HR teams in identifying the right tech talent.

## 🛠️ Tools & Libraries
- **pandas**: Data manipulation
- **re**: Regular expressions for pattern matching
