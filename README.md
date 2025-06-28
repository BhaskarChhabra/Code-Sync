

# 🖥️ Interview Platform

A full-featured **Interview Platform** designed for seamless technical interviews with built-in video conferencing, code editor, meeting scheduling, recording, and real-time feedback features. This project focuses on delivering an intuitive and reliable experience for both interviewers and candidates.

---

## 🚀 Features

### 🎥 Meeting Room UI

* Setup and join meetings with video and audio options.
* Live camera preview and participant management.
* Custom hooks manage call state transitions for smooth user experience.
* Toggle audio/video, manage participants, and flexible meeting layouts.

### 💻 Code Editor Component

* Integrated **Monaco Editor** for coding during interviews.
* Supports multiple languages and selectable coding questions.
* Resizable editor panels that replicate **VS Code**-like experience.
* Dynamic starter code updates for an interactive coding environment.

### 📼 Recordings Page

* View all recorded calls with duration and timestamps.
* Uses `useGetCalls` custom hook for fetching and managing recording data.
* User-friendly UI displaying recording cards with playback functionality.

### 📅 Schedule Page

* Create, view, and manage interview schedules.
* Modal for entering title, description, candidate, and multiple interviewers.
* Date and time slot selection with validation, loading states, and error handling.

### 📊 Dashboard Page

* Overview of interviews: Upcoming, Completed, Failed.
* Real-time updates on interview status.
* Options to add ratings and comments post-interview.
* Clean UI with categorized interview grouping.

### 💬 Comment Dialogue & Rating Component

* Submit ratings and feedback for completed interviews.
* Star-based rating system with integrated comment section.
* Handles asynchronous submissions, loading states, and error feedback.
* Displays existing comments and ratings dynamically.

### 🎯 Candidate View

* Dedicated interface for candidates to view upcoming and completed interviews.
* Meeting cards with essential interview details.
* Optimized loading states and responsive UI for candidates.

---

## 🌐 Deployment & Hosting

* Deployed via **Vercel** for seamless CI/CD.
* Source code hosted on **GitHub**, ready for collaborative development.
* Environment variables configured securely for production use.
* Quick deployment process, typically under a minute.

---

## ⚒️ Tech Stack

* **Next.js** for frontend framework.
* **React** for building component-based UI.
* **Monaco Editor** for in-browser code editing.
* **Vercel** for hosting and deployment.
* **Custom Hooks** for state management.
* **CSS & Modular Components** for responsive layouts.

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/BhaskarChhabra/Code-Sync.git
cd interview-platform

# Install dependencies
npm install

# Run development server
npm run dev
```

Open `http://localhost:3000` to view the application locally.
