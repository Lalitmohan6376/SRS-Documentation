# 📘 Unit 5 — System Design Fundamentals

---

# 🌟 Introduction

After understanding:

* 📄 SRS Document
* 🧠 Requirement Engineering
* 🔄 SDLC

the next important step is:

> 🏗️ System Design

System Design is one of the most important parts of software engineering because it defines:

* ⚙️ how the system will work
* 🧩 how components connect
* 📈 how the application scales
* 🔒 how security is handled

---

# 🧠 What is System Design?

System Design is the process of:

> Planning the architecture, components, database, APIs, and workflow of a software system 💻🏗️

It converts requirements into a technical solution.

---

# 🎯 Goals of System Design

System Design helps in:

* 📈 Building scalable systems
* ⚡ Improving performance
* 🔒 Maintaining security
* 🧩 Organizing system structure
* 🛠️ Making development easier

---

# 🏗️ Types of System Design

There are mainly two types:

---

## 📌 1. High-Level Design (HLD)

HLD gives the overall architecture of the system.

### Includes:

* 🧩 System architecture
* 🔌 API structure
* ☁️ Cloud services
* 🗄️ Database selection

### Example:

* Frontend → React ⚛️
* Backend → FastAPI ⚡
* Database → PostgreSQL 🗄️

---

## 🔍 2. Low-Level Design (LLD)

LLD focuses on internal details.

### Includes:

* 📄 Class diagrams
* 🔗 Function logic
* 🗂️ Database tables
* ⚙️ Algorithms

---

# 🧩 Components of System Design

---

## 🎨 1. Frontend Design

Frontend is the user-facing part of the system 👥

### Responsibilities:

* UI/UX design 🎨
* Forms and pages 📄
* User interaction 🖱️

### Technologies:

* HTML
* CSS
* JavaScript
* React ⚛️

---

## ⚙️ 2. Backend Design

Backend handles business logic and server operations 🧠

### Responsibilities:

* Authentication 🔐
* APIs 🔌
* Data processing 📊
* Server logic ⚡

### Technologies:

* FastAPI
* Node.js
* Django
* Spring Boot

---

## 🗄️ 3. Database Design

Database stores system data 💾

### Examples:

* User information 👤
* Resume data 📄
* Chat history 💬

### Popular Databases:

* PostgreSQL 🐘
* MySQL 🗄️
* MongoDB 🍃

---

## 🔌 4. API Design

APIs connect frontend and backend 🔗

### Example APIs:

* `/login` 🔐
* `/upload-resume` 📄
* `/generate-feedback` 🤖

### API Methods:

* GET 📥
* POST 📤
* PUT 🔄
* DELETE ❌

---

# 📊 System Architecture

Architecture defines:

> How different parts of the system communicate 🧩

---

## 🏛️ Monolithic Architecture

Entire application is built as one system.

### ✅ Advantages:

* Simple development
* Easy deployment

### ❌ Disadvantages:

* Difficult to scale
* Hard maintenance

---

## ☁️ Microservices Architecture

Application is divided into smaller services.

### Example:

* Authentication service 🔐
* AI service 🤖
* Payment service 💳

### ✅ Advantages:

* Better scalability
* Independent services

### ❌ Disadvantages:

* Complex management

---

# 🔒 Security in System Design

Security is a critical part of system design.

### Includes:

* 🔐 Password encryption
* 🧾 JWT authentication
* 🚫 SQL injection prevention
* 🛡️ Firewall protection

---

# 📈 Scalability

Scalability means:

> Ability of system to handle increasing users and traffic 👥⚡

---

## Types of Scaling

### 📊 Vertical Scaling

Increasing server power.

### 🌐 Horizontal Scaling

Adding multiple servers.

---

# ⚡ Performance Optimization

To improve speed and efficiency:

* ⚡ Caching
* 🗄️ Database indexing
* ☁️ CDN usage
* 🔄 Load balancing

---

# 🧪 System Design Diagrams

Diagrams help visualize the system.

---

## 📄 Flowchart

Shows process flow.

---

## 🧩 Use Case Diagram

Shows user interactions.

---

## 🗄️ ER Diagram

Shows database relationships.

---

## 🔗 Sequence Diagram

Shows communication between components.

---

# ☁️ Cloud & Deployment Design

Modern systems mostly use cloud platforms.

### Popular Platforms:

* AWS ☁️
* Azure 🔵
* Google Cloud 🌐

### Deployment Tools:

* Docker 🐳
* Kubernetes ☸️
* CI/CD pipelines 🔄

---

# 🚀 Real-Life Example

Suppose we build:

> 🤖 AI Mock Interview Platform

---

## 🎨 Frontend

React dashboard for users ⚛️

---

## ⚙️ Backend

FastAPI handles APIs ⚡

---

## 🗄️ Database

PostgreSQL stores user data 🐘

---

## 🤖 AI Service

OpenAI API generates interview feedback

---

## ☁️ Deployment

Hosted on AWS using Docker 🐳

---

# ⚠️ Common Mistakes in System Design

* ❌ Ignoring scalability
* ❌ Poor database structure
* ❌ Weak security
* ❌ Tight coupling between modules
* ❌ No backup strategy

---

# 🎯 Advantages of Good System Design

* ⚡ Better performance
* 📈 Easy scalability
* 🔒 Strong security
* 🛠️ Easier maintenance
* 👥 Better user experience

---

# 🧾 Final Summary

System Design converts requirements into a technical architecture 🏗️💻

It defines:

* frontend
* backend
* database
* APIs
* security
* scalability

A strong system design helps build:

* 🚀 scalable systems
* 🔒 secure applications
* ⚡ high-performance software
* 🧩 maintainable products

👉 Every modern software product depends on good system design principles.
