A simple yet powerful finance management system that analyzes user spending patterns using K-Means clustering and provides financial insights through an interactive Streamlit web app, along with an integrated chatbot for financial queries.

📈 Features
Analyzes 2 years of daily spending data for 5 users.

K-Means clustering (k=3) to group users as Low, Medium, or High spenders.

Visualizes spending trends and cluster insights using Streamlit.

NLTK-based chatbot answers general financial questions and user-specific spending queries.

🛠️ Technologies Used
Python

Pandas (Data Preprocessing)

Scikit-learn (K-Means Clustering)

Matplotlib & Seaborn (Data Visualization)

Streamlit (Web App Development)

NLTK (Chatbot Integration)

📂 Dataset
Source: Kaggle

Description: Daily spending data for 5 users over a period of 2 years, including fields like UserID, Date, and AmountSpent.

🚀 How to Run the Project
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/finance-management-system.git
cd finance-management-system
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Streamlit app:

bash
Copy
Edit
streamlit run app.py
Start chatting with the financial assistant and explore the insights!

🤖 Chatbot Commands (Examples)
"How much did I spend in March?"

"Am I a high spender?"

"Give me saving tips."

"Show my spending in December."

📊 Visualizations Included
Spending trends over time

Monthly expense bar charts

Spending clusters scatter plot

🔥 Future Enhancements
Improve chatbot using advanced NLP models (e.g., spaCy, Transformers).

Add user authentication.

Predict future spending using time-series forecasting.

Real-time spending alerts and budgeting suggestions.
