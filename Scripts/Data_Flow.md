# 📂 Data Sources

Data is ingested from two enterprise systems via **CSV file extracts** (batch ingestion):

## 🔵 CRM System

| File | Description |
|------|-------------|
| `cust_info.csv` | Customer master information |
| `prd_info.csv` | Product details |
| `sales_details.csv` | Transactional sales / order records |

## 🟢 ERP System

| File | Description |
|------|-------------|
| `cust_az12.csv` | Customer demographics — birth date, gender |
| `loc_a101.csv` | Customer geography — country mapping via customer ID |
| `px_cat_g1v2.csv` | Product classification — category, subcategory, maintenance indicator, product line |

## 🔀 Data Flow & Lineage

![Data Flow Diagram](https://github.com/user-attachments/assets/3e0a3eb0-d4a1-422c-9e7a-65667554d1c4)
