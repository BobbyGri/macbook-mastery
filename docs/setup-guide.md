# ⚙️ Setup Guide

## 🎯 Purpose

This guide provides a **practical, reproducible, and optimized macOS setup** for developers and power users.

It focuses on:

* Reducing friction
* Increasing speed of interaction
* Standardizing your environment
* Enabling automation

This is not a checklist — it is a **system design for your daily work environment**.

---

# 🧱 1. macOS System Configuration

## 🖱️ Trackpad Configuration

### Enable Tap to Click

**Why:**
Reduces physical effort and increases speed when navigating.

**How:**

1. Open **System Settings**
2. Go to **Trackpad**
3. Enable:
   → `Tap to click`

---

### Adjust Tracking Speed

**Why:**
Default speed is slow and increases movement time.

**How:**

1. System Settings → Trackpad
2. Increase **Tracking Speed** to ~70–80%

---

## ⌨️ Keyboard Configuration

### Increase Key Repeat Rate

**Why:**
Faster typing, navigation, and command execution.

**How:**

1. System Settings → Keyboard
2. Set:

   * **Key Repeat** → Fast
   * **Delay Until Repeat** → Short

---

### Enable Full Keyboard Access (Optional)

**Why:**
Allows navigating UI elements using keyboard.

**How:**

1. System Settings → Accessibility → Keyboard
2. Enable:
   → Full Keyboard Access

---

## 📂 Finder Configuration

### Show File Extensions

**Why:**
Prevents ambiguity between file types.

**How:**

1. Open Finder
2. Settings (⌘ + ,)
3. Advanced
4. Enable:
   → `Show all filename extensions`

---

### Show Path Bar

**Why:**
Provides full visibility of current directory.

**How:**

* Finder → View → Show Path Bar

---

### Show Status Bar

**Why:**
Displays file count and disk info.

**How:**

* Finder → View → Show Status Bar

---

### Set Default Finder Location

**Why:**
Avoids starting in Recents (low value).

**How:**

1. Finder Settings → General
2. Set:
   → “New Finder windows show” → Home or Projects folder

---

## 🔍 Spotlight Optimization

### Customize Search Categories

**Why:**
Reduces noise and improves search relevance.

**How:**

1. System Settings → Spotlight
2. Disable unnecessary categories (e.g., Fonts, Siri Suggestions)

---

### Usage Strategy

Use Spotlight as your primary launcher:

* Open apps
* Search files
* Execute quick calculations

Shortcut:

```bash
⌘ + Space
```

---

# 🧑‍💻 2. Terminal Setup

## Shell

macOS uses:

```bash
zsh
```

---

## Basic Configuration

Edit your config file:

```bash
nano ~/.zshrc
```

---

### Add Useful Aliases

```bash
alias ll="ls -la"
alias gs="git status"
alias ..="cd .."
alias ...="cd ../.."
```

**Why:**
Reduces typing and speeds up navigation.

---

### Apply Changes

```bash
source ~/.zshrc
```

---

# 🔧 3. Package Manager (Homebrew)

## Install Homebrew

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

---

## Verify Installation

```bash
brew --version
```

---

## Install Core Tools

```bash
brew install git
brew install node
brew install python
brew install wget
```

**Why these:**

* `git` → version control
* `node` → tooling ecosystem
* `python` → scripting / automation
* `wget` → file retrieval

---

# 🔐 4. Git & SSH Setup

## Configure Git Identity

```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

---

## Generate SSH Key

```bash
ssh-keygen -t ed25519 -C "your@email.com"
```

Press Enter to accept defaults.

---

## Start SSH Agent

```bash
eval "$(ssh-agent -s)"
```

---

## Add Key

```bash
ssh-add ~/.ssh/id_ed25519
```

---

## Add Key to GitHub

```bash
cat ~/.ssh/id_ed25519.pub
```

Copy output → Add to GitHub → SSH Keys

---

# 🧩 5. VS Code Setup

## Install

Download from:
https://code.visualstudio.com/

---

## Recommended Extensions

* GitLens
* Prettier
* Markdown Preview
* Python / C++ (depending on usage)

---

## Enable CLI Access

```bash
Cmd + Shift + P → "Shell Command: Install 'code' command in PATH"
```

---

# ⚡ 6. Productivity Foundations

## Folder Structure

Create a clean workspace:

```bash
mkdir -p ~/dev
mkdir -p ~/documents
```

---

### Recommended Separation

* `~/dev` → code and repositories
* `~/documents` → personal and knowledge

---

## Terminal Navigation Tip

Drag a folder into Terminal to auto-fill path:

```bash
cd [drag folder here]
```

---

# 🔄 7. Next Steps

After setup:

* Learn shortcuts → `shortcuts/`
* Implement workflows → `workflows/`
* Use scripts → `scripts/`

---

# 🧠 Final Thought

A fast system is not built by chance.

It is **designed**.

Every configuration decision should reduce friction, increase speed, and improve clarity.
