# Math Quiz Game (C++)

A console-based arithmetic quiz game written in C++. Choose how many questions you want, the difficulty, and the operation type, then answer and get instant feedback with a final pass/fail result.

## Features
- Choose the number of questions
- 4 difficulty levels: **Easy** (1–20), **Medium** (20–60), **Hard** (60–150), **Mix** (random level per question)
- 5 operation types: **Addition**, **Subtraction**, **Multiplication**, **Division**, **Mix** (random operation per question)
- Instant feedback after each question (the correct answer is shown if you're wrong)
- Console color feedback: green for correct, red for wrong
- Final summary: total questions, level, operation, correct and wrong answers
- Pass/Fail result (pass = at least half of the answers are correct)
- Play again without restarting the program

## Tech Stack
- Language: C++
- IDE: Visual Studio (`Project2 Course5.slnx`)
- Libraries: standard library only (`iostream`, `cstdlib`, `ctime`, `string`, `algorithm`)

## Getting Started

### Prerequisites
- Windows (the game uses `system("cls")` and `system("color ...")`)
- Visual Studio 2026 or any version that supports `.slnx`

### Build & Run
```bash
git clone https://github.com/hasanhlala/Project2-Course5.git
```
1. Open `Project2 Course5.slnx` in Visual Studio.
2. Press `Ctrl+F5` to run without debugging.

## How to Play
1. Enter the number of questions.
2. Pick a level: `[1] Easy, [2] Med, [3] Hard, [4] Mix`.
3. Pick an operation: `[1] Add, [2] Sub, [3] Mul, [4] Div, [5] Mix`.
4. Answer each question when prompted.
5. See your final result, then choose whether to play again (`Y/N`).

### Example
```
Question [1/3]

12
7 +
_______________
19
Rigth Answer :-)
```

## Project Structure
```
Project2-Course5/
├── Project2 Course5/       # C++ source code
├── Project2 Course5.slnx   # Visual Studio solution
├── .gitignore
└── .gitattributes
```

## Concepts Practiced
- `enum` and `struct` for organizing game data
- Functions and pass-by-reference
- Random number generation (`rand`, `srand`)
- `switch` statements and input validation loops

## Author
[hasanhlala](https://github.com/hasanhlala)
