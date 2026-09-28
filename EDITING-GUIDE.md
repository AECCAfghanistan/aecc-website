# AECC Website — Editable Static Version

## Website address
The site is prepared for:
**https://aecc.engineering.in**

This package is a static, hosting-ready website. No database, WordPress installation, paid plugin, or external form service is required.

## Main files
- `index.html` — all website content and editable sections
- `assets/css/styles.css` — layout, colors, typography and responsive design
- `assets/js/main.js` — mobile menu, image gallery/lightbox and current-year footer
- `assets/images/` — AECC logo and project photographs extracted from the supplied company profile

## Staff photographs
The Team section intentionally contains editable placeholders.

To add a staff photo:
1. Put the photograph in `assets/images/`, for example `staff-01.jpg`.
2. Open `index.html`.
3. Replace a `<div class="staff-placeholder">...</div>` with:
   `<img src="assets/images/staff-01.jpg" alt="Staff Member Name">`
4. Change the staff member name and position directly below the image.

## Updating company information
The confirmed public information used in this version is:
- Established: 2008
- Commercial Registration No.: D-02-8
- Kabul Office: House ( ), Street #4, Shaheed Square, Kabul
- Nangarhar Office: Faiz Ahmad Haidari Plaza, Near Dharamsala Chowk, Jalalabad
- Phone: 0788333030 / 0707320082
- Email: aecc_afg06@yahoo.com
- Website: https://aecc.engineering.in
- Social media icons: intentionally omitted

## Project photographs
The gallery uses real project photographs contained in the supplied AECC PDF. The equipment section also uses field equipment photographs visible in the supplied project imagery.

## Hosting
Upload the entire `AECC_Website` folder to your hosting public web directory. The entry point is `index.html`.

For `https://aecc.engineering.in`, configure the domain/subdomain document root to this folder.

## Future editing
Because this is plain HTML/CSS/JS, you can edit it with VS Code, Notepad++, Dreamweaver, or another code editor. It can later be migrated to WordPress or another CMS if a browser-based content editor is required.
