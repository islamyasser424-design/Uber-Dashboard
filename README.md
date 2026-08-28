# 🚀 Uber Performance Dashboard

An interactive, end-to-end Business Intelligence project built to analyze smart mobility operations, revenue growth, loss factors, and trip cancellations using Power BI.

## 📊 Project Overview
The dashboard consists of 5 main integrated pages designed to cover all operational and financial aspects:
1. **Home:** Interactive welcome landing page for seamless and smart navigation across dashboard sections.
2. **Overview:** High-level summary of total operations, core booking rates, and overall ride performance distribution.
3. **Revenue:** Precise financial tracking, revenue growth, and analysis of customer payment methods and channels.
4. **Losses:** Accurate monitoring of lost revenue, incomplete distances, and their direct impact on earnings.
5. **Cancellations:** In-depth breakdown and analysis of trip cancellations, root causes, and operational impact.

## 🗄️ Data Modeling & Architecture
* **Star Schema Design:** Built a robust relational schema with `Dataset` acting as the central Fact Table connected to dimensional tables (`Booking Status`, `Vehicle Type`, and `Date`).
* **Dedicated Measures Table:** Organized all advanced DAX formulas inside a clean, centralized `mesures` table for optimal maintenance and readability.

## 🔧 Technologies & Tools Used
* **Data Modeling:** Star Schema architecture ensuring high performance and reliable relationship management (1-to-Many).
* **Power Query & M Language:** Data extraction, cleaning, separation of tables, and transformation of texts/dates for error-free data readiness.
* **DAX Formulas:** Developed an advanced and complex suite of DAX measures (such as actual revenue calculations, unique customer counts, cancellation rates, and operational KPIs) to produce precise, filter-responsive analytics.
* **Dynamic Design:** A fully interactive visual design tailored for executive decision-making.

## 🖼️ Project Previews & Screenshots

### Data Model Architecture
![Data Model](Screenshot%202026-08-28%213908.png)

### Dashboard Pages
* **Home Page:**
  ![Home](Screenshot%202026-08-28%213541.png)
* **Overview Page:**
  ![Overview](Screenshot%202026-08-28%213607.png)
* **Revenue Page:**
  ![Revenue](Screenshot%202026-08-28%213621.png)
* **Lost Revenue Page:**
  ![Lost Revenue](Screenshot%202026-08-28%213635.png)
* **Cancellation Page:**
  ![Cancellation](Screenshot%202026-08-28%213651.png)

## 📂 Repository Contents
* `.pbix` file (Power BI dashboard)
* Cleaned dataset / source files
* Project preview screenshots

---
**🙏 Special Thanks:**
I would like to express my sincere gratitude to Instant Software Solutions for their continuous support. 
Special thanks to my instructors and mentors, **Eng. Abdelrahman Farraag** and **Eng. Ismail Mustafa**, for their valuable guidance, continuous support, and valuable knowledge throughout my learning journey.
