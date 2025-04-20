# TimeIsMoney

## Concept

TimeIsMoney visualizes your day as a bank account where each second equals one euro. The dashboard shows a live countdown of the seconds remaining in the day as your balance. When you click **Pause**, you "save" time—use it for productive tasks—and the counter stops, tracking your saved seconds (euros). Upon **Resume**, the session logs how much you saved versus spent, giving you insight into how much of your day was wasted versus used effectively.


A live, interactive “bank dashboard” that counts down the remaining seconds in the day as euros, while visually displaying how much you’ve “saved” by pausing the countdown. Each visitor gets their own instance with persistent data stored in their browser’s Local Storage.

---

## 🚀 Features

- **Live countdown** of seconds left in the current day, converted to a euro balance.
- **Pause / Resume** button to simulate “saving”: while paused, the counter stops and tracks saved seconds (euros).
- **Payment History** tab logs each pause session with date, time, remaining balance, saved amount, and total spent.
- **Persistent data** in Local Storage: your bank name, daily saves, and history survive page reloads and browser restarts.
- **Responsive design**: fills entire viewport (minus navigation and header) and scales the balance text dynamically to fit.
- **Editable Bank Name**: click the ✏️ icon to change the bank name, which updates the footer too.
- **Full‑screen toggle** and **Clear History** functionality.

---

## 📦 Installation

All assets are static. To run locally:

1. Clone the repo:
   ```bash
   git clone https://github.com/predator6968/TimeIsMoney.git
   cd TimeIsMoney
   ```
2. Ensure your main file is named `index.html` (Pages requires lowercase).
3. Open `index.html` in your browser.

---

## 📖 Usage

- **Pause**: Click the button to stop the countdown—your savings accrue in real time.
- **Resume**: Click again to end the session; it logs the date/time, remaining balance, saved amount, and spent amount to the **Payments** tab.
- **Clear History**: Remove all logged sessions for a fresh start.
- **Edit Bank Name**: Click the ✏️ icon, type a new name, then click outside to save.
- **Full‑Screen**: Toggle full‑screen mode for an immersive view.

---

## 🌐 Deployment on GitHub Pages

1. Rename `Index.html` → `index.html` (lowercase).
2. Push to your `main` branch on GitHub:
   ```bash
   git add .
   git commit -m "Add dashboard files"
   git push -u origin main
   ```
3. In your repository’s **Settings → Pages**, set:
   - **Branch:** `main`
   - **Folder:** `/ (root)`
   - Clear **Custom domain** if present.
4. Your site will be live at:
   ```
   https://<your-username>.github.io/TimeIsMoney/
   ```

---

## 🤝 Contributing

1. Fork this repository.
2. Create a new branch: `git checkout -b feature/YourFeature`.
3. Commit your changes: `git commit -m "Add some feature"`.
4. Push to the branch: `git push origin feature/YourFeature`.
5. Open a Pull Request.

Please ensure code style consistency and test responsiveness.

---

## 📝 License

This project is released under the [MIT License](LICENSE). Feel free to use and modify!

