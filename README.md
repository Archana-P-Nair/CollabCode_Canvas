## ✨ CollabCode Canvas

A real‑time **collaborative coding & whiteboard workspace** with built‑in **video**, **chat**, and **AI assistance** — all in one place. 🚀  

- **GitHub**: [`https://github.com/Archana-P-Nair/CollabCode_Canvas`](https://github.com/Archana-P-Nair/CollabCode_Canvas)  
- **Live Demo**: [`https://collabcode-canvas-h14w.onrender.com/`](https://collabcode-canvas-h14w.onrender.com/)  

---

### 🧠 What is this project?

**CollabCode Canvas** is an online environment where people can:

- 👩‍💻 Write and run code together in the browser  
- 📝 Sketch ideas on a shared whiteboard / flowchart canvas  
- 💬 Chat in real time while collaborating  
- 📹 Jump on a built‑in video call  
- 🤖 Use AI to help with code, explanations, and brainstorming  

Think of it as a mix of a **collaborative IDE**, **digital whiteboard**, and **virtual study room**.

---

### 👥 Who is it for?

- **Students & study groups** – pair programming, DSA practice, project discussions  
- **Teachers, mentors & coaches** – live coding, explaining concepts visually  
- **Interviewers & candidates** – remote coding interviews with editor + whiteboard  
- **Remote dev teams** – debugging sessions, architecture discussions, quick experiments  
- **Anyone learning to code** – try code, ask AI, and visualize logic easily  

---

### 🧰 Tech stack

**Frontend** (`frontend/`)  
- ⚛️ React / Next.js (App Router)  
- 🧩 TypeScript  
- 🎨 Tailwind CSS  
- 🔌 WebSockets for real‑time collaboration  

**Backend** (`backend/`)  
- 🟩 Node.js  
- 🧾 TypeScript  
- 🌐 REST APIs + WebSockets  
- 🧮 Code execution services (e.g. Python, JavaScript, etc.)  

**Tooling & misc**  
- 📦 npm  
- 🔐 Security middleware for safe code execution  

---

### 🌟 Key features

- **Real‑time collaborative code editor**  
  - Multiple users can type in the same document  
  - Support for multiple languages (e.g. Python, JavaScript, etc.)  
  - Integrated code execution via backend services  

- **Shared whiteboard / canvas**  
  - Draw diagrams, annotate, highlight code logic  
  - Great for explaining algorithms or system design  

- **Flowchart & diagram panel**  
  - Build flowcharts to plan logic and architecture  

- **AI assistant panel** 🤖  
  - Ask coding questions  
  - Get explanations, suggestions, and improvements  

- **Room‑based collaboration**  
  - Create/join rooms for different sessions  
  - Each room has its own code, whiteboard, chat, and participants  

- **Built‑in chat 💬**  
  - Real‑time messaging inside each room  
  - Share ideas, links, and quick notes  

- **Video call integration 📹**  
  - Talk face‑to‑face while coding and drawing  

- **Share links 🔗**  
  - Share rooms / content via URLs for quick access  

---

### 📁 High‑level project structure

```text
CollabCode_Canvas/
  ├─ backend/        # Node.js + TypeScript backend, APIs, WebSockets, code execution
  ├─ frontend/       # Next.js/React UI, components (editor, whiteboard, chat, video, AI, etc.)
  ├─ package.json    # Root config / scripts (if used)
  └─ package-lock.json
```

*(Details may vary slightly depending on your current code; this is the general idea.)*

---

### 🏁 Getting started (run locally)

> ⚠️ Requirements: **Node.js (LTS)** and **npm** installed.

#### 1️⃣ Clone the repository

```bash
git clone https://github.com/Archana-P-Nair/CollabCode_Canvas.git
cd CollabCode_Canvas
```

#### 2️⃣ Install dependencies

> If your root `package.json` has no install step, you can skip the root and only install inside `frontend` and `backend`.

**Root (optional):**

```bash
npm install
```

**Frontend:**

```bash
cd frontend
npm install
```

**Backend:**

```bash
cd ../backend
npm install
```

#### 3️⃣ Configure environment variables

Create `.env` / `.env.local` files where needed (check the code for `process.env.*` usage):

Typical things you may need:

- **Frontend** (`frontend/.env.local` for Next.js)  
  - API base URL (e.g. `NEXT_PUBLIC_API_URL=http://localhost:4000`)  
  - WebSocket URL  
  - AI endpoint URL/keys (if applicable)  

- **Backend** (`backend/.env`)  
  - Server port (e.g. `PORT=4000`)  
  - Execution service URLs / API keys  
  - CORS origin(s) (e.g. `http://localhost:3000`)  

> If you already know your exact env variables, you can list them explicitly here.

#### 4️⃣ Run the backend server

From the `backend/` folder:

```bash
npm run dev
# or, depending on your scripts:
npm start
```

The backend will typically run on something like `http://localhost:4000` (update if your code uses a different port).

#### 5️⃣ Run the frontend

In a **new terminal**, from the `frontend/` folder:

```bash
npm run dev
```

Then open the URL shown in the terminal, usually:

```text
http://localhost:3000
```

---

### 🚀 Using the app

1. Open `http://localhost:3000` (or the **deployed URL**:  
   [`https://collabcode-canvas-h14w.onrender.com/`](https://collabcode-canvas-h14w.onrender.com/))  
2. **Create or join a room**.  
3. **Invite others** by sharing the room link.  
4. Use:
   - The **code editor** to write & run code together  
   - The **whiteboard / canvas** to sketch ideas  
   - The **flowchart tools** to map logic  
   - The **chat** for coordination and notes  
   - The **video call** to communicate in real time  
   - The **AI assistant** to ask questions or get coding help  

---

### 🧪 Common scripts (quick reference)

> Check `frontend/package.json` and `backend/package.json` for the exact script names. Typical patterns:

**Frontend:**

```bash
npm run dev      # Start Next.js dev server
npm run build   # Build for production
npm run start   # Start production server
```

**Backend:**

```bash
npm run dev      # Start backend in watch/dev mode
npm run build   # Compile TypeScript
npm start       # Run compiled server
```

---

### 🤝 Contributing

Contributions, suggestions, and feedback are very welcome! 💡  

1. 🍴 Fork the repo  
2. 🌿 Create a feature branch (`git checkout -b feature/my-feature`)  
3. ✅ Commit your changes with clear messages  
4. 📬 Open a pull request against `master` with a short description  

---

### 📜 License

> _Add your license here_ (for example, **MIT License**).  
> If you haven’t chosen one yet, you can generate an MIT license from GitHub’s “Add file → Create new file → `LICENSE`” flow.

---

### 💡 Future improvements (ideas)

- Support for more programming languages and runtimes  
- Session recording / playback  
- Richer AI capabilities (debugging, code review, explanations, test generation)  
- Better permissions/roles in rooms (host, viewer, editor)  
- Integrated file system / multi‑file projects  

---

If you’d like, I can now:  
- Tailor the **env variable section** to your actual keys once you share them, or  
- Add an extra section for **screenshots/GIFs** with placeholder image names you can swap in.
