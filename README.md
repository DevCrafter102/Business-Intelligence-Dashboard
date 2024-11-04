**Business Intelligence Dashboard**

---

**Description**  
I created this business intelligence dashboard to deliver a powerful analytics tool that visualizes data, helping teams make informed, data-driven decisions across various business functions. This application provides easy access to essential metrics and reporting for actionable insights.

---

**Features and Key Functions**

- **📈 Sales Performance Tracking**: Analyze historical sales and profitability trends.
- **🌍 Geographical Insights**: Visualize regional sales distribution for targeted strategies.
- **📊 Product Category Comparison**: Compare sales versus profit by product category.
- **✨ Interactive Visualization**: Use hover details and dropdown filters to dynamically adjust the data view.

---

**Tech Stack**

- **Frontend & Visualization**: ![Dash](https://img.shields.io/badge/Dash-017ACC?logo=dash&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-2E2EFE?logo=plotly&logoColor=white) ![Dash-Bootstrap-Components](https://img.shields.io/badge/Dash--Bootstrap--Components-7952B3?logo=bootstrap&logoColor=white)
- **Backend**: ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-4B0082)
- **Data Management**: ![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)

---

**Data Pipeline**

1. **Data Extraction**: Loaded, normalized, and stored data in SQLite.
2. **Transformation**: Applied ETL techniques, denormalized data, and moved it to a data warehouse.
3. **Visualization**: Queried and visualized data through the app for web-based insights.

---

**Folder Structure**

```plaintext
app.py
assets/
    ├── index.css
    ├── images/
        └── logo.png
datasets/
    ├── DBmanager.py
    ├── elt.py
    ├── extract_load.py
    ├── initialize_datawh.py
    ├── operation_database.py
    ├── data_warehouse.db
    ├── operation.db
    └── sources/
        ├── Product_Details.xls
        └── Sales_Orders.xls
```

---

**Running the Application**

1. **Set Up Databases**: Run `DBmanager.py` to set up and populate the database and data warehouse.
2. **Launch Application**: Execute `app.py` to start the dashboard on a local server.
3. **Access Dashboard**: Open `http://127.0.0.1:8050/` in a browser.

---

**Future Enhancements**

- **Conversational Analytics**: Plan to integrate conversational analytics using `dash_core_components.Input` for an enriched user experience.

**Snapshots**

![dashboard_show](https://github.com/user-attachments/assets/13cbb4f2-a9e5-4d5a-9d4e-ae7b27bee54e)
![DATA FLOW](https://github.com/user-attachments/assets/739f6ebd-173c-4f34-b94e-9d1c88c47dad)
![KPI_indicator](https://github.com/user-attachments/assets/72d5a16f-c2a9-47cb-8c33-af920f911880)


