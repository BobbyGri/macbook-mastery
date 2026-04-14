# ⌨️ Keyboard Configuration & Customization 

## 🎯 Purpose

This guide explains how to configure and customize keyboard behavior on macOS.

It is intentionally **layout-independent** and applies to all keyboard layouts, including:

* US
* DE
* FR
* MX
* RU

It covers:

* Input source configuration
* Layout switching
* Basic keyboard settings
* Text replacements
* Advanced key customization

---

## 🧱 1. Input Sources

### Add a Keyboard Layout

To add a new keyboard layout:

1. Open **System Settings**
2. Go to **Keyboard**
3. Click **Input Sources**
4. Click **Edit**
5. Click **Add (+)**
6. Select the language and layout you want
7. Click **Add**

### Why this matters

If you work in multiple languages or environments, adding multiple layouts allows you to:

* Write naturally in different languages
* Use the most convenient layout for coding
* Reduce friction when switching contexts

---

## 🔄 2. Switching Between Layouts

Once multiple input sources are enabled, you can switch between them.

### Default shortcut

```text
Control + Space
```

You can also enable the input menu in the menu bar to switch manually.

### Recommended strategy

* Use **US** for coding and terminal work
* Use your native layout for writing and communication

### Why this matters

Most development tools, documentation, and symbol-heavy workflows are easier with the US layout.

---

## ⚙️ 3. Basic Keyboard Settings

Open:

1. **System Settings**
2. **Keyboard**

Recommended settings:

### Key Repeat

Set **Key Repeat** to **Fast**.

**Why:**
Improves speed when navigating or editing text.

### Delay Until Repeat

Set **Delay Until Repeat** to **Short**.

**Why:**
Makes the keyboard feel more responsive.

### Keyboard Brightness

Adjust if needed for visibility and comfort.

---

## ✍️ 4. Text Replacements

macOS supports text replacements.

### How to configure

1. Open **System Settings**
2. Go to **Keyboard**
3. Open **Text Replacements**
4. Click **Add (+)**

Example:

* Replace `;;e` with `€`
* Replace `;;n` with `ñ`

### When to use this

Use text replacements when:

* You frequently type the same symbols
* You want a quick shortcut-like behavior for text
* You do not need a true key remap

### Limitation

Text replacements are **not real keyboard shortcuts**.

They replace typed text after input, rather than remapping a key combination directly.

---

## 🧩 5. Modifier Keys

Some keyboards allow modifier key adjustments.

### Possible changes

You may be able to remap:

* Caps Lock
* Control
* Option
* Command
* Globe / Fn

### Example use cases

* Turn **Caps Lock** into **Escape**
* Swap **Control** and **Caps Lock**
* Adjust modifier behavior for external keyboards

### Why this matters

Modifier customization can significantly improve comfort and efficiency, especially for developers.

---

## 🛠️ 6. Advanced Customization

If you want to press a specific key combination and produce a custom character or behavior, basic macOS settings may not be enough.

Advanced customization usually falls into three categories:

---

### A. Text Replacement

Best for:

* Frequently used words or symbols
* Quick substitutions
* Simple text automation

Use when:

* You want simplicity
* A typed sequence is enough

---

### B. Custom Keyboard Layouts

A custom keyboard layout allows you to redefine how keys behave at the layout level.

Best for:

* Changing how characters are produced
* Creating your own symbol mapping
* Adapting a layout to a specific workflow

Use when:

* You want a system-wide layout change
* You need consistent character mapping

---

### C. Key Remapping Tools

Key remapping tools allow deeper customization.

Examples of what they can do:

* Map one key combination to another
* Trigger text output
* Change modifier behavior
* Create custom keyboard workflows

Use when:

* You want full control
* You need advanced behavior beyond built-in settings

---

## 🧠 7. Choosing the Right Approach

Use this rule of thumb:

| Need                              | Best Approach          |
| --------------------------------- | ---------------------- |
| Quick symbol insertion            | Text replacement       |
| Permanent layout change           | Custom keyboard layout |
| Advanced remapping and automation | Key remapping tool     |

---

## ⚡ 8. Recommended Strategy

A practical approach for most users:

1. Start with the correct input sources
2. Configure repeat rate and delay
3. Add a few text replacements for frequently used symbols
4. Only move to advanced remapping if needed

### Why this approach works

It keeps the system simple at first, while still allowing growth into more advanced customization later.

---

## 🔗 Related

* See [Cross-Layout Mappings](../../keyboards/README.md) for layout overview
* See [US Keyboard Layout](../../keyboards/US/keymap.md) for a layout-specific example
* See [shortcuts](`../../shortcuts/) for system and application shortcuts
* See [workflows](../../workflows/) for practical keyboard-based workflows

---

## 🧠 Final Thought

Your keyboard is not just a device.

It is part of your working system.

A well-configured keyboard reduces friction, improves consistency, and makes daily work faster and more comfortable.
