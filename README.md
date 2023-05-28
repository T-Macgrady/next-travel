# Building a full-stack travel app with Next.js and MongoDB.

## Tech stack

- Client
  - Typescript
  - Next
  - zustand
  - TailwindCSS

- Serve
  - MongoDB
  - Prisma

## About

- Login (Google and Facebook)
- Image upload
- Location selection
- Map component
- Country autocomplete
- Fetching listings with server components

## Getting Started

### Prerequisites

- Install Node JS in your computer <a href='https://nodejs.org/en/'>HERE</a>
- Sign up for a Cloudinary account <a href='https://cloudinary.com/'>HERE</a>
- Sign up for a Google Cloud Platform <a href='https://console.cloud.google.com/'>HERE</a>
- Sign up for a Meta for Developers <a href='https://developers.facebook.com'>HERE</a>
- Get Lookup APi Key <a href='https://extreme-ip-lookup.com/'>HERE</a>

<!-- Env Variables -->

### Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`DATABASE_URL`

`GOOGLE_CLIENT_ID`

`GOOGLE_CLIENT_SECRET`

`FACEBOOK_ID`

`FACEBOOK_SECRET`

`NEXTAUTH_SECRET`

`NEXTAUTH_URL`

`NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME`

`NEXT_PUBLIC_LOOKUP_KEY`

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### Installation

![](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![](https://img.shields.io/badge/next.js-20232A?style=for-the-badge&logo=next.js&logoColor=61DAFB)

Install my-project with npm

```
npx create-next-app@latest my-project --typescript --eslint
```

```
cd my-project
```

Install dependencies

### :test_tube: Install Tailwind CSS with Next.js

#### Install Tailwind CSS

![](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

Install tailwindcss and its peer dependencies via npm, and then run the init command to generate both `tailwind.config.js` and `postcss.config.js`.

```
npm install -D tailwindcss postcss autoprefixer
```

```
npx tailwindcss init -p
```

#### Configure your template paths

Add the paths to all of your template files in your `tailwind.config.js` file.
<br>

```js
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    './app/**/*.{js,ts,jsx,tsx}',
    './pages/**/*.{js,ts,jsx,tsx}',
    './components/**/*.{js,ts,jsx,tsx}',

    // Or if using `src` directory:
    './src/**/*.{js,ts,jsx,tsx}',
  ],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

#### Add the Tailwind directives to your CSS

Add the `@tailwind` directives for each of Tailwind’s layers to your `./styles/globals.css` file.

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

<!-- Run Locally -->

### Run Locally

![](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)

Clone the project

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run dev
```

<hr />

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

<hr />

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

<!-- Deployment -->

### Deployment

To deploy this project run

##### Deploy on Vercel

![](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
