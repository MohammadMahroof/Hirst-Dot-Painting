# 🎨 Hirst Dot Painting Generator

![Python](https://img.shields.io/badge/Python-3.x-blue)
![License](https://img.shields.io/badge/License-MIT-green)

A Python Turtle project that generates a Hirst-style dot painting using random RGB colors.  
The program creates a structured 10×10 grid of colorful dots inspired by Damien Hirst’s spot paintings.

---

## 🖼️ Project Preview

![Hirst Painting Output](Hirst-Painting-Output.png)

> *(Add a screenshot of your turtle output and save it as `screenshot.png` in the repository folder.)*

---

## 🚀 Features

- Generates a 10×10 grid of colorful dots
- Uses RGB color mode (0–255)
- Random color selection using Python’s `random` module
- Fast rendering with optimized turtle speed
- Optional color extraction using the `colorgram` library

---

## 🛠️ Technologies Used

- Python
- Turtle Graphics
- Random Module
- Colorgram (for extracting colors from an image)

---

## 📂 Project Structure

```bash
.
├── main.py                # Main program file
├── image.jpg              # Reference image for color extraction
├── OutputScreenshot.png   # Output preview image
└── README.md              # Project documentation
```

---

## ⚙️ How It Works

1. Extract RGB colors from an image using `colorgram` (optional).
2. Store extracted colors in a list.
3. Use Turtle graphics to draw dots in a grid pattern.
4. Randomly select a color for each dot.
5. Move to the next row after every 10 dots.

---

## ▶️ How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/MohammadMahroof/hirst-dot-painting.git
cd hirst-dot-painting
```

### 2️⃣ Run the program
```bash
python main.py
```

---

## 📌 Learning Outcomes

- Understanding Turtle graphics
- Working with RGB color systems
- Using loops and conditionals
- Implementing grid-based logic
- Basic use of external libraries

---

## 📜 License

This project is licensed under the MIT License.
