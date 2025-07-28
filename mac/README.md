# 🖥️ Mac Setup Guide

This guide helps you set up your macOS environment after a clean install or system reset.

---

## 1. Install Homebrew

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

---

## 2. Install CLI Tools

```bash
brew install git              # Version control
brew install node             # JavaScript runtime (includes npm)
brew install python           # Latest Python 3
brew install mas              # Mac App Store CLI
```

---

## 3. Install GUI Apps via Homebrew Cask

```bash
brew install --cask docker                  # Docker Desktop GUI
brew install --cask chatgpt                 # ChatGPT desktop app
brew install --cask vlc                     # VLC media player
brew install --cask postman                 # API development
brew install --cask visual-studio-code      # Code editor
brew install --cask google-chrome           # Browser
brew install --cask notion                  # Notes and docs
brew install --cask discord                 # Discord app
```

---

## 4. Apps Available on Both Homebrew and App Store

### Option A: Install via Homebrew (easy to script)

```bash
brew install --cask whatsapp
brew install --cask telegram
brew install --cask wechat
```

### Option B (Recommended): Install from the Mac App Store

> For the latest versions and App Store integration, install manually or use `mas`:

```bash
mas install 310633997    # WhatsApp Messenger
mas install 747648890    # Telegram
mas install 836500024    # WeChat
mas install 1451685025   # WireGuard
```

Or manually download from:

* [WhatsApp Messenger](https://apps.apple.com/in/app/whatsapp-messenger/id310633997)
* [Telegram](https://apps.apple.com/in/app/telegram/id747648890)
* [WeChat](https://apps.apple.com/in/app/wechat/id836500024)
* [WireGuard](https://apps.apple.com/in/app/wireguard/id1451685025)

---

## ✅ After Setup Checklist

* Sign in to App Store before using `mas`
* Launch Docker Desktop and allow permissions
* Configure Git with your name and email:

  ```bash
  git config --global user.name "Your Name"
  git config --global user.email "you@example.com"
  ```
