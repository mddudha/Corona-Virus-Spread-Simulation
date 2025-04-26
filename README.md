# 🦠 Coronavirus Spread Simulator

This is a simple **Java-based simulation** that visually demonstrates the **spread of a virus (like COVID-19)** among a population of people within a city. Built using **Java AWT** and **Swing**, this project models individual movement and interaction to simulate infection spread in real time.

## 📽️ Demo Video
Check out the demo on YouTube: [Watch Here](https://youtu.be/kVpHmMpdNgI)

## 📷 Preview
The simulator creates a window titled `CORONA VIRUS SIMULATOR`, where 100 individuals (`People` objects) move within a city (`City` class).

## 💻 Features
- 100 people are generated and displayed.
- GUI created using `JFrame`, `JPanel`, and other Swing components.
- Simulates virus transmission dynamics.
- Uses Java's built-in `Timer` and `ActionListener` for screen refresh and animation.

## 🛠️ Technologies Used
- Java
- Java AWT (`java.awt.*`)
- Java Swing (`javax.swing.*`)
- Object-Oriented Programming
- Event-driven programming (`ActionListener`, `ActionEvent`)

## 🧪 How It Works
- A `JFrame` window is created and contains a `City` panel.
- The `City` class maintains and animates a population of `People` objects.
- Each `People` object is assigned a status (e.g., healthy, infected) and moves around the screen.
- Collisions or close interactions between infected and healthy people can simulate virus transmission.

## 🚀 Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/corona-virus-simulator.git
