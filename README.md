# Luna Books Web

A responsive bookstore website for the Repositories and Branches with Git and GitHub laboratory.

## Team
- Raymundo Herrera
- Omar Rodríguez

## Run locally
Use any static web server. With Python 3:

```sh
python3 -m http.server 8080
```

Open http://localhost:8080. No npm installation or API key is required.

## Pages
- Home: `index.html`
- Catalog: `pages/catalog.html`, with book genre filters
- Login: `pages/login.html`, with client-side validation
- Contact: `pages/contact.html`, with form validation

The login and contact forms are classroom demonstrations. They do not authenticate users, store passwords, or send messages. The address, prices, opening hours and phone are fictional sample content from the classroom scenario.

## Branching workflow
`main` contains the stable release. `develop` integrates features through pull requests. `feature/catalog-page`, `feature/login-form`, and `feature/contact-page` start from develop. `hotfix/footer-phone` starts from main and must be integrated into both main and develop. Release: develop → main, then tag v1.0.0.

Keep all feature and hotfix branches on GitHub until the teacher checks the evidence. This delivery rule supersedes the lab's instruction to delete merged branches.

## Team participation
Suggested task distribution: Raymundo handles catalog and contact; Omar handles login. These assignments do not claim independent authorship or completed peer review. Each teammate must perform and document their own review from their own GitHub account.

## Verification
Check all page links, menu filters, invalid and valid form inputs, keyboard navigation, mobile layout, and the corrected footer phone `(614) 555-0199` on main and develop.
