# SmartType Pro Keyboard

*[SmartType Pro Banner Placeholder]*

**[Download] [Downloads] [Stars]**

**SmartType Pro Keyboard** is a highly advanced, privacy-conscious open-source keyboard. Built on the solid foundations of HeliBoard and LeanType, this project offers a true hybrid experience: a private, offline typing core combined with optional, on-demand cloud intelligence.

---

### ✨ What's New in SmartType Pro
* **🤖 Multi-Provider AI** - Proofread using Gemini, Groq (Llama 3, Mixtral), or OpenAI-compatible providers.
* **🛡️ Offline AI** - Private, on-device proofreading and translation using ONNX models (Offline build only).
* **🌐 AI Translation** - Translate selected text directly using your chosen AI provider.
* **🧠 Custom AI Keys** - Assign custom prompts and personas (#editor, #proofread) to 10 customizable toolbar keys.
* **⌨️ Dual Toolbar / Split Suggestions** - Option to split suggestions and toolbar for easier access.
* **🖱️ Touchpad Mode** - Swipe spacebar up to toggle touchpad; custom sensitivity controls.
* **🎨 Modern UI** - "Squircle" key backgrounds, refined icons, and polished aesthetics.
* **🔄 Google Dictionary Import** - Easily import your personal dictionary words.
* **⚙️ Enhanced Customization** - Force auto-capitalization toggle, reorganized settings, and more.
* **🕵️ Clear Incognito Mode** - Distinct "Hat & Glasses" icon for clear visibility.
* **🔍 Clipboard Search & Undo** - Search through your clipboard history directly from the toolbar, and undo accidental item deletions.
* **📸 Screenshot Suggestion & Clipboard** - Suggests recently taken screenshots for quick sharing via the suggestion strip and saves them to your clipboard history.
* **🔎 Emoji Search** - Search for emojis by name. Requires loading an Emoji Dictionary.
* **🔒 Privacy Choices** - Choose Standard (Opt-in AI), Offline (Hard-disabled network, offline model load), or Offline Lite (Minimalist, no AI) versions.

---

### 📸 Screenshots
[Screenshot 1] | [Screenshot 2] | [Screenshot 3] | [Screenshot 4] | [Screenshot 5] | [Screenshot 6]

---

### 📥 Download
You can download the latest release from the GitHub Releases page or generate it directly via GitHub Actions.

#### 📦 Choose Your Version

**1. Standard Version (-standard-release.apk)**
* **Features:** Full suite including AI Proofreading, AI Translation, and Gesture Library Downloader.
* **Permissions:** Requests INTERNET permission (used strictly when you explicitly trigger AI features).
* **Setup:** Use the built-in downloader for Gesture Typing. Configure AI keys in Settings.

**2. Offline Version (-offline-release.apk)**
* **Features:** All UI/UX enhancements and Offline Neural Proofreading (ONNX).
* **Permissions:** NO INTERNET PERMISSION. Guaranteed at the OS level.
* **Best For:** Privacy purists.
* **Manual Setup Required:**
    * Gesture Typing: Download library manually and load via Settings > Gesture typing.
    * Offline AI: Download ONNX models and load via Settings > AI Integration.

**3. Offline Lite Version (-offlinelite-release.apk)**
* **Features:** All UI/UX enhancements but NO AI FEATURES.
* **Permissions:** NO INTERNET PERMISSION. Guaranteed at the OS level.
* **Best For:** Minimalists who want a modern keyboard without any AI components (~20MB size).
* **Manual Setup Required:**
    * Gesture Typing: Download library manually and load via Settings > Gesture typing.

---

### ⌨️ Original HeliBoard Features
* Add dictionaries for suggestions and spell check
* Customize keyboard themes (style, colors, and background image)
* Customize keyboard layouts
* Multilingual typing
* Glide typing (requires library)
* Clipboard history
* One-handed mode
* Split keyboard
* Number pad
* Backup and restore settings

---

### ⚙️ AI Features Setup
SmartType Pro supports multiple AI providers: Google Gemini, Groq, and OpenAI-compatible (OpenRouter, HuggingFace, etc.).

**Quick Start:**
1. Get a free key from **Google AI Studio** (Gemini) or **Groq Console** (Groq).
2. Copy the API key.
3. Go to **Settings → AI Integration → Set AI Provider**.
4. Select your provider and paste the API Token.
5. Select the Model and target language.

*Important: Your input data is sent to the configured provider only when you activate the AI features. Please view the Privacy Policies for your selected providers.*

---

### 🤝 Contributing
* For issues specific to SmartType Pro features, please open an issue in this repository.
* For issues with core HeliBoard functionality, please report to the original HeliBoard repository.

### 📄 License
SmartType Pro (as a fork of LeanType/HeliBoard/OpenBoard) is licensed under GNU General Public License v3.0. See the LICENSE file.

### 🏆 Credits
**Original Projects**
* LeanType by LeanBitLab - The excellent AI-integrated fork architecture
* HeliBoard by Helium314 - The highly customizable privacy keyboard
* OpenBoard & AOSP Keyboard
* Original icon by Fabian OvrWrt
* All HeliBoard & LeanType Contributors

---

### 🛡️ Creative Learning Pro Ecosystem
**SmartType Pro Keyboard** is proudly maintained by **Creative Learning Pro**. 

**Support the Development**
Building and maintaining privacy-focused tools takes time and resources. If you find SmartType Pro useful for your daily workflow, please consider supporting the project and starring the repository to keep it 100% Free and Open Source!
