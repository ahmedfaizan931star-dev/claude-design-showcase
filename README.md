# Claude Sonnet 5.5 Design Showcase

A free, single-file promo page designed and coded by Claude Sonnet 5.5. No build step, no framework.
Independent demo, not endorsed by or affiliated with Anthropic. Claude and its spark logo are Anthropic trademarks.

## Deploy on Vercel
1. Push this folder to GitHub (suggested repo name: `claude-sonnet-5-5-design-showcase`).
2. Vercel: Add New Project, import the repo, preset "Other", Deploy.
3. Set your real URL everywhere (run once in the repo, change the URL):
   `grep -rl "YOUR-SITE.vercel.app" . | xargs sed -i 's#https://YOUR-SITE.vercel.app#https://your-real-site.vercel.app#g'`
   Also rename nothing else: the IndexNow key file must stay at the site root.
4. Push again.

## Get found
- Google Search Console: add the site, verify (paste the tag into the comment in `index.html`), submit `sitemap.xml`, then URL Inspection and Request indexing.
- Bing Webmaster Tools: same steps. Then open once: `https://api.indexnow.org/indexnow?url=https://your-real-site.vercel.app/&key=29fad1d0fe484cf22950f4c6f1cf91de`
- Share the link from your YouTube, Facebook, GitHub and Fiverr pages: links from other sites help most.
