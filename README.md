# GitHunt Chrome Extension - Manifest V3 Update

**Ready-to-install Chrome extension** - Updated for modern Chrome compatibility.

## 🚀 Quick Install (No Building Required):

### Option 1: Direct Download
1. **Click "Code" → "Download ZIP"** above
2. **Extract the ZIP file**
3. **Navigate to the `build/` folder** 
4. **Open Chrome** → `chrome://extensions/`
5. **Enable "Developer mode"** (toggle top-right)
6. **Click "Load unpacked"**
7. **Select the `build/` folder**
8. **Done!** GitHunt replaces your new tab

### Option 2: Git Clone
```bash
git clone https://github.com/SpaceDudem/githunt.git
cd githunt
# Install the 'build' folder as Chrome extension
```

## ✅ What's Fixed:
- **Manifest V3** - Compatible with Chrome 88+
- **Modern APIs** - Updated from deprecated browser_action
- **Host Permissions** - Proper GitHub API access
- **Security Compliant** - Passes Chrome Web Store requirements

## 📁 Extension Files:
The **ready-to-install extension** is in the `build/` folder:
```
build/
├── manifest.json (V3 format)
├── index.html
├── img/ (icons)
└── static/ (CSS, JS)
```

## 🐛 Issues?
- Extension loads immediately after installation
- No additional setup or API keys required
- Works with latest Chrome versions

## 📚 Original Project:
https://github.com/kamranahmedse/githunt

---
*This fork updates the extension to work with modern Chrome's Manifest V3 requirements.*