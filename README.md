# PT-Program04

# Go Hello World Web Server

A simple web server built with Go that displays a "Hello World" message. This project demonstrates how to build a basic web server with Go and how to containerize it with Docker.

## 🛠️ Technologies used

- Go 1.23
- Docker
- Alpine Linux
- Net/HTTP package (Go standard library)

## 📋 Prerequisites

For local development:
- Go 1.23 or higher
- Docker
- Git

## 🔧 Installation

### Local method

1. Clone the repository:
```bash
git clone https://github.com/PammeC/PT-Program04.git
cd PT-Program04
```

2. Run the server:
```bash
go run Program04.go
```

The server will be available at `http://localhost:8080`

### Using Docker

#### Option 1: Pull from Docker Hub
```bash
docker pull pammec/program04
docker run -p 8080:8080 pammec/program04
```

#### Option 2: Local build
```bash
docker build -t program04 .
docker run -p 8080:8080 program04
```

## 📦 Project Structure

```
PT-Program04/
│
├── Program04.go # Main source code
├── Dockerfile # Docker configuration
├── go.mod # Go dependencies
├── go.sum # Dependency checksums
└── README.md # Documentation
```

## 🚀 Deployment Options

The application can be deployed on several platforms:

- ✅ Render (Currently deployed)
- Heroku
- Digital Ocean
- Railway
- Vercel
- Laravel Cloud

The application is currently deployed on Render and can be accessed at the following link: [https://pt-program04.onrender.com](https://pt-program04.onrender.com)
