# AI Image Editor 🎨🤖

An AI-powered image editing web application that allows users to edit, enhance, and export images in real time. The platform combines modern frontend technologies with AI features to deliver a fast, intuitive, and scalable image editing experience.

🔗 **Live Demo:** https://ai-image-editor-six-beige.vercel.app/

---

## 🚀 Features

- AI-powered image editing with real-time canvas interaction
- Background removal and image enhancement using AI
- Crop, resize, rotate, and manipulate images dynamically
- Secure user authentication and protected routes
- Optimized image upload, storage, and delivery
- High-quality image export and download

---

## 🛠️ Tech Stack

- **Framework:** Next.js (App Router)
- **Frontend:** React, Tailwind CSS
- **Canvas & Editing:** Fabric.js
- **Authentication:** Clerk
- **Image Management:** ImageKit
- **Deployment:** Vercel

---

## 📂 Project Structure

```
app/
├─ dashboard/
├─ editor/[projectId]/
├─ api/
│ └─ imagekit/upload
├─ sign-in/
└─ sign-up/
```

## ⚙️ Environment Variables

Create a `.env.local` file and add the following variables:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_IMAGEKIT_PUBLIC_KEY=
IMAGEKIT_PRIVATE_KEY=
NEXT_PUBLIC_IMAGEKIT_URL_ENDPOINT=
```

## 🧪 Running Locally

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build
```

The app will be available at:

http://localhost:3000

## 🌐 Deployment

The project is deployed on Vercel using a production-ready configuration with optimized static and dynamic rendering.

**Live URL:**
👉 https://ai-image-editor-six-beige.vercel.app/

## 📌 Highlights

- Optimized bundle size and fast first-load performance
- Serverless API routes for image upload
- Scalable architecture suitable for production use

## 📄 License

This project is for educational and portfolio purposes.

## 🙌 Author

Omkar Tigade
Computer Engineering Student | Full Stack Developer

---

If you want, I can:

- Make it **shorter for recruiters**
- Add **screenshots section**
- Add **badges (Next.js, Vercel, Clerk)**
- Rewrite it in a **startup / SaaS style**

Just tell me 😄
