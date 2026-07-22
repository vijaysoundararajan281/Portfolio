# Vijay S — Portfolio

A single-page, dependency-free portfolio (plain HTML/CSS/JS). No build step, no framework.

```
.
├── index.html        ← the whole site
└── assets/
    └── vijay.png     ← portrait
```

## Put it online with Vercel (free, gives you a public link)

You have two easy routes. Route A is the quickest. Route B gives you a nicer URL and auto-updates when you push changes.

### Route A — drag & drop (about 2 minutes)
1. Go to https://vercel.com and sign up / log in (the free "Hobby" plan is fine).
2. On the dashboard, click **Add New… → Project**.
3. Choose the **deploy without Git / upload** option and drag this whole folder (the one containing `index.html` and `assets/`) into the uploader.
4. Leave every setting as default — there's no framework and no build command. Click **Deploy**.
5. After a few seconds you get a live link like `https://vijay-portfolio.vercel.app`. That link is public — anyone can open it.

### Route B — connect GitHub (auto-deploys on every push)
1. Create a new GitHub repo, e.g. `portfolio`, and upload these files (`index.html` + the `assets/` folder) to it. You can do this straight from github.com with **Add file → Upload files**.
2. In Vercel, click **Add New… → Project**, then **Import** that repo.
3. Framework preset: **Other**. Build command: leave blank. Output directory: leave blank (root). Click **Deploy**.
4. You get a public `*.vercel.app` link. Any time you edit `index.html` and push to GitHub, Vercel redeploys automatically.

### Custom domain (optional)
In your Vercel project: **Settings → Domains → Add**. You can attach a domain you own (e.g. `vijay.dev`) or use the free `*.vercel.app` subdomain. You can also rename the project in **Settings → General** to control the subdomain (e.g. `vijay-s.vercel.app`).

## Before you publish — quick edits
Open `index.html` and update these placeholders (search for them):

- **Email** — `vijay@example.com` appears twice (hero heading link + contact buttons). Replace with your real address.
- **LinkedIn** — the contact button still points to `#` (marked `data-edit="linkedin"`). Put your LinkedIn URL there.
- **Résumé** — the "Résumé (PDF)" button points to `#` (`data-edit="resume"`). Drop a `resume.pdf` into this folder and change the link to `resume.pdf`, or link to a hosted copy.
- GitHub links are already wired to `github.com/vijaysoundararajan281`.
- The part-time "Front of House / Madurai Restaurant" entry is in the Experience section — remove it if you'd prefer a purely technical CV.

That's it. No other maintenance needed.
