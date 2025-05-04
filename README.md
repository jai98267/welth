# 💸 AI Finance Platform

An **AI-powered finance management platform** designed to help individuals and businesses take control of their finances. By leveraging modern web technologies and AI, the platform allows users to track their income, expenses, and receive personalized insights to make better financial decisions. Whether you're managing a personal budget or overseeing company finances, the AI Finance Platform makes financial management more intuitive and efficient.

---

## 📚 Table of Contents

- [📌 Introduction](#introduction)
- [🚀 Features](#features)
- [📸 Screenshots](#-screenshots)
- [🛠️ Technologies Used](#technologies-used)
- [⚙️ How to Run the Application](#how-to-run-the-application)
  - [✅ Prerequisites](#prerequisites)
  - [📦 Installation Steps](#installation-steps)
  - [🧪 Running Tests](#running-tests)
- [🌐 Deployment](#deployment)
- [🤝 Contribution](#contribution)
- [🪪 License](#license)
- [👨‍💻 Author](#author)

---

## Introduction

The **AI Finance Platform** is a modern web application built using **Next.js**, **Supabase**, and other cutting-edge tools to help users efficiently manage their finances. It enables individuals and businesses to track income and expenses, receive AI-driven insights, and visualize financial trends in real-time.

The platform leverages:

- **Next.js** for a full-stack development environment, enabling a seamless combination of frontend and backend in one codebase.
- **Supabase** as the backend infrastructure, offering real-time databases, authentication, and storage.
- **Ingest** to process and transform financial data for analytics and AI predictions.
- **ShadCN UI** to build a sleek, responsive, and accessible user interface.
- **Clerk** for secure and easy-to-integrate user authentication and session management.
- **Resend** to deliver timely financial alerts and notifications via email.

This ecosystem creates a seamless experience for users to input, manage, and analyze their financial activities—all in one place with high performance and security.

## 🚀 Features

### ✅ Expense Tracker

📉 Track your daily expenses by category — Food, Travel, Rent, and more — to monitor and manage spending patterns effectively.

### ✅ Income Tracker

💰 Log multiple income sources such as salary, freelance work, and investments for a full view of your inflow.

### 🤖 AI Insights

🧠 Analyze historical data using AI models to generate personalized tips, optimize savings, and identify spending leaks.

### 📊 Interactive Dashboard

📈 Real-time data visualization with graphs, charts, and overviews to track financial health and trends.

### 🔄 Data Synchronization

🔗 Integrate APIs like **Google Finance**, **Gemini**, and **Resend** to sync real-time financial data automatically.

### 📋 Reports & Analytics

📃 Generate detailed monthly/quarterly/yearly financial reports and explore trends in categories and timeframes.

### 🔐 User Authentication

🧾 Secure login and user management with **Clerk**, allowing smooth sign-up, sign-in, and onboarding flows.

### 📱 Multi-Device Support

🖥️💻📱 Access the platform from mobile, tablet, or desktop with synchronized user data and responsive UI.

---

## 📸 Screenshots

### 🏠 Home Page

![Home](https://drive.google.com/uc?export=view&id=1rKBSnLwyuHyBgHvQ0rs26QGkaCBj8TAD)
![Home Alt](https://drive.google.com/uc?export=view&id=1z4muNgrbzh551RR1YQ1QIfJhUXk2YOzS)

### 📊 Dashboard View

![Dashboard](https://drive.google.com/uc?export=view&id=1y6PXzwtnSBkY92XtHaettEK36SD9b5OQ)
![Dashboard Alt](https://drive.google.com/uc?export=view&id=1QkTBGEp-GePy3IwoOoIbBUIWWn-RURa9)

### 📈 Analytics Overview

![Analytics](https://drive.google.com/uc?export=view&id=1YeKxvCJScyHJ6tv4lYlGTUaKlMSuI9fX)

---

## 🛠️ Technologies Used

| 🧩 Technology    | 🔍 Description                                                                                                     |
| ---------------- | ------------------------------------------------------------------------------------------------------------------ |
| ⚡ **Next.js**   | Full-stack React framework used for building the frontend and API routes.                                          |
| 🛢️ **Supabase**  | Backend-as-a-Service for database, auth, and real-time updates. Used in place of traditional MongoDB/Node backend. |
| 📥 **Ingest**    | Efficient data ingestion and analytics pipeline to process and transform financial records.                        |
| 💅 **ShadCN UI** | Modern UI component library for building beautiful, accessible components with Tailwind CSS.                       |
| 📧 **Resend**    | Email delivery service used to send real-time email alerts and notifications.                                      |
| 🔐 **Clerk**     | Authentication and user session management provider for secure sign-in, sign-up, and onboarding.                   |

## ⚙️ How to Run the Application

### ✅ Prerequisites

- 📦 [Node.js (>= v16)](https://nodejs.org/)
- 🛢️ Supabase or MongoDB (cloud/local)
- 🔐 Google Cloud API Key (for AI)
- 📄 `.env` file with required keys

### 📦 Installation Steps

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/ai-finance-platform.git

# 2. Navigate to the project directory
cd ai-finance-platform

# 3. Install dependencies
npm install

# 4. Create a `.env` file and add the following:
# Database Configuration
DATABASE_URL=
DIRECT_URL=

# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

# Gemini API (for AI features)
GEMINI_API_KEY=

# Resend API (for emails)
RESEND_API_KEY=

# Arcjet (bot detection)
ARCJET_KEY=

```
