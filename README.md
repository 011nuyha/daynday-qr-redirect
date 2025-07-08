# qr-redirect-daynday

**Redirect landing page for QR codes by Day n Day Cafe, Ian Building branch**

This project provides a simple redirect landing page for QR codes printed and distributed by the Ian Building branch of Day n Day Cafe.  
It is used to ensure that even if the event website changes in the future, the QR code printed on physical materials remains valid.

## 🔁 Redirection

All traffic to this page is redirected to the actual event page via Netlify’s static `_redirects` file.  
To change the destination URL, edit the `_redirects` file and re-deploy.

## 🛠 Usage

1. Edit `_redirects` and `index.html` with your actual event page URL.
2. Deploy this repository to [Netlify](https://netlify.com).
3. Use the resulting Netlify URL (e.g., `https://cafeevent2025.netlify.app`) to generate your QR code.

---
