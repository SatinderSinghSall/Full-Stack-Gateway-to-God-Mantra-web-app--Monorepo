# 🕉️ Gateway to God – Mantras

A **modern full-stack devotional web application** where users can explore sacred Hindu mantras, read their meanings, and maintain a personal spiritual profile.

The application provides a clean, responsive reading experience for sacred chants like **Hanuman Chalisa**, **Lalita Sahasranama**, and **Rama Mantra**, while allowing users to create accounts and manage their profiles.

Built with a **modern full-stack JavaScript architecture** using **Next.js, Tailwind CSS, shadcn UI, Node.js, Express, and MongoDB**.

---

# ✨ Features

### 🧘 Spiritual Content

- 📜 **Hanuman Chalisa**
  - Hindi verses
  - Meaning for each verse
  - Clean devotional reading UI

- 🌺 **Lalita Sahasranama**
  - Sacred names of Goddess Lalita
  - Meaning for each name
  - Scrollable reading experience

- 🕉️ **Rama Mantra**
  - Chant display
  - Interactive chant counter

---

### 👤 User System

- Secure **User Signup**
- **User Login**
- **JWT Authentication**
- Protected **Profile Page**
- Fetch logged-in user data

---

### 🎨 Modern UI

- Fully **responsive design**
- Built with **Tailwind CSS**
- Modern UI components using **shadcn/ui**
- Clean spiritual reading layout
- Mobile-first design

---

### ⚡ Full Stack Architecture

- **Frontend:** Next.js (React)
- **Backend:** Node.js + Express
- **Database:** MongoDB
- **Authentication:** JWT
- **API Communication:** Axios

---

# 🏗️ Tech Stack

## Frontend

- **Next.js (App Router)**
- **React**
- **Tailwind CSS**
- **shadcn/ui**
- **Axios**
- **Lucide Icons**

## Backend

- **Node.js**
- **Express.js**
- **MongoDB**
- **Mongoose**

## Authentication

- **JWT (JSON Web Token)**
- **bcryptjs**

## Dev Tools

- ESLint
- Nodemon
- dotenv

---

# 📂 Project Structure

# File Tree: Gateway to God - Mantras

**Generated:** 3/16/2026, 8:36:50 PM
**Root Path:** `e:\My Projects\Full-Stack Mantra Web App\Gateway to God - Mantras`

```
├── 📁 backend
│   ├── 📁 src
│   │   ├── 📁 config
│   │   │   └── 📄 db.js
│   │   ├── 📁 controllers
│   │   │   ├── 📄 authController.js
│   │   │   ├── 📄 chantController.js
│   │   │   └── 📄 mantraController.js
│   │   ├── 📁 middleware
│   │   │   └── 📄 authMiddleware.js
│   │   ├── 📁 models
│   │   │   ├── 📄 Chant.js
│   │   │   ├── 📄 Mantra.js
│   │   │   └── 📄 User.js
│   │   ├── 📁 routes
│   │   │   ├── 📄 authRoutes.js
│   │   │   ├── 📄 chantRoutes.js
│   │   │   └── 📄 mantraRoutes.js
│   │   ├── 📁 seed
│   │   │   └── 📄 seedMantras.js
│   │   └── 📁 utils
│   │       └── 📄 generateToken.js
│   ├── ⚙️ package-lock.json
│   ├── ⚙️ package.json
│   └── 📄 server.js
├── 📁 frontend
│   ├── 📁 app
│   │   ├── 📁 hanuman-chalisa
│   │   │   └── 📄 page.jsx
│   │   ├── 📁 lalita-sahasranama
│   │   │   └── 📄 page.jsx
│   │   ├── 📁 login
│   │   │   └── 📄 page.jsx
│   │   ├── 📁 profile
│   │   │   └── 📄 page.jsx
│   │   ├── 📁 rama-mantra
│   │   │   └── 📄 page.jsx
│   │   ├── 📁 signup
│   │   │   └── 📄 page.jsx
│   │   ├── 📄 favicon.ico
│   │   ├── 🎨 globals.css
│   │   ├── 📄 layout.tsx
│   │   └── 📄 page.tsx
│   ├── 📁 components
│   │   ├── 📁 ui
│   │   │   ├── 📄 avatar.tsx
│   │   │   ├── 📄 button.tsx
│   │   │   ├── 📄 card.tsx
│   │   │   ├── 📄 dialog.tsx
│   │   │   ├── 📄 dropdown-menu.tsx
│   │   │   ├── 📄 input.tsx
│   │   │   └── 📄 label.tsx
│   │   ├── 📄 MantraCard.jsx
│   │   ├── 📄 Navbar.jsx
│   │   └── 📄 VerseCard.jsx
│   ├── 📁 context
│   │   └── 📄 AuthContext.jsx
│   ├── 📁 data
│   │   ├── 📄 hanumanChalisa.js
│   │   ├── 📄 lalitaSahasranama.js
│   │   └── 📄 ramaMantra.js
│   ├── 📁 lib
│   │   ├── 📄 api.js
│   │   └── 📄 utils.ts
│   ├── 📁 public
│   │   ├── 🖼️ file.svg
│   │   ├── 🖼️ globe.svg
│   │   ├── 🖼️ next.svg
│   │   ├── 🖼️ vercel.svg
│   │   └── 🖼️ window.svg
│   ├── ⚙️ .gitignore
│   ├── 📝 README.md
│   ├── ⚙️ components.json
│   ├── 📄 eslint.config.mjs
│   ├── 📄 next-env.d.ts
│   ├── 📄 next.config.ts
│   ├── ⚙️ package-lock.json
│   ├── ⚙️ package.json
│   ├── 📄 postcss.config.mjs
│   └── ⚙️ tsconfig.json
├── ⚙️ .gitignore
└── 📝 README.md
```

---

_Generated by FileTree Pro Extension_

```
Gateway to God - Mantras
│
├── backend
│   ├── src
│   │   ├── config
│   │   │   └── db.js
│   │   │
│   │   ├── controllers
│   │   │   ├── authController.js
│   │   │   ├── mantraController.js
│   │   │   └── chantController.js
│   │   │
│   │   ├── middleware
│   │   │   └── authMiddleware.js
│   │   │
│   │   ├── models
│   │   │   ├── User.js
│   │   │   ├── Mantra.js
│   │   │   └── Chant.js
│   │   │
│   │   ├── routes
│   │   │   ├── authRoutes.js
│   │   │   ├── mantraRoutes.js
│   │   │   └── chantRoutes.js
│   │   │
│   │   └── utils
│   │       └── generateToken.js
│   │
│   └── server.js
│
└── frontend
    ├── app
    │   ├── login
    │   ├── signup
    │   ├── profile
    │   ├── hanuman-chalisa
    │   ├── lalita-sahasranama
    │   └── rama-mantra
    │
    ├── components
    │   ├── Navbar
    │   ├── MantraCard
    │   └── VerseCard
    │
    ├── data
    │   ├── hanumanChalisa.js
    │   ├── lalitaSahasranama.js
    │   └── ramaMantra.js
    │
    ├── lib
    │   └── api.js
    │
    └── context
        └── AuthContext.jsx
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/gateway-to-god-mantras.git
cd gateway-to-god-mantras
```

---

# 🚀 Backend Setup

Navigate to backend folder:

```bash
cd backend
```

Install dependencies:

```bash
npm install
```

Create `.env` file:

```
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
```

Run backend server:

```bash
npm run dev
```

Server will start on:

```
http://localhost:5000
```

---

# 💻 Frontend Setup

Navigate to frontend folder:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Run development server:

```bash
npm run dev
```

Frontend will start on:

```
http://localhost:3000
```

---

# 🔐 Authentication Flow

1. User signs up
2. Password is hashed using **bcrypt**
3. Backend generates **JWT token**
4. Token stored in **localStorage**
5. Protected API routes verify token
6. Profile data fetched from backend

---

# 📡 API Endpoints

### Authentication

```
POST /api/auth/signup
POST /api/auth/login
GET  /api/auth/me
```

---

### Mantras

```
GET /api/mantras
GET /api/mantras/:slug
```

---

### Chant Counter

```
POST /api/chants/increment
GET /api/chants
```

---

# 📱 Responsive Design

The UI is fully responsive using **Tailwind breakpoints**:

| Device  | Layout        |
| ------- | ------------- |
| Mobile  | Single column |
| Tablet  | Two columns   |
| Desktop | Three columns |

---

# 🌟 Future Improvements

Planned enhancements:

- 🔊 Mantra audio playback
- 📿 Digital mala counter (108 beads)
- 🌙 Dark mode
- ⭐ Favorite mantras
- 📅 Daily mantra reminders
- 📱 Progressive Web App (PWA)
- 🌐 Multi-language support

---

# 🤝 Contributing

Contributions are welcome.

Steps:

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Push to branch
5. Open Pull Request

---

# 📜 License

This project is licensed under the **MIT License**.

---

# 🙏 Acknowledgements

Inspired by traditional Hindu devotional practices and the timeless wisdom of sacred mantras.

---

# 👨‍💻 Author

**Satinder Singh Sall**

Full-Stack Developer
Passionate about building meaningful spiritual and modern web applications.

---

# ⭐ Support

If you like this project, consider giving it a **star on GitHub** ⭐
