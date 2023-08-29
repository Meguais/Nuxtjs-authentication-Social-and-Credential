# Nuxt 3 starter

A modular template that provides essential features to quickly get started on your full stack Nuxt 3 project

## Features

- ✔️ Prisma integration
- ✔️ User authentication with password and social login
- ✔️ File upload to S3 compatible file storage services
- ✔️ Customizable UI layer based on Naive UI
- ✔️ Firebase Cloud Messaging integration
- ✔️ Tailwindcss integration via [@nuxtjs/tailwindcss](https://github.com/nuxt-modules/tailwindcss) module
- ✔️ HTTP security via [nuxt-security]() module
- ✔️ Error monitoring via [bugsnag-js]() module

## Setup
1. Create new repository from this [template](https://github.com/Meguais/Nuxtjs-authentication-Social-and-Credential).
2. Make sure to install the dependencies:

```bash
# yarn
yarn install

# npm
npm install

# pnpm
pnpm install
```

4. Run prisma migration
```bash
npx prisma migrate dev
```

That's it! You can now get started on your project ✨
## Development Server

Start the development server on http://localhost:3000

```bash
npm run dev
```

## Production

Build the application for production:

```bash
npm run build
```

Locally preview production build:

```bash
npm run preview
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.
