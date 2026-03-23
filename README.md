# 🚀 IntelliScaleSim (Intelligent Scaling Simulator)

IntelliScaleSim is a premium, high-fidelity cloud simulation platform designed for education, research, and infrastructure optimization. It allows users to deploy applications, simulate realistic traffic loads, and analyze scaling behaviors with real-time billing and monitoring telemetry.

---

## ✨ Key Features

- **🎯 Scenario-Based Billing**: Simulate cloud provider costs (AWS, GCP, Azure) for hypothetical scaling scenarios. Pre-fill configurations directly from your running containers.
- **⚡ Real-Time Monitoring**: Integrated **Prometheus & Grafana** stack for live tracking of CPU, Memory, and Network telemetry.
- **📈 Load Testing Studio**: Launch concurrent traffic simulations against your deployments with interactiveAreaCharts and peak performance analytics.
- **🐳 Container Orchestration**: Deploy and manage Docker containers with granular control over resource limits and scaling policies.
- **🎨 Premium UI/UX**: Built with a sleek, modern Glassmorphism aesthetic, featuring micro-animations and a unified Violet-Fuchsia-Pink theme.

---

## 🛠️ Tech Stack

**Frontend:**
- React (TypeScript) + Vite
- TailwindCSS (Premium UI Styling)
- Recharts (Data Visualization)
- Lucide Icons

**Backend:**
- FastAPI (High Performance)
- SQLAlchemy (PostgreSQL ORM)
- Docker Engine API
- Pydantic (Data Validation)

**Infrastructure:**
- PostgreSQL (Primary Database)
- Prometheus (Metrics Collection)
- Grafana (Visualization Dashboard)

---

## 🚀 Quick Start

### 1. Prerequisites
- Python 3.9+
- Node.js & npm
- Docker Desktop
- PostgreSQL installed and running

### 2. Backend Setup
```bash
cd backend
python -m venv .venv
# Windows
.venv\Scripts\activate
# Unix/macOS
source .venv/bin/activate

pip install -r requirements.txt

# Configure your database URL
$env:DATABASE_URL="postgresql+psycopg2://postgres:postgres@localhost:5432/intelliscalesim"

uvicorn app.main:app --reload
```

### 3. Frontend Setup
```bash
cd frontend
npm install
npm run dev
```

### 4. Monitoring Stack
Launch the integrated monitoring tools:
```bash
docker-compose -f docker-compose.monitoring.yml up -d
```
- **Grafana**: http://localhost:3500 (Admin dashboard)
- **Prometheus**: http://localhost:9090

---

## 🔐 Demo Account
Explore the platform immediately using the pre-configured student account:
- **Email**: `demo@test.com`
- **Password**: `Password123!`

---

## 📁 Project Structure

- `/backend` — FastAPI application and simulation services.
- `/frontend` — React/Vite dashboard and UI components.
- `/infrastructure` — Configuration for metrics and monitoring.
- `/scripts` — Database initialization and utility scripts.

---

## 🤝 Contributing
IntelliScaleSim is open for contributions! Feel free to fork the repository and submit pull requests for new features or bug fixes.

---
#   I n t e l l i g e n t s c a l e s i m  "# Major_Project-" 
