# My Personal VSCode Configuration
<img width="1940" height="1163" alt="image" src="https://github.com/user-attachments/assets/dc7ef917-1cf0-47a9-a526-3b5340703943" />

---
A clean, distraction-free VSCode configuration inspired by **GNU Nano**, **Micro**, and **Focus Editor**.
- **Zero Distractions:** No tabs, no status bar, and no activity bar clutter.
- **Clean UI:** Hidden title bar icons, no scrollbars, and no breadcrumbs.
- **Terminal Ready:** Designed to be used alongside a terminal-heavy workflow.

## Extensions

| Extension | Purpose | Link |
| :--- | :--- | :--- |
| **August Themes** | The core color themes | [Install](https://marketplace.visualstudio.com/items?itemName=inci-august.august-themes) |
| **Symbols** | Minimalist file icons | [Install](https://marketplace.visualstudio.com/items?itemName=miguelsolorio.symbols) |
| **Fluent Icons** | Clean product/UI icons | [Install](https://marketplace.visualstudio.com/items?itemName=miguelsolorio.fluent-icons) |
| **Custom UI Style** | Allows CSS modification (Stripping useless UI) | [Install](https://marketplace.visualstudio.com/items?itemName=subframe7536.custom-ui-style) |
| **File Browser** | Simple file browser palette | [Install](https://marketplace.visualstudio.com/items?itemName=bodil.file-browser) |

## Typography

* **Space Mono:** [Download here](https://fonts.google.com/specimen/Space+Mono) (My personal choice)
* **JetBrains Mono:** [Download here](https://www.jetbrains.com/lp/mono/) (Good alternative)

## Installation

1. **Install the Extensions:** Click the links in the table above and install them in VSCode.
2. **Install the Font:** Download and install "Space Mono" on your operating system.
3. **Apply Settings:**
   - Open VSCode.
   - Press `Ctrl + Shift + P` (or `Cmd + Shift + P` on Mac).
   - Type `Preferences: Open User Settings (JSON)`.
   - Paste the contents of the `settings.json` file from this repo into that window.
   - Type `Preferences: Open Keyboard Shortcuts (JSON)`.
   - Paste the contents of the `keybindings.json` file from this repo into that window.
4. **Apply CSS Fixes:**
   - Because this config uses the `Custom UI Style` extension to hide the title bar and window controls, you may need to restart VSCode or run the command `Custom UI Style: Reload` from the command palette.
---
*Configuration by Demiero.*
