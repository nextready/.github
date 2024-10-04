# About NextReady

[**NextReady**](https://nextready.dev) is more than just a boilerplate. It's a complete solution for building and deploying your next project. Or, build a quick MVP to validate your idea and the market first. It's easy to maintain for the long term and you get a constantly updated code base & dependencies.

### Tech Stack

- [Bun](https://bun.sh/): as the bundler & runtime,
- [TypeScript](https://www.typescriptlang.org/): as the language,
- [PostgreSQL](https://www.postgresql.org/): as the database,
- [Next.js](https://nextjs.org/): as the core framework,
- [Prisma](https://www.prisma.io/): as the ORM,
- [shadcn/ui](https://ui.shadcn.com/): as the UI library,
- [AI SDK](https://sdk.vercel.ai/): as the AI toolkit,
- [Nodemailer](https://nodemailer.com/): as the email sender,
- Payment: [Xendit](https://www.xendit.co) & [Lemon Squeezy](https://lemonsqueezy.com/),
- Auth: self-managed with complete flows,
- And many more.

With [shadcn/ui](https://ui.shadcn.com/) and [TailwindCSS](https://tailwindcss.com/) as the UI library, you can build unlimited components and pages using [v0](https://v0.dev). It's also compatible with [Magic UI](https://magicui.design/) for more beautiful components.

### Principles and Motivation

The NextReady principle is to use minimal third party services. So, you can build as fast as possible without doing a lot of configurations. We prefer to manage our services independently to avoid relying on third parties. For example, we use self-managed auth instead of Auth0 or Firebase. The same goes for email, databases, and other services.

NextReady prefers to use APIs rather than relying heavily on Server Components. This approach will be easier to maintain and scale in the future. We can deploy APIs separately and integrate them into the front end.

### Screenshots

![Landing Page contrast](https://nextready.dev/docs/landing2.png)

![Admin Panel contrast](https://nextready.dev/docs/admin.png)

### Project Structure

```
.
├── README.md
├── app
│   ├── (landing)
│   │   └── ... [landing pages]
│   ├── ~admin
│   │   └── ... [admin pages]
│   ├── api
│   │   ├── _middlewares
│   │   │   ├── authorization.ts
│   │   │   └── rbac.ts
│   │   ├── ~admin
│   │   │   └── ... [admin APIs]
│   │   ├── auth
│   │   │   └── ... [auth APIs]
│   │   └── ... [more APIs]
│   ├── auth
│   │   └── ... [auth pages]
│   ├── blog
│   │   └── ... [blog pages]
│   ├── dash
│   │   └── ... [dashboard pages]
│   ├── favicon.ico
│   ├── globals.css
│   └── layout.tsx
├── bun.lockb
├── components
│   ├── footer.tsx
│   ├── header.tsx
│   └── ui
│       └── ... [more components]
├── components.json
├── lib
│   ├── constant.ts
│   ├── random.ts
│   ├── utils.ts
│   ├── server
│   │   ├── db.ts
│   │   ├── email.ts
│   │   ├── payments
│   │   │   ├── lemonsqueezy.ts
│   │   │   └── xendit.ts
│   │   └── ... [more server libs]
│   └── web
│       └── ... [more web libs]
├── next.config.mjs
├── package.json
├── postcss.config.mjs
├── prisma
│   ├── migrations
│   │   └── ... [migrations]
│   └── schema.prisma
├── public
│   └── ... [images and other assets]
├── tailwind.config.ts
├── templates
│   └── email
│       └── ... [email templates]
└── tsconfig.json
```

**Note.** The structure and library may be changed based on needs.

### License

Buy the license key [here](https://mgilangjanuar.lemonsqueezy.com/buy/1af9f3f6-815a-429f-ad4f-dcb5c5fb557b?checkout%5Bdiscount_code%5D=LAUNCHNR).
