<div align="center">

<img width="136" height="135" alt="2026-08-24_00-58-11-Photoroom" src="https://github.com/user-attachments/assets/867bd774-7cbc-4040-8ce4-74b0a4b5fafa" />

# 🎵 MusicMote (Beta)

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey)
![UI](https://img.shields.io/badge/UI-CustomTkinter-purple)
![Status](https://img.shields.io/badge/status-active-success)

</div>

---

## 💜 About the Project

**MusicMote** is a lightweight and convenient desktop application for controlling Yandex Music directly from your desktop.

The application allows you to control music playback without opening the player itself, using a modern interface and global hotkeys.

---

## ✨ Features

* ▶️ Play / Pause
* ⏭ Next / Previous track
* 🔊 Volume control
* 🚀 Launch Yandex Music
* 🪟 Switch to the player window
* ⌨️ Global hotkeys
* ⚙️ Customize and reassign hotkeys
* 🌐 Interface language selection:
  * 🇷🇺 Russian
  * 🇬🇧 English
  * 🖥 System
* 🎨 Interface theme selection:
  * 🌙 Dark
  * ☀️ Light
  * 🖥 System
* 📌 Minimize to the system tray
* 📂 Select the path to Yandex Music
* 🖱 Drag & Drop a Yandex Music executable or shortcut into the application
* 💾 Save application settings

---

<div align="center">

## 🖼 Screenshot

<img width="322" height="582" alt="2026-08-24_01-18-24" src="https://github.com/user-attachments/assets/0880b672-480d-4f5a-8202-c8ca2ce85ff2" />

</div>

---

## 🛠 Technologies Used

* Python 3.10+
* CustomTkinter (GUI)
* Win32 API (pywin32)
* keyboard (global hotkeys)
* pystray (system tray)
* tkinterdnd2 (Drag & Drop)
* Pillow (image handling)

---

## 📦 Installation

### 🔹 Option 1 (Recommended)

Download the ready-to-use `.exe` file from the **Releases** section and launch it.

---

### 🔹 Option 2 (Using Python)

```bash
git clone https://github.com/Anyusek/MusicMote.git
cd MusicMote
pip install -r requirements.txt
python MusicMote.py
```

### ⚙️ How to Use

1. Launch the application.
2. Select the path to Yandex Music:

* use the file picker;
* or drag & drop the .exe file or shortcut into the application window.

3. Click "Open Yandex Music".
4. Control your music 🎧

### ⚠️ Notes
* Currently works only on Windows.
* Yandex Music must be installed on your computer.
* Python 3.10+ is required when running from source.
* Some global hotkeys may require administrator privileges.
* If some dependencies are missing, certain features may not be available.

### 🔥 Global Hotkeys

MusicMote supports global hotkeys — they work even when the application or Yandex Music window is not focused.

<div align="center"> 
  
<img width="382" height="632" alt="2026-08-24_01-19-54" src="https://github.com/user-attachments/assets/e97bd97d-b9af-4d41-b1eb-60089038126b" /> 

</div>

### ⚙️ Hotkey Settings

In the Control Settings section, you can customize the hotkeys to your preference.

You can:

* 🔄 Change the shortcut assigned to any command;
* 💾 Save your custom shortcuts;
* ↩️ Reset the settings to their default values.

> 💡 After changing the hotkeys, they can be used to control MusicMote regardless of which application is currently in the foreground.

### 📌 Roadmap

* [ ] 🚧 Display the currently playing track — in development
* [ ] 🎨 Improve the application design and create a more convenient and beautiful interface — in development
* [ ] Automatic startup with Windows
* [ ] macOS version

### 🤝 Feedback

If you have any ideas, questions, or find a bug, feel free to contact me:

Telegram: @anyusek
VK: https://vk.ru/anyusek
MAX: https://max.ru/u/f9LHodD0cOJWoqJyV49iP9Xd-AhGVIP2DDCrlU77-ERzrRKGaMeFtnXXbvU

### 👨‍💻 Author

Developed with ❤️ by Anyusek

<details>
<summary>📄 <strong>License</strong></summary>

MusicMote is distributed under a custom project license.

You may use the application for personal and non-commercial purposes.

Without prior permission from the author, you may not:

* redistribute the application or its copies;
* publish the source code or parts of it;
* modify and redistribute modified versions;
* claim the project or any part of it as your own work;
* use the project for commercial purposes.

The full license terms are available in the [`LICENSE`](LICENSE) file.

</details>
