# 🎮 Tic Tac Toe Game (Java Swing)

A simple yet fun **Tic Tac Toe** (X-O) game built with **Java Swing**.  
This GUI-based game allows two players to take turns and play the classic 3x3 grid game.

---

## 📌 Features

✅ 3x3 interactive grid using buttons  
✅ Player turns alternate automatically  
✅ Winner detection (Rows, Columns, Diagonals)  
✅ Draw detection when the grid is full  
✅ Pop-up message box announcing the winner or tie  
✅ Auto-reset after each round

---

## 🧱 Technologies Used

- Java
- Java Swing (`JFrame`, `JButton`, `JOptionPane`)
- Java AWT (`Font`, `GridLayout`, `ActionEvent`)

---

## 🎮 How to Play

1. Player **X** starts first.
2. Players take turns clicking on empty cells.
3. The first player to get **three in a row** (horizontally, vertically, or diagonally) wins.
4. If all cells are filled without a winner, it's a **draw**.
5. After a win or draw, the board **resets automatically**.

---

## 🚀 How to Run

1. Save the file as `TicTacToe.java`
2. Open terminal / command prompt and compile:
   ```bash
   javac TicTacToe.java
3. Run the game:
java TicTacToe

🧑‍💻 Code Highlights
JButton[][] buttons: Holds the 3x3 grid buttons.
actionPerformed: Handles user input and turn-based logic.
checkForWinner(): Checks all possible winning combinations.
resetBoard(): Clears the board after a game ends.
JOptionPane: Used to display the result to the players.

🎯 Future Enhancements (Optional)
Add score tracking for Player X and O
Add option to choose player names
Add game mode vs Computer (AI)
Add restart or exit button in the UI
Responsive GUI design with themes
