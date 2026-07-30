# fde-portfolio

Rob's Forward Deployed Engineer portfolio + application packet.

## Contents

- **`index.html`** &mdash; standalone landing page. Open in a browser or deploy anywhere static (Render, Netlify, Vercel, GitHub Pages, Cloudflare Pages).
- **`resume.md`** &mdash; one-page FDE-focused résumé (markdown, ready to render to PDF).
- **`applications/`** &mdash; targeted cover letters per company: Anthropic, OpenAI, Palantir, Varick Agents.
- **`WHERE-TO-APPLY.md`** &mdash; the actual playbook: which companies, in what order, with live job URLs and the case study to lead with.

## Deploy

Fastest path — GitHub Pages:
```
git init
git add .
git commit -m "FDE portfolio"
gh repo create fde-portfolio --public --source=. --push
# then enable Pages in repo settings, source: main / root
```

Alt: drop the folder onto Netlify Drop, or connect to Render as a static site.

## Next steps

1. Fill in placeholders (see `WHERE-TO-APPLY.md` bottom section).
2. Deploy the site.
3. Send the first two applications (Varick + Anthropic).
