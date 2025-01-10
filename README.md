# Threadify 🚀💬

![Threadify Logo](iconUrl)

## Full Stack Threads Clone 🌐✨

Created a full-stack replica of the popular discussion platform **Threads**, enabling users to post and engage in threaded conversations. 🧵💻

---

## 🌟 Features 🌈

- **Authentication:** 🔒
  - Email, password, and social logins (Google and GitHub) powered by Clerk. 📧🔑
  - Comprehensive profile management system. 👤⚙️

- **Visually Appealing Home Page:** 🏡🎨
  - Showcases the latest threads for an engaging user experience. 🌟

- **Create Threads and Comments:** ✍️💬
  - Dedicated pages for creating threads and fostering discussions. 🤝
  - Nested commenting system for structured conversations. 🗨️🔗

- **User and Community Features:** 👥🌍
  - User search with pagination for easy exploration. 🔍📖
  - Notifications for thread activity. 🔔
  - User profiles with editable settings. 🛠️👤
  - Community creation, invitations, and member management. 🏘️📩
  - Admin-specific threads and community profiles. 🛡️👑

- **Modern UI and Performance:** 🎨⚡
  - Figma-inspired design implemented with Shadcn UI and TailwindCSS. 🖼️💅
  - Blazing-fast performance with Next.js and Server Side Rendering (SSR). 🚀🖥️
  - Real-time updates powered by webhooks. 🔄⏱️

- **Robust Backend:** 🛠️🔗
  - MongoDB for managing complex schemas and relationships. 🗄️📊
  - Serverless APIs and middleware for secure and scalable architecture. 🌐🔐
  - Form validation with Zod and React Hook Form. ✅📝

- **Media Support:** 📷🎥
  - Seamless file uploads using UploadThing. 📤✨

---

## 🛠️ Tech Stack 🧰💡

- **Frontend:** 🖥️
  - Next.js 14+ 🎉
  - TailwindCSS 🎨
  - Shadcn UI 🛋️

- **Backend:** 🗄️
  - MongoDB 🛢️
  - Serverless APIs 🌐
  - Clerk for authentication 🔐
  - Zod for validation ✅

- **Other Tools:** 🧩
  - React Hook Form 🖊️
  - Webhooks 🔄
  - UploadThing 📤

---

## 🚀 Quick Start ⚡✨

### Prerequisites ✅

Ensure you have the following installed: 🖥️🔧
- Git 🐙
- Node.js 🟢
- npm (Node Package Manager) 📦

### Installation Steps 🛠️

1. **Clone the Repository:** 📂
   ```bash
   git clone https://github.com/mohamedayoub97/Threadify.git
   cd Threadify
   ```

2. **Install Dependencies:** 📦
   ```bash
   npm install
   ```

3. **Set Up Environment Variables:** 🌱
   Create a `.env` file in the root directory and add the following:
   ```env
   MONGODB_URL=
   CLERK_SECRET_KEY=
   UPLOADTHING_SECRET=
   UPLOADTHING_APP_ID=
   NEXT_CLERK_WEBHOOK_SECRET=
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
   ```
   Replace placeholders with your actual credentials. 🔑

4. **Run the Application:** 🏃‍♂️
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser. 🌐✨

---

## 📋 Table of Contents 📚

1. [Introduction](#-introduction)
2. [Features](#-features)
3. [Tech Stack](#-tech-stack)
4. [Quick Start](#-quick-start)
5. [Snippets](#-snippets)
6. [Links](#-links)
7. [More Resources](#-more-resources)

---

## 🕸️ Snippets ✂️📄

### Key Code Files:
- `clerk.route.ts` 🔗
- `community.actions.ts` 🤝
- `CommunityCard.tsx` 💳
- `constants.index.ts` 📚
- `globals.css` 🎨
- `next.config.js` ⚙️
- `tailwind.config.js` 🖌️
- `thread.actions.ts` 🧵
- `uploadthing.ts` 📤
- `user.actions.ts` 👤
- `utils.ts` 🛠️

---

## 🔗 Links 🔗✨

- **GitHub Repository:** [Threadify](https://github.com/mohamedayoub97/Threadify.git) 🐙
- **Assets Used in Project:** [Link to Assets](#) 📂

---

## 🚀 More Resources 📖🎉

### Advance Your Skills 🎓
- Check out the [Next.js 14 Pro Course](#) for deeper insights. 📘✨

### Join the Community 🧑‍🤝‍🧑
- Engage with like-minded developers on our active Discord server. 🗨️🌐

---

## 👩‍💻 Created By

Mohamed Ayoub Essalami 🌟🌍
