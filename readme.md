How it works:

Both HTML files simply link to styles.css with <link rel="stylesheet" href="styles.css">
The background image is referenced in CSS as url('img/background.png') — no base64, clean and lightweight
To add a new page, copy portfolio.html, change the page title, active menu item, and content — the layout is already done

What each file controls in styles.css:

Tokens (colours, sidebar width) — change once, updates everywhere
Sidebar — shared across all pages
.home-hero — home page only
.article — all interior pages
Footer + mobile responsive — shared

