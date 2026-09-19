<h1 align="center">Hi, I'm Mohib Qureshi 👋</h1>
<h3 align="center">Aspiring Data Analyst | Turning messy data into clear decisions</h3>

<p align="center">
  <a href="mailto:mohibqureshi101@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/mohib-qureshi/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" /></a>
</p>

---

### 👤 About Me

I'm a data analyst focused on data cleaning, SQL, and turning raw, inconsistent datasets into something reliable enough to actually make decisions from. I enjoy the "unglamorous" part of analytics most people skip past — finding the duplicate records, the mismatched category names, the five different date formats hiding in one column — because that's where a lot of real analysis actually breaks down.

I'm currently looking for **entry-level Data Analyst** opportunities where I can keep building on these skills.

---

### 🛠️ Skills & Tools

**Languages & Query Tools**
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)

**Libraries**
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)

**Visualization / BI**
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/PowerBI-F2C811?style=flat&logo=powerbi&logoColor=black)

**Databases**
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-56B9EB?style=flat&logo=snowflake&logoColor=white)

---

### 📂 Featured Projects

#### 🧹 [E-Commerce Data Cleaning (SQL)](https://docs.google.com/document/d/1kMVxWg8NrexyOsS0AZg-36K5PAkQxgQBMSPu1wuJlLs/edit?usp=sharing)
Cleaned a raw e-commerce orders dataset containing duplicate and conflicting records, inconsistent text formatting, invalid emails, mixed currency formatting, and five different date formats within a single column.

- Identified true duplicate rows vs. conflicting records sharing the same `order_id`, and resolved the difference by rebuilding a reliable surrogate key rather than discarding legitimate orders
- Standardized inconsistent categorical text (casing, whitespace, spelling variants) across `product_category` and `country`
- Cleaned and validated `email` addresses, correcting a recurring domain typo and nulling invalid entries
- Parsed `unit_price` out of three different currency formats into a clean numeric column
- Standardized `order_date` across five mixed date formats into a single `DATE` type using `COALESCE` + `STR_TO_DATE`

**Tools:** MySQL
**[📄 Full write-up](https://docs.google.com/document/d/1kMVxWg8NrexyOsS0AZg-36K5PAkQxgQBMSPu1wuJlLs/edit?usp=sharing)** · **[📁 Raw dataset (CSV)](https://docs.google.com/spreadsheets/d/187qOUQ6ga8kbSX7Qs4-Lk_iNj4HcRwDqgrInzgCbL1w/edit?usp=sharing)**

<!--
#### 📊 [Project Name 2](link-to-repo)
One or two sentences on what the project does and what you learned from it.
**Tools:** ...

#### 📈 [Project Name 3](link-to-repo)
One or two sentences on what the project does and what you learned from it.
**Tools:** ...
-->

---

#### 📊 [Insurance Policy & Claims Analysis (Power BI)](https://github.com/mohib7182/Insurance_Analysis_Project_Power_Bi)
Cleaned a 10,000-row insurance operations export in Power Query and built a Power BI dashboard comparing claims activity against premium income across five policy lines.

- Enabled full-dataset column profiling instead of the default 1,000-row sample, which exposed data quality issues invisible in the preview
- Removed duplicate policy records on `PolicyNumber`, confirming 10,000 distinct / 10,000 unique values afterward
- Diagnosed a ~60% type-conversion error rate on three date columns as a locale mismatch (DD-MM-YYYY read as month-first) and resolved it with *Change Type Using Locale* → English (United Kingdom)
- Built KPI cards and a quick measure for a claims-to-premium ratio, plus a Rejection Rate measure
- Surfaced the core finding: claims (≈16.9M) outpace premiums (≈5.97M) in every policy line — a ratio of ≈2.8x with a ≈43.5% rejection rate

**Tools:** Power Query, Power BI Desktop
**[📄 Full write-up](https://docs.google.com/document/d/1VzKag4eP6a_fUPd3oIlN3-hYs5vMuQa57WVlRxOtSRQ/edit?usp=sharing)** · **[📁 Raw dataset (CSV)](https://docs.google.com/spreadsheets/d/1DSz6TGdELZWczhQxy8d9lY3ogc4c3xBGdnsQPVxRoBM/edit?usp=sharing)**

---

### 📫 Let's Connect
Feel free to reach out if you'd like to discuss data, collaborate on a project, or just say hi.

<p align="left">
  <a href="mailto:mohibqureshi101@gmail.com">Email</a> •
  <a href="https://www.linkedin.com/in/mohib-qureshi/">LinkedIn</a>
</p>
