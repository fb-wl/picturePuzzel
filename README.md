# 🇳🇱 Wat zie je hier? (Image Guessing Quiz) 🌷

A fun, interactive, and fully client-side image guessing quiz built with HTML5 Canvas and Vanilla JavaScript. 

## ✨ Features

* **Zero Setup / 100% Client-Side:** No backend, server, or database required. Just open the HTML file in your browser.
* **Custom Local Images:** Select your own images directly from your computer via the built-in file picker. Your files are processed entirely in the browser and never leave your device.
* **Dynamic Visual Effects:** Images are obfuscated and slowly revealed over time using 4 different HTML5 Canvas effects:
  * 🧩 **Puzzle:** Scrambled pieces smoothly moving to their correct positions.
  * ⬛ **Covered:** Black blocks randomly disappearing to reveal the image.
  * 🌀 **Swirl:** A heavily twisted image untangling itself.
  * 👾 **Pixel:** A highly pixelated image sharpening up.
* **Multilingual & Themed UI:** Switch between **Dutch**, **German**, **English**, and **Traditional Chinese**. The application instantly adapts its UI colors, flags, background emojis, and countdown animations (Bicycle 🚴, Racecar 🏎️, London Bus 🚌, Rocket 🚀) to match the chosen language.
* **URL Parameters:** You can pre-select the default language using the `?lang=` parameter in the URL (e.g., `puzzel.html?lang=de`). The default is Dutch (`nl`).
* **Interactive Gameplay:** Click the image to pause the countdown. Click "Reveal" to skip the timer and solve the image immediately.

## 🚀 How to Play

1. Clone or download this repository.
2. Open the `puzzel.html` file in any modern web browser (Chrome, Firefox, Edge, Safari).
3. Click the **⚙️ (Gear icon)** in the bottom left corner to open the configuration menu.
4. Choose your preferred language, time limit, and active effects.
5. Click **"Choose files"** (or the respective translation) and select the image files from your computer that you want to play with.
6. Click **OK** to save the configuration.
7. Click **Start** to begin the quiz!

## 🛠️ Technologies Used

* HTML5 & CSS3
* Vanilla JavaScript (ES6)
* HTML5 `<canvas>` API for real-time pixel manipulation and rendering

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).