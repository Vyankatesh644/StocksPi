# 📈 StocksPI — AI-Powered Stock Market Intelligence Platform

StocksPI is a modern Streamlit-based stock market analytics platform that combines **real-time market tracking**, **AI-powered insights**, **sentiment analysis**, and **interactive visualizations** into a single user-friendly dashboard.

Designed for beginners, learners, and market enthusiasts, the platform simplifies stock analysis using automation, predictive insights, and an intuitive interface.

---

## 🚀 Features

### 📊 Real-Time Stock Tracking

* Live stock market data integration using Yahoo Finance APIs
* Interactive stock charts and analytics
* Company fundamentals and performance overview
* Dynamic visual dashboards with Plotly

### 🤖 AI-Powered PI Assistant

* Smart market insights using AI models
* Simplified explanations for market trends
* Interactive investment guidance experience
* AI-generated sector and stock insights

### 📰 Sentiment Analysis Engine

* News sentiment tracking for stocks
* Market mood analysis using NLP models
* Positive, negative, and neutral sentiment classification
* Data-driven decision support

### 📉 Visualization & Prediction

* Interactive financial charts
* Historical stock performance analysis
* Trend visualization
* Prediction modules for market movement analysis

### 🎨 Modern UI/UX

* Responsive Streamlit interface
* Animated dashboard experience
* Neon-themed modern design
* Easy navigation with multi-page architecture

---

## 🛠️ Tech Stack

| Category        | Technologies                            |
| --------------- | --------------------------------------- |
| Frontend        | Streamlit, HTML, CSS                    |
| Visualization   | Plotly                                  |
| Data Processing | Pandas, NumPy                           |
| Stock Data      | Yahoo Finance (yfinance), Alpha Vantage |
| AI & NLP        | Groq API, Transformers, VaderSentiment  |
| Backend Logic   | Python                                  |

---

## 📂 Project Structure

```bash
StocksPI/
│
├── main.py                 # Main application entry point
├── home.py                 # Landing page
├── stock.py                # Stock analytics module
├── sentiment.py            # Sentiment analysis engine
├── sector.py               # AI-powered PI assistant
├── style.css               # Custom styling
├── views/
│   ├── data.py             # Data processing utilities
│   ├── prediction.py       # Prediction logic
│   └── visuals.py          # Visualization components
│
├── Requirements.txt
└── .env                    # API keys and environment variables
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/stockspi.git
cd stockspi
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

Activate environment:

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r Requirements.txt
```

### 4️⃣ Configure Environment Variables

Create a `.env` file:

```env
GROQ_API_KEY=your_groq_api_key
ALPHA_VANTAGE_API_KEY=your_alpha_vantage_key
```

---

## ▶️ Run the Application

```bash
streamlit run main.py
```

Application will start at:

```bash
http://localhost:8501
```

---

## 📸 Application Modules

### 🏠 Home Dashboard

* Introduction to the platform
* Animated landing experience
* Quick navigation

### 📈 Stock Analytics

* Live market tracking
* Historical charts
* Company insights
* Technical visualization

### 📰 Sentiment Dashboard

* AI-powered news analysis
* Sentiment score breakdown
* Market psychology indicators

### 🤖 PI AI Assistant

* Conversational market insights
* Simplified stock explanations
* Sector-level intelligence

---

## 🔐 Environment Variables

| Variable                | Description                      |
| ----------------------- | -------------------------------- |
| `GROQ_API_KEY`          | API key for AI-powered assistant |
| `ALPHA_VANTAGE_API_KEY` | API key for stock fundamentals   |

---

## 📦 Requirements

Core libraries used in the project:

```txt
streamlit
pandas
numpy
plotly
yfinance
requests
python-dotenv
transformers
vaderSentiment
alpha_vantage
groq
```

---

## 🌟 Future Improvements

* Portfolio management system
* AI-based trading recommendations
* Multi-stock comparison engine
* Real-time alerts and notifications
* Deep learning prediction models
* Cloud deployment support

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Developed with passion using Python, AI, and Streamlit.

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub.
