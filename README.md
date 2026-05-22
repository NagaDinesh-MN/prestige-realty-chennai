# 🏠 Prestige Realty Chennai — Official Website

A premium real estate agency website for **Prestige Realty**, Chennai's leading property consultancy. Built with pure HTML, CSS, and JavaScript. Form submissions connect directly to **Airtable** via the Claude MCP integration.

---

## 🚀 Live Features

| Feature | Status |
|---|---|
| Full responsive website | ✅ |
| Page loader (2-second animated entry) | ✅ |
| Nav transition loader | ✅ |
| Property listings grid | ✅ |
| Neighbourhood / location grid | ✅ |
| Client testimonials | ✅ |
| Contact form with validation | ✅ |
| **Airtable MCP form integration** | ✅ |
| RERA badge & compliance section | ✅ |
| Mobile responsive layout | ✅ |

---

## 📁 Project Structure

```
prestige-realty/
├── src/
│   └── index.html          # Main website (all-in-one)
├── docs/
│   └── airtable-setup.md   # Airtable configuration guide
├── README.md
└── .gitignore
```

---

## 🗄 Airtable Setup

Create a base called **"Prestige Realty CRM"** with a table named **"Leads"** and these fields:

| Field Name | Field Type |
|---|---|
| Name | Single line text |
| Phone | Phone number |
| Email | Email |
| Enquiry Type | Single select |
| Preferred Location | Single select |
| Message | Long text |
| Source | Single line text |
| Status | Single select (New / Contacted / Qualified / Closed) |
| Submitted At | Single line text |

> The form submission automatically calls the Anthropic API with Airtable MCP to create a new record on every enquiry.

---

## 🛠 Tech Stack

- **HTML5 / CSS3 / Vanilla JS** — zero dependencies, no build step
- **Google Fonts** — Playfair Display + DM Sans
- **Anthropic Claude API** — powers Airtable form submission via MCP
- **Airtable MCP** — `https://mcp.airtable.com/mcp`

---

## 📦 Deployment

### Netlify (recommended)
1. Drag and drop the `src/` folder onto [Netlify Drop](https://app.netlify.com/drop)
2. Done — live in seconds

### Vercel
```bash
npx vercel --prod
```

### GitHub Pages
1. Push this repo to GitHub
2. Go to **Settings → Pages → Source → `/src` folder**
3. Save — live at `https://yourusername.github.io/prestige-realty`

---

## 📞 Agency Contact

- **Address:** 12, Lattice Bridge Road, Adyar, Chennai – 600 020
- **Phone:** +91 98400 12345
- **Email:** info@prestigerealty.in
- **RERA:** TN/01/Building/0026/2024

---
