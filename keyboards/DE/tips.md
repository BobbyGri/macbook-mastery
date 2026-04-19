# 💡 DE Keyboard Tips 

## 🎯 Purpose

Practical tips to improve efficiency when using the **German (QWERTZ) keyboard layout on macOS**.

---

## ⚡ Use Shortcuts by Position, Not Letters

Shortcuts are based on **physical key position**, not visible characters.

Example:

```text id="de_tip_1"
⌘ + Z (Undo) → still uses the same key position, even if Z/Y are swapped
```

**Why:**

* macOS shortcuts do not change with layout
* muscle memory is more reliable than visual reference

---

## 🔄 Be Aware of the Y / Z Swap

The German layout uses **QWERTZ**:

* Y and Z are swapped compared to US

**Why it matters:**

* Typing mistakes are common at first
* especially in shortcuts like Undo (⌘ + Z)

---

## 🔤 Use Umlauts Efficiently

The layout provides direct access to:

* ä, ö, ü, ß

**Why:**

* Faster than using dead keys or copy-paste
* Essential for correct German writing

---

## 💻 Expect Symbol Differences

Some symbols are not directly accessible:

* [ ] { } @ \ |

They often require ⌥ or ⇧ + ⌥.

**Why:**

Even though DE is closer to US than FR, symbols are still redistributed.

---

## ⚡ Learn Key Symbols Once

Important symbols to internalize:

* @
* [ ]
* { }
* \

**Why:**

These are frequently used in development and configuration.

---

## 🔤 Use Character Reference When Needed

If you cannot type a symbol quickly:

→ Use [Character Reference](characters.md)

This provides a complete set of copyable characters.

---

## ⚡ Use Spotlight as a Launcher

```text id="de_tip_2"
⌘ + Space → type → Enter
```

**Why:**

* Works regardless of keyboard layout
* Faster than navigating manually

---

## 📂 Open Terminal in Current Folder

### Method 1: Drag & Drop

```bash id="de_tip_3"
cd [drag folder here]
```

### Method 2: Right Click (Automator Service)

Create a workflow to open Terminal in the selected folder.

**Why:**

Reduces navigation and works independently of layout.

---

## ✍️ Faster Navigation in Terminal

| Action        | Shortcut   |
| ------------- | ---------- |
| Move by word  | ⌥ + ← / →  |
| Start of line | Ctrl + A   |
| End of line   | Ctrl + E   |
| Delete word   | ⌥ + Delete |

---

## 🧠 Think in Workflows

Instead of isolated actions:

* Combine shortcuts
* Automate repetitive steps
* Reduce context switching

👉 Example:
Finder → Terminal → Script → Done

---

## ⚠️ Common Mistakes

* Confusing Y and Z while typing
* Expecting US symbol positions
* Forgetting Option-based characters
* Overusing mouse instead of shortcuts

---

## 🚀 Next Steps

* See [Shortcuts](shortcuts.md) for system actions
* Explore [Workflows](../../workflows/README.md) to build real processes
* Use [Scripts](../../scripts/README.md) to automate tasks
