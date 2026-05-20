# Deploy to Vercel

This folder contains a static HTML dashboard. Two simple options to deploy:

1) Using the Vercel CLI

```bash
npm install -g vercel
cd "c:\\Users\\Acer\\Downloads\\DS Task"
vercel           # first-time interactive deploy (login + project settings)
vercel --prod    # promote to production
```

2) Using Vercel via Git provider

- Create a Git repo, push to GitHub/GitLab/Bitbucket.
- In the Vercel dashboard, "New Project" → import the repo.
- Vercel will detect a static site and deploy automatically.

If you want, I can prepare a Git repo and run the CLI deploy for you (you'll need to complete the Vercel login flow).
