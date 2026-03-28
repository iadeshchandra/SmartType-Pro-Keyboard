# SmartType Pro Keyboard

![SmartType Pro Banner](https://via.placeholder.com/800x200.png?text=SmartType+Pro+Keyboard)

[![Download](https://img.shields.io/badge/Download-Latest-blue)](#download) [![Stars](https://img.shields.io/github/stars/iadeshchandra/SmartType-Pro-Keyboard?style=social)](https://github.com/iadeshchandra/SmartType-Pro-Keyboard)

**SmartType Pro Keyboard** is a customized fork of LeanType and HeliBoard — a privacy-conscious and customizable open-source keyboard based on AOSP/OpenBoard.

This fork adds optional AI-powered features using Gemini, Groq, and OpenAI-compatible APIs, offering a hybrid experience: a private, offline core with opt-in cloud intelligence.

## ✨ What's New in SmartType Pro
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

## 📸 Screenshots

| Screenshot 1 | Screenshot 2 | Screenshot 3 |
|:---:|:---:|:---:|
| <img src="https://via.placeholder.com/200x400.png?text=1" width="200"/> | <img src="https://via.placeholder.com/200x400.png?text=2" width="200"/> | <img src="https://via.placeholder.com/200x400.png?text=3" width="200"/> |
| **Screenshot 4** | **Screenshot 5** | **Screenshot 6** |
| <img src="https://via.placeholder.com/200x400.png?text=4" width="200"/> | <img src="https://via.placeholder.com/200x400.png?text=5" width="200"/> | <img src="https://via.placeholder.com/200x400.png?text=6" width="200"/> |

## 📥 Download
You can download the latest release from the **GitHub Actions** or **Releases** page.

### 📦 Choose Your Version

**1. Standard Version (`-standard-release.apk`)**
* **Features:** Full suite including AI Proofreading, AI Translation, and Gesture Library Downloader.
* **Permissions:** Request `INTERNET` permission (used only when you explicitly use AI features).
* **Setup:** Use the built-in downloader for Gesture Typing. Configure AI keys in Settings.

**2. Offline Version (`-offline-release.apk`)**
* **Features:** All UI/UX enhancements and Offline Neural Proofreading (ONNX).
* **Permissions:** `NO INTERNET PERMISSION`. Guaranteed at OS level.
* **Best For:** Privacy purists.
* **Manual Setup Required:**
  * *Gesture Typing:* Download library manually and load via `Settings > Gesture typing`.
  * *Offline AI:* Download ONNX models and load via `Settings > AI Integration`. 

**3. Offline Lite Version (`-offlinelite-release.apk`)**
* **Features:** All UI/UX enhancements but `NO AI FEATURES`.
* **Permissions:** `NO INTERNET PERMISSION`. Guaranteed at OS level.
* **Best For:** Minimalists who want a modern keyboard without any AI components (~20MB size).
* **Manual Setup Required:**
  * *Gesture Typing:* Download library manually and load via `Settings > Gesture typing`.

## ⌨️ Original HeliBoard Features
* Add dictionaries for suggestions and spell check
* Customize keyboard themes (style, colors and background image)
* Customize keyboard layouts
* Multilingual typing
* Glide typing (requires library)
* Clipboard history
* One-handed mode
* Split keyboard
* Number pad
* Backup and restore settings

## ⚙️ Setup

### AI Features Setup
SmartType Pro supports multiple AI providers: Google Gemini, Groq, and OpenAI-compatible (OpenRouter, HuggingFace, etc.).

**Quick Start:**
1. Get a free key from **Google AI Studio** (Gemini) or **Groq Console** (Groq).
2. Copy the API key.
3. Go to `Settings → AI Integration → Set AI Provider`.
4. Select your provider and paste the API Token.
5. Select Model and target language.

### ⚠️ Important
**Privacy:** Your input data is sent to the configured provider only when you activate the AI tools. 

## 🤝 Contributing
For issues specific to SmartType Pro features, please open an issue in this repository.
For issues with core HeliBoard functionality, please report to the original HeliBoard repository.

## 📄 License
SmartType Pro Keyboard (as a fork of LeanType/HeliBoard/OpenBoard) is licensed under GNU General Public License v3.0. See `LICENSE` file.

## 🏆 Credits

**Original Projects**
* **LeanType by LeanBitLab** - The excellent AI keyboard this fork is based on
* **HeliBoard by Helium314**
* **OpenBoard**
* **AOSP Keyboard**
* Original icon by Fabian OvrWrt
* All HeliBoard and LeanType Contributors

**SmartType Pro**
Built with ❤️ by **Creative Learning Pro**

### 🛡️ Creative Learning Pro Ecosystem
Subscribe and check out our other tutorials on YouTube for digital marketing, AI, tech, and more!

---
*SmartType Pro Keyboard • Privacy-focused keyboard with AI enhancements*
