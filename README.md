# 🌾 AgriBridge (2025)

**A Platform Bridging Farmers and Consumers**

AgriBridge is a full-stack web application that directly connects farmers with consumers, eliminating middlemen to ensure fair pricing and transparency. Alongside commerce, it integrates **smart food and health analysis tools** to empower users with agricultural, nutritional, and ingredient insights.

🌐 **Live Demo:** [https://farm-bridge.vercel.app/](https://farm-bridge.vercel.app/)

---

## 📁 Repositories

* **Backend:** [https://github.com/govind-sing/farmBridge_backend](https://github.com/govind-sing/farmBridge_backend)
* **Frontend:** [https://github.com/govind-sing/farmBridge_frontend](https://github.com/govind-sing/farmBridge_frontend)

---

## ✨ Key Features

### 🚜 Farmer–Consumer Marketplace

* Direct farmer-to-consumer product listings
* Role-based access for farmers and consumers
* Inventory management and order handling
* Fair pricing with complete transparency

### 🌿 Smart Agriculture & Food Analysis

* **Plant & leaf recognition** using image uploads
* **Crop disease detection** with server-side API integration
* Graceful failure handling for unreliable image inputs

### 🥗 Nutrition Intelligence

* USDA-based food nutrition analysis
* Fetches detailed data including:

  * Protein
  * Fat
  * Energy (calories)
  * Vitamins and nutrients

### 🧪 Ingredient Safety Checker

* Ingredient analysis for **food and cosmetic products**
* Classifies ingredients as **safe or harmful**
* Provides fallback search links when data is unavailable

### 🔐 Authentication & UX

* Secure JWT-based authentication
* Responsive and mobile-friendly UI
* Smooth and efficient product and data workflows

---

## 🏗️ Tech Stack

### Frontend

* React.js
* Tailwind CSS

### Backend

* Node.js
* Express.js
* MongoDB

### Authentication & Utilities

* JWT (JSON Web Tokens)
* Multer & Formidable (image uploads)
* External REST APIs (Plant detection, nutrition, ingredient analysis)

---

## 📌 Project Highlights (2025)

* Engineered a **direct farmer-to-consumer ecosystem**
* Removed intermediaries to support farmers’ income
* Integrated **AI-powered food and agriculture insights**
* Designed resilient APIs with fallback mechanisms
* Focused on scalability, security, and real-world usability

---

## 🚀 Getting Started (Local Setup)

### Clone the repositories

```bash
git clone https://github.com/govind-sing/farmBridge_frontend
git clone https://github.com/govind-sing/farmBridge_backend
```

### Install dependencies

```bash
npm install
```

### Run the application

```bash
npm run dev
```

> Ensure environment variables are configured for MongoDB, JWT secrets, and third-party API keys.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🙌 Vision

AgriBridge aims to **empower farmers**, promote **healthy consumer choices**, and leverage technology to create a more **transparent and intelligent agricultural ecosystem**.

---
