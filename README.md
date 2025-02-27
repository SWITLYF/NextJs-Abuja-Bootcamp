# Full Stack E-Commerce: NEXT.js14, React, Typescript, Prisma, Kinde, Tailwind CSS, UploadThing, PostgreSQL, Shadcn UI, Zustand

## Key Features

- 🛠️ Complete marketplace built from scratch in Next.js 14
- 💻 Beautiful landing page & product pages included
- 🎨 Custom artwork included
- 💳 Full admin dashboard
- 🛍️ Users can purchase and sell their own products
- 🛒 Locally persisted shopping cart
- 🔑 Authentication using Payload
- 🖥️ Learn how to self-host Next.js
- 🌟 Clean, modern UI using shadcn-ui
- ✉️ Beautiful emails for signing up and after purchase
- ✅ Admins can verify products to ensure high quality
- ⌨️ 100% written in TypeScript
🎁 ...much more

## Setup .env file

```bash
DATABASE_URL=

KINDE_CLIENT_ID=
KINDE_CLIENT_SECRET=
KINDE_ISSUER_URL=
KINDE_SITE_URL=http://localhost:3000
KINDE_POST_LOGOUT_REDIRECT_URL=http://localhost:3000
KINDE_POST_LOGIN_REDIRECT_URL=http://localhost:3000/auth-callback

ADMIN_EMAIL=your email

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=

NEXT_PUBLIC_SERVER_URL=http://localhost:3000
```

## Setup Prisma

```bash
npx prisma generate
npx prisma db push

```

## Available commands

| Command                | Description                              |
| ---------------------- | ---------------------------------------- |
| `npm run dev`          | Starts a development instance of the app |
| `npm run build`        | Builds the app for production            |
| `npm run start`        | Starts the app in production mode        |
