# TOPSHUGAR — Temporary Email by Topshugar

> Get a temporary email address in one second. No sign-up. No personal details. 100% Free.

**TOPSHUGAR Mail** is a temporary email service created by **TOPSHUGAR** — stage name of Temitope Abraham Olorunmola.

It was built for people in Pakistan and several other countries who are currently unable to create a standard email account due to phone verification blocks and other restrictions. TOPSHUGAR gives them a fast, private address to receive verification codes and complete their daily tasks.

**Status:** Not yet deployed.
**Domain (Planned):** `topshugar.site`

---

## ✨ Features

- **Instant Address Generation** — Receive an address such as `sweet-tiger-482@topshugar.site` in one tap.
- **No Sign-Up Required** — No name, no password, no personal details collected.
- **Live Inbox** — Messages appear automatically. Tap to open and view your code.
- **One-Tap Copy** — Copy your address or your verification code instantly.
- **Auto-Expiry** — Every inbox expires after 10 minutes to protect your privacy.
- **Mobile-Friendly Design** — Optimised for phones, tablets, and desktops.

---

## 🛠 How It Works

### Frontend (Current Build — v1.0.0)
This repository contains the frontend interface only.

1. User opens the site.
2. A random address is generated: `adjective-noun-number@topshugar.site`
3. User copies the address and pastes it where an email is requested.
4. Inbox displays incoming messages.
5. Inbox deletes itself after 10 minutes.

### Backend (Planned — v2.0.0)
The live version will require:

1. **Domain:** `topshugar.site` — to be verified.
2. **MX Records:** Pointing to the mail server, e.g.:
Type: MX | Host: @ | Value: http://mail.topshugar.site | Priority: 10
3. **Mail Server:** Node.js / Python service to receive and store incoming mail.
4. **API:** `GET /api/inbox?address=...` to fetch messages for the frontend.

> **Important:** This build uses demonstration inbox data for preview purposes only. The demo data must be removed before production deployment. Real email reception requires the backend above.

---

## 📁 Project Structure

topshugar-mail/
├── http://index.html          # Main application — TOPSHUGAR Mail interface
├── http://README.md           # Project documentation (this file)
└── LICENSE            # MIT Licence

---

## 🚀 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/topshugar-mail.git
2. Open the project folder:
   cd topshugar-mail
3. Open `index.html` in your browser:
   - Double-click `index.html`, or
   - Use Live Server in VS Code.

No build step is required. No dependencies are required.

---

## 🌍 Deploy to GitHub Pages

1. Push this repository to GitHub.
2. Go to *Settings > Pages*.
3. Under *Source*, select *Deploy from a branch*.
4. Select branch `main` and folder `/ (root)`.
5. Save. Your site will be live at:
   https://your-username.github.io/topshugar-mail/
---

## 🔒 Privacy & Fair Use

TOPSHUGAR Mail is designed for legitimate, everyday use:

- *Receiving Only* — Users can receive emails. Sending is disabled to prevent spam.
- *No Data Selling* — Personal data is never collected or sold.
- *Auto-Delete* — Inboxes and messages are deleted after expiry.
- *Do Not Use For:* Banking, government services, or any account you may need to recover later.

TOPSHUGAR does not own or provide `@gmail.com`, `@yahoo.com`, or `@outlook.com` addresses. All addresses are issued under the TOPSHUGAR domain only: `@topshugar.site`.

---

## 🎤 About TOPSHUGAR

*TOPSHUGAR* is the stage name of *Temitope Abraham Olorunmola*, founder of Aurum Lexicon and creator of TopTalk.

This project is part of the TOPSHUGAR brand — building simple, useful tools for everyday people.

- *Website:* https://aurumlexicon.onrender.com
- *Contact:* lexiconaurum@gmail.com

---

## 🚀 More Projects by TOPSHUGAR
Project	Link
ClearCode System	https://clearcodesystem.onrender.com
TOPSHUGAR PythonAnywhere	https://topshugar.pythonanywhere.com
Ruler Terminal	https://ruler-terminal.onrender.com
Flipperguard	https://topshugar.github.io/Flipperguard
Ghostshot	https://topshugar.github.io/ghostshot/
Interstice	https://topshugar.github.io/interstice/
---

## 📄 Licence

This project is licensed under the MIT Licence. See the `LICENSE` file for details.

---

## 🙏 Acknowledgements

Thank you to everyone in Pakistan and around the world who inspired this tool. Built with care.

© 2026 TOPSHUGAR. All rights reserved.
