🌐 Virtual Desktop Widget with Rainmeter & AutoHotkey

🌿 Version 3.0 – Stable Release 🌿
🌹 Created by AndrianAngel 🌹

🧠 Overview

This project enhances Windows Virtual Desktops with a live visual widget powered by Rainmeter and controlled via AutoHotkey. It displays the current virtual desktop number in real time and updates instantly as you switch desktops using custom hotkeys.

You also get a built-in GUI to customize the widget's appearance—choose your favorite color, font size, and weight with just a few clicks.

---

🖼️ Screenshots


😎 Widget 😎

![A1 Settings](Images/A1.png)
![A2 Settings](Images/A2.png)
![A3 Settings](Images/A3.png)
![A4 Settings](Images/A4.png)

---

🚀 Features

- Live Desktop Number Display  
  Rainmeter skin reads from current_desktop.txt and updates as you switch desktops.

- Custom Hotkey System (AutoHotkey)  
  - LCtrl + Numpad [1–9]: Switch to desktop  
  - LCtrl + Win + Numpad [1–9]: Move window and follow  
  - RCtrl + Numpad [1–9]: Throw window without following  
  - Alt + Numpad+ / Numpad-: Create/remove desktops  
  - Alt + Numpad0: Pin/unpin window  
  - LCtrl + F1/F2/F6: Query desktop info

- Rainmeter Widget Customization GUI  
  Right-click the widget → Virtual.Desktop.Widget.3.0 > Settings > Settings.ini  
  - 15 preset colors  
  - Adjustable font size and weight  
  - Live preview with instant refresh

---

🛠️ Installation & Setup

1. AutoHotkey Script
- Run Virtual.Desktop.Autohotkey.3.0.Stable.Release.ahk
- It creates current_desktop.txt in the same folder

2. Rainmeter Skin
- Unzip Virtual.Desktop.Widget.Rainmeter.3.0.Stable.Release.zip into:  
  Documents\Rainmeter\Skins\Virtual.Desktop.Widget.3.0
- Open Virtual.Desktop.Number.ini and set the correct path:
  `ini
  DesktopFile=D:\Your\Path\To\current_desktop.txt
  `
- Load the skin in Rainmeter and refresh everything

3. Customize
- Right-click the widget → Settings
- Use the GUI to tweak color, font size, and weight

---

📁 File Structure

| File | Purpose |
|------|---------|
| Virtual.Desktop.Autohotkey.3.0.Stable.Release.ahk | Main AHK script with hotkeys and Rainmeter sync |
| VD.ahk | Virtual Desktop library |
| current_desktop.txt | Auto-generated file storing current desktop number |
| Virtual.Desktop.Widget.Rainmeter.3.0.Stable.Release.zip | Rainmeter skin package |
| Settings.ini | GUI configuration for widget customization |
| Variables.inc | Stores user preferences (color, font size, weight) |
| Images/A1–A4.png | Screenshots for visual reference |

---

💡 Why This Project?

Windows Virtual Desktops are powerful—but invisible. This widget makes them visible, interactive, and customizable, bridging the gap between automation and aesthetics.
