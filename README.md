
🧾 OrderTrack – Smart Order Management System

👤 Participant Details

- Name: Zayed Shaikh


---

📌 Project Description

OrderTrack is a modern web-based Order Management System designed for wholesalers, bulk-order businesses, and order-based shops.

Unlike traditional retail billing systems, OrderTrack focuses on businesses that handle custom, multi-item, and large-volume orders, where managing orders manually in notebooks becomes slow, error-prone, and difficult to track.

It helps business owners:

- Digitally manage orders
- Track payments (advance / remaining)
- Maintain complete order history
- Communicate easily with customers

---

🎯 Problem Statement

Many small and medium businesses still rely on manual registers to track bulk orders. This leads to:

- ❌ Human errors in calculations
- ❌ Difficult tracking of pending payments
- ❌ No proper order history
- ❌ Poor customer communication

OrderTrack solves this by digitizing the entire process.

---

🚀 Key Features

- 🔐 Secure Authentication (Supabase Auth)
- 🧾 Multi-item Order Creation (Dynamic Cart)
- 💰 Automatic Payment Calculation (Advance, Remaining, Status)
- 📊 Order History & Tracking
- 📱 Click-to-Call & WhatsApp Integration
- ⚡ Real-time UI Updates using React
- 🔒 Data Isolation using Row Level Security (RLS)

---

🛠️ Tech Stack (Simple Explanation)

Frontend

- React 18 → Builds fast and interactive UI
- TypeScript → Reduces bugs with type safety
- Vite → Fast development and build tool
- Tailwind CSS → Makes UI clean and responsive
- Lucide React → Icons for better UI

Backend & Database

- Supabase → Handles backend (Auth + Database)
- PostgreSQL → Stores all data securely

---

🧠 How It Works (Simple)

- User logs in securely
- Creates a new order
- Adds multiple items dynamically
- System calculates:
  - Total amount
  - Advance paid
  - Remaining amount
- Order is saved in database
- User can:
  - View order history
  - Call customer
  - Send WhatsApp receipt

---

🗄️ Database Structure (Simple)

1. Users

Stores shop owner details

2. Orders

Stores main order info:

- Customer name
- Total amount
- Payment status

3. Order Items

Stores products inside each order:

- Product name
- Quantity
- Price

---

🧪 Key Highlights (For Judges / Presentation)

- ✅ Clean and simple UI
- ✅ Real-world business use case (wholesale orders)
- ✅ Proper database design (Orders + Items separation)
- ✅ Secure data using RLS
- ✅ Smart calculations (auto payment status)
- ✅ Improves customer communication

---

⚙️ Installation & Setup

1. Clone Repository

git clone https://github.com/zayedshaikh7/ordertrack
cd ordertrack

2. Install Dependencies

npm install

3. Setup Environment Variables

Create a ".env" file:

VITE_SUPABASE_URL=your_url
VITE_SUPABASE_ANON_KEY=your_key

4. Run Project

npm run dev

Open in browser:

http://localhost:5173

---

🌐 Live Demo

👉 https://ordertrack-vp5b.onrender.com/

---

📷 Screenshots


<img width="300" height="350" alt="1000068825" src="https://github.com/user-attachments/assets/20ad2c87-5881-4a15-bde7-049b61614b43" />
<img width="300" height="350" alt="1000068828" src="https://github.com/user-attachments/assets/13fad0b8-27cc-4b20-8ea9-20e63208c239" />
<img width="300" height="350" alt="1000068827" src="https://github.com/user-attachments/assets/6318c4f0-6826-4cb0-904d-26d98303c8d2" />
<img width="300" height="350" alt="1000068826" src="https://github.com/user-attachments/assets/53224bb0-f4a8-4fff-a8cb-4f7238af67fd" />
<img width="300" height="350" alt="1000068824" src="https://github.com/user-attachments/assets/13d65bfb-0790-4338-aaa2-459f142c026b" />


---

🔗 GitHub Repository

👉 https://github.com/zayedshaikh7/ordertrack

---

🌍 Future Improvements

- 📦 Inventory management system
- 📊 Advanced analytics dashboard
- 📱 Mobile app version
- 🧾 PDF invoice generation

---

🤝 Contribution

This is an open-source project. Contributions are welcome!

