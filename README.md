# PostCraft

PostCraft is a full-stack blogging platform that lets users register, log in, and manage their posts securely. It was originally developed as a backend service for a larger private application and later extended with a standalone front-end and AWS deployment for demonstration purposes.

The project showcases secure data handling, authentication, input validation, and cloud deployment, along with a simple, responsive UI for managing content.

---

## 🚀 Live Demo

- **App:** http://ec2-51-20-118-183.eu-north-1.compute.amazonaws.com/

*(If the link is down, the EC2 instance is probably stopped to save costs.)*

---

## ✨ Features

- **User authentication**
  - User registration and login
  - JWT-based authentication and authorization
- **Post management**
  - Create, read, update, and delete posts
  - Posts are tied to user accounts
- **Secure data handling**
  - Input validation on both client and server
  - Clear error handling and validation messages
- **Email & payments (demo)**
  - Integration with **SendGrid** for email workflows
  - Integration with **Stripe** for payment-related flows (demo / test mode)
- **Modern UX**
  - Responsive layout
  - Simple, clean interface for managing posts
- **DevOps & deployment**
  - Dockerized application
  - `docker-compose` for local development
  - Deployed on **AWS EC2**

---

## 🧰 Tech Stack

### Frontend

- JavaScript
- React (component-based UI)
- HTML, CSS

### Backend

- Node.js
- Express
- REST API
- JWT authentication & authorization
- Input validation

### Infrastructure & Tools

- Docker & Docker Compose
- AWS EC2
- SendGrid (email)
- Stripe (payments)
- Environment-based configuration

---

## 🗂️ Project Structure

At a high level:

```bash
.
├── src/           # Frontend source (React / client-side code)
├── public/        # Static assets
├── server/        # Backend source (API, auth, validation, integrations)
├── build/         # Production build output
├── Dockerfile     # Container definition
├── docker-compose.yml
└── package.json
