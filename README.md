# 🚀 Repofy – AI-Powered Developer Productivity Platform

Repofy is a full-stack AI-powered developer productivity platform that helps developers understand repositories, interact with AI, and retrieve relevant information using semantic vector search.

## ✨ Features

* 🤖 AI-powered developer assistance
* 📂 Repository analysis and understanding
* 💬 AI chat interface
* 🔍 Semantic search using vector embeddings
* 🧠 Context-aware AI responses
* 🔐 Secure authentication
* 🗄️ PostgreSQL database integration
* 🐳 Docker-based database setup

## 🛠️ Tech Stack

**Frontend:** Next.js, React.js, TypeScript, Tailwind CSS, shadcn/ui

**Backend:** Java, Spring Boot, Spring Security, Spring AI, Maven

**AI:** OpenAI, Embeddings, Vector Search

**Database:** PostgreSQL, pgvector

**Tools:** Docker, Docker Compose, Git, GitHub

## 🏗️ Project Architecture

```text
User
  ↓
Next.js Frontend
  ↓
REST API
  ↓
Spring Boot Backend
  ↓
Spring AI
  ↓
OpenAI
  ↓
PostgreSQL + pgvector
  ↓
AI Response
  ↓
Frontend
```

## 🧠 AI & Vector Search Architecture

```text
User Query
    ↓
Spring Boot API
    ↓
Generate Embedding
    ↓
pgvector Similarity Search
    ↓
Retrieve Relevant Context
    ↓
Spring AI + OpenAI
    ↓
Generate AI Response
    ↓
Return Response to User
```

This architecture enables Repofy to retrieve relevant information using vector similarity and provide context-aware AI responses.

## 🎯 Project Goals

* Improve developer productivity using AI
* Simplify understanding of complex repositories
* Provide intelligent repository search
* Combine LLMs with semantic vector search
* Build a scalable full-stack AI application
* Demonstrate modern Java and AI integration

## 🚀 Steps to Run

### 1. Clone Repository

```bash
git clone https://github.com/Utsav159/Repofy---AI-Powered-Developer-Productivity-Platform.git

cd Repofy---AI-Powered-Developer-Productivity-Platform
```

### 2. Start Database

```bash
docker compose up -d
```

### 3. Configure Environment

Add your required database and OpenAI API credentials to the backend configuration.

```text
OPENAI_API_KEY=your_api_key
DATABASE_URL=your_database_url
DATABASE_USERNAME=your_username
DATABASE_PASSWORD=your_password
```

### 4. Run Backend

```bash
cd backend
mvn spring-boot:run
```

Backend:

```text
http://localhost:8080
```

### 5. Run Frontend

Open another terminal:

```bash
cd client
npm install
npm run dev
```

Frontend:

```text
http://localhost:3000
```

## 📌 Project Structure

```text
Repofy/
├── backend/       # Spring Boot backend
├── client/        # Next.js frontend
├── docker-compose.yml
└── README.md
```

## 👨‍💻 Author

**Utsav Bhardwaj**

GitHub: https://github.com/Utsav159
