# 🌙 Luna Books Web

> A responsive bookstore website built for the **Repositories and Branches with Git and GitHub** laboratory.

## 👥 Team
| Member | Role |
|--------|------|
| Raymundo Herrera | Catalog & Contact pages |
| Omar Rodríguez | Login page |

> **Note:** These assignments do not claim independent authorship or completed peer review. Each teammate must perform and document their own review from their own GitHub account.

## 🛠️ Technologies

- **HTML5** — Semantic markup with accessibility features (`aria-label`, `aria-current`, skip links)
- **CSS3** — Custom properties, flexbox layout, responsive design
- **JavaScript (ES6)** — Client-side form validation, DOM manipulation
- No frameworks or external dependencies required.

## 📁 Project Structure

```
luna-books-web/
├── index.html              # Home page
├── pages/
│   ├── catalog.html        # Book catalog with genre filters
│   ├── contact.html        # Contact form with validation
│   └── login.html          # Login form with client-side validation
├── css/
│   ├── styles.css          # Main stylesheet and design system
│   ├── contact.css         # Contact page specific styles
│   └── login.css           # Login page specific styles
├── js/
│   ├── main.js             # Shared scripts
│   ├── contact.js          # Contact form validation
│   └── login.js            # Login form validation
├── assets/                 # Images and static assets
├── CONTRIBUTING.md         # Team workflow and PR guidelines
└── README.md               # This file
```

## 🚀 Run Locally

Use any static web server. No npm installation or API key is required.

**With Python 3:**
```sh
python3 -m http.server 8080
```

**With VS Code Live Server:**
Right-click `index.html` → *Open with Live Server*

Then open [http://localhost:8080](http://localhost:8080) in your browser.

## 📄 Pages

| Page | File | Features |
|------|------|----------|
| Home | `index.html` | Hero section, navigation, footer |
| Catalog | `pages/catalog.html` | Book listing with genre filters |
| Login | `pages/login.html` | Client-side form validation |
| Contact | `pages/contact.html` | Contact form with validation |

> ⚠️ The login and contact forms are classroom demonstrations. They do not authenticate users, store passwords, or send messages. The address, prices, opening hours, and phone number are fictional sample content.

## 🌿 Branching Workflow

```
main ─────────────────────────────────── stable release
 │                                        ↑
 ├── hotfix/footer-phone ────────────────┘ (also merged into develop)
 │
 └── develop ────────────────────────────── integration branch
      ├── feature/catalog-page              ↑
      ├── feature/login-form ──────────────┘
      └── feature/contact-page
```

- **`main`** — Contains the stable release
- **`develop`** — Integrates features through pull requests
- **`feature/*`** — Feature branches created from `develop`
- **`hotfix/*`** — Urgent fixes created from `main`, merged into both `main` and `develop`
- **Release** — `develop` → `main`, then tag `v1.0.0`

> All feature and hotfix branches are preserved on GitHub for grading purposes.

## ✅ Verification Checklist

- [ ] All page links work correctly
- [ ] Menu filters function on the catalog page
- [ ] Forms validate invalid and valid inputs
- [ ] Keyboard navigation is accessible
- [ ] Mobile/responsive layout renders properly
- [ ] Footer phone displays `(614) 555-0199` on both `main` and `develop`
