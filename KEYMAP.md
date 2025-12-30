# 🧠 Neovim – Personal Cheatsheet (Backend Dev)

## ⌨️ Leader

* **Leader**: `<Space>`

---

## 🔍 File / Search (Telescope)

| Phím             | Chức năng                |
| ---------------- | ------------------------ |
| `<Space>sf`      | Find file                |
| `<Space>sg`      | Live grep (toàn project) |
| `<Space>sw`      | Grep word dưới cursor    |
| `<Space>s.`      | Recent files             |
| `<Space><Space>` | List buffers             |
| `<Space>sh`      | Help                     |
| `<Space>sk`      | Keymaps                  |

### 📂 Mở file nâng cao (trong Telescope)

| Phím    | Kết quả                      |
| ------- | ---------------------------- |
| `Enter` | Mở buffer (đè file hiện tại) |
| `Alt+v` | Mở **vertical split**        |
| `Alt+s` | Mở **horizontal split**      |
| `Alt+t` | Mở **tab mới**               |

---

## 🪟 Window / Split

| Phím       | Chức năng        |
| ---------- | ---------------- |
| `Ctrl+h`   | Move left split  |
| `Ctrl+l`   | Move right split |
| `Ctrl+j`   | Move down        |
| `Ctrl+k`   | Move up          |
| `Ctrl+w =` | Cân lại split    |
| `Ctrl+w q` | Đóng split       |

### 🔁 Toggle Split (custom)

| Phím        | Hành vi           |
| ----------- | ----------------- |
| `<Space>sv` | Toggle **vsplit** |
| `<Space>sh` | Toggle **hsplit** |

---

## 🖥 Terminal (Scratchpad)

| Phím         | Chức năng                |
| ------------ | ------------------------ |
| `<Space>tt`  | Toggle floating terminal |
| `<Esc><Esc>` | Thoát terminal mode      |

---

## 🧱 Buffer / Tab

### Buffer

| Phím             | Chức năng     |
| ---------------- | ------------- |
| `<Space><Space>` | Switch buffer |
| `:bd`            | Close buffer  |
| `:ls`            | List buffer   |

### Tab

| Phím        | Chức năng       |
| ----------- | --------------- |
| `:tabnew`   | New tab         |
| `gt / gT`   | Next / Prev tab |
| `:tabclose` | Close tab       |

> 🧠 Rule: **Buffer = file**, **Tab = context**

---

## 🧠 LSP (Code Intelligence)

| Phím        | Chức năng             |
| ----------- | --------------------- |
| `grd`       | Go to definition      |
| `grr`       | Find references       |
| `gri`       | Go to implementation  |
| `grt`       | Go to type definition |
| `grn`       | Rename                |
| `gra`       | Code action           |
| `gO`        | Document symbols      |
| `gW`        | Workspace symbols     |
| `<Space>th` | Toggle inlay hints    |

---

## ⚠ Diagnostics

| Phím        | Chức năng          |
| ----------- | ------------------ |
| `<Space>sd` | Search diagnostics |
| `<Space>q`  | Diagnostic list    |

---

## 🎨 Format

| Phím       | Chức năng     |
| ---------- | ------------- |
| `<Space>f` | Format buffer |

---

## ✂ Editing (Vim core)

| Phím         | Chức năng            |
| ------------ | -------------------- |
| `ciw`        | Change inner word    |
| `di"`        | Delete inside quotes |
| `vap`        | Select paragraph     |
| `.`          | Repeat last action   |
| `u / Ctrl+r` | Undo / Redo          |

---

## 🌿 Git

| Phím        | Chức năng    |
| ----------- | ------------ |
| `<Space>hp` | Preview hunk |
| `<Space>hs` | Stage hunk   |
| `<Space>hr` | Reset hunk   |
| `<Space>hb` | Blame line   |

---

## 🛠 Utility

| Lệnh           | Chức năng          |
| -------------- | ------------------ |
| `:Lazy`        | Plugin manager     |
| `:Mason`       | LSP / tool manager |
| `:checkhealth` | Check system       |

