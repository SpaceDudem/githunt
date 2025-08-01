<h1 align="center">
  <img height="100" src="https://raw.github.com/kamranahmedse/githunt/master/public/img/logo.svg?sanitize=true" alt="GitHunt" /> <br> GitHunt - Manifest V3
</h1>

<p align="center">
  <a href="https://github.com/SpaceDudem/githunt/releases/latest">
    <img src="https://img.shields.io/github/v/release/SpaceDudem/githunt" alt="version" />
  </a>
  <a href="https://github.com/SpaceDudem/githunt">
    <img src="https://img.shields.io/badge/Chrome-Manifest%20V3-brightgreen" alt="manifest-v3" />
  </a>
  <a href="https://github.com/SpaceDudem/githunt/blob/master/license.md">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="license-mit" />
  </a>
</p>

<p align="center">
  <b>Hunt the most starred projects on GitHub</b><br>
  <sub>✨ Modern Chrome Extension with Manifest V3 support ✨</sub> 
</p>

## 🚀 Quick Install (No Building Required):

### Method 1: Download Release
1. **[Download Latest Release](https://github.com/SpaceDudem/githunt/releases/latest)**
2. **Extract the ZIP file**
3. **Open Chrome** → `chrome://extensions/`
4. **Enable "Developer mode"** (toggle top-right)
5. **Click "Load unpacked"**
6. **Select the extracted folder**
7. **Done!** GitHunt replaces your new tab

### Method 2: Clone Repository
```bash
git clone https://github.com/SpaceDudem/githunt.git
cd githunt
# Load the 'build' folder in Chrome extensions
```

## ✅ What's Fixed in This Version:
- **✅ Manifest V3** - Works with Chrome 88+ (original was V2)
- **✅ Modern APIs** - Updated deprecated `browser_action` → `action`
- **✅ Host Permissions** - Proper `host_permissions` for GitHub API
- **✅ Security Compliant** - Passes modern Chrome Web Store requirements
- **✅ Build Process** - Fixed Node.js v20+ compatibility issues

## 📸 Screenshots:

<p align="center">
  <img alt="GitHunt Weekly Trending" src="./.github/list.png">
  <b>Weekly Trending Projects – List View</b><br>
  <sub>💥 Keep Scrolling to load past weeks 💥</sub>
</p>

<p align="center">
  <img alt="GitHunt Grid View" src="./.github/grid.png">
  <b>Weekly Trending Projects – Grid View</b><br>
  <sub>💥 Change the view options from the filters list 💥</sub>
</p>

## 🛠️ For Developers:

To build from source:
```bash
git clone https://github.com/SpaceDudem/githunt.git
cd githunt
npm install
npm run build-chrome
# Load the 'build' folder in Chrome extensions
```

## 🐛 Issues & Contributions:
- Report bugs in [Issues](https://github.com/SpaceDudem/githunt/issues)
- Pull requests welcome!
- This fork maintains the original functionality with modern Chrome compatibility

## 📚 Credits:
- **Original Project**: [kamranahmedse/githunt](https://github.com/kamranahmedse/githunt)
- **Created by**: [Kamran Ahmed](https://kamranahmed.info)
- **Manifest V3 Update**: SpaceDudem

## 📄 License:
MIT © [Kamran Ahmed](https://kamranahmed.info)