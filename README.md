# 💸 SmartSplit

SmartSplit is a **React Native** bill-splitting application built with **Expo** and **TypeScript**.  
It allows users to easily scan receipts using OCR, split expenses with friends, manage groups, and track shared spending — all in one intuitive mobile app.

---

## 🚀 Core Functionality

- 📸 **OCR Receipt Scanning** — Scan receipts using **ocr.space** API to automatically extract and process text.  
- 👥 **Group Management** — Create and manage friend groups for shared expenses.  
- 💰 **Bill Splitting** — Split bills evenly or by custom amounts among group members.  
- 🔔 **Real-Time Notifications** — Get notified instantly when bills are added or settled.  
- 💬 **Group Chat** — Chat with your group members within the app.  
- 📊 **Expense Dashboard** — View an overview of your spending and balances at a glance.

---

## 🧠 Tech Stack

### Frontend
- ⚛️ **React Native (Expo)**
- 🟦 **TypeScript**
- 🧭 **React Navigation** — For navigation and screen management.
- 🧩 **Supabase** — Backend integration for authentication, data storage, and real-time updates.
- 🔍 **ocr.space** — Optical Character Recognition (OCR) for receipt scanning.

### Backend
- 🗄️ **Supabase (PostgreSQL)** — Database and authentication provider.
- 🔒 **Row Level Security (RLS)** — Ensures user-specific data access and privacy.



---

## 🔑 Key Components & Services

- **`AppNavigator`** — Handles app navigation flow between authenticated and guest users.  
- **`DashboardScreen`** — Displays user finances and shortcuts to core app features.  
- **`ocrService`** — Handles OCR image upload, optimization, and text extraction.  
- **`AuthProvider`** — Manages authentication state and provides user data globally.  
- **`BillCard`** — Reusable component for displaying individual bill details.  
- **`useGroupSelection`** — Custom hook for handling group selection and filtering logic.

---

## 🗃️ Database Schema Overview

- **users** — Stores user profiles and authentication data.  
- **groups** — Defines user groups for bill sharing.  
- **bills** — Tracks each bill created within a group.  
- **bill_items** — Stores individual items for each bill.  
- **bill_splits** — Records how bills are split among members.  
- **payments** — Tracks settlements and payments between users.  
- **notifications** — Stores in-app and push notifications.  
- **messages** — Enables real-time chat functionality.

> 🛡️ **Security:** Row Level Security (RLS) is applied throughout the database to ensure users can only access their own data.

---

## 🧩 Architecture

SmartSplit follows a **modern, scalable architecture** emphasizing:
- **Type safety** via TypeScript  
- **Code reusability** using modular components and hooks  
- **Separation of concerns** between frontend and backend  
- **Real-time synchronization** powered by Supabase  
- **Robust security** with RLS and authentication guards  

---

## 🏁 Getting Started

### Prerequisites
- Node.js ≥ 18
- Expo CLI
- Supabase project setup
- OCR.space API key

### Installation
```bash
# Clone the repository
git clone https://github.com/your-username/SmartSplit.git

# Navigate into the project
cd SmartSplit/frontend

# Install dependencies
npm install

# Start the Expo development server
npx expo start


## 🏗️ Project Structure

