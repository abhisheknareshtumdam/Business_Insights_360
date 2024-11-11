# **Business Insights 360**

## **Project Overview**

**AtliQ Hardware** is experiencing rapid growth and has chosen to implement data analytics using **Power BI** to stay ahead of competitors and enable data-driven decisions. This project is designed to answer stakeholders' questions across finance, sales, marketing, and supply chain.

I followed the **Codebasics Power BI Course** for this project.  
**[Link to the course](https://codebasics.io/powerbi)**

### **[Live Report Link](#)**

---

## **Tech Stacks**

- **SQL**
- **Power BI Desktop**
- **Excel**
- **DAX Language**
- **DAX Studio** (for optimizing reports)
- **Project Charter File**

---

## **Power BI Techniques Learned**

- Key project questions to ask before starting
- Creating calculated columns
- Using **DAX language** to create measures
- Data modeling
- Using **Bookmarks** for visual switching
- **Page navigation** with buttons
- Avoiding zero-division errors using the **Divide function**
- Creating a date table with **M language**
- Setting **Dynamic titles** based on filters
- Using **KPI indicators**
- **Conditional formatting** with icons or background color
- Data validation techniques

---

## **Power BI Services**

- Publishing reports to Power BI Services
- Setting up **Personal Gateway** for auto-refresh
- **Power BI App creation**
- Collaboration, workspaces, and access permissions in Power BI Services  
  And more 😅

---

### **GitHub Skills**

- Uploading large files using **GitHub LFS**
- Tracking specific file extensions with LFS

---

## **Business-Related Terms**

- **Gross Price**
- **Pre-Invoice Deductions**
- **Post-Invoice Deductions**
- **Net Invoice Sale**
- **Gross Margin**
- **Net Sales**
- **Net Profit**
- **COGS** (Cost of Goods Sold)
- **YTD** (Year to Date)
- **YTG** (Year to Go)
- **Direct, Retailer, Distributor, Consumer**

---

## **Company Background**

**AtliQ Hardware** has rapidly expanded globally, selling computers and accessories through **Retailers, Direct,** and **Distributors**. Recently, it faced losses due to opening a store in America based on surveys and intuition rather than deep analytics. With competitors investing heavily in data analytics, AtliQ Hardware is now building its analytics team to enable data-driven insights.

**Project Kick-Off Session**

- Clarifying project goals and objectives
- Key questions before starting dashboard development:
  - Objective of the Power BI dashboard
  - Success criteria for the project
  - Time deadlines and stakeholder expectations
  - Previews and feedback mechanisms
  - Stakeholder hopes, fears, and target users
  - Potential issues and required resources/data

After the kick-off session, the **data engineering team** provided data as requested, ready for exploration.

---

## **Dataset Understanding**

Understanding available data is essential before analysis.

### **Dimensional Table:**
Contains static data such as **customer** and **product details**

- **dim_customer**: 27 markets (e.g., India, USA, Spain), 75 customers, 2 platforms (Brick & Mortar, E-commerce)
- **dim_market**: 27 markets, 7 sub-zones, 4 regions (APAC, EU, LATAM, nan)
- **dim_product**: Divisions: P & A, N & S; Categories include Internal HDD, Keyboard

### **Fact Tables:**
Contain transactional data

- **fact_forecast_monthly**: Forecasting customer needs to enhance satisfaction and reduce warehouse costs
- **fact_sales_monthly**: Similar structure to fact_forecast_monthly, replacing forecast with sold quantity
- **gdb056** tables: freight_cost, gross_price, manufacturing_cost, pre_invoice_deductions, post_invoice_deductions

### **Data Importation in Power BI**

The **MySQL database** was imported into Power BI using database credentials.

---

## **Data Modeling**

Data modeling is fundamental for report performance. Poor data modeling affects report performance, and following good practices is essential. We used **Snowflake data modeling** in this project. [Refer to good practices here](https://addendanalytics.com/blog/data-modelling-best-practices/)

<img src="https://github.com/abhisheknareshtumdam/Business_Insights_360/blob/main/Resources/Data_model.png" class="center">

## **Dashboard Design**

With mockups as a requirement, the team began creating visuals and measures as needed.

## **Dashboard Views**

- **Home View**

![Home View](https://github.com/abhisheknareshtumdam/Business_Insights_360/blob/main/Resources/Home.gif)

Contains all view buttons; users navigate by clicking specific buttons to access different views.

- **Info & Support View**
  
![Info](https://github.com/abhisheknareshtumdam/Business_Insights_360/blob/main/Resources/INFO.gif)

- **Finance View**

![Info](https://github.com/abhisheknareshtumdam/Business_Insights_360/blob/main/Resources/Finance.gif)

- **Sales View**

![Sales](https://github.com/abhisheknareshtumdam/Business_Insights_360/blob/main/Resources/Sales.gif)

- **Marketing View**

![Marketing](https://github.com/abhisheknareshtumdam/Business_Insights_360/blob/main/Resources/Marketing.gif)

- **Supply Chain View**

![Supplychain](https://github.com/abhisheknareshtumdam/Business_Insights_360/blob/main/Resources/Supplychain.gif)

- **Executive View**

![Executive](https://github.com/abhisheknareshtumdam/Business_Insights_360/blob/main/Resources/Executive.gif)


### **Overall Report**  
Full report [here](#)

---

## **Project Outcome**

The dashboard empowers data-driven decisions, providing insights and answers to numerous "why" questions based on evolving situations.
