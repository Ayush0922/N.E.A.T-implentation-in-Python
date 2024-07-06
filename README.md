# N.E.A.T Implementation in Python

This project implements the classic Flappy Bird game with a twist: the bird's actions are controlled by a neural network trained using the NEAT (Neuro-Evolution of Augmenting Topologies) library.

## Features

- **Trainable AI** using NEAT for bird control
- **Pixel-perfect collision detection**
- **Animated bird** with smooth movement
- **Scrolling background and base**
- **Fitness scoring** based on bird survival time
- **Customizable game configuration** (optional)

## Getting Started

### Prerequisites

- **Python 3.x**
- **Pygame library:** 
  ```sh
  pip install pygame
  ```
- **NEAT library:** 
  ```sh
  pip install neat-python
  ```
- Check the **REQUIREMENTS** folder for better assistance.

### Run the Game

1. **Clone or download** the repository.
2. **Open a terminal** in the project directory.
3. **Run the script:**
   ```sh
   python3 game.py
   ```

### Training the AI

The game is configured to run for 50 generations by default. You can modify this behavior in the `game.py` script.

The NEAT library offers various configuration options for fine-tuning the training process. Refer to the [NEAT documentation](https://neat-python.readthedocs.io/) for details.

## Project Structure

```plaintext
flappy_bird_neat/
├── config.txt         # (Optional: NEAT configuration file)
├── imgs/              # Image assets
│   ├── base.png
│   ├── bg.png
│   ├── bird1.png
│   ├── bird2.png
│   ├── bird3.png
│   └── pipe.png
├── main.py            # Entry point for the game
├── neat/              # NEAT library modules (installed package)
├── pygame/            # Pygame library modules (installed package)
├── game.py            # Script to run the game and train the AI
```

## Further Enhancements

- **Implement different obstacle types** (varying heights, gaps)
- **Introduce a reward system** for the AI (points for passing pipes)
- **Visualize the neural network's structure and weights**
- **Add a user-controllable bird mode** (optional)

Feel free to explore and customize the code to create your own variations of the Flappy Bird game!

---

With these steps, you should have all your project dependencies installed and ready to go. Happy coding! 🎉

