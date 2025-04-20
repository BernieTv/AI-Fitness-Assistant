<h1 align="center">💪 AI Fitness Assistant 🤖</h1>  
<p align="center"><em>Level up your health journey with personalized, intelligent fitness coaching powered by voice and AI.</em></p>

<p align="center">
  <img src="https://raw.githubusercontent.com/burakorkmez/codeflex-ai/refs/heads/master/public/screenshot-for-readme.png" alt="Demo App Screenshot" />
</p>

---

## 🌟 Project Highlights

- ⚡ **Modern Tech Stack**: Next.js, React, Tailwind CSS, Shadcn UI
- 🎹 **Conversational Voice Assistant** powered by **Vapi**
- 🧠 **LLM Integration** using **Gemini AI** for dynamic fitness plans
- 🏋️ **Custom Workout Generation** tailored to your goals
- 🥗 **Smart Diet Recommendations** based on personal needs
- 🔐 **Secure Authentication & Authorization** via **Clerk**
- 💃 **Realtime Database** with **Convex**
- 💡 **Client-Server Architecture**: Hybrid components
- 📱 **Responsive Design**: Mobile-first and user-friendly

---

## 🚀 Features

### 🤖 AI-Powered Coach

Engage in natural voice conversations with an intelligent assistant that understands your fitness goals, health conditions, and preferences.

### 🗕️ Personalized Workout Plans

Auto-generated training routines customized to your fitness level, injuries, and objectives.

### 🥦 Diet Program Generator

Receive adaptive meal recommendations accounting for allergies, nutrition goals, and food preferences.

### 🔐 Seamless Authentication

Login using GitHub, Google, or email/password via Clerk.

### 🧹 Program Management

Create, manage, and track multiple fitness programs — only the latest remains active, keeping your progress on point.

### 📱 Responsive & Accessible

Elegant, intuitive UI designed for seamless interaction on all devices.

---

## 🧪 Getting Started Locally

1. **Clone the repository**

```bash
git clone https://github.com/BernieTv/AI-Fitness-Assistant.git
```

2. **Install dependencies**

```bash
npm install
```

3. **Create a `.env` file in the root directory and configure the following:**

```env
# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
CLERK_WEBHOOK_SECRET=

# Clerk Redirect URLs
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# Vapi Voice AI
NEXT_PUBLIC_VAPI_WORKFLOW_ID=
NEXT_PUBLIC_VAPI_API_KEY=

# Convex Database
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=

# Google Gemini
GEMINI_API_KEY=
```

4. **Run the development server**

```bash
npm run dev
```

5. **Open your browser** and navigate to `http://localhost:3000`

---

## 🚀 Deployment Instructions

This app is optimized for deployment on [Vercel](https://vercel.com/):

```bash
npm run build
npm run start
```

Alternatively, connect your GitHub repository to Vercel for CI/CD and automatic deployments.

---

## 🧹 Tech Stack

| Tool/Service     | Role                                        |
| ---------------- | ------------------------------------------- |
| **Next.js**      | Frontend framework with SSR capabilities    |
| **React**        | Component-based UI architecture             |
| **Tailwind CSS** | Utility-first styling                       |
| **Shadcn UI**    | Modern component library                    |
| **Vapi**         | Voice-based conversational AI               |
| **Gemini AI**    | Large Language Model for content generation |
| **Clerk**        | Secure authentication and user management   |
| **Convex**       | Real-time cloud-native database             |

---

## 📚 Learn More

- [Next.js Documentation](https://nextjs.org/docs)
- [Clerk Documentation](https://clerk.com/docs)
- [Vapi Documentation](https://docs.vapi.ai)
- [Convex Documentation](https://docs.convex.dev)
- [Gemini AI Documentation](https://ai.google.dev/gemini-api)

---
