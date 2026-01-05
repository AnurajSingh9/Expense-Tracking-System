# Expense Management System

This project is an expense management system that consists of a Streamlit frontend application and a FastAPI backend server.


## Project Structure

- **frontend/**: Contains the Streamlit application code.
- **backend/**: Contains the FastAPI backend server code.
- **tests/**: Contains the test cases for both frontend and backend.
- **requirements.txt**: Lists the required Python packages.
- **README.md**: Provides an overview and instructions for the project.

## 🛠️ Features I Worked On

### Expense Entry (Streamlit UI)
- Built dynamic expense input rows with amount, category, and notes
- Implemented date-based expense logging
- Added validation to avoid invalid or empty entries

### Analytics Dashboard
- Implemented **Expense Breakdown by Category**
- Built interactive bar charts for:
  - Category-wise totals
  - Percentage-wise expense distribution
- Added hover tooltips showing category, total amount, and percentage

### Data Processing
- Aggregated expense data using Pandas
- Calculated category-wise totals and percentages
- Integrated backend API data with frontend analytics

---

## 📊 Screens Implemented
- Add / Update Expense UI
- Expense Breakdown Chart
- Category-wise Analytics View
- Expense Summary Table

---

## 🔧 Tech Stack
- Streamlit
- FastAPI (API integration)
- Pandas
- Requests

---

## 📚 What I Learned
- Building analytics dashboards from raw data
- Frontend–backend integration
- Data aggregation and visualization
- Designing user-friendly finance dashboards

---

## ▶️ How to Run
```bash
pip install -r requirements.txt
uvicorn server.server:app --reload
streamlit run frontend/app.py
