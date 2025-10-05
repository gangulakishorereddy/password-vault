# 🔐 Password Vault (MVP)

A minimal secure password vault built with **Next.js (TypeScript)** and **MongoDB**.

## 🔗 Live Demo
http://gangulakishorereddy-git-main-gangulakishorereddys-projects.vercel.app
## 🧠 Features
- Password generator (length slider, symbols, numbers, letters)
- Save passwords securely to your vault
- Client-side encryption (Web Crypto API)
- Search, edit, delete vault items
- Copy-to-clipboard with auto-clear

## 🧩 Tech Stack
- Frontend/Backend: Next.js (TypeScript)
- Database: MongoDB Atlas
- Crypto: Web Crypto API (AES-GCM + PBKDF2)

## 🔐 Crypto Note
Client-side encryption is implemented using the **Web Crypto API (PBKDF2 → AES-GCM)**.  
Only ciphertext, iv, and salt are sent to the server — plaintext is never stored.

## 🚀 Run Locally
```bash
npm install
npm run dev
