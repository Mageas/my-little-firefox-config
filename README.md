# My Little Firefox Configuration

A personal Firefox customization setup using userChrome.css and userContent.css to enhance the browsing experience with custom styles and tweaks.

## 📦 Installation

### 1. Locate Your Firefox Profile

Navigate to `about:profiles` in Firefox to find your profile directory path.

### 2. Copy Theme Files

Copy the `chrome` folder from this repository into your Firefox profile directory.

```
<your-firefox-profile>/
└── chrome/
    ├── userChrome.css
    └── userContent.css
```

## ⚙️ Firefox Configuration

To enable custom stylesheets and other config, you need to modify some Firefox preferences:

1. Go to `about:config` in Firefox
2. Set the following preferences:
```
toolkit.legacyUserProfileCustomizations.stylesheets : true
sidebar.verticalTabs : true
sidebar.visibility : expand-on-hover
```

## 🔄 Applying Changes

Restart Firefox to apply the custom styles.

---

*Feel free to customize the CSS files to match your personal preferences!*