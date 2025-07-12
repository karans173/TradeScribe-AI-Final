🧠 TradeScribe AI
AI-Driven Intelligent Trading Assistant for Real-Time Market Analysis and Automated Execution





📌 Overview
TradeScribe AI is a powerful AI-driven platform that:

📉 Analyzes historical stock market data,

📰 Gathers and summarizes recent financial news using Gemini/GPT-based NLP, and

🤖 Executes real-time trading strategies using Machine Learning (LSTM) for price prediction and sentiment analysis.

This intelligent assistant helps both individual traders and institutions make data-informed investment decisions with confidence.

🚀 Features
📊 LSTM-based Stock Price Prediction
Time-series forecasting using Recurrent Neural Networks.

🧠 News Sentiment Analysis
Uses Google's Gemini or LLMs to summarize news and extract sentiment.

🛠️ Real-Time Execution & Risk Management
Automatically execute trades with custom risk tolerance (0–100) and time horizon (days/months/years).

🔗 Supabase Integration
Stores user preferences, model results, and CSV exports in a cloud database.

📁 No Local Storage Needed
Direct Supabase file uploads for privacy and speed.

🧱 Tech Stack
Category	Tools & Libraries
Backend	Python, Flask
AI/ML	TensorFlow, Scikit-learn, Hugging Face Transformers
LLM	Google Gemini (Generative AI), OpenAI GPT
Data Handling	Pandas, NumPy
Cloud Database	Supabase
Deployment	Railway for backend and Vercel for frontend

📸 Live Demo (Make sure don't put too manu request at one time and it generates and give ai insights slowly so please be patient)
https://tradescribe-nine.vercel.app/

🧰 Installation
🔄 Clone the repository:
git clone https://github.com/karans173/TradeScribe-AI-Final.git
cd TradeScribe-AI-Final/AI-Driven-Intelligent-Trading-Assistant-for-Real-Time-Market-Analysis-and-Automated-Execution-main

📦 Set up virtual environment:
python -m venv venv
source venv/bin/activate  # For Linux/Mac
venv\Scripts\activate     # For Windows

📥 Install dependencies:
pip install -r requirements.txt

⚙️ Configuration
🧾 Environment Variables:
Create a .env file with the following:
SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_anon_key
GEMINI_API_KEY=your_gemini_api_key

🧪 Usage
1.  Run Flask Server
   python app.py

2.  Start frontend
   npm run dev

3.  Select stock ticker, date range, and risk level.
Get:
Predicted prices (LSTM)
News-based sentiment
AI-generated investment summary
Export as CSV to Supabase

📈 Model Highlights
LSTM trained per-stock for higher accuracy.

Sentiment scoring on top 30 days’ financial news using Gemini.

Auto-updated CSV logs for all user interactions.

👨‍💻 Team Members

Name	          GitHub Profile	
Mandeep Singh	  @mandeepsingh2007 
Jaskaran Singh	@karans173	l
Jaskeerat Singh	@jaskeerat01 


🛡 License
This project is licensed under the MIT License.


