# 📝 Notes Editor with AI Chat Integration

![GitHub repo size](https://img.shields.io/github/repo-size/dLomas26/Notes-Editor)
![GitHub stars](https://img.shields.io/github/stars/dLomas26/Notes-Editor?style=social)
![GitHub forks](https://img.shields.io/github/forks/dLomas26/Notes-Editor?style=social)

A sleek, Notion-inspired notes editor built with **Next.js**, **TypeScript**, and **Tailwind CSS**, featuring rich-text editing via **TipTap v2** and an embedded ChatGPT-style AI assistant for each note.

---

## 🚀 Features

- **Multi-Note Management**: Sidebar navigation to create, view, and switch between multiple notes.
- **Rich Text Editing**: Utilize TipTap v2 for formatting options like headings, bullet lists, and numbered lists.
- **Embedded AI Chat**: Each note includes a floating AI chat interface that responds to user prompts using a dummy API.
- **Note-Specific Chat History**: Chats are stored per note, ensuring context is maintained.
- **Responsive Design**: Optimized for both desktop and mobile devices.

---

## 🛠️ Tech Stack

- **Framework**: [Next.js](https://nextjs.org/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Editor**: [TipTap v2](https://tiptap.dev/)
- **State Management**: [Zustand](https://github.com/pmndrs/zustand) (optional)

---

## 📂 Project Structure

📦 Notes-Editor
├── app/ # Next.js app directory
├── components/ # Reusable UI components
├── hooks/ # Custom React hooks
├── lib/ # Utility functions and API interactions
├── types/ # TypeScript type definitions
├── public/ # Static assets
├── styles/ # Global styles and Tailwind configurations
├── .eslintrc.json # ESLint configuration
├── next.config.js # Next.js configuration
├── tailwind.config.ts # Tailwind CSS configuration
└── tsconfig.json # TypeScript configuration


---

## 🧪 Getting Started

### Prerequisites

- Node.js (v14 or later)
- npm or yarn

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/dLomas26/Notes-Editor.git
   cd Notes-Editor

2. Install dependencies:

  ```bash
  npm install
  # or
  yarn install


3. Run the development server:

  ```bash
  npm run dev
  # or
  yarn dev

4. Open in browser:

  Navigate to http://localhost:3000 to view the application.

```

🙌 Acknowledgements
  TipTap for the rich-text editor.
  Tailwind CSS for utility-first styling.
  Next.js for the React framework.
