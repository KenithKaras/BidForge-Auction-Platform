🚀 BidForge – Real-Time Auction Platform

BidForge is a full-stack real-time auction platform designed to deliver a seamless and interactive bidding experience. It enables users to participate in live auctions with instant bid updates powered by WebSocket technology, ensuring that every action is reflected in real time without delays or page refreshes.

The platform operates on a 💰 credit-based economy, allowing controlled and strategic bidding while maintaining fairness and engagement among users. Alongside this, BidForge integrates 🤖 AI-powered features using the Google Gemini API, helping admins generate high-quality item descriptions and assisting bidders with smart bid suggestions based on ongoing auction activity.

With a modern UI 🎨, smooth animations, and scalable architecture, BidForge focuses on performance, usability, and intelligent decision-making, making it a complete solution for next-generation digital auction systems.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-View%20Project-00BFA6?style=for-the-badge&logo=vercel&logoColor=white)](https://your-live-link.com)

### ✨ Key Features

🔴 Real-time bidding using WebSockets

💰 Credit-based bidding system

⚡ Instant bid updates without refresh

🤖 AI-powered item descriptions

📊 Smart bid suggestions for users

🎨 Modern responsive UI with smooth animations

### 🛠️ Tech Stack
🎨 Frontend:-
⚛️ React
🎨 Tailwind CSS
🎞️ Framer Motion
🧩 Lucide Icons

⚙️ Backend:-
🟢 Node.js
🚏 Express.js
🔌 Socket.io
🗄️ Database
🟩 Supabase (PostgreSQL)

🤖 AI Integration:-
🧠 Google Gemini API

### ⚙️ Setup Instructions
1️⃣ Database Setup (Supabase)
🌐 Create a new project on https://supabase.com/
🧾 Open the SQL Editor
▶️ Run the contents of supabase_schema.sql
⚙️ Go to Project Settings → API
📋 Copy:
Project URL
anon public key

###

2️⃣ Environment Variables
📁 Create a .env file in the root directory:

VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
GEMINI_API_KEY=your_gemini_api_key
###

3️⃣ Installation
npm install
###

4️⃣ Run the Application
npm run dev

### 🤖 AI Features
👨‍💼 Admin Side

✨ AI Generate Button
Automatically creates professional item descriptions using Gemini API

👤 Bidder Side

📊 Smart Bid Suggestions
Recommends optimal bid values based on current auction activity

### 🔄 Real-Time Bidding Logic

BidForge uses 🔌 Socket.io for real-time communication.

When a user places a bid:

📡 The server broadcasts the update instantly

👥 All connected users see the updated price live

🔄 No page refresh required

### 🎯 Project Objective

To build a scalable, real-time auction system that combines:

🔴 Live interaction

🤖 Intelligent bidding assistance

⚡ Seamless user experience

### 🚀 Future Enhancements

💳 Payment gateway integration

📈 Advanced AI analytics for bidding trends

📱 Mobile app version

🛡️ Fraud detection system
