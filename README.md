<div align="center">

# 🛡️ Enterprise Cybersecurity Incident & Threat Intelligence Analysis

### 🔐 Security Operations Center (SOC) Database System

[![Python](https://img.shields.io/badge/Python-3.13-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![MySQL](https://img.shields.io/badge/MySQL-8.4.7-orange?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![AWS](https://img.shields.io/badge/AWS-RDS-yellow?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/rds/)
[![Pandas](https://img.shields.io/badge/Pandas-2.3.3-green?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.10.7-purple?style=for-the-badge&logo=plotly&logoColor=white)](https://matplotlib.org/)

<img src="https://img.shields.io/badge/Team-Syntax%20Soldiers-red?style=for-the-badge" alt="Team"/>
<img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" alt="Status"/>
<img src="https://img.shields.io/badge/License-Academic-lightgrey?style=for-the-badge" alt="License"/>

---

### 👥 **Team Syntax Soldiers**
**Swasthika Rajendran** • **Moses Kanagaraj** • **Riya Gupta**

---

</div>

## 🎯 Project Overview

<table>
<tr>
<td width="50%">

### 🚀 **What We Built**
A **comprehensive Security Operations Center (SOC)** database system for enterprise cybersecurity management with:

✨ **14 Interconnected Tables**  
🔍 **Real-time Threat Intelligence**  
📊 **8 Advanced Analytics Queries**  
☁️ **AWS Cloud Deployment**  
🎨 **Interactive Dashboards**  
🔐 **Role-Based Access Control**  

</td>
<td width="50%">

### 🎯 **Key Features**
- 🛡️ Incident tracking and management
- 🌐 Threat intelligence monitoring  
- 🚨 Alert correlation and escalation
- 💻 Asset and vulnerability management
- 📡 Network traffic analysis
- 👤 User activity monitoring
- 📈 Interactive analytics dashboard
- 🔒 Multi-level security controls

</td>
</tr>
</table>

---

## 🗂️ Project Architecture

```
🏗️ Enterprise-Cybersecurity-Analysis/
│
├── 📁 step1_topic_selection/          # 🎯 Domain analysis & business requirements
│   └── README.md
│
├── 📁 step2_database_design/          # 🎨 ERD & database schema design
│   └── README.md
│
├── 📁 step3_implementation/           # 💾 Database implementation
│   ├── 📁 ddl/
│   │   └── create_tables.sql         # 🔧 14 table definitions
│   ├── 📁 dml/
│   │   └── insert_data.sql           # 📝 Sample security data
│   └── README.md
│
├── 📁 step4_deployment/              # ☁️ AWS RDS deployment
│   ├── indexes.sql                   # ⚡ Performance optimization
│   ├── views.sql                     # 👁️ Security analytics views
│   ├── triggers.sql                  # 🔔 Automated incident tracking
│   ├── stored_procedures.sql         # 🔧 Business logic
│   ├── user_management.sql           # 🔐 Role-based access control
│   └── README.md
│
├── 📁 step5_analytics_dashboard/     # 📊 Python analytics dashboard
│   ├── 686.py                        # 🎨 Main dashboard generator
│   ├── SOC_Analytics_Colab.ipynb     # 📓 Jupyter/Colab notebook
│   ├── MATPLOTLIB_DASHBOARD.html     # 🌐 Generated dashboard
│   ├── analytical_queries.sql        # 🔍 8 analytical queries
│   ├── 📁 charts/                    # 📈 Generated visualizations
│   └── README.md
│
├── 📁 .venv/                         # 🐍 Python virtual environment
├── requirements.txt                  # 📦 Python dependencies
└── README.md                         # 📖 You are here!
```

---

<div align="center">

## 🚀 Quick Start Guide

</div>

### 1️⃣ **Clone the Repository**

```bash
git clone https://github.com/swasthi-raj/Enterprise-Cybersecurity-Analysis.git
cd Enterprise-Cybersecurity-Analysis
```

### 2️⃣ **Setup Python Environment**

```powershell
# Windows PowerShell - Run directly from venv
.\.venv\Scripts\python.exe step5_analytics_dashboard\686.py
```

### 3️⃣ **Install Dependencies**

```powershell
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
```

### 4️⃣ **Database Configuration**

<table>
<tr>
<td width="30%"><b>🌐 Host</b></td>
<td>soc-db-instance.clg6uiiq0hr9.us-east-1.rds.amazonaws.com</td>
</tr>
<tr>
<td><b>💾 Database</b></td>
<td>soc_db</td>
</tr>
<tr>
<td><b>📊 Tables</b></td>
<td>14 interconnected security tables</td>
</tr>
<tr>
<td><b>☁️ Platform</b></td>
<td>AWS RDS MySQL 8.4.7</td>
</tr>
</table>

---

## 💾 Database Schema

<div align="center">

### 🎯 **14 Core Security Tables**

</div>

<table>
<tr>
<td width="33%">

#### 👥 **Personnel & Organization**
- 🧑‍💼 `employees`
- 🏢 `departments`
- 👤 `users`

</td>
<td width="33%">

#### 🚨 **Security Operations**
- 🔴 `incidents`
- ⚠️ `alerts`
- 📋 `detection_rules`
- 🔗 `incident_iocs`

</td>
<td width="33%">

#### 🌐 **Infrastructure**
- 💻 `assets`
- 🔓 `asset_vulnerabilities`
- 📡 `network_logs`
- 🔌 `network_connections`

</td>
</tr>
<tr>
<td colspan="3" align="center">

#### 🎯 **Threat Intelligence**
🎭 `threat_actors` • 🔍 `iocs` (Indicators of Compromise) • 📰 `threat_intel`

</td>
</tr>
</table>

---

## 📈 Analytics Dashboard - 8 Key Questions

<table>
<tr>
<td width="50%">

### 🎯 **Q1: Departmental Risk Density**
```
📊 Quadrant Analysis
🎯 High-severity incidents per employee/asset
🔍 Identifies high-risk departments
```

### 🎯 **Q2: Incident Response Timing**
```
⏱️ MTTD - Mean Time To Detect
🛡️ MTTC - Mean Time To Contain
✅ MTTR - Mean Time To Resolve
📈 Performance metrics by severity
```

### 🎯 **Q3: Threat Actor Mapping**
```
🎭 Threat actor analysis
💰 Motivation tracking
🎯 Sophistication levels
🔗 Incident attribution
```

### 🎯 **Q4: Network Traffic Analysis**
```
📡 Traffic volume distribution
🌐 Source category breakdown
⚠️ Alert correlation
🔍 Anomaly detection
```

</td>
<td width="50%">

### 🎯 **Q5: Alert Escalation Rate**
```
🚨 Alert → Incident conversion
📊 False positive identification
📈 Escalation trends by severity
🎯 SOC efficiency metrics
```

### 🎯 **Q6: User Privilege Risk**
```
👤 User privilege analysis
⚠️ Alert rates by access level
🔴 Incident correlation
🎯 Insider threat indicators
```

### 🎯 **Q7: IOC Confidence & Impact**
```
🔍 Indicator of Compromise types
📊 Confidence scoring
🎯 Incident correlation
📈 Threat impact assessment
```

### 🎯 **Q8: Temporal Alert Spikes**
```
⏰ 24-hour cycle analysis
📊 Anomaly detection
🎯 Attack pattern recognition
⚡ Real-time spike alerts
```

</td>
</tr>
</table>

### Running the Dashboard

**Python Script:**
```powershell
cd step5_analytics_dashboard
..\​.venv\Scripts\python.exe 686.py
```

**Jupyter Notebook:**
- Open `SOC_Analytics_Colab.ipynb` in Jupyter or Google Colab
- Run all cells to generate inline visualizations
- Dashboard HTML automatically generated

---

<div align="center">

## 🛠️ Technology Stack

</div>

<table align="center">
<tr>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/MySQL-8.4.7-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
<br><b>Database Engine</b>
<br>AWS RDS Cloud
</td>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/Python-3.13-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
<br><b>Programming</b>
<br>Analytics & Automation
</td>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/Pandas-2.3.3-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
<br><b>Data Analysis</b>
<br>Data Manipulation
</td>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/Matplotlib-3.10.7-11557c?style=for-the-badge&logo=plotly&logoColor=white" alt="Matplotlib"/>
<br><b>Visualization</b>
<br>Chart Generation
</td>
</tr>
</table>

### 📦 **Python Libraries**

| Library | Version | Purpose |
|---------|---------|---------|
| 🐼 **pandas** | 2.3.3 | Data manipulation and analysis |
| 🔗 **sqlalchemy** | 2.0.44 | Database connectivity |
| 🐬 **pymysql** | 1.1.2 | MySQL driver |
| 📊 **matplotlib** | 3.10.7 | Static chart generation |
| 🔢 **numpy** | 2.3.5 | Numerical computing |
| 🔌 **mysql-connector** | 9.5.0 | Alternative MySQL connector |

---

<div align="center">

## 🔐 Security Features

</div>

<table>
<tr>
<td width="50%">

### 👥 **User Role Management**

```diff
+ 🔴 Admin
  Full database access and management
  
+ 🟡 Data Entry
  Insert/update capabilities
  
+ 🟢 Read-Only
  Query and view permissions only
```

</td>
<td width="50%">

### 🛡️ **Database Objects**

```yaml
⚡ Indexes:
  - Optimized query performance
  - Critical table acceleration

👁️ Views:
  - Pre-built analytical queries
  - Common use case templates

🔔 Triggers:
  - Automated incident tracking
  - Real-time alert escalation

🔧 Stored Procedures:
  - Complex business logic
  - Encapsulated operations
```

</td>
</tr>
</table>

---

<div align="center">

## 📊 Visualizations & Outputs

</div>

<table>
<tr>
<td width="33%" align="center">

### 📈 **Chart Types**

🔵 Scatter Plots  
📊 Bar Charts  
📉 Line Graphs  
🥧 Pie Charts  
📱 Multi-Panel Dashboards

</td>
<td width="33%" align="center">

### 🎨 **Output Quality**

⚡ **300 DPI** Resolution  
🖼️ PNG Image Format  
🌐 HTML Dashboards  
📓 Jupyter Notebooks  
💎 Production Ready

</td>
<td width="33%" align="center">

### 📁 **File Formats**

`charts/*.png`  
PNG images

`MATPLOTLIB_DASHBOARD.html`  
Interactive HTML

`SOC_Analytics_Colab.ipynb`  
Jupyter notebook

</td>
</tr>
</table>

---

<div align="center">

## ✨ Key Features

</div>

<table>
<tr>
<td width="50%">

### 🎯 **Technical Highlights**

```
✅ 14 Interconnected Tables
   Comprehensive security data model

☁️ AWS RDS Deployment
   Cloud-based scalable infrastructure

🔐 Role-Based Access Control
   Secure multi-user environment

📊 8 Analytical Queries
   Deep security insights
```

</td>
<td width="50%">

### 🚀 **Advanced Features**

```
⚡ Automated Triggers
   Real-time incident tracking

🔍 Performance Indexes
   Optimized query execution

🎨 Python Dashboard
   Interactive data visualization

📓 Jupyter Notebook
   Portable analysis environment
```

</td>
</tr>
</table>

---

## 👥 Team Information

**Team Name:** Syntax Soldiers

**Group Members:**
1. Swasthika Rajendran
2. Moses Kanagaraj
3. Riya Gupta

---

## 📚 Documentation

Detailed documentation available in each directory:
- [Step 1: Domain Selection](step1_topic_selection/README.md)
- [Step 2: Database Design](step2_database_design/README.md)
- [Step 3: Implementation](step3_implementation/README.md)
- [Step 4: AWS Deployment](step4_deployment/README.md)
- [Step 5: Analytics Dashboard](step5_analytics_dashboard/README.md)

---

<div align="center">

## 🎯 Usage Examples

</div>

### 🎨 **Generate Dashboard**

```powershell
# Navigate to dashboard directory
cd step5_analytics_dashboard

# Run dashboard generator
..\​.venv\Scripts\python.exe 686.py

# 🎉 Output: MATPLOTLIB_DASHBOARD.html opens in browser
# 📊 Charts saved to: charts/*.png
```

### 📓 **Run Jupyter Notebook**

```bash
# Upload SOC_Analytics_Colab.ipynb to Google Colab
# Or run locally with Jupyter
jupyter notebook SOC_Analytics_Colab.ipynb
```

### 🔍 **Query Database Directly**

```python
from sqlalchemy import create_engine
import pandas as pd

# Connect to AWS RDS
engine = create_engine('mysql+pymysql://admin:password@host/soc_db')

# Query critical incidents
df = pd.read_sql("SELECT * FROM incidents WHERE severity='critical'", engine)
```

---

<div align="center">

## 📚 Documentation

**Detailed documentation available in each directory**

[![Step 1](https://img.shields.io/badge/📖_Step_1-Domain_Selection-blue?style=for-the-badge)](step1_topic_selection/README.md)
[![Step 2](https://img.shields.io/badge/📖_Step_2-Database_Design-green?style=for-the-badge)](step2_database_design/README.md)
[![Step 3](https://img.shields.io/badge/📖_Step_3-Implementation-orange?style=for-the-badge)](step3_implementation/README.md)
[![Step 4](https://img.shields.io/badge/📖_Step_4-AWS_Deployment-yellow?style=for-the-badge)](step4_deployment/README.md)
[![Step 5](https://img.shields.io/badge/📖_Step_5-Analytics_Dashboard-purple?style=for-the-badge)](step5_analytics_dashboard/README.md)

</div>

---

<div align="center">

## 👥 Meet the Team

### 🎖️ **Syntax Soldiers**

<table>
<tr>
<td align="center" width="33%">
<img src="https://img.shields.io/badge/👤-Swasthika_Rajendran-ff69b4?style=for-the-badge" alt="Swasthika"/>
</td>
<td align="center" width="33%">
<img src="https://img.shields.io/badge/👤-Moses_Kanagaraj-00d4ff?style=for-the-badge" alt="Moses"/>
</td>
<td align="center" width="33%">
<img src="https://img.shields.io/badge/👤-Riya_Gupta-ffcc00?style=for-the-badge" alt="Riya"/>
</td>
</tr>
</table>

</div>

---

<div align="center">

## 📄 License

**Academic Project** • MIS686 Enterprise Database Management

[![License](https://img.shields.io/badge/License-Academic-lightgrey?style=for-the-badge)](LICENSE)

---

### ⭐ **Star this repository if you find it helpful!**

[![GitHub stars](https://img.shields.io/github/stars/Enterprise-Cybersecurity-Analysis/SQL_Project?style=social)](https://github.com/Enterprise-Cybersecurity-Analysis/SQL_Project)

---

**Last Updated:** December 2025

<img src="https://img.shields.io/badge/Made_with-❤️_and_☕-red?style=for-the-badge" alt="Made with love"/>

</div>
