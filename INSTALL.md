# GitHunt Chrome Extension v4.0 - Installation Guide

## 📦 Quick Install (No Building Required):

### Method 1: Download ZIP
1. **[Click here to download](https://github.com/SpaceDudem/githunt/archive/refs/heads/master.zip)**
2. **Extract the ZIP file**
3. **Navigate to `githunt-master/build/` folder**
4. **Open Chrome** → `chrome://extensions/`
5. **Enable "Developer mode"** (toggle top-right)
6. **Click "Load unpacked"**
7. **Select the `build/` folder**
8. **Done!** GitHunt replaces your new tab

### Method 2: Git Clone
```bash
git clone https://github.com/SpaceDudem/githunt.git
cd githunt
# Load the 'build' folder in Chrome extensions
```

## ✅ Ready-to-Install Files:
The `build/` folder contains the complete, working Chrome extension:
```
build/
├── manifest.json (Manifest V3)
├── index.html
├── img/ (icons)
├── static/ (CSS, JS files)
└── All dependencies included
```

## 🎯 What This Extension Does:
- **Replaces Chrome new tab** with trending GitHub repositories
- **Browse by week** - scroll to see past weeks
- **Filter by language** - focus on specific technologies
- **Detailed repo info** - stars, description, language
- **Fast & responsive** - works great on all screen sizes

## 🔧 Troubleshooting:
- **Extension not loading?** Make sure you selected the `build/` folder specifically
- **Blank page?** Check Chrome DevTools console for errors
- **No data?** Check internet connection - requires GitHub API access

## 📚 More Info:
- **Report Issues**: [GitHub Issues](https://github.com/SpaceDudem/githunt/issues)
- **Original Project**: [kamranahmedse/githunt](https://github.com/kamranahredse/githunt)
- **License**: MIT

---
*Updated for Manifest V3 - Compatible with modern Chrome versions*