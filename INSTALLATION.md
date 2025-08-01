# GitHunt Chrome Extension - Ready to Install

## Instant Installation (No Building Required):

### Method 1: Download Ready Extension
1. **Download**: [GitHunt-v3-Extension.zip](../../releases/latest)
2. **Extract** the zip file
3. **Open Chrome** → `chrome://extensions/`
4. **Enable "Developer mode"** (toggle top-right)
5. **Click "Load unpacked"**
6. **Select the extracted folder**
7. **Done!** - GitHunt replaces your new tab

### Method 2: Build from Source (Developers)
```bash
git clone https://github.com/SpaceDudem/githunt.git
cd githunt
npm install
npm run build-chrome
# Load the 'build' folder in Chrome extensions
```

## What's Fixed:
- ✅ **Manifest V3** - Compatible with modern Chrome
- ✅ **Updated APIs** - browser_action → action
- ✅ **Host Permissions** - Proper GitHub API access
- ✅ **Build Process** - Fixed Node.js v20+ compatibility

## Issues?
The extension works immediately after loading. No additional setup required.

Original project: https://github.com/kamranahmedse/githunt