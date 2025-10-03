# 🔔 NotifyGrid  

**NotifyGrid** is a lightweight, **FastAPI-powered notification microservice** designed to handle multi-channel notifications including **Email, SMS, Push, and WhatsApp** — all exposed via a clean, RESTful API. It’s containerized with Docker for fast and scalable deployments.  

---

## 🚀 Features  
- ✅ Send Email, SMS, Push, and WhatsApp notifications  
- 📨 Unified REST API for multiple channels  
- 🔐 Secure integration with API key/token authentication  
- 🧩 Modular design — extendable with more channels/providers  
- 📄 Built-in API docs with Swagger (via FastAPI)  
- 🐳 Docker-ready  

---

## 🏗️ Tech Stack  
- **FastAPI** – high-performance Python web framework  
- **Pydantic** – data validation  
- **MongoDB** – NoSQL database for message logs and tracking  
- **JWT / API Key** – for secure client authentication  
- **Docker** – containerization  

---

## 📦 Getting Started  

### Prerequisites  
- **Docker** installed on your system  
- Optionally, **Docker Compose** if using a `docker-compose.yml`  

---

### 🔧 Clone the Repository  
```bash
git clone https://github.com/emperorkez/NotifyGrid.git
cd NotifyGrid

---

## 🐳 Run with Docker

Build and run the container:
docker build -t notifygrid .
docker run -d -p 8001:8000 --name notifygrid notifygrid

Once running, the API docs will be available at:  
👉 http://localhost:8001/docs

---

## 🙌 Contributing
Contributions are welcome! To get started:
1. Fork the repository  
2. Create a new branch  
3. Make your changes  
4. Open a pull request  

---

## 📝 License
MIT License © Emperor Kez  

---

## 📬 Contact
For inquiries, reach out at emperorkez@gmail.com
