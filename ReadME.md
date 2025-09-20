# 💰 AI-Powered Personal Finance Assistant

An interactive Streamlit web application that analyzes your Paytm transaction history PDF and provides personalized financial insights using Google Gemini AI.

This tool helps users track their income, expenses, savings, and spending patterns, along with AI-powered suggestions for smarter financial planning.

# 🚀 Features

    ✅ Upload & Analyze PDFs – Upload Paytm transaction history in PDF format.
    ✅ AI-Powered Insights – Uses Google Gemini AI to analyze transactions and extract financial insights.
    ✅ Expense Breakdown – Provides category-wise spending and unnecessary expense detection.
    ✅ Savings Analysis – Calculates savings percentage and identifies cost-control opportunities.
    ✅ Trends & Recommendations – Detects expense trends and suggests better financial habits.
    ✅ Modern UI – Styled with custom CSS for a premium look.
    ✅ 💲 Falling Dollar Animation – Fun celebratory animation after analysis.
    ✅ Background Image Support – Professional finance-themed design.

# 📂 Project Structure
    
    Finance-Assistant/
    │── app.py                  # Main Streamlit app
    │── requirements.txt        # Python dependencies
    │── .env                    # Stores Gemini API key
    │── sample.pdf              # Example Paytm statement (optional)
    │── README.md               # Project documentation


# 2️⃣ Create a Virtual Environment
    
    python -m venv venv
    source venv/bin/activate   # On Mac/Linux
    venv\Scripts\activate      # On Windows

# 3️⃣ Install Dependencies
    
    pip install -r requirements.txt

# 4️⃣ Add Environment Variables

    Create a .env file in the project root and add your Google Gemini API Key:

    GEMINI_API_KEY=your_api_key_here

# 5️⃣ Run the App

    streamlit run app.py

# 📊 How It Works

Upload your Paytm transaction PDF.

The app extracts raw text using PyPDF2.

Transactions are sent to Google Gemini AI with a structured financial analysis prompt.

Insights are displayed in categories:

Monthly income & expenses

Savings percentage

Expense trends

Cost control suggestions

Category-wise breakdown

A 🎉 falling dollar animation is triggered for a rewarding experience.

# 🔐 Security

API keys are stored securely in a .env file.

Uploaded PDFs are processed temporarily and deleted automatically after use.

# 📦 Dependencies

* Streamlit
 – Web app framework

* PyPDF2
 – PDF text extraction

* Google Generative AI SDK
 – Financial analysis

* python-dotenv
 – Environment variables

# Install them manually if needed:

* pip install streamlit PyPDF2 google-generativeai python-dotenv

# 🎯 Future Improvements

# 📊 Interactive charts for spending analysis

# 📈 Monthly report export (PDF/Excel)

# 🧾 Multi-bank statement support

# 📱 Deployable mobile-friendly UI

# 🤝 Contribution

    Contributions are welcome! Fork the repo, create a feature branch, and submit a pull request.

# 📜 License

    This project is licensed under the MIT License – feel free to use and modify it.

# ⚡️ Now you can turn your Paytm statements into powerful insights for smarter financial decisions!