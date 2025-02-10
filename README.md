# Expense Management System

📝 Overview
The Expense Tracker App is a full-stack application designed to track, manage, and analyze daily expenses. This project helps users gain insights into their spending habits by categorizing expenses and providing month-wise breakdowns.

By building this project, you will develop hands-on experience in backend development, database management, and frontend UI design.

✨ Key Features

🚀 1. Expense Management
Users can log expenses with amount, category, date, and notes.
Supports multiple categories such as food, rent, shopping, and entertainment.
📊 2. Monthly & Category Breakdown
Visualizes total expenses per category (e.g., "How much was spent on food?").
Displays monthly spending trends to help users track financial progress.
📉 3. Data Analytics & Visualization
Uses bar charts and tables to represent expenses.
Provides insights into spending patterns over time.

# Project Structure

 **frontend/**: Contains the Streamlit application code.
- **backend/**: Contains the FastAPI backend server code.
- **tests/**: Contains the test cases for both frontend and backend.
- **requirements.txt**: Lists the required Python packages.
- **README.md**: Provides an overview and instructions for the project.


## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/expense-management-system.git
   cd expense-management-system
   ```
1. **Install dependencies:**:   
   ```commandline
    pip install -r requirements.txt
   ```
1. **Run the FastAPI server:**:   
   ```commandline
    uvicorn server.server:app --reload
   ```
1. **Run the Streamlit app:**:   
   ```commandline
    streamlit run frontend/app.py
   ```
