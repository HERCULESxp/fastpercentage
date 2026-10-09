# Percent Sprint ⚡

**Train your mental math. Calculate percentages. Beat the clock.**

Percent Sprint is a lightweight Progressive Web App (PWA) that helps you practice calculating percentages mentally under time pressure. Customize each session, answer multiple-choice questions, and track your accuracy and average response time.

## ✨ Features

- **Custom number length:** Practice with numbers from 1 to 9 digits.
- **Flexible percentages:** Choose a fixed percentage from 10% to 90%, or select random percentages.
- **Adjustable timer:** Set a time limit from 3 to 30 seconds per question.
- **Custom sessions:** Complete 10, 20, 30, or 50 questions, or use endless mode.
- **Multiple-choice questions:** Four answer options are generated for each question.
- **Instant feedback:** See whether your answer was correct, incorrect, or timed out. The next question starts automatically after one second.
- **Session statistics:** Review your correct answers, accuracy, and average response time.
- **Installable PWA:** Add the app to your home screen and launch it in a standalone window.
- **Offline support:** After the app has loaded and its assets have been cached, it can run without an internet connection.
- **Responsive design:** Works on mobile phones, tablets, and desktop browsers.
- **Keyboard support:** Use keys `1`, `2`, `3`, and `4` to select an answer on a physical keyboard.

## 🚀 Getting Started

### Run locally

Because service workers require a secure context, use a local development server instead of opening `index.html` directly as a file.

For example, if Python is installed:

```bash
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in your browser.

### Deploy as a PWA

1. Upload the project files while preserving the folder structure.
2. Deploy the site to a static hosting provider that supports HTTPS, such as GitHub Pages or Netlify.
3. Open the deployed HTTPS URL in a supported browser.
4. On Android, open the browser menu and select **Install app** or **Add to Home screen**. The exact wording may vary by browser.

> **Note:** The PWA installation prompt and offline support require the app to be served from HTTPS (or `localhost` for local development). Offline access is available after the service worker has installed and cached the required files.

## 🛠️ Built With

- HTML
- CSS
- Vanilla JavaScript
- Web App Manifest
- Service Worker API

No framework, build step, account, or backend is required.

## 📁 Project Structure

```text
percent-sprint/
├── index.html
├── manifest.webmanifest
├── service-worker.js
├── icons/
│   ├── icon-192.png
│   ├── icon-512.png
│   └── icon-512-maskable.png
└── README.md
```

## 🎮 How to Play

1. Choose how many digits the numbers should have.
2. Select a percentage from 10% to 90%, or choose random.
3. Set the time limit for each question.
4. Choose the number of questions or endless mode.
5. Calculate the percentage mentally and select one of the four answers before time runs out.
6. Review your results and try to improve your speed and accuracy.

## 📄 License

Unless another license is added to this repository, all rights are reserved by the project owner. Add a `LICENSE` file if you want to grant others explicit permission to use, modify, or distribute the project.
