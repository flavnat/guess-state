# 🗺️ Ethiopia Regions Guessing Game

A fun and interactive **geography quiz game** built using **Python Turtle Graphics** and **Pandas**.  
The goal of this game is to guess all the **regions (states)** of **Ethiopia** by typing their names.  
Each correct guess will be displayed directly on the **map of Ethiopia** at its correct position.

---

## 🚀 Features

- Displays a **map of Ethiopia** using Turtle graphics.
- Accepts **user input** for guessing region names.
- Tracks the number of **correct guesses**.
- Automatically **marks the correct region name** on the map at its exact coordinates.
- Allows users to **exit anytime** and saves their progress to a CSV file.
- Uses **Pandas** for efficient data handling.

---

## 🧩 Project Structure

bash ```
├── RegionalMap.gif # Map image of Ethiopia (used as the main background)
├── RegionalData.csv # CSV file containing region names and coordinates
├── main.py # Main game script (the code you provided)
└── guessed_state.csv # Automatically generated file of correctly guessed regions

```

## Installation & Setup

1. Clone this repository

bash ```

git clone https://github.com/yourusername/EthiopiaRegionsGame.git
cd EthiopiaRegionsGame

```
2.Install dependencies

bash ```

pip install pandas

```

3.Run the game

bash ```

python main.py

```