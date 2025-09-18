# 🌍 TravelViz

TravelViz is an interactive data visualization web application built with **Streamlit**.  
It helps users explore and analyze travel-related data using dynamic maps, charts, and dashboards, making insights more engaging and easy to understand.

---

## ✨ Features
- 📊 Interactive dashboards to explore travel data  
- 🌍 Geographical visualizations using maps  
- 📈 Trend analysis with charts and graphs  
- ⚡ User-friendly interface powered by Streamlit  
- 🔑 Environment variable support via `.env` file  

---

## 🛠️ Tech Stack
- **Frontend & Backend:** [Streamlit](https://streamlit.io)  
- **Language:** Python 3.9+  
- **Visualization:** Plotly, Matplotlib, Seaborn  
- **Database:** SQLite (`data.db`)  
- **Environment Management:** python-dotenv  

---

## 🚀 Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/Akshaya-2004-Analytics/TravelViz.git
cd TravelViz
````

### 2. Create a Virtual Environment (Recommended)

```bash
python -m venv venv
# Activate it
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Set Up Environment Variables

Create a `.env` file in the project root and add required variables (example):

```env
API_KEY=your_api_key_here
DB_PATH=data.db
```

### 5. Run the App

```bash
streamlit run travelviz_main.py
```

The app will be available at `http://localhost:8501`.

---

## 🌐 Deployment

You can deploy TravelViz on:

* [Streamlit Community Cloud](https://share.streamlit.io) (quick & free)
* [Render](https://render.com)
* Docker + any cloud platform (Heroku, AWS, GCP, Azure)

---

## 📂 Project Structure

```
TravelViz/
│-- travelviz_main.py      # Main Streamlit app
│-- requirements.txt       # Project dependencies
│-- data.db                # Sample database (if provided)
│-- .env                   # Environment variables (not committed)
│-- README.md              # Project documentation
```

---

## 📸 Demo

Deployed App: [TravelViz Live](https://travelviz-vishwakdhoni.streamlit.app/)

---

## 🤝 Contributing

Contributions are welcome!

* Fork the repo
* Create a feature branch (`git checkout -b feature-name`)
* Commit changes (`git commit -m 'Add new feature'`)
* Push to branch (`git push origin feature-name`)
* Open a Pull Request

---

## 📜 License

This project is licensed under the **MIT License**.

---

### 👩‍💻 Author

Developed by [Vishwak Dhoni](https://github.com/vishwakdhoni)

---
