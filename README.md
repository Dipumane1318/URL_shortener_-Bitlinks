# 🔗 Bitlinks

## 📌 Description

**Bitlinks** is a fast and minimal URL shortener web application. Paste any long URL and get a clean, shareable short link instantly — all powered by a modern full-stack setup.

---

## ✨ Features

- 🔗 Shorten any long URL into a compact link
- ⚡ Instant redirect on visiting the short URL
- 🗄️ Persistent storage with MongoDB
- 🌐 Hosted-ready with configurable base host URL
- 📱 Responsive UI built with Tailwind CSS

---

## 🛠️ Tech Stack

| Layer      | Technology              |
|------------|-------------------------|
| Framework  | Next.js 16              |
| UI Library | React 19                |
| Styling    | Tailwind CSS v4         |
| Database   | MongoDB                 |
| Language   | JavaScript (ES Modules) |

---

## 📂 Project Structure

```
bitlinks/
├── app/                  # Next.js App Router (pages & API routes)
├── public/               # Static assets
├── .env.local            # Environment variables (not committed)
├── jsconfig.json         # Path aliases (@/*)
├── next.config.mjs       # Next.js configuration
├── eslint.config.mjs     # ESLint configuration
└── package.json          # Project dependencies & scripts
```

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/bitlinks.git
   cd bitlinks
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**

   Create a `.env.local` file in the root directory:
   ```env
   MONGO_URI=mongodb://localhost:27017/bitlinks
   NEXT_PUBLIC_HOST=http://localhost:3000
   ```

   > 🔹 Replace `MONGO_URI` with your MongoDB Atlas connection string for production.  
   > 🔹 Replace `NEXT_PUBLIC_HOST` with your deployed domain in production.

4. **Run the development server**
   ```bash
   npm run dev
   ```

   Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## ▶️ Usage

1. Visit the homepage
2. Paste your long URL into the input field
3. Click **Shorten** to generate a short link
4. Copy and share your short link
5. Visiting the short link will redirect to the original URL

---

## 🎯 Future Improvements

- 📊 Add click analytics & tracking per link
- 🔐 User authentication for managing personal links
- ✏️ Custom short URL aliases
- 📋 Dashboard to view and manage all shortened links
- ⏳ Link expiration / auto-delete after a set time

---

## 👤 Author

**Dipak Mane**  
[GitHub]((https://github.com/Dipumane1318)) • [LinkedIn](https://www.linkedin.com/in/dipak-mane-b11abb318/)

---

