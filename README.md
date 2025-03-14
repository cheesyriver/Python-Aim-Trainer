# My Epic Aim Trainer

This is a simple aim trainer game built using Python and Pygame. The game challenges the player to click on growing and shrinking targets within a limited number of lives.

## Features

* **Dynamic Targets:** Targets spawn randomly and change size.
* **Score Tracking:** Tracks time elapsed, targets hit per second, hits, and accuracy.
* **Lives System:** The game ends when the player misses too many targets.
* **Game Over Screen:** Displays final statistics after the game ends.
* **User-Friendly Interface:** Clear and simple graphics with informative labels.

## How to Run

1.  **Install Python:** Ensure you have Python 3.x installed on your system.
2.  **Install Pygame:** Install the Pygame library using pip:

    ```bash
    pip install pygame
    ```

3.  **Save the Code:** Save the provided Python code as a `.py` file (e.g., `aim_trainer.py`).
4.  **Run the Game:** Open a terminal or command prompt, navigate to the directory where you saved the file, and run the script:

    ```bash
    python aim_trainer.py
    ```

## Game Mechanics

* Targets spawn at random locations and grow to a maximum size, then shrink until they disappear.
* If a target shrinks to zero size without being clicked, the player loses a life.
* The player's speed is calculated as the number of targets hit divided by the elapsed time.
* The player's accuracy is calculated as the number of targets hit divided by the total number of clicks.
* The game displays the time, speed, hits, and lives remaining on the top bar.
* The game ends when the player loses all lives.
* The game displays the time, speed, hits, and accuracy on the game over screen.

## Customization

* `WIDTH`, `HEIGHT`: Adjust the game window size.
* `TARGET_INCRIMENT`: Adjust the target spawn rate (lower values = faster spawns).
* `TARGET_PADDING`: Adjust the padding around the edges of the screen where targets can spawn (taking the maximum size the targets can get into account).
* `BG_COLOUR`: Change the background color.
* `LIVES`: Change the number of lives the player has.
* `TOP_BAR_HEIGHT`: change the height of the top bar.
* `LABEL_FONT`: Change the font and size of the labels.
* `Target.MAX_SIZE`, `Target.GROWTH_RATE`, `Target.COLOR`, `Target.ALT_COLOR`: Change the target's properties.