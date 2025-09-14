# TeamCollab

A modern SaaS-style application built with **Next.js 14**, **TypeScript**, **Tailwind CSS**, and **NextAuth.js**.

## 🚀 Features

- 🔐 **Authentication** – Secure login, signup, and session management with NextAuth.js

- 👤 **Role Management** – Separate dashboards for Users and Admins
- 📊 **Dashboard UI** – Responsive, modern dashboard interface built with Tailwind CSS
- 💳 **Payments Integration** – Subscription & one-time payments via Stripe
- 🎨 **UI/UX** – Pixel-perfect design system using Tailwind’s utility-first workflow
- 📱 **Responsive Design** – Works seamlessly across desktop, tablet, and mobile

## 🛠️ Tech Stack

- [Next.js 14](https://nextjs.org/) – React framework for production apps
- [TypeScript](https://www.typescriptlang.org/) – Type safety and maintainability
- [Tailwind CSS](https://tailwindcss.com/) – Utility-first styling
- [NextAuth.js](https://next-auth.js.org/) – Authentication and session management
- [Stripe](https://stripe.com/) – Payments integration (subscription + one-time)

## 📂 Project Structure

```bash
src/
 ├── app/              # Next.js App Router pages
 ├── components/       # Reusable UI components
 ├── utils/            # Helpers & utilities
 ├── hooks/            # Custom React hooks
 └── lib/              # Configurations (auth, stripe, etc.)
```

## ⚡ Getting Started

1. Clone the repo

   ```sh
   git clone https://github.com/ObiFaith/teamcollab.git
   cd teamcollab
   ```

2. Install dependencies

   ```sh
   npm install
   ```

3. Create `.env.local` file with the following:

   ```sh
    NEXTAUTH_SECRET=your-secret
    NEXTAUTH_URL=http://localhost:3000
    STRIPE_SECRET_KEY=your-stripe-secret
    STRIPE_PUBLIC_KEY=your-stripe-public
   ```

4. Run the development server

   ```sh
   npm run dev
   ```

## 🧑‍💻 Author

Built with ❤️ by [Faith Obi](https://github.com/ObiFaith)

## 📜 License

This project is licensed under the `MIT License`.
