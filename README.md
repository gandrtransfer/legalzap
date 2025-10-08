# LegalZap.pro — For Sale (Dan & Afternic)

This is a tiny GitHub Pages site to sell **LegalZap.pro**, with buttons for **Dan.com** and **Afternic (GoDaddy)**.

## Deploy on GitHub Pages
1. Create a new GitHub repo (e.g., `legalzap-pro-site`).
2. Upload these files.
3. Settings → Pages → Source: `main` branch.
4. Registrar DNS: add a **CNAME** record `@` → `<your-username>.github.io`.
5. (Optional) Keep the `CNAME` file as `legalzap.pro` for the custom domain.

## Update links
In `index.html`:
```js
const DAN_URL = "https://dan.com/buy-domain/legalzap.pro";
const AFTERNIC_URL = "https://www.afternic.com/domain/legalzap.pro";
const CONTACT_EMAIL = "offer@legalzap.pro";
```
Replace with your actual listing URLs and desired contact email.

## Pricing
Default BIN shows **$2,495**. Edit the text in the Buy section to change.
