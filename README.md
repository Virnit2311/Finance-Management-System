A simple yet powerful finance management system that analyzes user spending patterns using K-Means clustering and provides financial insights through an interactive Streamlit web app, along with an integrated chatbot for financial queries.

📈 Features
  Analyzes 2 years of daily spending data for 5 users.
  
  K-Means clustering (k=3) to group users as Low, Medium, or High spenders.
  
  Visualizes spending trends and cluster insights using Streamlit.
  
  NLTK-based chatbot answers general finance-related questions and user-specific spending queries.

🛠️ Technologies Used
  Python
  Pandas (Data preprocessing)
  Scikit-learn (K-Means clustering)
  Matplotlib & Seaborn (Data visualization)
  Streamlit (Web app development)
  NLTK (Chatbot integration)

📂 Dataset
  Source: Kaggle
  Description: Daily spending data for 5 users over a 2-year period, with fields such as UserID, Date, and AmountSpent.

🚀 How to Run the Project
  Clone the repository:
    git clone https://github.com/Virnit2311/Finance-Management-System.git
    cd Finance-Management-System
  
  Install dependencies:
    pip install -r requirements.txt
  
  Run the Streamlit app:
    streamlit run app.py

  Explore:
    Visualize personalized spending insights.
    Chat with the financial assistant for tips and reports.

🤖 Chatbot Commands (Sample Queries)
  "How much did I spend in March?"
  "Am I a high spender?"
  "Give me saving tips."
  "Show my spending in December."
  "What is my highest spending month?"

📊 Visualizations Included
  Line plots showing spending trends over time.
  Bar charts comparing monthly expenses.
  Scatter plots visualizing the spending clusters.

🔥 Future Enhancements
  Advanced chatbot using spaCy or Transformer models.
  User authentication and profile management.
  Time-series forecasting for predicting future expenses.
  Real-time budget alerts and recommendations.
