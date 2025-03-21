# DataSphere 🌐📊

**DataSphere** is an interactive **data visualization dashboard** that transforms raw data into actionable insights. Built with **Flask (Python), React (JavaScript), and MongoDB**, it offers dynamic charts and intuitive analytics using **D3.js and Chart.js**.


You can access the live application here: [InsightViz Deployment]([https://poetic-mooncake-a5c15f.netlify.app/](https://poetic-mooncake-a5c15f.netlify.app/))

## 🚀 Features
- 📊 **Advanced Visualizations** – Interactive graphs for **intensity, likelihood, relevance, topics, and regions**.
- 🔍 **Dynamic Filtering** – Filter by **year, country, city, sector, PEST & SWOT factors**.
- ⚡ **Fast & Scalable** – Built with **Flask API + MongoDB** for seamless data handling.
- 🎨 **Modern UI** – Developed using **React & Bootstrap** for a smooth user experience.
- 🔗 **RESTful API** – Provides structured data access for custom analytics.

## 📁 Project Structure
```
DataSphere/
│── backend/               # Flask Backend
│   ├── app.py             # Main Flask app
│   ├── config.py          # Configuration file
│   ├── database.py        # MongoDB connection
│   ├── routes.py          # API routes
│   ├── requirements.txt   # Dependencies
│   ├── data/
│   │   ├── jsondata.json  # Provided dataset
│
│── frontend/              # React Frontend
│   ├── src/
│   │   ├── components/    # UI Components
│   │   │   ├── Dashboard.js
│   │   │   ├── Charts.js
│   │   │   ├── Filters.js
│   │   ├── services/      # API requests
│   │   ├── App.js
│   │   ├── index.js
│   ├── package.json       # React dependencies
│   ├── .env               # Environment variables
│
│── README.md              # Project Documentation
│── .gitignore             # Ignore unnecessary files
│── docker-compose.yml     # Docker setup (if needed)
```

## 🛠️ Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/BadakalaYashwanth/DataSphere-.git
cd DataSphere
```

### 2️⃣ Backend Setup (Flask + MongoDB)
```bash
cd backend
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
python app.py
```
Ensure MongoDB is running and the dataset (`jsondata.json`) is loaded.

### 3️⃣ Frontend Setup (React + Chart.js)
```bash
cd frontend
npm install
npm start
```

## 🔗 API Endpoints
| Endpoint          | Method | Description |
|------------------|--------|-------------|
| `/data`         | GET    | Fetch all data |
| `/countries`    | GET    | Get unique countries |

## 📊 Technologies Used
- **Backend:** Flask, MongoDB
- **Frontend:** React, Bootstrap
- **Visualization:** D3.js, Chart.js, Plotly
- **API:** RESTful Flask API

## 📌 Contributing
Feel free to submit issues, fork the repo, and make pull requests!

## 📜 License
MIT License

---
🔍 **DataSphere – Transforming data into actionable insights!** 🚀
