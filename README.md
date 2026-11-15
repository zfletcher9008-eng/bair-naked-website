# Bair Naked Cosmetics website

Static one-page site, ready for Vercel. No build step.

## Deploy
**Option A, GitHub (recommended):** push this folder to a GitHub repo, then on vercel.com choose
Add New > Project, import the repo, Framework Preset "Other", and click Deploy.

**Option B, command line:** in this folder run `npx vercel` and follow the prompts, then `npx vercel --prod`.

## Edit
- Everything is in `index.html`. Product details live in the `PRODUCTS` list in the script near the bottom.
- Add your store links at `const SHOP_URL = ''` and `const TIKTOK_URL = ''`.
- Logos and icons are in `/assets`.
