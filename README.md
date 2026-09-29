# Ondrel: concept website

Static site. No build step. Files:
- index.html  (whole site, Blender model embedded)
- favicon.svg, og.jpg  (tab icon and share image)

## Deploy on Vercel (free)
Option A: CLI
1. Install Node.js, then:  npm i -g vercel
2. In this folder run:  vercel      (log in, accept defaults, framework: Other)
3. Go live:  vercel --prod

Option B: GitHub
1. Put these files in a new GitHub repo.
2. vercel.com/new, import the repo, framework preset "Other", Deploy.

## After deploying
- In index.html set og:image to the full URL, e.g. https://YOUR-SITE.vercel.app/og.jpg
- Needs internet at runtime for Three.js (cdnjs) and Google Fonts.
- Ondrel is a fictional studio; hello@ondrel.example is not a real inbox.
