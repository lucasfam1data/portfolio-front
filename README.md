
# 🧩 Flow CRM - Frontend Mock (Next.js + Tailwind)

This is a mock CRM dashboard interface developed as a portfolio project.  
It demonstrates how a complete CRM UI could be structured using **Next.js 13 App Router**, **Tailwind CSS**, and **TypeScript**.

> 🔗 Available at: `/crm`

---

## 🚀 Features

- ✅ Kanban board for managing appointments
- 👥 Client and service modules
- 📈 Insights with charts and metrics
- 📬 Message section simulation
- 🧩 Modular and reusable UI components
- 🎨 Fully styled with Tailwind CSS
- 💼 Clean layout for SaaS-style platforms

---

## 🖼️ Screenshots

### 📊 Dashboard - Insights & Metrics

![image](https://github.com/user-attachments/assets/20f84ed4-5637-4596-bba3-f98b9b39bc53)


### 🗂️ Kanban Board - Appointments Flow

![image](https://github.com/user-attachments/assets/323d8d50-c2c8-4664-896b-ad9aeacfa24c)


> _You’ll find these screens under the route `/crm`._

---

## 📂 Folder structure (simplified)

```
src/
├── app/crm/           → CRM main route and pages
├── components/        → UI elements (Board, Cards, Sidebar, Topbar)
├── hooks/             → Custom React logic
├── lib/               → Reusable utilities
├── styles/            → Global Tailwind setup
```

---

## 💻 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/lucasmello-dev/portfolio-front.git
cd portfolio-front
```

### 2. Install dependencies

```bash
pnpm install
# or
npm install
```

### 3. Run the development server

```bash
pnpm dev
# or
npm run dev
```

Then open:

```
http://localhost:3000/crm
```

---

## 🛠️ Troubleshooting

### App stuck on `✓ Starting...`?

```bash
rm -rf .next
npm run dev
# or change port:
PORT=3001 npm run dev
```

---

## 👨‍💻 Author

Developed by [@lucasmello-dev](https://github.com/lucasmello-dev) for learning and portfolio purposes.

---

## 📄 License

MIT License  
Feel free to use, fork or adapt this project for educational use — credit is appreciated.
