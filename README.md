# Flappy Birds Arduino Game

This project is an implementation of the popular game Flappy Birds using Arduino. The game is played on an LCD screen and controlled using a button.

## Files

- `arduinoFlappyBirds.ino`: This is the main Arduino sketch file that contains the game logic and controls.
- `notes.h`: This file contains the musical notes used for the chime sounds in the game.

## Dependencies

- `Wire.h`: Arduino library for I2C communication.
- `rgb_lcd.h`: Arduino library for controlling RGB LCD displays.

## Hardware Setup

1. Connect an RGB LCD display to your Arduino board.
2. Connect a button to the designated button pin on the Arduino board.
3. Connect a buzzer to the designated buzzer pin on the Arduino board.
4. Connect green and red LEDs to the designated pins on the Arduino board.

## How to Play

1. Upload the `arduinoFlappyBirds.ino` sketch to your Arduino board.
2. Press the button to make the bird fly and avoid collision with the pipes.
3. Collect coins to increase your score.
4. The game ends when the bird collides with three pipes and you run out of lives.

## Credits

This project is inspired by the original Flappy Birds game and was created as a learning exercise.

## License

This project is licensed under the [MIT License](LICENSE).
