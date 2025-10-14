# MoGo Delivery — Legal Pages

**Repository Purpose**  
This public repository hosts the official **Terms of Service** and **Privacy Policy** pages for **MoGo Delivery**.  
These pages support **A2P 10DLC SMS compliance** and provide transparency for users and partners.

---

## 🔗 Live Pages

Once GitHub Pages is enabled, these documents are publicly viewable at:

- **Terms of Service:** https://bizmizzo.github.io/mogo-legal/terms.html  
- **Privacy Policy:** https://bizmizzo.github.io/mogo-legal/privacy.html  

> Both pages are publicly accessible for compliance and verification purposes.

---

## ⚙️ GitHub Pages Setup

This site is hosted via [GitHub Pages](https://pages.github.com/).  
To confirm or reconfigure:

1. Go to **Settings → Pages**  
2. Under **Source**, select **Deploy from a branch**  
3. Choose branch: `main`  
4. Folder: `/ (root)`  
5. Click **Save**

After 30–60 seconds, you’ll see a green banner confirming the site is live.  
If not visible, refresh the page or check:  
**https://bizmizzo.github.io/mogo-legal/**

---

## 🧾 Notes

- These are **static HTML** pages only — no dependencies, builds, or sensitive data.  
- Safe to keep public for Twilio, carriers, and user reference.  
- Optional: You can later map to your custom subdomain (`https://legal.mogodelivery.com/`) by adding a CNAME in your Squarespace DNS:
  - **Type:** CNAME  
  - **Host:** `legal`  
  - **Target:** `bizmizzo.github.io`  
  - **TTL:** 1 hour (default)
- The subdomain option is **not required** for Twilio compliance but provides a cleaner URL.

---

## 🧩 Repository Structure

mogo-legal/
├── terms.html # MoGo Delivery Terms of Service
├── privacy.html # MoGo Delivery Privacy Policy
└── README.md # Repository overview and setup info

less
Copy code

---

## 💬 Contact

For questions regarding these policies or MoGo Delivery services:

**Website:** [https://mogodelivery.com](https://mogodelivery.com)  
**Email:** [support@mogodelivery.com](mailto:support@mogodelivery.com)

---

© 2025 MoGo Delivery. All rights reserved.
