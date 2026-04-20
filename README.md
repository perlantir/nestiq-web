# nestiq-web

Marketing + legal landing site for the NestIQ iOS app.

Live at: `https://nestiq.mortgage`

## Pages

- `/` — landing + calculator overview
- `/privacy` — privacy policy
- `/terms` — terms of service
- `/support` — support contact

## Tech

Plain static HTML. No framework, no build step. Deployed via Vercel with `cleanUrls: true` so `/privacy` resolves to `privacy.html` without the extension.

## Deploy

Pushing to `main` auto-deploys via Vercel's GitHub integration.

Initial Vercel setup:
1. Import repo at vercel.com → select this repo → Deploy
2. Settings → Domains → add `nestiq.mortgage` and `www.nestiq.mortgage`
3. Add the DNS records Vercel provides to your domain registrar
4. Wait 5–15 min for DNS + SSL provisioning

## Editing

Edit the HTML files directly. No transpilation, no bundler. Changes commit → push → live in ~30 seconds.

## Contact

Uber Kiwi LLC · support@uberkiwi.com
