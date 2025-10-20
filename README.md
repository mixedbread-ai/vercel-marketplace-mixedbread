# Vercel with Mixedbread

A minimal template for building AI Search applications using Next.js, Vercel, and Mixedbread.

## Getting Started

Click the "Deploy to Vercel" button to clone this repo and create a new Vercel project:

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fmixedbread-ai%2Fvercel-marketplace-mixedbread%2Ftree%2Fmain&project-name=my-vercel-mixedbread-app&repository-name=my-vercel-mixedbread-app)

This will:

1. Clone this repository to your GitHub account
2. Create a new Vercel project

## Local Development

### 1. Clone your repository

```bash
git clone <your-repo-url>
cd my-vercel-mixedbread-app
```

### 2. Install dependencies

```bash
npm install
```

### 3. Install Mixedbread Integration

**If this is your first time installing:**

1. Visit the [Mixedbread integration page](https://vercel.com/marketplace/mixedbread) and click **Install**
2. Select your Vercel project
3. Accept to create a Mixedbread account
4. Create your first product and choose a plan
5. You'll be redirected to the product page
6. Copy the environment variables from the product page

**If you already have the integration installed:**

1. Go to your Vercel project **Integrations** tab
2. Click on your Mixedbread integration
3. Select an existing product
4. Copy the environment variables from the product page

### 4. Create local .env file

```bash
cp .env.example .env
```

Add the environment variables you copied from the Mixedbread product page:

```txt
MIXEDBREAD_API_KEY=your-api-key-here
```

### 5. Start the development server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

## Learn More

To learn more about Mixedbread, check out the Mixedbread documentation:

- [Mixedbread Documentation](https://www.mixedbread.com/docs) - learn about Mixedbread's features and APIs.
- [Mixedbread Discord](https://discord.gg/fCpaq2dr) - join the Mixedbread Discord server to ask questions and join the community.

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

## Deploy on Vercel

Commit and push your code changes to your GitHub repository to automatically trigger a new deployment.
