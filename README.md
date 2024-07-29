# Rock Paper Scissors Game 🎮✊📄✂️

## Description 📜
Rock Paper Scissors is a classic hand game usually played between two people. In this C++ mini project, one player is automated as a Computerized Player, while the other player (you!) provides their choice of rock, paper, or scissors.

## Introduction 🌟
Rock Paper Scissors (also known as Roshambo) is a hand game where each player simultaneously forms one of three shapes with their hand:

- **Rock** (a closed fist) ✊
- **Paper** (a flat hand) 📄
- **Scissors** (a fist with the index and middle fingers extended, forming a V) ✂️

It's a zero-sum game with two possible outcomes: a draw or a win/loss. The rules are simple:
- Rock crushes scissors ✊ > ✂️
- Scissors cuts paper ✂️ > 📄
- Paper covers rock 📄 > ✊

## Game Play 🎮
Players count aloud to three, or speak the name of the game ("Rock! Paper! Scissors!"), while swinging their hand down with each syllable. On the third count, players extend their chosen shape towards their opponent.

In this automated version, the computer will randomly choose a shape, and you get to make your choice. Let's see who wins!

## Rules 📏
- Rock beats scissors (Rock crushes scissors) ✊ > ✂️
- Scissors beats paper (Scissors cuts paper) ✂️ > 📄
- Paper beats rock (Paper covers rock) 📄 > ✊
- Same shapes result in a tie 🤝

## Possible Outcomes 🎲
- Rock vs Paper: Paper wins 📄 > ✊
- Paper vs Paper: Tie 🤝
- Scissors vs Paper: Scissors wins ✂️ > 📄
- Rock vs Rock: Tie 🤝
- Paper vs Rock: Paper wins 📄 > ✊
- Scissors vs Rock: Rock wins ✊ > ✂️
- Rock vs Scissors: Rock wins ✊ > ✂️
- Paper vs Scissors: Scissors wins ✂️ > 📄
- Scissors vs Scissors: Tie 🤝

## Algorithm 🧠
1. The computer randomly chooses between Rock, Paper, and Scissors:
   - Number < 33: Rock ✊
   - 33 ≤ Number < 66: Paper 📄
   - Number ≥ 66: Scissors ✂️
2. User input is taken.
3. Compare user input with the computer's choice.
4. Determine the winner based on the rules.

## Dependencies 🛠️
- C++ Language
- 64 Bit Windows / Open Source Linux & its derivatives
- Open Source Programming Tools like G++/GCC, C++ IDE (Visual Studio Code or any other)

## How to Run 🚀
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/Rock-Paper-Scissors-New.git
2. Navigate to the project directory:
   ```sh
   cd Rock-Paper-Scissors-New
3. Compile the program using G++:
   ```sh
   g++ main.cpp -o rps_game
4. Run the game:
   ```sh
   ./rps_game

## Output

<img src="https://github.com/Geetika09/Rock-Paper-Scissors-New/blob/main/Images/rock-paper-scissor.gif" width="1080" height="600" />


## Future Enhancements 🌟
- Add a graphical user interface (GUI) for a more interactive experience.
- Implement multiplayer mode.
- Add a scoring system to track wins, losses, and ties over multiple rounds.
- Provide statistics and insights on the user's gameplay.

## Contributing 🤝
We welcome contributions! Feel free to fork the repository, make your changes, and submit a pull request. Let's make this project even better together!

## Acknowledgments 🙌
- Wikipedia for the detailed explanation of Rock Paper Scissors.
- The open-source community for the development tools and libraries.

Enjoy playing Rock Paper Scissors! 🎉
