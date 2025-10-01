**Next.js AI Chatbot** is a full-stack chatbot application powered by **Next.js**, **TypeScript**, and **AI model integration (LLMs)**.  
It provides a clean and scalable architecture to build **production-ready AI assistants**.  

---

## 📖 Summary  

This chatbot is designed as an **AI-first application** with:  

- ⚡ **Fast and type-safe frontend** built in **Next.js**  
- 🔌 **AI integrations** through `lib/` for calling LLM APIs (e.g., OpenAI, Hugging Face)  
- 🗄️ **Database support** with **Drizzle ORM** to store chat history and user sessions  
- 🛡️ **Middleware** for input validation, authentication, and rate limiting  
- 📊 **Instrumentation** to monitor requests, track performance, and analyze usage  
- 🧪 **Playwright E2E tests** for stable chatbot flows  
- 🚀 **Vercel deployment** for serverless, global-scale hosting  

---

## ✨ Features  

- 💬 **Real-time Chat** – Users can send and receive AI responses instantly  
- 📜 **Chat History** – Persist conversations with Drizzle ORM  
- 👤 **User Authentication** – Secure sessions (middleware support for auth)  
- 🔐 **Rate Limiting** – Prevent abuse with request-level middleware  
- 📊 **Analytics** – Built-in instrumentation for monitoring AI usage  
- 🧪 **Testing Suite** – Playwright and unit tests ensure stability  
- 🌍 **One-click Deployment** – Pre-configured for Vercel  

---

## 📂 Project Structure  

```bash
.
├── app/                   # Main chatbot logic & Next.js routes
├── components/            # UI components (chat window, message list, input box)
├── hooks/                 # Custom hooks for state management & API calls
├── lib/                   # AI integration, utilities, helpers
├── tests/                 # Unit and E2E tests
├── public/images/         # Static assets (icons, logos, etc.)
│
├── drizzle.config.ts      # Database ORM config
├── instrumentation.ts     # Analytics & logging
├── middleware.ts          # Auth, validation, and AI request pipelines
├── next.config.ts         # Next.js app config
├── tsconfig.json          # TypeScript configuration
├── postcss.config.mjs     # PostCSS configuration
├── playwright.config.ts   # Playwright testing configuration
└── vercel-template.json   # Vercel deployment template

