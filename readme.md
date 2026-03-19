# 🛡️ Junior Dev Terminal: The Ultimate Toddler "Work" Simulator

A high-immersion, Hollywood-style "Hacker Terminal" designed specifically for toddlers who insist on "helping" their parents work. It provides constant visual and auditory feedback for every keypress, keeping little hands busy and away from your actual source code.

## 🚀 Live Demo
**[Insert Your GitHub Pages URL Here]**

---

## ✨ Features for the "Junior Agent"

* **Mechanical Feedback:** Every keypress generates unique synthesized "click" and "beep" sounds using the Web Audio API (no external assets required).
* **Mission Progress:** A persistent progress bar and percentage counter that increases as they "work."
* **The "L" Key Secret:** Holding the **'L'** key triggers a high-stakes 5-second "Nuclear Launch" countdown with red-alert visuals.
* **Security Breach:** Hitting **Backspace** triggers a screen-shake and a "Security Restricted" warning.
* **Biometric Scanner:** An animated fingerprint scanner that makes them feel like they've just bypassed a Level-5 firewall.
* **☕ Coffee Break Mode:** If no keys are pressed for 30 seconds, the system enters a "Standby" mode with a coffee mug icon. They must "log back in" by typing to resume.

## 🛠️ How to Use (For Parents)

### 1. Simple Access
Simply open the GitHub Pages link in any modern browser (Chrome/Edge recommended). **Click anywhere on the screen** to enable audio and trigger Fullscreen mode.

### 2. Kiosk Mode (The "Toddler Lock")
To prevent your child from Alt-Tabbing into your actual work, follow these steps on **Windows**:
1.  Search for **"Set up a kiosk"** in the Windows Start menu.
2.  Select **Microsoft Edge** as the kiosk app.
3.  Choose **"As a public browser"**.
4.  Enter your **GitHub Pages URL** as the home page.
5.  To exit Kiosk mode, press `Ctrl + Alt + Del`.

## 👨‍💻 Installation & Customization

If you want to host this yourself or modify the code:

1.  Fork this repository.
2.  Enable **GitHub Pages** in your repository settings.
3.  Modify the `snippets` array in the `<script>` tag to change the "code" that appears on screen.

```javascript
const snippets = ["INJECTING TOAST...", "DOWNLOADING MORE RAM...", "HACKING THE GIBSON..."];

⚠️ Safety Note
This is a front-end simulation only. It does not actually access any system files, networks, or "nuclear" facilities. It is 100% safe for children.