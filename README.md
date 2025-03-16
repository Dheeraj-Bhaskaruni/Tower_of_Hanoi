# Towers of Hanoi (Python CLI Game)

This is a simple command-line game implementation of the classic **Towers of Hanoi** puzzle using Python. It uses a custom `Stack` class and walks you through the puzzle interactively. Great for anyone learning recursion, stack operations, or just looking to challenge themselves with a brain-teaser.

## How to Play

- The goal is to move all disks from the **Left** stack to the **Right** stack.
- You can only move **one disk at a time**, and you can never place a **larger disk on top of a smaller one**.
- The **Middle** stack is there to help — use it wisely.

## Getting Started

1. Make sure you have Python 3 installed.
2. Download or clone this repo.
3. Ensure your project folder contains both:
   - `script.py` → your main game file
   - `stack.py` → contains the `Stack` class

4. Open a terminal and run the game like this:

```bash
python3 script.py
```

_(Replace `script.py` with whatever your main file is named.)_

## Game Example

```text
Let's play Towers of Hanoi!!
How many disks do you want to play with?
3

The fastest you can solve this game is in 7 moves.

Enter L for Left  
Enter M for Middle  
Enter R for Right

Which stack do you want to move from?  
L  
Which stack do you want to move to?  
R
```

## Project Structure

```
your-folder/
├── script.py       # Main game logic
├── stack.py        # Stack class
├── node.py        # Node class for Stack
└── README.md       # This file
```

## Final Notes

- You’ll see your moves printed after each step.
- The game ends when all disks are successfully moved to the Right stack.
- It also tells you how many moves you took vs. the optimal number.

Try to solve it in the minimum number of moves (2^n - 1). It's a fun challenge and a good way to get better at thinking recursively.

---
