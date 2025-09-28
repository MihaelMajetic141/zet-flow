
# 💻 Zagreb public transit tracking application

This app tracks live geolocation of Zagreb public transit buses and trams and provides detailed information about each trip. <br/>
It uses live [GSTR data](https://www.zet.hr/preuzimanja/odredbe/datoteke-u-gtfs-formatu/669) from official ZET website and displays vehicles on a Leaflet map.

---

## 🛠️ Tech Stack

- **Back-end:** Spring Boot • Kotlin• Gradle • Stomp WebSockets
- **Front-end:** Angular • Leaflet.js
- **Containerization:** Docker • Docker Compose
---

## ⚙️ Features

- ✅ Live GSTR updates broadcasted through WebSocket Stomp endpoint
- ✅ Clean and intuitive UI/UX
- ✅ Docker containers for both Angular and Spring Boot app

---

## 🔧 Prerequisites

- [Docker & Docker Compose](https://docs.docker.com/get-started/get-docker/)
- [Git](https://github.com/git-guides/install-git)

---

## 🚀 Quick Start with Docker Compose

1. **Clone the repo**  
   ```bash
   git clone https://github.com/MihaelMajetic141/zet-flow
   cd zet-flow
   ```

2. **Build & run**

   ```bash
   docker-compose up --build
   ```

3. **Open the app**

    * Go to http://localhost/ in your browser.

---

## 🔬 App demo


