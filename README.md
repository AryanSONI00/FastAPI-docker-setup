# 🚀 FastAPI Dockerized App

This is a simple FastAPI application, containerized with Docker. It provides a REST API with endpoints to fetch data dynamically.

## 🛠️ Features
- FastAPI framework 🚀
- Dockerized for easy deployment 🐳
- Swagger UI for API documentation 📝

## 📌 Installation & Setup

### **1️⃣ Clone the repository**
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### **2️⃣ Run Locally**
#### Using Python:
```bash
pip install -r requirements.txt
uvicorn main:app --reload
```
#### Using Docker:
```bash
docker build -t fastapi-app .
docker run -d -p 8000:8000 fastapi-app
```

## 🔗 API Endpoints
| Method | Endpoint        | Description              |
|--------|---------------|--------------------------|
| GET    | `/`           | Returns a welcome message |
| GET    | `/items/{id}` | Fetch an item by ID      |

## 📝 Documentation
Access API docs in your browser:
- Swagger UI: [http://localhost:8000/docs](http://localhost:8000/docs)
- Redoc UI: [http://localhost:8000/redoc](http://localhost:8000/redoc)

## 🐜 License
This project is open-source and available under the MIT License.

---

### 📌 **Contributions Welcome!**
Want to improve this project? Feel free to fork, open an issue, or submit a PR! 🚀

