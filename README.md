# 🎓 Academia Access

**Free access to quality educational resources for every student.**

Academia Access is a free study-material library: question papers, sample papers, Olympiad papers and holiday homework for students across schools and colleges. It is an initiative of the **Oberoi Group of Companies**, founded by **Aarush Oberoi**.

🔗 **Live site:** https://academiaaccess.aarushoberoi.workers.dev

---

## 🎯 Mission

To make academic excellence accessible to every student by offering free, high-quality study materials.

## ✨ Features

- **Free papers** with no sign-up
- **Filter-based browsing** by category, exam, grade/year and paper type
- **Four categories:** School, College, Olympiads and College Admissions
- **Wide grade coverage:** School Grades 5–12 and College Years 1–4
- **Three paper types:** Question Paper, Sample Paper and Holiday Homework
- **Lightweight static site** with no backend or database

## 🏆 Olympiads Covered

- ACG (Āryabhaṭa Ganit Challenge)
- SOF IMO (International Mathematics Olympiad)
- CMO (CREST Mathematics Olympiad)
- iOS (International Olympiad of Science)
- NSTSE (National Level Science Talent Search Examination)
- UIMO (Unified International Mathematics Olympiad)
- CEO (CREST English Olympiad)
- SOF IEO (International English Olympiad)

## 🗂️ Project Structure

```
Academia-Access/
├── Academia Access.html   # The website (Home, About, Papers)
├── main_logo.jpg          # Academia Access logo
├── parent_logo.jpg        # Oberoi Group of Companies logo
├── 1.pdf … 50.pdf         # Papers served by the site
└── README.md
```

## 🚀 Run Locally

Clone the repo and serve the folder with any static server:

```bash
git clone https://github.com/AarushOberoi/Academia-Access.git
cd Academia-Access

# Option 1: Python
python -m http.server 8000

# Option 2: Node
npx serve .
```

Then open `http://localhost:8000/Academia%20Access.html`.

## ☁️ Deployment

Deployed as static assets on **Cloudflare Workers**:

```bash
npx wrangler deploy
```

## ➕ Adding Papers

1. Add the new PDF to the repository root, using the next number (e.g. `51.pdf`).
2. Register it in `Academia Access.html` with its category, exam, grade/year and paper type so it shows up in the filters.
3. Commit and redeploy.

## 🤝 Contributing

Have a paper to share or a fix to suggest?

1. Fork the repository
2. Create a branch: `git checkout -b add/paper-name`
3. Commit your changes and open a pull request

Please only contribute materials you have the right to share.

## ⚠️ Disclaimer

Academia Access is an independent educational initiative. Papers are shared for study and practice, and all rights to original exam content remain with the respective organisers and publishers. If you are a rights holder and want something removed, please open an issue.

## 👤 Author

**Aarush Oberoi**, Founder, Academia Access
Part of the **Oberoi Group of Companies**

© 2025 Academia Access
