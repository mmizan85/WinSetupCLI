# 🚀 WinSetup: Ultimate Windows Post-Installation Tool

**WinSetup** is a powerful, modern, and open-source software installer designed for Windows 10 and 11. Built with **PowerShell** and powered by **Microsoft Winget**, it allows users to set up their fresh Windows environment with 100+ essential tools in just a few clicks.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-original)
![Language](https://img.shields.io/badge/language-PowerShell-blue)

---

## ✨ Key Features

* **100+ Software Collection:** From Browsers to Development tools, all the most-used software is included.
* **Modern Dark UI:** A sleek, user-friendly interface inspired by VS Code aesthetics.
* **Category-Based Selection:** Easily browse software by category (Media, Dev, Gaming, etc.).
* **One-Click Installation:** Select multiple apps and install them all at once—completely unattended (Silent Install).
* **Real-Time Progress & Logs:** Watch the installation progress with a live terminal-style log and progress bar.
* **Winget Integration:** Uses the official Microsoft Package Manager for safe and verified downloads.

---

## 🛠️ How to Use

Setting up your PC with WinSetup is incredibly easy:

1.  **Download** the repository to your local machine.
2.  Locate the `start.bat` file.
3.  **Right-click** on `start.bat` and select **"Run as Administrator"**.
4.  The **WinSetup** GUI will appear.
5.  Select a **Category**, check the apps you want, and hit **INSTALL SELECTED**.

> **Note:** Administrative privileges are required to install software system-wide.

---

## 📦 Categories Included

| Category | Description |
| :--- | :--- |
| **⭐ Must Have Essentials** | Chrome, VLC, WinRAR, Zoom, IDM, etc. |
| **🌐 Browsers** | Edge, Firefox, Brave, Opera GX, Tor. |
| **👨‍💻 Development** | VS Code, Python, Node.js, Git, Docker. |
| **🎨 Graphics & Design** | Blender, GIMP, Figma, OBS Studio. |
| **🎮 Gaming** | Steam, Epic Games, EA App, Ubisoft. |
| **🛠️ System Utilities** | CCleaner, Rufus, CPU-Z, TreeSize. |
| **📁 Office & Docs** | LibreOffice, Notion, Adobe Reader. |

---

## 📸 Interface Preview

*(You can add a screenshot of your tool here)*
> The tool features a **Dark Theme** with a custom **RichText Log** that displays real-time installation status in green "terminal-style" text.

---

## 🏗️ Technical Details

* **Backend:** PowerShell Core.
* **Frontend:** .NET Windows Forms (System.Windows.Forms).
* **Package Engine:** Windows Package Manager (winget).
* **Execution Policy:** The `start.bat` automatically bypasses execution policies to ensure smooth startup.

---

## 🤝 Contributing

Contributions are welcome! If you want to add a new category or software:
1. Fork the Project.
2. Update the `$SoftwareCatalog` variable in the script.
3. Open a Pull Request.

---

## 📜 License

Distributed under the **MIT License**. See `LICENSE` for more information.

---
**WinSetup** - *Setting up Windows has never been this fast.*

What's next?
 * Screenshots: Open your tool, take a screenshot, and upload it to your GitHub repository. Then update the README.md with the image link.
 * License: You can add a file named LICENSE (usually MIT) to make it more professional.
Would you like me to help you with a LICENSE file or any other documentation?

