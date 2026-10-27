# Perilux (perilux.pro)

Static site for the perilux.pro project. Pure HTML + CSS + JS, no build step —
deploy-ready for Vercel.

## Deploy
```bash
vercel          # preview deploy
vercel --prod   # production
```
Then add the custom domain (`perilux.pro`) in the Vercel dashboard
(Settings → Domains). DNS is managed at Hostinger: apex A → `76.76.21.21`,
www → `cname.vercel-dns.com`.

## TODO
- [ ] Wire the contact form to a backend (Formspree / Vercel Function)
- [ ] Fill in `data-youtube-id` attributes on embed cards
- [ ] Replace `#` placeholders in footer social links with real profile URLs
- [ ] Replace TODO copy blocks with real project content
