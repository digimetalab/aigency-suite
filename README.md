# AIgency Suite

AIgency Suite is a **multi-tenant AI Agency CMS & WebApp**, built with modern full-stack technologies.  
Designed for AI agencies to manage branding, content, automation, SEO, analytics, and more — all in one platform.  
The first agency using AIgency Suite is **Digimetalab**.

---

## 🚀 Features

### ✅ Multi-Tenant Architecture
- Each agency has isolated data and settings
- Custom branding (logo, colors, favicon)
- Custom domain or subdomain support

### ✅ Admin Dashboard
- Agency profile & settings
- Blog & content manager
- Media library
- Social media integrations
- SEO optimization tools
- Google Analytics support

### ✅ AI-Powered Tools *(optional modules)*
- AI content generator  
- Auto-publishing to social media  
- Automated workflows (cron-ready)

---

## 🛠️ Tech Stack

### **Frontend**
- Next.js 15 (App Router)
- React Server Components
- Tailwind CSS
- shadcn/ui components

### **Backend**
- Supabase (PostgreSQL + Auth + RLS + Storage)
- Server Actions

### **Deployment**
- Netlify (web)
- Supabase hosting (database & auth)

### **Mobile (Optional)**
- Next.js + Capacitor (one codebase)

---

## 📁 Project Structure

/app → Next.js routes (RSC + Server Actions)
/components → UI components (shadcn/ui + custom)
/lib → Supabase clients, utils, helpers
/types → TypeScript interfaces & types
/public → Static assets

## 🔧 Environment Variables

Create a `.env.local` file:

NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
SUPABASE_SERVICE_ROLE_KEY=
NEXT_PUBLIC_APP_URL=https://yourdomain.com

---

## ▶️ Development

```bash
npm install
npm run dev
Open:
http://localhost:3000

🌐 Deployment

Deploy frontend → Netlify

Host DB & Auth → Supabase

Add environment variables in Netlify

Configure redirect URLs in Supabase

📝 License

MIT License
© 2025 Digimetalab – AIgency Suite

💬 Support

For setup or customization requests:
Digimetalab – AI Automation Agency
