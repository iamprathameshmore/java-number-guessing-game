# Number Guessing Game in Java

Welcome to the Number Guessing Game in Java! This console-based game challenges you to guess a randomly generated number within a specified range.

## How to Play

1. The program generates a random number between 1 and 100.
2. You will be prompted to guess the number.
3. If your guess is too high, you'll be informed with a "Too high!" message.
4. If your guess is too low, you'll be informed with a "Too low!" message.
5. When you guess the correct number, you'll receive a "Correct!" message.

Keep guessing until you get it right!

## Getting Started

To run the game on your local machine, make sure you have Java installed. You can follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/iamprathameshmore/java-number-guessing-game.git
   ```

2. Compile the Java code:

   ```bash
   javac NumberGuessingGame.java
   ```

3. Run the game:

   ```bash
   java NumberGuessingGame
   ```

## Customize the Range

You can customize the range of numbers by modifying the code. For instance, you can change the lower and upper bounds to make the game easier or more challenging. Simply edit the following lines in the code:

```java
int randomNumber = random.nextInt(100) + 1;  // Change 100 to your desired upper bound
```

## Features

- Randomly generated secret number within a specified range.
- Interactive and simple gameplay.
- Easy-to-understand instructions.

## Contributing

If you'd like to contribute to this project, feel free to open an issue, create a pull request, or offer suggestions. We welcome contributions!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
