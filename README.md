Chatbot Project Overview (Zettalogix AI)

Project Name: Zettalogix AI – Conversational Chatbot
Developer:Badikol Akash Reddyssss
Deployment: https://zettalogix-ai.vercel.app

Project Summary

Zettalogix AI is an intelligent conversational chatbot built using Next.js and integrated with Google’s Gemini 2.0 Flash model via the Vercel AI SDK.
It simulates ChatGPT-like interaction through streaming text responses, enabling smooth and real-time conversations in the browser.

Tech Stack

Frontend:
- Framework: Next.js (React-based)
- Styling: Tailwind CSS
- UI Components: Assistant UI + ShadCN UI
- Language: TypeScript
- Hosting Platform: Vercel (Production)

Backend:
- Runtime: Node.js (Serverless functions in Next.js)
- AI Model API: Google Gemini 2.0 Flash
- Integration SDKs:
  - @ai-sdk/google – for Gemini model connection
  - ai – for streaming responses and message handling

API Keys Used

- Google Generative AI API Key (Gemini):
  GOOGLE_GENERATIVE_AI_API_KEY (stored securely in .env.local and Vercel environment variables)
This key enables the chatbot to connect with the Gemini model and stream intelligent replies.

-----------------------------------------------------------
Core Files & Architecture
-----------------------------------------------------------
- /app/api/chat/route.ts → Handles incoming chat requests and streams AI responses.
- /app/page.tsx → Chat interface and frontend layout.
- /components/assistant-ui/ → Contains chat UI components (threads, markdown text, attachments, etc.)
- /lib/utils.ts → Utility functions used across the app.
- .env.local → Stores API keys and environment configuration.

How It Works

1. User enters a message in the chat UI.
2. The frontend sends the conversation to /api/chat/route.ts.
3. The serverless API calls Google Gemini 2.0 Flash via the AI SDK.
4. The model streams the response back word-by-word to the UI.
5. The frontend displays the typing animation in real time.

Deployment Steps (Completed)

1. Pushed source code to GitHub.
2. Imported project to Vercel and linked environment variables.
3. Configured build using npm install && npm run build through vercel.json.
4. Successfully deployed to:
   https://zettalogix-ai.vercel.app



