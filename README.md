# Stratus Co - GitHub Pages Setup

This folder contains the files for the Stratus Co landing page and legal documents.

## Files

- `index.html` - Landing page
- `privacy.html` - Privacy Policy (covers all platform integrations)
- `terms.html` - Terms of Service

## Setup Instructions

### Option 1: Create a new repository (Recommended)

1. **Create a new repo on GitHub:**
   - Go to https://github.com/new
   - Repository name: `stratusco` (or `stratus-co`)
   - Make it **Public**
   - Don't initialize with README

2. **Push these files:**
   ```bash
   cd "D:\Projects\Side Projects\Passive Income\docs\github-pages"
   git init
   git add .
   git commit -m "Initial commit - Stratus Co landing page"
   git branch -M main
   git remote add origin https://github.com/Mikielomas/stratusco.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to repo Settings → Pages
   - Source: "Deploy from a branch"
   - Branch: `main` / `/ (root)`
   - Click Save

4. **Your URL will be:**
   ```
   https://mikielomas.github.io/stratusco/
   ```

### Option 2: Use username.github.io (Primary domain)

If you want `https://mikielomas.github.io/` as your main site:

1. Create repo named exactly `Mikielomas.github.io`
2. Push these files to that repo
3. It will automatically deploy to `https://mikielomas.github.io/`

## URLs for Platform Applications

Once deployed, use these URLs:

| Platform | URL to Provide |
|----------|----------------|
| Website/Homepage | `https://mikielomas.github.io/stratusco/` |
| Privacy Policy | `https://mikielomas.github.io/stratusco/privacy.html` |
| Terms of Service | `https://mikielomas.github.io/stratusco/terms.html` |

## Custom Domain (Optional Later)

If you purchase `stratusco.com`:

1. Add a `CNAME` file with content: `stratusco.com`
2. Configure DNS at your registrar:
   - A record: `185.199.108.153` (and .109, .110, .111)
   - Or CNAME: `mikielomas.github.io`
3. Enable HTTPS in GitHub Pages settings

## Updating Content

If you change the brand name later (e.g., to Nimbus Co), just:
1. Find and replace "Stratus Co" with new name
2. Find and replace "stratusco" with new handle
3. Update email addresses
4. Commit and push

## Notes

- The privacy policy covers all platforms: Pinterest, Twitter, Meta, YouTube, LinkedIn, TikTok, Threads, Stripe, Amazon
- FTC affiliate disclosure is mentioned
- Australian law jurisdiction (adjust if needed)
- References Arcus Cloud Computing Pty Ltd as parent entity
