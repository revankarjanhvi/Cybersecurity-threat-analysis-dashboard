# 🔐 Cybersecurity Threat Analysis Dashboard

## 📌 Project Overview
This project presents an end-to-end **Cybersecurity Threat Analysis Dashboard** built using Power BI.  
It analyzes global cyber attack data from **2015 to 2024** to identify trends, high-risk vulnerabilities, attack sources, and the effectiveness of defense mechanisms.

## 🎯 Objectives
- Analyze cyber attack trends over time and across countries  
- Identify high-risk industries and critical vulnerabilities  
- Evaluate attack sources and their patterns  
- Assess defense mechanisms and incident response efficiency  
- Generate actionable insights to reduce cyber risks  


## 📊 Dataset Details
- **Source:** Cybersecurity Threat Dataset  
- **Time Period:** 2015–2024  
- **Total Records:** ~3000+ cyber attack incidents  

### 🔑 Key Fields:
- Attack_ID – Unique identifier for each attack  
- Country – Location where the attack occurred  
- Year – Time of attack  
- Target Industry – Industry affected  
- Financial Loss (Million $) – Economic impact  
- Affected Users – Number of users impacted  
- Attack Source – Nation-State, Insider, Hacker Group, Unknown  
- Vulnerability Type – Zero-day, Social Engineering, Unpatched Software, etc.  
- Defense Mechanism – Firewall, Antivirus, Encryption, VPN, AI Detection  
- Resolution Time (Hours) – Time taken to resolve the attack  

## 🛠️ Tools & Technologies
- **Power BI** – Data visualization and dashboard creation  
- **Power Query** – Data cleaning and transformation  
- **DAX (Data Analysis Expressions)** – KPI and measure creation  
- **Microsoft Excel** – Data source  


## 🧹 Data Processing & Transformation

### 🔹 Data Cleaning
- Removed duplicate records using Attack_ID  
- Handled missing/null values  
- Standardized inconsistent category names  
- Corrected data types for numerical and categorical fields  


## 📊 Key DAX Measures
- Total Attacks = COUNT(Attack_ID)  
- Total Financial Loss = SUM(Financial Loss)  
- Total Affected Users = SUM(Affected Users)  
- Avg Resolution Time = AVERAGE(Resolution Time)  
- High Loss Attacks = Attacks with loss > 50M  
- Fast Resolution % = Fast resolved / Total attacks  
- Attack Growth % (Year-over-Year)  


## 📈 Dashboard Structure

### 🟣 Page 1: Overview
**Key Question:** What is the overall impact of cyber attacks?

- KPI cards: Total Attacks, Loss, Users, Resolution Time  
- Year-wise trend analysis  
- Country-wise attack distribution  
- Industry-wise financial loss  
- Attack source breakdown  


### 🟣 Page 2: Threat Analysis
**Key Question:** What vulnerabilities drive cyber attacks?

- Vulnerability distribution  
- Attack source vs vulnerability analysis  
- Industry risk breakdown  
- Loss category segmentation  
- High-loss attack identification  

### 🟣 Page 3: Defense & Response
**Key Question:** How effective are defense mechanisms?

- Defense mechanisms vs attacks  
- Resolution time analysis  
- Response speed distribution  
- Scatter plot: Resolution time vs financial loss  


### 🟣 Page 4: Actionable Insights
**Key Question:** What actions should organizations take?

- Top high-risk countries  
- Top industries by financial loss  
- Most dangerous vulnerabilities  
- Slow response areas  
- Summary insights and recommendations  

## 🔍 Key Insights
- Cyber attacks are **increasing year by year**, indicating a growing threat landscape  
- **Banking and IT sectors** face the highest financial losses  
- **Zero-day vulnerabilities and social engineering attacks** are most critical  
- Majority of attacks originate from **external sources (nation-state & unknown)**  
- **Delayed response significantly increases financial damage**  
- Large number of users affected indicates **mass-scale breaches**  

## ✅ Recommendations
- Improve **incident response time** to reduce financial impact  
- Strengthen **employee awareness programs** to prevent phishing attacks  
- Adopt **advanced security solutions** such as AI-based threat detection  
- Focus on **high-risk industries and countries**  
- Conduct **regular system updates and security audits**  

## 👤 Author
**Janhvi J Revankar**  
