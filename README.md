# 🐍 Python Snake Game 🍎

A classic implementation of the **Snake Game** developed using Python and the built-in `turtle` graphics library.

---

## 🚀 Getting Started

### Prerequisites

Ensure you have **Python 3** installed on your system. The `turtle` library is included with the standard Python installation, so no additional dependencies are required.

### How to Run

1.  **Download:** Save the provided code into a file (e.g., `snake_game.py`).
2.  **Execute:** Open your terminal or command prompt, navigate to the directory where you saved the file, and run the following command:

    ```bash
    python snake_game.py
    ```

---

## 🕹️ How to Play

The goal is to guide the snake (the red square) to eat the food (the yellow circle) to grow longer, while avoiding collisions with the screen borders or the snake's own body.

### Controls

The game uses the **W-A-S-D** keys for directional movement:

| Key | Movement |
| :---: | :---: |
| **W** | Up |
| **S** | Down |
| **A** | Left |
| **D** | Right |

### Scoring

* Each piece of food eaten **increases the snake's length** and awards **10 points**.
* The **Current Score** and **High Score** are displayed at the top of the screen.
* The **game speed** dynamically increases as your score rises, making the challenge progressively harder.

---

## ⚙️ Key Features

* **Graphics:** Utilizes the built-in Python **`turtle` library** for the game window and all graphical elements.
* **Simple Design:** Features distinct colors for the background (`#81d0b5`), snake head (`#ff3b3b`), snake body (`#ff9d9d`), and food (`#ffd500`).
* **Collision Logic:** Robust detection for hitting the screen boundaries and self-collision (head hitting the body segments).
* **Dynamic Difficulty:** The movement delay is incrementally reduced (`delay -= 0.001`) after each meal, accelerating the gameplay.

---

## 🛠️ Customization

You can easily modify the following aspects of the game:

1.  **Colors:** Change the hexadecimal color values (e.g., `#ff3b3b`) to adjust the colors of the screen, snake, and food.
2.  **Speed:** Adjust the initial value of the `delay` variable or the decrement value (`0.001`) to set the base speed and the rate of difficulty increase.
3.  **Window Size:** Modify the `width` and `height` parameters within the `wn.setup()` function.
