<p align="center">
  <img src="https://online-project-images.s3.us-east-2.amazonaws.com/dentalpro/DentalProLogo-2.svg" height="55%" width="55%" alt="Dental Pro Logo"/>
</p>

<div align="center" id="toc">
  <ul style="list-style: none">
    <summary>
      <h1>🦷 Dental Pro – AI Dental Assistant 🦷</h1>
    </summary>
  </ul>
</div>

<div align="center">

[![Built With](https://img.shields.io/badge/Built_with-Next.js_App_Router-blue)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/Language-TypeScript-blue)](https://www.typescriptlang.org/)
[![UI](https://img.shields.io/badge/UI-TailwindCSS_+_Shadcn_UI-blue)](https://ui.shadcn.com/)
[![Auth](https://img.shields.io/badge/Auth_+_Billing-Clerk-blue)](https://clerk.com/)
[![Database](https://img.shields.io/badge/Database-PostgreSQL-blue)](https://www.postgresql.org/)
[![Data](https://img.shields.io/badge/Data-TanStack_Query-blue)](https://tanstack.com/query)
[![Emails](https://img.shields.io/badge/Emails-Resend-blue)](https://resend.com/)
[![Voice AI](https://img.shields.io/badge/Voice_AI-Vapi-blue)](https://vapi.ai/)
[![Deploy](https://img.shields.io/badge/Deploy-Vercel-blue)](https://vercel.com/)

[![Version](https://img.shields.io/badge/version-10.0.0-blue.svg)](https://github.com/isaiahpeoples/dental-pro)
[![Maintenance](https://img.shields.io/badge/Maintained-yes-brightgreen.svg)](https://github.com/Isaiahpeoples/DentalPro/graphs/commit-activity)
[![Live](https://img.shields.io/badge/Live-Demo-brightgreen)](https://dental-pro-phi.vercel.app/)

</div>
<br/>

## 💡 Project Overview

**Dental Pro** is a modern dental platform that combines an **appointment booking system**, a **full admin dashboard**, and an optional **AI voice assistant** (paid plans only) in one place.

It includes a clean, conversion-focused landing page, secure authentication via **Clerk**, a 3-step booking flow (Dentist → Service & Time → Confirm), **email notifications** for bookings and invoices, and **subscription billing** (Free + two paid tiers) with smart upgrade behavior (pay only the difference).

<br/>

## 🚀 Technologies Used

| Technology | Description |
|-----------|-------------|
| **Next.js (App Router)** | ⚡ Full-stack React framework with server components, server actions, and API routes. |
| **TypeScript** | 🔒 Strong typing for maintainable, scalable code. |
| **Tailwind CSS** | 🎨 Utility-first styling for responsive UI. |
| **Shadcn UI** | 🧩 Accessible, modern UI components. |
| **TanStack Query** | 🔄 Data fetching, caching, and server-state management. |
| **Clerk** | 🔐 Authentication + subscription billing (Free + Paid tiers). |
| **PostgreSQL** | 🗃️ Relational database for appointments, users, plans, and records. |
| **Resend** | 📩 Booking confirmations + invoices delivered via email. |
| **Vapi** | 🗣️ AI voice agent for real-time dental Q&A (paid plans only). |

<br/>

## 📸 Project Screenshot

![Dental Pro Preview](https://online-project-images.s3.us-east-2.amazonaws.com/dentalpro/DentalPro-4.png)

*A modern dental booking platform with admin dashboard and Pro voice assistant.*

<br/>

## 📑 Key Features

- 🏠 **Modern Landing Page** — Gradients, images, and clean marketing sections.
- 🔐 **Authentication** — Clerk login via Google, GitHub, or email/password.
- 🔑 **Email Verification** — 6-digit code verification for email/password sign-ups.
- 📅 **Appointment Booking** — Create and manage bookings end-to-end.
- 🦷 **3-Step Booking Flow** — Dentist → Service & Time → Confirm (with back/edit option).
- ⏱️ **Slot Availability** — Detect and prevent double-booking.
- 📩 **Email Notifications** — Booking confirmation emails sent via Resend.
- 📊 **Admin Dashboard** — Manage appointments and view upcoming bookings.
- 💳 **Subscriptions** — Free plan + two paid plans via Clerk Billing.
- 🧾 **Automatic Invoices** — Invoice emails automatically sent after subscription.
- 💸 **Smart Upgrades** — Upgrade flow charges only the difference.
- 🗣️ **AI Voice Agent (Pro)** — Vapi-powered real-time dental assistant (paid plans only).
- ⚡ **Optimized Data Fetching** — TanStack Query for smooth UX and caching.
- 🧑‍💻 **GitHub Workflow Ready** — Branches, PRs, reviews, merges supported.
- 🚀 **Deployment** — Production-ready setup for Vercel.

<br/>

## 🔧 Installation & Setup 🔧

1. **Clone the repository**:
```bash
git clone https://github.com/USERNAME/dental-pro.git
cd dental-pro
```

2. **Install dependencies**:
```bash
npm install
```

3. **Environment variables: Configure the .env file with the following keys**:

```js
# App
NEXT_PUBLIC_APP_URL=your_app_url

# Clerk Auth + Billing
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

# Database (PostgreSQL)
DATABASE_URL=your_postgres_database_url

# Resend (Emails)
RESEND_API_KEY=your_resend_api_key
ADMIN_EMAIL=your_admin_email

# Vapi (Voice AI - Paid Plans)
NEXT_PUBLIC_VAPI_ASSISTANT_ID=your_vapi_assistant_id
NEXT_PUBLIC_VAPI_API_KEY=your_vapi_api_key
```

4. **Run database migrations**:
```bash
# If using Prisma:
 npx prisma migrate dev

# If using Drizzle:
 npx drizzle-kit push
```

5. **Start the development server**:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

<br/>

## 📂 Project Structure 📂

- **/app: Next.js routes, server actions, and API handlers**

- **/components: UI components, forms, and shared modules**

- **/lib: Helpers and integrations (auth, email, billing, utilities)**

- **/prisma: Database schema/migrations/queries (PostgreSQL)**

- **/public: Static assets (images, icons, branding)**

<br/>

## 📌 Learn More 📌

To learn more about the technologies used in this project:

## 📌 Learn More 📌

- [Next.js Documentation](https://nextjs.org/docs)  
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)  
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)  
- [Shadcn UI Documentation](https://ui.shadcn.com/docs)  
- [TanStack Query Documentation](https://tanstack.com/query/latest/docs/framework/react/overview)  
- [Clerk Documentation](https://clerk.com/docs)  
- [PostgreSQL Documentation](https://www.postgresql.org/docs/)  
- [Resend Documentation](https://resend.com/docs)  
- [Vapi Documentation](https://docs.vapi.ai)  
- [CodeRabbit](https://coderabbit.ai/)  
- [Vercel Deployment Docs](https://nextjs.org/docs/app/building-your-application/deploying)

<br/>

## 🌐 Live Demo

Check out the live version:  
👉 [Dental Pro Live Demo](https://dental-pro-phi.vercel.app/)

<br/>

### ⭐️ Support ⭐️
If you found this project helpful or interesting, please give it a ⭐️! Your support helps to grow the project and boosts visibility. Thank you!