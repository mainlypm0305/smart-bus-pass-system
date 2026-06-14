# 🚌 Smart Bus Pass Management System

[![React](https://img.shields.io/badge/React-19.x-61DAFB?style=flat-square&logo=react)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat-square&logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-4.x-06B6D4?style=flat-square&logo=tailwindcss)](https://tailwindcss.com)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.100+-009688?style=flat-square&logo=fastapi)](https://fastapi.tiangolo.com/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![Docker Ready](https://img.shields.io/badge/Docker-Ready-2496ED?style=flat-square&logo=docker)](https://www.docker.com/)

A production-ready, enterprise-grade bus pass management system built with modern technologies and clean architecture principles. Featuring ML-powered fraud detection, QR-based validation, and real-time analytics.

## ✨ Features

### 🔐 Authentication & Security
* **JWT Authentication** - Secure token-based auth with refresh tokens
* **Rate Limiting** - Redis-powered API rate limiting
* **Role-Based Access** - Admin, Student, and Operator roles
* **Fraud Detection** - ML-powered anomaly detection for pass usage

### 👨‍💼 Admin Portal
* 📊 **Dashboard** - Real-time analytics with interactive charts
* 👥 **User Management** - Full CRUD for users and operators
* 📄 **Pass Management** - Approve, reject, or revoke bus passes
* 🗺️ **Route Management** - Create and manage bus routes and stops
* 📈 **Reports** - Revenue trends and usage insights
* ⚙️ **System Config** - Pricing, schedules, and global settings

### 👤 Student Portal
* 💳 **Apply Online** - Streamlined pass application with document upload
* 📱 **Digital Pass** - QR code-based digital pass for instant validation
* 💰 **Easy Payments** - Integrated Stripe payment gateway
* 🔔 **Smart Alerts** - Notifications for expiry and status changes
* 📝 **Support** - Integrated ticketing system for issues

## 🛠️ Tech Stack

| Technology | Purpose |
| --- | --- |
| **React 19** | UI Framework |
| **FastAPI** | High-performance Python Backend |
| **PostgreSQL** | Primary Relational Database |
| **Redis** | Caching & Rate Limiting |
| **Tailwind CSS 4** | Styling & UI |
| **Stripe** | Payment Processing |
| **Docker** | Containerization |
| **ML/Scikit-learn** | Fraud Detection Models |

## 🏗️ Architecture

The system follows **Clean Architecture** principles with a layered approach:
* **Presentation Layer**: React frontend & Admin dashboard
* **API Gateway**: FastAPI with JWT & Rate Limiting
* **Application Layer**: Business logic & Services
* **Domain Layer**: Core entities & ML models
* **Infrastructure Layer**: PostgreSQL, Redis, S3, & Stripe

## 🚀 Quick Start

### Prerequisites
* Docker & Docker Compose
* Node.js 18+ (for local dev)
* Python 3.11+ (for local dev)

### Setup
```bash
# Clone the repository
git clone https://github.com/mainlypm0305/smart-bus-pass-system.git

# Navigate to project directory
cd smart-bus-pass-system

# Start all services with Docker
docker-compose up -d
```

Access the app:
- **Frontend**: http://localhost:3000
- **Backend API**: http://localhost:8000
- **API Docs**: http://localhost:8000/docs

## 📁 Project Structure
```text
src/
├── backend/            # FastAPI Backend
│   ├── app/
│   │   ├── api/        # Endpoints
│   │   ├── services/   # Business Logic
│   │   ├── models/     # SQL Models
│   │   └── ml/         # Fraud Detection
├── frontend/           # React Frontend
│   ├── src/
│   │   ├── components/ # UI Components
│   │   └── pages/      # View Pages
└── docker-compose.yml  # Orchestration
```

## 🏆 Resume Highlights
1. **Clean Architecture** - Layered design with separation of concerns
2. **ML Integration** - Rule-based + ML fraud detection
3. **Real-time Processing** - Redis caching and WebSocket notifications
4. **Payment Integration** - Production-ready Stripe implementation
5. **Security First** - JWT, rate limiting, and input validation

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author
**mainlypm0305**
* GitHub: [@mainlypm0305](https://github.com/mainlypm0305)
