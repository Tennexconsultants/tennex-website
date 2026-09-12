# Tennex Website V1.2

A lightweight, responsive one-page website for **Tennex Consultants**.

## Files

- `index.html` — website content
- `styles.css` — layout and visual styling
- `CNAME` — custom domain for GitHub Pages
- `README.md` — these instructions

No external libraries, images, fonts, analytics, or tracking scripts are required.

## Before publishing

Search `index.html` for these placeholders and confirm them:

1. `MJ [Surname]` — replace with your full public name.
2. `mj@tennexconsultants.com` — confirm your Zoho mailbox is active before launch.
3. `Founder video / Loom` — this is currently a visual placeholder. We can replace it with the real Loom embed later.

## Publish on GitHub Pages

1. Create a free GitHub account if you do not already have one.
2. Create a **new public repository**. A simple name such as `tennex-website` is fine.
3. Upload all files from this folder to the repository root:
   - `index.html`
   - `styles.css`
   - `CNAME`
   - `README.md`
4. Open the repository **Settings**.
5. Open **Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select the `main` branch and `/ (root)` folder, then save.
8. GitHub will publish the site and show you its temporary GitHub Pages URL.

## Connect tennexconsultants.com

The included `CNAME` file already contains:

`tennexconsultants.com`

In GitHub Pages settings, set the custom domain to `tennexconsultants.com`.

GitHub will show the DNS records required for the domain. Add those records in the DNS manager at your domain registrar. Once DNS has propagated and GitHub confirms the domain, enable **Enforce HTTPS**.

Important: your Zoho email DNS records (MX, SPF, DKIM, DMARC) and your website DNS records can coexist. Do not delete your Zoho mail records when adding the GitHub website records.

## Preview locally

Keep `index.html` and `styles.css` in the same folder and double-click `index.html`.

## Design system

- Deep navy: `#111D2B`
- Soft grey: `#F4F6F8`
- Main text: `#111827`
- Muted text: `#66727E`
- Muted gold accent: `#C89B4B`
- White: `#FFFFFF`

The site intentionally avoids unsupported claims, testimonials, statistics, fake client logos, and revenue promises.


## V1.1 polish
- Removed unfinished `[Surname]` placeholder from the live founder section.
- Replaced the unfinished Loom placeholder with a finished brand panel until the real video exists.
- Added favicon and social metadata.
- Added a restrained credibility strip beneath the hero.
- Improved mobile header CTA visibility and focus states.
- Tightened a few pieces of copy without adding unsupported claims.

- Updated founder name from MJ to MJ Louw.
