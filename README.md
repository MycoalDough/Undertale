# Undertale Within YouTube

**Play ANY Undertale fight animation directly over YouTube videos!**

<p align="center">
  <img src="https://img.shields.io/github/stars/MycoalDough/Undertale?style=social" alt="GitHub stars">
  <img src="https://img.shields.io/github/forks/MycoalDough/Undertale?style=social" alt="GitHub forks">
  <img src="https://img.shields.io/github/v/release/MycoalDough/Undertale" alt="Latest Release">
  <img src="https://img.shields.io/github/license/MycoalDough/Undertale" alt="MIT License">
</p>

---

## 🤔 What is this?

Ever wanted to actually *play* those sick Undertale fight animations on YouTube? Well now you can!

This app creates a controllable SOUL (heart) on your screen that you can move around like in the actual game. Watch any Undertale animation on YouTube and dodge bullets in real-time. It's basically turning YouTube into an interactive bullet hell game.

> **Fun fact:** I made this because Ari's Dusttrust animations weren't out yet and I was in both my Undertale phase AND Just Shapes & Beats phase at the same time. So I thought... why not just play the animations that already exist? And here we are! 😄

---

## ✨ Features

- 🎯 **Dynamic Border Detection** - AI-powered object detection automatically tracks the bullet box border
- 🌈 **Multiple SOUL Colors** - Red, Blue (gravity), Orange (keep moving), Yellow (dash), Green (shield)
- ⚙️ **Customizable Settings** - Import/export custom level configs
- 🎨 **AU Support** - Includes settings from various Undertale AUs
- 🔧 **Built-in Config Menu** - Adjust gameplay and performance on the fly
- ☠️ **KR (Karmic Retribution)** - Optional Sans-style poison damage
- ⚡ **Multithreaded Performance** - Smooth gameplay with high FPS

---

## 🎮 Controls

| Key | Action |
|-----|--------|
| **WASD** | Move your SOUL |
| **Z** | Heal (when available) |
| **SPACE** | Activate ability (shield/dash depending on SOUL color) |
| **Q** | Hide/show SOUL |
| **1-5** | Switch SOUL colors |

### SOUL Colors & Abilities

- **1 - Red Heart** 🔴 - Classic mode, not affected by gravity
- **2 - Blue Heart** 💙 - Affected by gravity (jump with W!)
- **3 - Orange Heart** 🧡 - Keep moving or take damage
- **4 - Yellow Heart** 💛 - Press SPACE to dash
- **5 - Green Heart** 💚 - Hold SPACE to activate shield

---

## 📥 Installation

1. Head over to [**Releases**](https://github.com/MycoalDough/Undertale/releases) →
2. Download the latest version (currently v1.1.2)
3. Extract and run the executable
4. That's it! 🎉

---

## 🚀 How to Use

1. **Open any Undertale fight video on YouTube** (Full screen recommended!)
2. **Launch the app** - A controllable heart will appear on your screen
3. **Click on the heart window** to focus it (this lets you control it)
4. **Set up the border:**
   - Choose the border color that matches the video's bullet box
   - Drag the blue corner points to match the bullet box corners
   - Enable "Dynamic Border" to auto-track it!
5. **Start playing!** Dodge those attacks! 💀

> **Pro tip:** Every time you click away from the heart window, you'll need to click it again to regain control. This is just how window focus works!

---

## 🎥 Dev Logs & Community

The dev logs for this project have gotten **over 100k views** and helped build an awesome community! 🙌

Check them out to see how everything works and learn some tips and tricks.

---

## ⚠️ Common Issues

### "My antivirus says it's a virus!"

**It's not, I promise!** 😅 

The program uses:
- **Key logging** (to detect WASD input for movement)
- **Screenshots** (to detect the border and check for damage)

Both are used for NON-malicious purposes, but antivirus software can flag these features. Feel free to check the source code yourself!

### "I can't control my heart!"

Make sure you **click on the heart window first** to give it focus. You need to do this every time you click away from it.

### "The border detection isn't working!"

1. Make sure you've set the correct border color
2. Position the blue corner points accurately on the bullet box corners
3. The video needs a clear, solid-colored border for auto-detection to work
4. If the video border is too thin or unclear, you might need to adjust manually

---

## 🐛 Known Issues

This program is **VERY buggy** (it's a passion project, cut me some slack! 😂). If you find bugs or have suggestions, feel free to open an issue on GitHub!

---

## 🛠️ Tech Stuff

This project taught me a ton about:
- **Object detection** (for tracking the bullet box)
- **Real-time overlays and screen capture**
- **Multi-threaded game loops**
- **Computer vision with Python**

---

## 📜 License

MIT License - Feel free to fork and modify!

---

## 💖 Support

If you like this project:
- ⭐ **Star the repo** (please I'm begging you)
- 🍴 **Fork it** and make your own version
- 📢 **Share it** with your friends who love Undertale
- 🐛 **Report bugs** to help make it better

---

## 🙏 Credits

- **Toby Fox** - For creating Undertale
- **The Undertale AU community** - For all the amazing fight animations
- **You!** - For checking out this project 💙

---

<p align="center">
  <b>Made with ❤️ (and way too much caffeine) by MycoalDough</b>
</p>

<p align="center">
  <i>"despite everything, it's still you."</i>
</p>
