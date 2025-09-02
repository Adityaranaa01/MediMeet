# MediMeet 🩺💻

MediMeet is a modern telemedicine platform built with **Next.js 15**, **Clerk authentication**, **Prisma ORM**, and **Vonage SDK** for secure video consultations. It enables doctors and patients to connect seamlessly with scheduling, authentication, and a responsive UI powered by **TailwindCSS** and **shadcn/ui** components.

---

## 🚀 Features

* 🔑 **Authentication & Authorization** with Clerk
* 🗂️ **Prisma ORM** for database access and schema management
* 🎥 **Vonage SDK Integration** for video consultations
* 🎨 **Modern UI** with TailwindCSS + shadcn/ui + Radix UI components
* 🌙 **Dark/Light Theme** support via next-themes
* ✅ **Form validation** using React Hook Form + Zod
* 📅 **Appointment booking and management**
* ⚡ **Fast dev experience** with Next.js Turbopack

---

## 🛠️ Tech Stack

* **Frontend & Backend**: [Next.js 15](https://nextjs.org/)
* **Auth**: [Clerk](https://clerk.dev/)
* **Database**: [Prisma](https://www.prisma.io/)
* **Video Calls**: [Vonage SDK](https://developer.vonage.com/)
* **Styling**: [Tailwind CSS](https://tailwindcss.com/) + [shadcn/ui](https://ui.shadcn.com/)
* **Validation**: [Zod](https://zod.dev/) + [React Hook Form](https://react-hook-form.com/)

---

## 📦 Installation

Clone the repo:

```bash
git clone https://github.com/yourusername/MediMeet.git
cd MediMeet
```

Install dependencies:

```bash
npm install
```

Generate Prisma client:

```bash
npx prisma generate
```

Set up environment variables in a `.env` file:

```env
DATABASE_URL="your_database_url"
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY="your_clerk_key"
CLERK_SECRET_KEY="your_clerk_secret"
VONAGE_API_KEY="your_vonage_key"
VONAGE_API_SECRET="your_vonage_secret"
```

Run development server:

```bash
npm run dev
```

---

## ▶️ Usage

* Register/login using Clerk authentication.
* Book or schedule a medical appointment.
* Join secure video calls powered by Vonage.
* Manage patient/doctor profiles and records.

---

## 📂 Project Structure

```
MediMeet/
│── app/              # Next.js App Router pages & layouts
│── components/       # Reusable UI components
│── hooks/            # Custom React hooks
│── lib/              # Utility functions
│── prisma/           # Prisma schema and migrations
│── public/           # Static assets
│── middleware.js     # Clerk middleware
│── package.json      # Dependencies & scripts
```

---

## 🤝 Contributing

Contributions are welcome! Please fork this repo and open a pull request.
