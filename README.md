# StockGuard AI 🚑🏎️

**StockGuard AI** is an AI-powered logistics control tower built on Snowflake that prevents stock-outs and waste across hospitals, NGOs, F1 logistics, and global supply chains.

## 🌍 Why it matters
Millions of patients miss life-saving medicines while companies lose billions due to poor inventory planning. StockGuard AI predicts shortages before they happen and tells teams exactly what to order and where.

## 🧠 What it does
- Live inventory heatmaps
- AI-powered stock-out prediction
- Demand spike detection
- Reorder quantity recommendations
- Exportable action lists

## 🏗 Architecture
Snowflake Dynamic Tables → AI logic → Streamlit Dashboard

## 🛠 Tech Stack
- Snowflake SQL
- Dynamic Tables
- Snowflake Streams
- Snowflake Streamlit
- (Optional) Snowpark

## 🚀 How it works
Raw inventory data is processed into a continuously updating AI table (`STOCK_HEALTH`). The Streamlit app reads this table to display risk, demand, and reorder priorities.

## 🏆 Hackathon
Built for **AI for Good – Inventory Heatmaps & Stockout Alerts for Essential Goods**

