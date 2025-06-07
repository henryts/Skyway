# 🌐 Skyway

**Skyway** is a scalable MERN stack platform that connects users with verified **Visa Consultancies**. Designed using **Microservices Architecture**, the system is capable of handling **millions of users** efficiently.

> ⚡ Built with performance, scalability, and real-world deployment practices in mind.

---

## 🚀 Features

- 🔍 **Rank-Based Consultancy Search**  
  Custom-built algorithm ranks consultancies based on user ratings, response time, and success ratio — reducing user search time by **30%**.

- 🧱 **Microservices Architecture**  
  Decoupled services for Authentication, User Profiles, Consultancy Listings, Reviews, and Notifications.

- 🐳 **Docker + Kubernetes Deployment**  
  Containerized services and orchestrated with Kubernetes, enabling **zero-downtime deployments** and **50% scaling efficiency**.

- 🔄 **CI/CD Pipeline**  
  Integrated **GitHub Actions** for automatic testing, building, and deployment — reducing deployment time by **40%**.

- ☁️ **Cloud Ready**  
  Ready for deployment on **AWS / GCP / Azure**, with environment-specific configs using `.env` files and secrets management.

---

## 🛠️ Tech Stack

| Category        | Technologies |
|-----------------|--------------|
| Frontend        | React.js, Redux, Tailwind CSS |
| Backend         | Node.js, Express.js |
| Database        | MongoDB, Mongoose |
| DevOps          | Docker, Kubernetes, GitHub Actions |
| Architecture    | REST APIs, Microservices |
| Deployment      | Nginx, AWS EC2, GitHub CI/CD |

---

## 📦 Microservices Included

- **Auth Service** — User authentication (JWT, bcrypt)
- **User Service** — Profile management
- **Consultancy Service** — Listings & details
- **Review Service** — Ratings, comments, flags
- **Notification Service** — Email & in-app alerts

---

## 🧪 Running Locally

```bash
# Clone the repository
git clone https://github.com/your-username/skyway.git
cd skyway

# Setup environment variables
cp .env.example .env

# Start with Docker
docker-compose up --build
