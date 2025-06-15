# 📊 Buyer Summary Automation – Excel Dashboard Generator

This project is a Python-based automation tool designed to transform a raw Excel file of buyer-wise summaries into a **cleaned dataset** with a professionally formatted **graphical dashboard** that can assist business decision-makers. The tool is built to be **simple for non-technical users**, requiring no coding skills and minimal Excel knowledge to operate.

---

## 🔍 Project Overview

* 📁 **Input File**: `Buyer wise summary-fake.xlsx`
* 📄 **Output File**: `Buyer_Summary_with_Charts.xlsx`
* 🚀 **Platform**: Google Colab (compatible with Google Drive)
* 🛠️ **Technologies Used**: Python, Pandas, XlsxWriter

---

## 📈 Key Features

### ✅ Data Cleaning & Structuring

* Skips header noise and structures the columns
* Converts relevant fields to numeric formats for accurate charting

### ✅ Automatically Generated Dashboard

Creates a new Excel sheet `Charts` that includes **five essential business visualizations**:

1. **Bar Chart – Order Quantity by Buyer**

   * Helps identify which buyers contribute the most in volume.
2. **Pie Chart – Total FOB (Free On Board) Distribution**

   * Visualizes revenue contribution from each buyer.
3. **Stacked Bar – Cost Margin (CM) Breakdown**

   * Highlights Production CM vs Other CM side-by-side.
4. **Line Chart – Daily Income Trend per Buyer**

   * Displays income consistency across buyers.
5. **Scatter Plot – Knit Minutes vs Total CM**

   * Assesses production efficiency and its correlation with margin.

---

## 📊 Business Impact

This tool helps office employees:

* Quickly understand **which buyers are most profitable**
* Spot trends in **income consistency**
* Analyze **production performance vs cost margins**
* Get an **instant summary** of all key metrics through a clean visual interface

---

## 👥 Who Can Use It?

Anyone with **basic IT skills** — if you know how to:

* Upload a file to Google Drive
* Open a Google Colab notebook
* Run code cells

…you can use this tool easily.

---

## ⚙️ How to Use

1. Upload the `Buyer wise summary-fake.xlsx` to your Google Drive.
2. Open the Colab notebook and mount your Drive.
3. Set the path to your Excel file and run the notebook.
4. A new Excel file with charts will be created in your specified Drive folder.

---

## 📂 Example Directory Structure

```
📁 My Drive
 └── 📁 Soniya_Sweaters
     └── 📁 Test_1
         ├── Buyer wise summary-fake.xlsx   ← Input file
         └── Buyer_Summary_with_Charts.xlsx ← Output with dashboard
```

---

## 📌 Evaluation Criteria Addressed

| Criteria         | Description                                                                      |
| ---------------- | -------------------------------------------------------------------------------- |
| **Creativity**   | Selected 5 relevant chart types that reveal different business insights          |
| **Metrics**      | Covers order volume, revenue, margin analysis, income trends, and efficiency     |
| **Presentation** | Charts are styled using XlsxWriter for clear visuals and business appeal         |
| **Usefulness**   | Each chart gives a direct decision-making view (e.g., revenue share, efficiency) |
| **Quality**      | Charts are minimal, clean, and business-ready                                    |
| **Ease of Use**  | One-click automation on Google Colab – no software installation needed           |


