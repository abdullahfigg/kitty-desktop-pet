# 🐱 Kitty — Your Little Desktop Companion

A playful little cat that lives on your Windows desktop! Kitty can roam around your screen, rest, react to your interactions, chase toys, and cause a little chaos with zoomies and disco mode.

**Kitty brings a little life to your desktop.** 🐾

<!-- Replace this with a screenshot or GIF of Kitty running -->
<!-- ![Kitty Desktop Pet](screenshots/kitty-demo.gif) -->

## ✨ Features

- 🐈 **Desktop roaming** — watch Kitty wander around your screen.
- 😴 **Resting and sleeping** — Kitty takes breaks too.
- 🖐️ **Pet Kitty** — interact with your little companion.
- 💨 **Zoomies** — trigger bursts of chaotic cat energy.
- 🧶 **Toy chasing** — let Kitty chase a toy around your desktop.
- 🪩 **Disco mode** — add some extra chaos and fun.
- ⌨️ **Keyboard shortcuts** — control Kitty without opening menus.
- ⚙️ **Control panel** — access Kitty's settings and controls.
- 🖥️ **System tray integration** — manage Kitty from the Windows notification area.
- 📦 **Windows executable** — run the packaged version without manually launching the Python script.

  🎮 Controls & Interactions

Kitty has several ways to interact with your desktop companion!

🖱️ Mouse Controls

Action

What it does

Left-click

Wake or pet Kitty

Right-click

Trigger zoomies — Kitty goes wild!

Middle-click + drag

Pick up Kitty and move it around your desktop

⌨️ Keyboard Shortcuts

Kitty supports global keyboard shortcuts, allowing you to control it without opening another window.

Action

Shortcut

Pause / Resume

Check the configured shortcut in your version

Show / Hide Kitty

Check the configured shortcut in your version

**Quit Kitty = ctrl + alt + Q**

Check the configured shortcut in your version

Shortcut keys may depend on the current application configuration. The mappings above should be updated with the actual keys before release.

🧶 Toys & Special Modes | ctrl + alt + K

Toy chasing: Activate toy mode to let Kitty chase the cursor or toy.

Zoomies: Trigger Kitty's chaotic movement with a right-click.

Disco mode: Turn on the disco effect for a more chaotic desktop experience.

⚙️ System Tray & Control Panel

Use Kitty's system tray icon to access its available controls and settings. The control panel provides another way to manage Kitty.

Depending on the current configuration, you can use these controls to manage Kitty's behavior or exit the application.

🚪 Exiting Kitty

Use the available Quit option in the system tray menu or control panel to close Kitty cleanly.

## 🎮 How to Use

1. Download and launch `Kitty.exe`.
2. Let Kitty roam around your desktop.
3. Interact with Kitty using the supported mouse actions and keyboard shortcuts.
4. Use the system tray icon or control panel to access additional options.
5. Try the different modes and see what Kitty gets up to!

> **Note:** Add the exact keyboard shortcuts and mouse controls here once they're verified against the current version of the code.

## 💻 Installation

### Option 1: Download the Windows executable

1. Open the repository's [Releases](../../releases) page.
2. Download the latest `Kitty.exe` asset, if a release is available.
3. Run the executable on Windows.

If no release is available yet, build the executable from source using the instructions below.

### Option 2: Run from source

**Requirements**
- Windows
- Python compatible with the project's dependencies
- Git (optional, for cloning the repository)

Clone the repository:

```bash
git clone https://github.com/abdullahfigg/burgers_webpet.git
cd burgers_webpet
```

Create and activate a virtual environment:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

Install the project's dependencies using its dependency file, if provided:

```powershell
pip install -r requirements.txt
```

Run Kitty using the project's Python entry point:

```powershell
python main.py
```

> If the project uses different entry-point or dependency filenames, update these commands to match the actual files in the repository.

## 🛠️ Building the Windows Executable

Kitty uses PyInstaller for packaging, if configured in the current project.

After installing the required dependencies, build the executable using the project's verified PyInstaller configuration. The resulting application is typically placed in the `dist` directory.

Make sure the required animation files, images, and icon resources are bundled correctly so Kitty works outside the development folder.

## 🧰 Built With

- **Python** — application logic.
- **PyQt** — desktop interface and system tray integration, if used by the current implementation.
- **PyInstaller** — packaging the application for Windows.
- **Git and GitHub** — version control and project hosting.

## 📁 Project Structure

The exact structure may change as development continues.

```text
burgers_webpet/
├── main.py
├── assets/
├── README.md
├── requirements.txt
└── dist/
    └── Kitty.exe
```

This is an illustrative structure. Your actual repository may use different folders and filenames.

## 🚧 Future Ideas

Some ideas for future development:

- 🐾 More animations and personality.
- 🧸 Additional toys and interactive behaviors.
- 💖 An affection system that responds to interactions.
- 📔 A Kitty diary with activity statistics.
- 🪟 Improved Windows startup and tray settings.
- 🎨 More customization options.

These are potential future features, not promises about the current version.

## 🤝 Contributing

Suggestions, bug reports, and ideas are welcome!

1. Fork the repository.
2. Create a branch for your changes.
3. Make and test your improvements.
4. Open a pull request describing what you changed.

## 📜 License

No license has been specified yet. A license will be added once the project’s distribution terms are decided. Until then, please don't assume the source code is licensed for unrestricted reuse.

## 👨‍💻 Author

Created by [@abdullahfigg](https://github.com/abdullahfigg).

Built as a fun desktop pet project, with the goal of making everyday computer use a little more entertaining.

---

**Thanks for checking out Kitty!** 🐱💖

If you enjoy the project, consider starring the repository ⭐
