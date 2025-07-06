# Splitter: AI‑Powered Expense Splitter (Ongoing)

Splitter is a full‑stack application that simplifies how groups and friends manage shared expenses. Leveraging AI and real‑time collaboration, users can scan receipts, split bills in multiple ways, and get personalized insights—all in one responsive web app.

---

## 🔍 Project Status

> ⚙️ **Ongoing**: This project is under active development. New features, optimizations, and UI improvements are continuously being added.

---

## 🚀 Features

- **Flexible Expense Splitting**: Support for one‑on‑one and group expenses with equal, percentage‑based, and exact‑amount splits. Includes a circular‑debt simplification algorithm to minimize the number of transactions needed.
- **Real‑Time Collaboration**: Built on Next.js with Convex for real‑time data sync and WebSockets. Create/join groups, add expenses or settlements, and view live balance updates without page refresh.
- **AI‑Driven Insights & Notifications**: Integrated Google Gemini AI to analyze spending patterns, generate unusual‑spending alerts and tailored saving tips. Automated monthly email reminders keep everyone on track.
- **Interactive Analytics**: Dynamic charts display monthly trends, top spenders, and overall balance overviews to help users make informed financial decisions.
- **User‑Friendly UI**: Crafted with Tailwind CSS and Shadcn UI for a polished, responsive design. React Hook Form + Zod ensure robust form validation; Clerk provides secure authentication.

---

## 🛠 Tech Stack

- **Frontend:** Next.js, React, Tailwind CSS, Shadcn UI, React Hook Form, Zod
- **Backend & Data:** Node.js, Convex, MongoDB/Your DB of choice
- **AI & Automation:** Google Gemini AI, Ingest (cron workflows)
- **Auth & Storage:** Clerk (authentication), Cloud Storage (e.g., AWS S3)
- **Deployment:** Vercel (frontend), (backend hosting platform)

---

## ⚙️ Getting Started

1. **Clone the Repo**  
   ```bash
   git clone https://github.com/your-username/splitter.git
   cd splitter
   ```
2. **Install Dependencies**  
   ```bash
   npm install
   ```
3. **Environment Variables**  
   Create a `.env.local` file at the root and add:
   ```env
   NEXT_PUBLIC_CONVEX_URL=<your-convex-url>
   GEMINI_API_KEY=<your-google-gemini-key>
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=<your-clerk-pub-key>
   CLERK_SECRET_KEY=<your-clerk-secret>
   ```
4. **Run Locally**  
   ```bash
   npm run dev
   ```
5. **Build for Production**  
   ```bash
   npm run build && npm start
   ```

---

## 📝 Usage

1. Sign up or log in via Clerk.
2. Browse or import contacts to form a group.
3. Upload receipt images or manually add expenses.
4. Choose your split method (equal, percentage, exact).
5. View live balances, analytics, and AI‑generated insights.

---

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request for bug fixes, feature requests, or enhancements.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

> Crafted by Mohammad Ashhar | June 2025 – Ongoing
