<!-- PROJECT TITLE -->
# 🎓 Web Scraping
### 📌 Data Extraction & Processing

<p align="center">
  <img src="https://img.shields.io/badge/Language-Python-blue?logo=python">
  <img src="https://img.shields.io/badge/Library-BeautifulSoup-orange">
  <img src="https://img.shields.io/badge/Library-Pandas-green">
  <img src="https://img.shields.io/badge/Library-Requests-red">
</p>

---

## 📋 Table of Contents
- [Ethical Disclaimer](#-ethical-disclaimer)
- [Project Overview](#-project-overview)
- [Technologies Used](#-technologies-used)
- [Key Features](#-key-features)
- [Installation & Usage](#-installation--usage)
- [Code Implementation](#-code-implementation)
- [Output Results](#-output-results)
- [Assignment Information](#-assignment-information)
- [How to Run](#-how-to-run-this-project-for-clients)
- [Author](#-author)


---
### ⚠️ Ethical Disclaimer

This project is created for educational purposes only.  
It follows ethical scraping practices and does not misuse scraped data.


## 🧾 Project Overview

This project demonstrates ***Web Scraping**, **Data Mining**, and **Data Processing** using Python.  
The goal is to scrape faculty and staff information from the **University of Pittsburgh at Bradford Directory** and convert it into a structured dataset using **Pandas**.

🔎 **Scraped Page:**  
[https://www.upb.pitt.edu/directory](https://www.upb.pitt.edu/directory)

---

## 🛠️ Technologies Used

| Library | Role |
|---------|------|
| **Requests** | Fetches HTML content from the website |
| **BeautifulSoup (bs4)** | Parses and extracts HTML elements |
| **Pandas** | Organizes and exports data to CSV |

---

## 📌 Key Features

- ✔ Web scraping using HTTP requests  
- ✔ Data parsing and cleaning  
- ✔ Converts unstructured HTML to DataFrame  
- ✔ Saves results into a CSV file  
- ✔ CSV is reloaded and verified  
- ✔ Error handling for robust scraping  
- ✔ Data validation and cleaning

---

## 📦 Installation & Usage

### 🔧 Step 1: Install Requirements
```bash
pip install requests beautifulsoup4 pandas lxml
```
## 🚀 Step 2: Run the Notebook

###### Open the project in PyCharm or Jupyter Notebook and run:
```bash
jupyter notebook Assignment1.ipynb
```
## 💾 Step 3: Output

###### Running the notebook automatically generates:

### 📊 Sample Output Structure

| Name       | Last Name     | Position | Role             | Location    |
|------------|-----------|------------|-----------------|----------|
| Angela   | Alexis | Financial Aid Counselor   | Financial Aid    | 106 Hangar Building |
|Elinam|Amevor|Professor of Communications|Division of Communication and the Arts|108 Blaisdell Hall|

*(a sample of cleaned data.)*

 
---

### 👨‍🏫 Assignment Information

| Field     | Details                                             |
|-----------|-----------------------------------------------------|
| Student   | Khairullah Ibrahim Khail                            |
| Program   | MS Data Science                                     |
| Course    | Advanced Tools and Techniques                       |
| Professor | Dr. Bahar Ali                                      |
| Institute | Institute of Management Sciences, Peshawar         |

 


 


  

### ✅ How a client can run your project from your GitHub repo:

1. Go to your repository URL:  
   [https://github.com/Sahil3044/University-Directory-Web-Scraping](https://github.com/Sahil3044/University-Directory-Web-Scraping)

2. Clone the repo to their machine:

```bash
git clone https://github.com/Sahil3044/University-Directory-Web-Scraping.git
cd University-Directory-Web-Scraping
```
3. Install required Python packages:
```bash
pip install requests beautifulsoup4 pandas lxml
```
4. Open the notebook Assignment1.ipynb in Jupyter Notebook or PyCharm.
5. Run all cells. Output CSV (Assignment1.csv) will be automatically generated.
### ✨ Author

👨‍🎓 Khairullah Ibrahim Khail  
MS Data Science Student  
Institute of Management Sciences, Peshawar

<p align="center">⭐ If you like this project, consider giving it a star on GitHub!</p>
