DEPLOYMENT INSTRUCTIONS — GitHub Pages (FREE)
--------------------------------------------
1. Create a GitHub account if you don't have one: https://github.com/join
2. Create a new repository:
   - Click "New" (top-left) -> Repository name: bganorge-site (or your choice)
   - Public repository (free) -> Initialize WITHOUT README (optional)
3. Upload site files:
   - On the repo page click "Add file" -> "Upload files"
   - Upload these files: index_pl.html, index_en.html, index_no.html, styles.css, logo.svg, contact.json
   - Commit the changes (bottom of page)
4. Enable GitHub Pages:
   - Go to Settings -> Pages (or "Pages" in sidebar)
   - Under "Source" choose "Deploy from a branch" (or "main" branch) and folder "/" (root)
   - Click "Save". GitHub will provide a URL like https://<your-username>.github.io/<repo-name>/
   - Wait a few minutes and open the provided URL.
5. Update contact details later:
   - Edit contact.json in the repository (click the file -> pencil icon -> update -> Commit changes)
   - Or edit any HTML file directly to change displayed contact info.
6. Optional: Use a custom domain
   - Purchase a domain (recommended) and follow GitHub Pages docs to configure DNS and add CNAME.
   - Or use a free subdomain provider and point it to GitHub Pages (requires DNS settings).

EDITING CONTACT INFO LOCALLY
----------------------------
- File: contact.json (included)
- Fields: company_name, phone, email, working_hours, address
- If you change contact.json locally, and host static site on GitHub Pages, remember to update HTML files if they don't load contact.json dynamically.

ALTERNATIVE FREE HOSTING OPTIONS (if not using GitHub Pages)
-----------------------------------------------------------
- Netlify: easy drag-and-drop deploy for static sites (free tier), supports custom domains.
- Vercel: also free for static sites, supports custom domains.
- InfinityFree: free hosting with FTP, good for beginners but limited.

COPYRIGHT AND LICENSE
---------------------
- Files provided: index_pl.html, index_en.html, index_no.html, styles.css, logo.svg, contact.json
- You own and may modify these files. No license restrictions from me.

TROUBLESHOOTING
---------------
- If the site shows a 404, ensure files are in the repository root and GitHub Pages source is the main branch / root.
- If images or CSS don't load, check filenames (case-sensitive) and paths in HTML (styles.css and logo.svg must be in same folder).

EMAIL TEMPLATE (to send files to yourself or a colleague)
--------------------------------------------------------
Subject: B G A Norge — Strona i pliki (gotowe do wdrożenia)

Cześć,

W załączeniu przesyłam pliki strony dla B G A Norge (PL/EN/NO) oraz logo i instrukcję wdrożenia na GitHub Pages. Pliki:
- index_pl.html
- index_en.html
- index_no.html
- styles.css
- logo.svg
- contact.json
- README (deployment instructions)

Kroki do wdrożenia: użyj GitHub Pages lub Netlify (instrukcja w README).

Pozdrawiam,
[Twoje imię]
