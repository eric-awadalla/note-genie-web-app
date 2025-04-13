# 🧠 NoteGenie

NoteGenie is a smart note-taking web app that helps users manage their notes and ask questions about them using AI. Powered by Gemini (Google GenAI), it provides intelligent answers based on your personal notes — all in a clean, responsive UI.

---

## 🚀 Features

- **🔐 Supabase Authentication**
  - Secure user authentication and session handling.
  - Notes stored and managed in Supabase database.

- **📚 Note Management**
  - Create, update, delete, and view all personal notes.
  - Display notes in a responsive sidebar layout.

- **💬 AI Assistant Integration**
  - Ask questions about your notes using Gemini (Google GenAI).
  - Context-aware answers rendered in semantic HTML.

- **🧠 Ask AI Modal**
  - Built using ShadCN Dialog components.
  - `useRef` for auto-focus and auto-height textarea.
  - Tracks user questions and AI responses for coherent conversations.

- **🎨 Dark and Light Mode**
  - Fully responsive theme switching using ShadCN theme provider.
  - Clean UI adapts to user preference or system setting.

- **📁 Sidebar Navigation**
  - Sidebar built with ShadCN components.
  - Displays all user notes for quick navigation and selection.

- **🧠 Styled AI Responses**
  - AI answers formatted in clean HTML.
  - Styled via `ai-response.css` and rendered safely with `dangerouslySetInnerHTML`.

- **💡 Smooth UX**
  - Transitions handled using `useTransition` hook for a responsive feel.
  - Auto-resizing input textarea for better writing experience.

---

## 🛠 Tech Stack

- **Frontend**: React (via Next.js 15), Tailwind CSS, ShadCN UI
- **Backend**: Next.js Server Actions, Supabase (Auth & DB)
- **Authentication**: Supabase Auth
- **Database**: Supabase (PostgreSQL)
- **AI**: Google GenAI (Gemini 2.0 Flash model)
- **Styling**: Tailwind CSS, ShadCN components, custom CSS
- **State Management**: React hooks (`useState`, `useRef`, `useTransition`, `useContext`)
- **Deployment**: Vercel

---

## 📦 Deployment

This project is deployed on **[Vercel](https://note-genie-web-app.vercel.app/)**.

## 🙏 Acknowledgement

This project was originally inspired by a FreeCodeCamp tutorial. I made several improvements and customizations, including the integration of Google GenAI (Gemini) instead of the original AI model.

