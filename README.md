<p align="center">
  <img src="assets/banner.png" alt="Rhythm Plus Discord RPC Banner" width="100%">
</p>

<h1 align="center">🎵 Rhythm Plus Discord RPC</h1>

<p align="center">
  A lightweight browser extension and userscript to display your <a href="https://v2.rhythm-plus.com/">Rhythm Plus</a> gameplay status directly on your Discord profile in real-time.
</p>

<p align="center">
  <a href="https://chromewebstore.google.com/">
    <img src="https://img.shields.io/badge/Chrome-Extension-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Chrome Extension">
  </a>
  <a href="https://addons.mozilla.org/">
    <img src="https://img.shields.io/badge/Firefox-Addon-FF7139?style=for-the-badge&logo=firefox-browser&logoColor=white" alt="Firefox Addon">
  </a>
  <a href="https://microsoftedge.microsoft.com/addons/">
    <img src="https://img.shields.io/badge/Edge-Addon-0078D7?style=for-the-badge&logo=microsoft-edge&logoColor=white" alt="Edge Addon">
  </a>
  <a href="https://addons.opera.com/">
    <img src="https://img.shields.io/badge/Opera-Addon-FF1B2D?style=for-the-badge&logo=opera&logoColor=white" alt="Opera Addon">
  </a>
  <a href="https://www.tampermonkey.net/">
    <img src="https://img.shields.io/badge/Tampermonkey-Script-002B36?style=for-the-badge&logo=tampermonkey&logoColor=white" alt="Tampermonkey Script">
  </a>
</p>

---

## 📚 Official Documentation & Links

* **[Chrome Web Store Developer Docs](https://developer.chrome.com/docs/extensions)**: Learn how Chromium-based extensions are structured and published.
* **[Firefox Extension Workshop](https://extensionworkshop.com/)**: Official guidelines for building and submitting WebExtensions to Mozilla Add-ons (AMO).
* **[Opera Add-ons Developer Hub](https://addons.opera.com/developer/)**: Portal for publishing extensions to the Opera ecosystem.
* **[Tampermonkey Documentation](https://www.tampermonkey.net/documentation.php)**: Guide for creating custom userscripts.

---

## 🚀 Installation & Usage

### 🌐 Browser Extensions (Chrome, Edge, Opera, Firefox)
1. Download the latest `.zip` release from the [Releases](../../releases) page or install it directly from your browser's store using the badges above.
2. **Manual Installation (Developer Mode):**
   * **Chrome / Edge / Opera:** Go to `chrome://extensions`, enable **Developer mode**, and drag and drop your extension folder or `.zip` file.
   * **Firefox:** Go to `about:debugging#/runtime` and click **Load Temporary Add-on...** by selecting your `manifest.json`.

### 🐒 Tampermonkey Userscript Alternative
If you prefer running a userscript instead of an extension:
1. Make sure you have the [Tampermonkey](https://www.tampermonkey.net/) extension installed in your browser.
2. Click on your script file (`rhythm-plus-rpc.user.js`) or install it directly via your local server setup.
3. The script will automatically inject into `https://v2.rhythm-plus.com/*`.

---

## 📸 Preview

<p align="center">
  <img src="assets/screenshot.png" alt="Discord RPC Preview" width="700">
</p>

---

## 🛠️ Built With

* **JavaScript (ES6+)**
* **Manifest V3** (Browser Extensions)
* **Userscript API** (Tampermonkey version)

---

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information.
