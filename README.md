<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/9/95/Vue.js_Logo_2.svg" alt="Vue.js Logo" width="150"/>
</p>

# My Vue.js Project

This is a Vue.js application containerized with Docker for easy setup and deployment.

---

## Features

- Built with Vue.js 3
- Fully containerized using Docker
- Ready for development and production

---

## Prerequisites

Before you begin, make sure you have the following installed:

- Docker
- Node.js & npm 

---

## Setup Guide

 1. **Clone the repository**

```bash
git clone https://github.com/pranavrjb/vue-app.git
cd vue-app
```

2. **Docker Setup**

```bash 
docker build -t vue-docker-app .
```

3. **Run Docker Container**

```bash 
docker run -d -p 8080:80 --name vue-app-v1 vue-docker-app
```

4. **Open browser**
https://localhost:8080

