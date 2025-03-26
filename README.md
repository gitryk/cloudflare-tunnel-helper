# Cloudflare Tunnel Credential Generator

This is a **client-side web tool** for generating `credentials.json` for Cloudflare Tunnels via the Cloudflare API.

👉 [Try it online via GitHub Pages](https://your-username.github.io/your-repo-name/) *(Replace with your actual URL)*

---

## 🚀 Features

- 🔐 Secure: All API requests are made directly from your browser to Cloudflare
- 📦 Generates `credentials.json` using your Account ID, API Token, and Tunnel Name
- 💾 One-click download of the generated credentials
- 🧭 Fully static – no server required

---

## 🛠 Usage

1. Clone this repository or [Download the HTML file](cloudflare-credentials-generator.html)
2. Open `index.html` in your browser using a local web server:
   ```bash
   npx serve .
   # or
   python3 -m http.server
   ```
3. Enter:
   - Your **Account ID**
   - Your **Scoped API Token** (with Tunnel permissions)
   - The **Tunnel Name** you want to create
4. Click **"Create Tunnel & Generate credentials.json"**
5. Click **"Download"** to save your credentials

---

## ⚠️ Security Notice

- This page **does not store or transmit** your API token to any server except **Cloudflare**
- For safety, use a **scoped API token** with minimal required permissions

---

## 📜 License

MIT License © 2025
