# 🔥 Glowing Animated Loading Bar

This project is a CSS-based animated loading effect with rotating, glowing bars that smoothly change color. It uses only **HTML and CSS**, with **no JavaScript required**.

🔗 **Live Demo:** [https://amit046.github.io/Glowing-Animated-Loading-Bar/](https://amit046.github.io/Glowing-Animated-Loading-Bar/)  
📂 **GitHub Repo:** [https://github.com/Amit046/Glowing-Animated-Loading-Bar](https://github.com/Amit046/Glowing-Animated-Loading-Bar)

---

## ✨ Features

- ✅ Pure CSS animation
- 🔄 Smooth rotation and glowing effect
- 🌈 Color transition from green (`#0f0`) to red (`#fe2323`)
- ⚙️ Easy to customize (bars, colors, speed, size)
- 📱 Fully responsive and centered on all screens

---

## 🔍 How it Works

Each bar (`<span>`) is animated with a delayed effect using a custom CSS variable (`--i`).  
This creates a **wave-like motion** as bars glow, rotate, and transition colors over an **infinite 8-second loop**.

---

## 📁 Project Structure

Glowing-Animated-Loading-Bar/
├── index.html # Contains the loading bar structure

└── style.css # Contains all animation and style logic



---

## 📦 Usage

1. Clone or download this repository  
   `https://github.com/Amit046/Glowing-Animated-Loading-Bar`

2. Open `index.html` in your browser to see the animated loading bar.

3. Customize it easily:
   - ✏️ Change number of `<span>` elements for more/less bars
   - 🎨 Modify colors, size, and animation speed in `style.css`

---

## 🛠️ Customization Tips

- **Colors:** Adjust `background` and `box-shadow` in `@keyframes animate`
- **Speed:** Change `animation: animate 8s linear infinite` to desired duration
- **Bar Count:** Add/remove `<span>`s inside the `.loading` div
- **Size:** Update `width`/`height` values for `.loading span`

---

## 📜 License

This project is **open-source and free** to use for both personal and commercial projects.  
Feel free to ⭐ star the repo if you find it useful!

---

Made with ❤️ by [Amit046](https://github.com/Amit046)

