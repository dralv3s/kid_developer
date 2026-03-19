# 🛡️ Junior Dev Terminal: The Ultimate Toddler "Work" Simulator

A high-immersion, Hollywood-style "Hacker Terminal" designed specifically for toddlers who insist on "helping" their parents work. It provides constant visual and auditory feedback for every keypress, keeping little hands busy and away from your actual source code.

## 🚀 Live Demo
**[kid-developer](https://dralv3s.github.io/kid_developer/)**

---

## ✨ Features for the "Junior Agent"

* **Mechanical Feedback:** Every keypress generates unique synthesized "click" and "beep" sounds using the Web Audio API (no external assets required).
* **Mission Progress:** A persistent progress bar and percentage counter that increases as they "work."
* **📂 Mission Logs:** A built-in history tracker that saves completed "missions" and total action counts to the device's local storage.
* **The "L" Key Secret:** Pressing the **'L'** key triggers a high-stakes 5-second "System Overload" countdown with red-alert visuals and emergency sirens.
* **Security Breach:** Hitting **Backspace** triggers a screen-shake and a low-frequency "Security Restricted" error tone.
* **Bio-Scanner:** An animated fingerprint scanner with a moving laser line—perfect for "authorizing" top-secret deployments.
* **☕ Coffee Break Mode:** If no keys are pressed for 30 seconds, the system enters a "Standby" mode. The agent must tap the screen or press a key to "re-authorize" and resume work.

---

## 🛠️ How to Use (For Parents)

### 1. Simple Access
Open the demo link in any modern browser. **Click anywhere on the screen** to enable the audio engine and trigger Fullscreen mode automatically.

### 2. Kiosk Mode (The "Toddler Lock")
To prevent your child from accidentally closing the tab or switching to your work apps, use **Kiosk Mode**:

#### **On Windows:**
1.  Search for **"Set up a kiosk"** in the Start menu.
2.  Select **Microsoft Edge** as the kiosk app.
3.  Choose **"As a public browser"**.
4.  Enter your **GitHub Pages URL** as the home page.
5.  *To exit:* Press `Ctrl + Alt + Del`.

#### **On iPad/iPhone (Guided Access):**
1.  Go to **Settings > Accessibility > Guided Access** and turn it on.
2.  Open the site in Safari.
3.  **Triple-click the side button** to lock the iPad into the browser.

---

## 👨‍💻 Customization

If you want to host this yourself or modify the "code" the toddler sees:

1.  **Fork** this repository.
2.  Enable **GitHub Pages** in your repository settings (`Settings > Pages`).
3.  Modify the `snippets` array in the `<script>` tag to change the text that appears on screen:

```javascript
const snippets = [
    "INJECTING TOAST...", 
    "DOWNLOADING MORE RAM...", 
    "HACKING THE GIBSON...",
    "UPDATING URUGUAY_RELAY_04..."
];
```

⚠️ Safety Note
This is a front-end simulation only. It does not actually access any system files, networks, or "nuclear" facilities. It is 100% safe for children.