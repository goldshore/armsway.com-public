# armsway.com - Public Website (B2B Medical Sleeve)

The public B2B website for ArmsWay™ — a patented medical product designed to block 99.9% of contaminants on reusable blood pressure cuffs.

## ✅ Site Features
- Responsive HTML/CSS landing page
- Clean B2B language for hospitals/clinics
- Logo and color scheme applied
- Inquiry/contact form placeholder (to connect with Flask backend)
- Favicon and brand asset integration
- Secure inquiry form connected to backend Flask API
- Downloadable product PDFs and spec sheets
- Legal/IP policy footer links
- Responsive, clean medical layout

## 🧠 Instructions
To serve this publicly:
1. Push all contents to `goldshore/armsway.com`
2. Verify custom domain `armsway.com` via GitHub Pages
3. Enable HTTPS via Cloudflare

Fields:
- name, email, company, message  
Optional integration via:
- 📬 Mailgun
- 💬 Discord webhook
- 📊 CRM backend (Flask app)

—

## 🚀 Deployment

- Hosted via **GitHub Pages**
- Branch: `main`
- Static only, no build step (use `.nojekyll`)
- Recommend enabling GitHub Actions later for automation

—

## 📌 DNS Configuration (Cloudflare)

Set the following `A` or `CNAME` records:

| Type | Name         | Value                              |
|------|--------------|-------------------------------------|
| A    | @            | `185.199.108.153` *(GitHub Pages)* |
| CNAME| www          | `armsway.com`                      |
| TXT  | _github-pages| `https://armsway.com`              |

—

## 📈 Meta & SEO (Coming Soon)

- Meta tags: description, keywords, OpenGraph  
- Twitter Card preview
- Schema.org markup (Product + MedicalDevice)

—

## 📌 Legal

- Includes: USPTO patent badge and legal notice
- Email opt-in fields must comply with CAN-SPAM
- Privacy and Terms pages required for any ad network (Google Ads)

—

## ✅ TODO

- [x] Static homepage
- [x] Assets, logo, PDF downloads
- [x] Inquiry endpoint
- [ ] Privacy/legal pages
- [ ] SEO + analytics
- [ ] Email blast opt-in
- [ ] Hospital outreach search page

—

## 📜 License

MIT License — See `LICENSE`  
© 2025 ArmsWay™  
[info@armsway.com](mailto:info@armsway.com)  
[7072 Hope Hill Rd, Brooksville, FL 34601](https://maps.google.com/?q=7072+Hope+Hill+Rd,+Brooksville,+FL)

🧪 Local Dev Setup
Use Live Server or any static server to preview:

> Backend is managed at [armsway.com-private](https://github.com/goldshore/armsway.com-private)

### Future Plans:
- Integrate contact form into backend (secure Flask API)
- Auto-pull USPTO data for patents
- Embed testimonials or case study PDF
- Add search tool for medical buyers
- Compliance and Legal Policy section

---
**Maintained by [Gold Shore Labs](https://goldshore.foundation)**