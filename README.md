# Number-Guessing-Game
Number Guessing Game using Python.


# Number Guessing Game with Background Music

## Short Description
A simple number guessing game built using Python's Tkinter library for the graphical interface and Pygame for background music. The game includes a mute/unmute toggle for the music.

## Long Description

This project is a **Number Guessing Game** implemented in Python using the Tkinter library for the graphical user interface (GUI) and the Pygame library for playing background music. In the game, the user is asked to guess a number between 1 and 100. The game provides feedback if the guess is too low or too high, and tracks the number of attempts made.

### Features:
- **Number Guessing Game:** Users have to guess a randomly selected number between 1 and 100.
- **Background Music:** Pygame is used to play background music throughout the game.
- **Mute/Unmute Toggle:** A button is provided to toggle the background music on and off. Clicking the button will mute the music when it's playing, and unmute it when it's muted.

### Dependencies:
- `Tkinter`: Used for creating the graphical user interface.
- `Pygame`: Used for handling background music and audio.

### Installation:
1. Ensure you have Python 3 installed on your system.
2. Install Pygame using the following command:
    ```bash
    pip install pygame
    ```
3. Download or clone this repository to your local machine.
4. Place your **background music** file (e.g., `background_music.mp3`) in the same directory as the script.
    - If you want to use your own background music:
        1. Delete the current background music file (included in the ZIP file).
        2. Bring your own `.mp3` music file inside the same directory as the game.
        3. Rename your music file to **`background_music.mp3`** to ensure it plays correctly.

5. Run the Python script to start the game.

### How to Play:
1. When you run the program, a window will pop up with instructions on how to play.
2. Type your guess in the input field and click the **Guess** button.
3. The game will tell you if your guess is too high or too low.
4. You can track the number of attempts made to guess the correct number.
5. The **Mute Music** button allows you to toggle background music on and off.

### Error Handling:
- If the music file is not found or if there is an issue with playing the music, an error message will appear in the interface and will be logged for debugging purposes.
  
### How to Contribute:
Feel free to fork this repository, submit pull requests, or create issues if you find any bugs or have ideas for improvements.

### License:
This project is open-source under the MIT License. You are free to modify and distribute the code for personal and educational use. However, you **may not** copy the code and upload it as your own project. Please give credit to the original author if you make improvements or modifications.

See the [LICENSE](LICENSE) file for more details.

---

Enjoy the game, and happy guessing!
