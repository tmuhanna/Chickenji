# 🍗 Chickenji — The Taste of Happiness

Official website for **Chickenji**, a fast-food restaurant specializing in broasted chicken and chicken sandwiches. This project features a modern, responsive, and dynamic web design utilizing a **Cyber-Street Bento Grid** theme, optimized for both English and Arabic audiences.

---

## 🌐 Live Site
Hosted via GitHub Pages: `https://<your-username>.github.io/chickenji`

---

## ✨ Key Features

- **Asymmetric Bento Layout**: Modern grid organization featuring:
  - Floating navigation pill.
  - Full-bleed hero background (`indoor.jpg`) with dark overlay and glassmorphism.
  - Interactive menu filter tabs (Broasted, Sandwiches, Western Meals, Sides).
  - Social media and location contact bento stack.
- **Bilingual Interface**: Seamless translation toggle (**English / Arabic**) with RTL (Right-to-Left) direction support, Cairo Arabic font integration, and LTR-corrected phone numbers.
- **Dynamic Admin Editor**:
  - Hidden Editor Mode triggered via the gear icon (`⚙️`) at the bottom right.
  - Allows adding, modifying, and deleting menu items.
  - Persistent storage of modifications in browser `localStorage`.
- **Secure Access**:
  - Passcode authorization with client-side **SHA-256 encryption** using the native Web Crypto API.
  - Secure Change Passcode overlay modal to reset the password.
  - Default access passcode is `1234` (stored as SHA-256 hash `03ac674216f3e15c761ee1a5e255f067953623c8b388b4459e13f978d7c846f4`).

---

## 📁 Repository Structure
```
chickenji/
├── index.html        # Main HTML file (Layout, bilingual logic, state management)
├── index.css         # Styling system (Outfit & DM Sans fonts, color system, bento structures)
├── logo.png          # Transparent brand logo (dark theme inverted)
├── indoor.jpg        # Store interior showcase image
├── .gitignore        # Standard Git exclusions (ignores backups, scratch tools, and logs)
└── README.md         # Repository documentation
```

---

## 🚀 How to Deploy on GitHub Pages

This is a static client-side web application, meaning it can be hosted for free on GitHub Pages in under a minute:

1. Create a new repository on GitHub (e.g. `chickenji`).
2. Push the files in this directory to your new repository.
3. On GitHub, navigate to **Settings → Pages**.
4. Set **Source** to "Deploy from a branch".
5. Set **Branch** to `main` (or `master`) and folder to `/ (root)`.
6. Click **Save**.
7. Your site will be live at `https://<your-username>.github.io/chickenji/` in about 60 seconds!

---

## 📞 Contact Information
- **Phone / WhatsApp**: [+963 984 444 151](tel:+963984444151) (LTR formatted)
- **Instagram**: [@chickenji.official](https://www.instagram.com/chickenji.official)
- **Facebook**: [CHICKENJI](https://www.facebook.com/share/1HbYpFoh54/)
- **Location**: Dariya — Al-Mudhamiya Road (50m before the Cultural Center)
