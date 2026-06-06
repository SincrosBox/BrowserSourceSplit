# ⏱️ BSSplit (BrowserSourceSplit)
A lightweight, 100% local, sandboxed speedrun timer designed to run entirely inside an **OBS Browser Source**. No installation, no cloud servers, and zero external tracking.

## 🚀 Features
* **Zero Install:** Just a single HTML file loaded straight into OBS.
* **Privacy First:** All data is saved locally inside your browser cache. No internet connection required.
* **Stream-Ready UI:** Hide all configuration menus with a single keypress for a clean stream overlay.

## 📥 How to Add Timer to OBS
1. In OBS, add a new source and select **Browser**.
2. Check the box that says **Local file**.
3. Click **Browse** and open the `BSSplit` HTML file from your folder.

## 🎮 How to Use & Controls
To configure your timer, interact with your OBS Browser Source window. 

### Menu Configuration
* Press **`H`** to toggle the configuration menu **On/Off**.
* Inside the menu, you can set the **Game Name**, **Load/Set** saves, add **Custom Splits**, delete specific splits via the **`X`** button, change text colors, or use **Clear All** to reset the game data.
* **⚠️ Important Note:** When the configuration options are hidden, all controls are completely locked. You cannot make any changes to the settings, text, or splits until you press **`H`** to unhide the menu again.
* Inside the active menu, you can set the **Game Name**, **Load/Set** saves, add **Custom Splits**, delete specific splits via the **`X`** button, change text colors, or use **Clear All** to reset the game data.

### Timer Hotkeys
* **`S`** — Start the timer.
* **`R`** — Reset the timer and all splits.
* **`P`** — Pause the current time/split.
* **`Spacebar`** — Split (stops time on the current segment but keeps the main timer rolling).

## 🎨 Recommended OBS Style Settings
To give the timer a clean, translucent background and a sharp border, paste the following code into the **"Custom CSS"** box inside your OBS Browser Source properties:

```css
.box { 
  background: rgba(0, 0, 0, 0.4) !important; 
  border: 1px solid #333; 
}
```
