# 🧠 Neovim Setup (My Configuration)

A modern Neovim setup focused on productivity, simplicity, and development.

---
## 🚀 Getting Started

Open a project:

```bash
nvim .
```

You’ll see a dashboard. From here, you can:

* open files
* browse folders
* start coding immediately

---

## 🧠 Core Concept: Modes

Neovim is based on modes:

| Mode   | What you do             |
| ------ | ----------------------- |
| NORMAL | Navigate & run commands |
| INSERT | Type text               |
| VISUAL | Select text             |

### Switch modes

* `i` → start typing (INSERT)
* `ESC` → go back to NORMAL

---

## ⌨️ The Leader Key

Your leader key is:

```
SPACE
```

Most commands start with it.

---

## 📁 Open and Navigate Files

### Open file explorer

```
SPACE + e
```

* Use arrows or `hjkl` to move
* Press `Enter` to open a file

---

### Find files quickly

```
SPACE + f
```

* Start typing file name
* Press `Enter` to open

👉 This is the fastest way to open files.

---

## ✍️ Editing Text

### Enter insert mode

```
i
```

### Save file

```
:w
```

### Quit

```
:q
```

### Save and quit

```
:wq
```

---

## 🔁 Moving Around

In NORMAL mode:

```
h → left
j → down
k → up
l → right
```

---

## 💬 Commenting Code

### Comment a line

```
gcc
```

### Comment multiple lines

1. Press `v` (visual mode)
2. Select lines
3. Press:

```
gc
```

---

## 💻 Using the Terminal

Open terminal:

```
CTRL + \
```

* Run commands inside Neovim
* Press again to close

---

## 🧠 Autocomplete (Very Important)

When typing in INSERT mode:

* `TAB` → next suggestion
* `SHIFT + TAB` → previous
* `ENTER` → confirm

You’ll get:

* function suggestions
* variables
* imports

---

## 🚨 Viewing Errors

### Show all errors

```
SPACE + xx
```

### Errors in current file

```
SPACE + xd
```

---

## 🧵 Switching Between Files

```
:bnext   → next file
:bprev   → previous file
```

---

## 🔄 Editing Surroundings

Examples:

```
ysiw" → add quotes to a word
cs"'  → change " to '
```

---

## 🧩 If You Forget Commands

Press:

```
SPACE
```

A menu will appear showing everything you can do.

---

## 🔥 Recommended Workflow

1. Open project

   ```
   nvim .
   ```

2. Find a file

   ```
   SPACE + f
   ```

3. Edit

   ```
   i
   ```

4. Save

   ```
   :w
   ```

5. Switch files

   ```
   :bnext
   ```

6. Open terminal

   ```
   CTRL + \
   ```

---

## 💡 Tips

* Stay in NORMAL mode as much as possible
* Use `SPACE + f` instead of browsing manually
* Learn small commands daily — they stack fast

---

