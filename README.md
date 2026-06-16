# Translator Old English — Website application

A comprehensive, beautifully styled web portal hosting interactive linguistic translation tools, career/student guidance resources, and historical English guides designed to bridge the gap between modern technology and the medieval origins of the English language.

Live Production URL: [https://partnerhoursguide.com](https://partnerhoursguide.com)

## 🌟 Key Interactive Features

- **Old English Translator:** AI-powered converter that translates modern English text into Anglo-Saxon prose, including runic (Futhorc) transcription and phonological pronunciation.
- **Shakespearean English Translator:** Converts modern text into the Early Modern English of William Shakespeare's plays and sonnets.
- **Old English Names Directory:** A fully filterable database of authentic Anglo-Saxon names with etymological details, gender filters, and text-to-speech pronunciation.
- **Random Name Maker:** Creative generator tool to construct historic names.

## 🛠️ Technology Stack & Architecture

- **Frontend:** Pure HTML5, CSS3 variables, and vanilla ES6+ Javascript for interactive UI elements and widgets.
- **Backend:** Node.js static files server (`server.js`) using Express/HTTP modules.
- **WordPress Integration Ready:** Includes a `wordpress-ready/` directory containing all pages wrapped and filtered with PHP scripts to disable duplicate Rank Math metadata, allowing direct insertion into live WordPress page templates.

## 🚀 Running Locally

1. Ensure you have **Node.js** installed on your system.
2. Clone this repository to your local machine:
   ```bash
   git clone <your-repository-url>
   cd <repository-folder>
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Run the local development server:
   ```bash
   npm start
   ```
5. Open your browser and navigate to `http://localhost:3000`.

## 📁 Repository Directory Structure

- `home.html` — The main directory landing page.
- `index.html` — The main dashboard containing the translation widget.
- `translator.html` — Translator tool specific view.
- `shakespeare-converter.html` — Shakespeare converter specific view.
- `old-english-names.html` — Names database page.
- `about.html`, `contact.html`, `privacy-policy.html` — Core system pages.
- `wordpress-ready/` — Wrappers and hooks to run seamlessly on WordPress.
- `Ancient-parchment-of-Beowulf.webp`, `Medieval-battle-scene.webp` — Premium design media assets.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
