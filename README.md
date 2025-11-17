# 🚀 **Zettalogix AI – Conversational Chatbot**

### **Developer:** Badikol Akash Reddy

🔗 **Live Deployment:** [https://zettalogix-ai.vercel.app](https://zettalogix-ai.vercel.app)

---

## 🧠 **Project Overview**

**Zettalogix AI** is a modern conversational chatbot designed to deliver fast, natural, and intelligent responses—similar to ChatGPT—directly inside the browser.
It leverages **Next.js**, **Google Gemini 2.0 Flash**, and the **Vercel AI SDK** to enable **real-time streaming responses**, giving users a seamless AI chat experience.

---

## 💡 **Key Highlights**

* ⚡ **Lightning-fast streaming responses** powered by Gemini Flash
* 🎨 **Beautiful chat UI** using Assistant UI + ShadCN UI
* 🛡️ **Secure API integration** with environment variables
* 🌐 **Deployed on Vercel** with serverless backend functions
* 🧩 **Clean architecture** with reusable components

---

## 🛠️ **Tech Stack**

### **Frontend**

* **Next.js** (App Router)
* **React + TypeScript**
* **Tailwind CSS** for styling
* **Assistant UI** for chat components
* **ShadCN UI** for modern UI elements

### **Backend**

* **Node.js Serverless Functions** (Next.js API Routes)
* **Vercel AI SDK** for message streaming
* **Gemini 2.0 Flash Model** for conversational intelligence

---

## 🔐 **API Keys Used**

### **Google Generative AI – Gemini**

Stored securely in:

* `.env.local`
* Vercel → Project Settings → Environment Variables

Environment variable:

```
GOOGLE_GENERATIVE_AI_API_KEY=
```

This key powers the chatbot’s ability to generate real-time responses.

---

## 🧩 **Core Architecture**

```
/app
├── api/chat/route.ts     → Streams AI responses
├── page.tsx              → Main chat interface
/components
│   └── assistant-ui/     → Chat UI elements (messages, markdown, file blocks)
/lib/utils.ts             → Helper utilities
.env.local                 → Secrets & configuration
```

---

## ⚙️ **How It Works (Flow)**

1. ✍️ User types a message
2. 📤 Frontend sends input to `/api/chat/route.ts`
3. 🤖 Gemini 2.0 Flash generates a response
4. 🔁 The Vercel AI SDK streams the reply token-by-token
5. 💬 The UI renders the response in real time with typing animation

---

## 🚀 **Deployment Process (Completed Successfully)**

1. Code pushed to **GitHub repository**
2. Project imported into **Vercel**
3. Environment variables configured
4. Build setup using:

   ```
   npm install && npm run build
   ```

   (via vercel.json if needed)
5. Deployment successful at 👉
   **[https://zettalogix-ai.vercel.app](https://zettalogix-ai.vercel.app)**

---

## 🎯 **Final Result**

Zettalogix AI is now a **fully deployed, professional-grade chatbot** demonstrating:

✔️ Strong frontend development
✔️ Serverless backend integration
✔️ Modern AI model usage
✔️ Real-time streaming implementation
✔️ Production deployment via Vercel

A perfect addition to your **portfolio, resume, and client demos**.

---

If you want, I can also create:

✨ A stunning **README.md**
✨ A **poster / banner image**
✨ A **LinkedIn announcement post**
✨ A **GitHub repository description**
✨ A **project logo**

Just tell me **what you want next**!
