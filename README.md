# Task-7-PowerBi-Dashboard


## 📌 Objective
The objective of this task is to create a beginner-level **interactive business dashboard** using **Power BI Desktop**.  
The dashboard analyzes sales and profit data to derive meaningful business insights using visuals, KPIs, and slicers.

---

## 🛠 Tools Used
- **Power BI Desktop (Free)**
- **Microsoft Excel 2018** (for initial dataset checking)
- **GitHub** (for project submission)

---

## 📂 Dataset Information
- **Dataset Name:** Global Superstore Dataset  
- **File Format:** CSV  
- **Source:** Public GitHub dataset  
- **Description:** Contains order, sales, profit, category, region, and customer-related data.

---

## 📁 Project Structure


---

## 🔄 Workflow with Screenshots

### 1️⃣ Dataset Preview
The dataset was reviewed to understand the structure, columns, and values before loading into Power BI.

![Dataset Preview](screenshots/dataset_preview.png)

---

### 2️⃣ Dataset Loaded into Power BI
The CSV file was successfully imported into Power BI Desktop.

![Dataset Loaded](screenshots/dataset_loaded.png)

---

### 3️⃣ Power Query Editor
Data types were verified and corrected using Power Query Editor.

![Power Query Editor](screenshots/power_query_editor.png)

---

### 4️⃣ Table Renamed
The dataset table was renamed to **Superstore** for clarity and best practice.

![Table Renamed](screenshots/table_renamed.png)

---

### 5️⃣ Close and Apply
All data transformations were applied to load the cleaned data into the report view.

![Close and Apply](screenshots/close_and_apply.png)

---

## 🧮 DAX Measures Created

### 🔹 Total Sales
```DAX
Total Sales = SUM(Superstore[Sales])

