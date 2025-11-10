# 🎵 SQL Music Store Analysis

## 📘 Project Overview
This project analyzes a **digital music store database** using **SQL** to uncover key business insights such as top-selling artists, customer spending habits, and popular music genres.  
It demonstrates practical use of **SQL joins, aggregations, and subqueries** — essential for data analytics.

---

## 🧠 Objectives
- Identify the most popular genres and artists  
- Find top customers based on total spending  
- Analyze track sales by country and genre  
- Determine revenue trends and customer behavior  

---

## 🗂️ Dataset
The project uses a **Music Store Database** (like Chinook) containing tables such as:
- `customers`
- `invoices`
- `invoice_line`
- `tracks`
- `albums`
- `artists`
- `genres`
- `media_type`
- `playlist`
- `playlist_track`
- 

> Note: Database files (`.sqlite`, `.db`) are excluded via `.gitignore`.

---

## 🧩 Tools & Technologies  
- **PostgreSQL ** – database used for queries  
    

---

## 📊 Key Insights
- 🎤 **Top Artists:** The top 5 artists contributed to over 40% of total sales  
- 🌍 **Top Countries:** USA and Canada generated the highest revenue  
- 🎶 **Popular Genre:** Rock and Alternative Rock were the most sold genres  
- 💰 **Top Customers:** Repeat customers significantly increased total revenue  

---

## 📁 Project Structure
SQL-Music-Store-Analysis/
│
├── README.md
├── .gitignore
│

│
├── queries/
│   ├── 01_easy/
│   │   ├── senior_most_employee.sql
│   │   ├── countries_with_most_invoices.sql
│   │   ├── top_3_invoice_values.sql
│   │   ├── best_city_customers.sql
│   │   └── best_customer.sql
│   │
│   ├── 02_moderate/
│   │   ├── rock_music_listeners.sql
│   │   ├── top_10_rock_artists.sql
│   │   └── longer_than_average_songs.sql
│   │
│   ├── 03_advanced/
│   │   ├── customer_spent_on_artist.sql
│   │   ├── top_genre_by_country.sql
│   │   └── top_customer_by_country.sql
│   │
│   └── all_queries_combined.sql
│
├── outputs/
│   ├── easy_queries_results.csv
│   ├── moderate_queries_results.csv
│   └── advanced_queries_results.csv
│
├── screenshots/
│   ├── ERD.png
│   
│
└── project_summary.txt


