# Mission 5 - Project L5

Welcome to Mission 5! This project is part of the Level 5 advanced track.

## 📋 Overview

This mission represents the **final advanced project** with two phases:
- **Phase 1 (Individual)** - Solo development work
- **Phase 2 (Team)** - Collaborative team development

The project demonstrates full-stack development with Docker containerization, demonstrating professional deployment practices.

## 📁 Project Structure

```
mission-5/
├── mission-5-phase-1-individual-13eppo/
│   ├── backend/
│   ├── frontend/
│   ├── workflow-showcase/
│   ├── MISSION.md
│   ├── AGENTS.md
│   ├── README.md
│   └── DOCUMENTATION_SUMMARY.md
│
└── mission-5-phase-2-t2-adrian-katrina-eleanor-zeus/
    ├── Backend/
    ├── frontend/
    ├── docker-compose.yml   # Docker orchestration
    ├── MISSION.md
    ├── AGENTS.md
    ├── README.md
    ├── DOCKER.md            # Docker documentation
    └── DOCUMENTATION_SUMMARY.md
```

## 🚀 Quick Start

### Phase 1 - Individual Project

```bash
cd mission-5-phase-1-individual-13eppo

# Backend
cd backend
npm install
npm start

# Frontend (in new terminal)
cd frontend
npm install
npm run dev
```

### Phase 2 - Team Project with Docker

```bash
cd mission-5-phase-2-t2-adrian-katrina-eleanor-zeus

# Using Docker Compose (recommended)
docker-compose up -d

# Or manual setup
cd Backend
npm install
npm start

cd ../frontend
npm install
npm run dev
```

## 🐳 Docker Setup (Phase 2)

The Phase 2 project includes Docker configuration for containerized deployment.

### Build and Run with Docker

```bash
docker-compose up --build
```

### Stop Services

```bash
docker-compose down
```

### View Logs

```bash
docker-compose logs -f
```

For detailed Docker setup instructions, see `DOCKER.md` in the Phase 2 directory.

## 🛠️ Technologies Used

- **Node.js/Express** - Backend framework
- **React** - Frontend library
- **Vite** - Build tool
- **Docker & Docker Compose** - Containerization
- **CSS** - Styling

## ✨ Features

- Full-stack application
- Individual and team development paths
- Docker containerization (Phase 2)
- Comprehensive documentation
- Testing and validation
- Professional deployment practices

## 📁 Key Directories

### backend/Backend
Express.js server with API endpoints

### frontend
React application with modern tooling

### workflow-showcase (Phase 1)
Demonstration of development workflow and best practices

## 📝 Documentation

Each phase includes:
- `MISSION.md` - Mission requirements and goals
- `README.md` - Project-specific documentation
- `AGENTS.md` - AI agent configuration and usage
- `DOCUMENTATION_SUMMARY.md` - Complete project documentation
- `DOCKER.md` (Phase 2) - Docker and deployment guide

## 🤝 Team Collaboration (Phase 2)

Phase 2 was developed collaboratively by:
- Adrian
- Katrina
- Eleanor
- Zeus

## 📄 License

This project is part of the Mission Ready Level 5 Advanced track.
