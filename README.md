# CodeHelper

CodeHelper is a macOS utility app that allows developers to quickly capture screen content and generate intelligent code suggestions, optimized solutions, and understanding approaches using AI.

---

## ✨ Features

- 🖼️ **Screen Capture Integration**  
  Automatically captures the current screen and processes it for code or prompt-based insights.

- ⌨️ **Customizable Keyboard Shortcuts**  
  Toggle overlay, request answers, or use voice commands with easy-to-assign hotkeys.

- 🧠 **AI-Powered Code Generation**  
  Send screen or voice-generated prompts to an API for AI-generated code and explanations.

- 🗣️ **Voice Commands**  
  Dictate coding prompts and receive code responses in real-time.

- 📋 **Text Recognition**  
  Uses macOS Vision framework (via `ScreenAnalyzer`) to extract text from screenshots.

---



## 🔐 Authentication

Authentication is handled via a secure key stored in the macOS Keychain. It is verified at launch using the endpoint:


If authentication succeeds, the app enables all overlay and AI features.

---

## 🧭 Shortcuts

| Shortcut | Action |
|----------|--------|
| ⌘⌃S | Toggle Overlay |
| ⌘⌃A | Ask for Answer |
| ⌘⌃N | Naive Solution |
| ⌘⌃O | Optimal Solution |
| ⌘⌃V | Voice Command |
| ⌘↑  | Scroll Up |
| ⌘↓  | Scroll Down |


---

## 📦 Setup

### 🛡️ macOS Gatekeeper – How to Run the App

If you see a warning like:  
**“CodeHelper” cannot be opened because it is from an unidentified developer.**

Here’s how to manually allow it:

1. **Try to open the app** (you’ll get a warning).
2. Go to **System Settings** → **Privacy & Security**.
3. Scroll down to the **Security** section.
4. You’ll see a message:  
   **“CodeHelper was blocked from use because it is not from an identified developer.”**
5. Click **“Open Anyway”**.
6. Try launching the app again — click **“Open”** when prompted.

> 🔁 You only need to do this once. After approval, the app will launch normally.

3. Grant screen recording permission:
   - System Settings → Privacy & Security → Screen Recording → Enable for **CodeHelper**
4. Ensure internet access for the API to work.

---

## 📋 Permissions

Make sure to enable **Screen Recording** in System Settings for the app to function correctly.


System Settings → Privacy & Security → Screen Recording → CodeHelper

## 👨‍💻 Author
Sk Jasimuddin
📅 Created: 04/04/2025 Saka
🚀 Code smarter. Build faster.





