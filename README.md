

### **Project Overview: power.pbix**

This repository contains **power.pbix**, an interactive Business Intelligence dashboard designed to deliver actionable insights through structured data visualization. The report is built to provide an intuitive user experience with responsive formatting and clear performance tracking.

---

### **Key Features**

* **Multi-Page Navigation:** A structured, multi-page layout that guides users through different levels of data granularity.
* **Advanced Visualizations:** Incorporates interactive KPI cards, funnel charts, and matrix heatmaps specifically configured for A/B testing analysis.
* **Mobile Optimization:** Features a custom-configured mobile canvas layout, ensuring that all report visuals remain readable and interactive on cellular devices.
* **Enhanced UX Formatting:** Utilizes tailored interface formatting, including optimized slicer interaction behavior, matrix drill-downs, and a custom dark mode theme (via integrated JSON themes).

---

### **Data Architecture & Preparation**

* **Data Source:** The underlying structured datasets are queried, cleaned, and prepared using PostgreSQL before being imported into the dashboard.
* **Data Model:** The internal engine utilizes robust relational modeling to ensure accurate metric calculations and fast rendering of dashboard elements.

---

### **Getting Started**

1. Download and install the latest version of [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/).
2. Clone this repository or download the **power.pbix** file directly.
3. Open the file in Power BI Desktop.
4. If prompted, update the PostgreSQL database credentials in the Data Source Settings to refresh the local data model.

