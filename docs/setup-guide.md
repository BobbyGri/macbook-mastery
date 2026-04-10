# ⚙️ Setup Guide

## 🎯 Purpose

This guide helps you configure a clean, efficient, and reproducible macOS environment.

It focuses on:

* System configuration
* Development setup
* Productivity optimization

---

## 🧱 1. macOS Initial Setup

### Basic Configuration

* Enable **Tap to click**
* Set **Trackpad speed**
* Configure **Keyboard repeat rate**
* Enable **Dark mode** (optional)

---

### Finder Configuration

* Show path bar
* Show status bar
* Set default folder (e.g. Home or Projects)
* Enable file extensions

---

### Spotlight

* Customize indexed categories
* Use it as a primary navigation tool

---

## 🧑‍💻 2. Terminal Setup

### Choose your shell

```bash
zsh (default)
```

---

### Recommended configuration

* Enable colors
* Customize prompt
* Add useful aliases

Example:

```bash
alias ll="ls -la"
alias gs="git status"
alias ..="cd .."
```

---

## 🔧 3. Development Environment

### Install Homebrew

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

---

### Install essential tools

```bash
brew install git
brew install node
brew install python
brew install wget
```

---

### Git Configuration

```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

---

## 🧩 4. VS Code Setup

* Install VS Code
* Install extensions:

  * GitLens
  * Prettier
  * Markdown Preview
  * Python / C++ (depending on your needs)

---

## 🔐 5. SSH Setup

Generate SSH key:

```bash
ssh-keygen -t ed25519 -C "your@email.com"
```

Add to ssh-agent:

```bash
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519
```

---

## ⚡ 6. Productivity Setup

* Configure shortcuts (see `shortcuts/`)
* Set up workflows (see `workflows/`)
* Install automation scripts (see `scripts/`)

---

## 📁 7. Folder Structure (Recommended)

Example:

```bash
~/dev/
~/documents/
~/downloads/
```

Keep development and personal files separated.

---

## 🔄 8. Continuous Improvement

This setup is not static.

Improve it over time:

* Add scripts
* Refine workflows
* Optimize shortcuts

---

## 🧠 Final Note

A well-configured system is not about tools.

It is about reducing friction and enabling focus.
