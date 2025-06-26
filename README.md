# 🗳️ Votely – Secure IoT‑Driven Smart Voting System

An advanced, secure voting platform that leverages **IoT devices**, provides **real-time insights**, and ensures **cloud resilience**—designed for safe, transparent, and scalable **class representative elections**.

---

## 🌟 Key Features

- 🔐 **Secure Voting** via IoT (RFID/Bluetooth verification)
- 👤 **User Management** – Admins, students, and candidates
- 🗓️ **Election Lifecycle** – Create, schedule, and manage elections
- 🖼️ **Photo Uploads** for voters and candidates
- 📊 **Real-Time Insights** – Vote counts, trends, live results
- ☁️ **Cloud Resilience** – Backup and recovery support
- 🧩 **Modular API-First Backend** using Node.js & Express
- 🔒 **Role-Based Authentication** using JWT

---

## 🚀 Setup & Installation

### 📦 Prerequisites

- ✅ Node.js v14+ and npm/yarn  
- 📡 IoT readers (e.g., RFID/Bluetooth) – optional hardware  
- 🛢️ PostgreSQL / MongoDB (optional for persistence)  
- ☁️ Access to cloud services (e.g., AWS/GCP/Azure)

### 🛠️ Installation Steps

```bash
# 1. Clone the repository
git clone https://github.com/thaaru05/Votely-Secure-IoT-Driven-Smart-Voting-System-with-Real-Time-Insights-and-Cloud-Resilience.git
cd Votely-Secure-IoT-Driven-Smart-Voting-System-with-Real-Time-Insights-and-Cloud-Resilience

# 2. Install dependencies
npm install

# 3. Configure environment variables
cp .env.example .env
# Edit .env file with: PORT, DATABASE_URL, JWT_SECRET, IOT_CONFIG, CLOUD_STORAGE

# 4. (Optional) Run database migrations
npm run migrate

# 5. Create media folder for image uploads
mkdir media

# 6. Start the development server
npm run dev
