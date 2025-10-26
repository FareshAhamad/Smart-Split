# 💸 SmartSplit – AI-Powered Bill Splitting App

SmartSplit is a **React Native application** that makes splitting bills with friends, roommates, and colleagues effortless.  
Using **advanced OCR technology**, users can scan receipts to automatically extract items and prices, then split costs fairly among group members.

---

## 🚀 Features

### 🧠 Core Functionality
- **OCR Receipt Scanning** – Scan receipts and automatically extract items, prices, and totals.  
- **Smart Bill Splitting** – Choose between equal, by item, or custom split methods.  
- **Group Management** – Create and manage groups for roommates, trips, or teams.  
- **Real-time Notifications** – Stay updated on new bills, payments, and group activity.  
- **Multi-platform Payments** – Supports **Stripe, PayPal, Venmo**, and cash payments.  

### 🎨 User Experience
- Clean and modern UI with smooth animations  
- **Offline Support** for key features  
- **Dark Mode** ready 🌙  
- Built with **accessibility best practices**

### ⚙️ Advanced Features
- **Expense Tracking** and insights dashboard  
- **Group Chat** for quick discussions  
- **Payment History** with filters and search  
- **Export Data** to CSV or PDF  

---

## 🧰 Tech Stack

### Frontend
- **React Native (Expo)**
- **TypeScript**
- **React Navigation**
- **Expo Camera** (for OCR scanning)
- **React Native Reanimated** (for animations)

### Backend
- **Supabase** – Database & authentication  
- **PostgreSQL** – Data storage  
- **Row Level Security (RLS)** – Data protection  
- **Realtime subscriptions** – Live updates  

### Services
- ** OCR.space**– OCR processing  
- **UPI (Unified Payments Interface)** – Payment handling  
- **Expo Notifications** – Push alerts  

---

## 🛠 Getting Started

### Prerequisites
- Node.js (v16+)
- npm or yarn
- Expo CLI
- iOS Simulator or Android Emulator (for testing)

### Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/smartsplit.git
cd smartsplit

# Install dependencies
npm install

# Create environment file
cp .env.example .env
