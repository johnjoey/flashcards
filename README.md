## Getting Started

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

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Spec

### potential tech stack
- hosting: Vercel
- frontend: Next.js 16 (app router)
- AWS API Gateway + Lambda functions
- DB: DynamoDB
- File storage: S3
- Auth: cognito

### overview of features
- Create a new flashcard
- organise cards into groups
- create a quiz from one or more groups
- save flashcards and fetch (DB stuff)
- bulk upload via .csv

### baby steps
- [ ] hello world app in Next.js 16 hosted on Vercel
- [ ] create a lambda to read and write to DynamoDB
- [ ] setup API Gateway to trigger the lambda
- [ ] connect Next.js app to the API Gateway endpoint (press a button and do a thing with DDB)

### stretch goals
- [] user auth with cognito
