# 1) Random Password Generator 🔐

Hey there! This is my first mini project - a simple password generator that I built while learning Python. Nothing fancy, but it gets the job done!

## What it does

Basically, it spits out a random 12-character password every time you run it. The passwords include letters (both upper and lowercase), numbers, and some special characters to make them pretty secure.

## How to use it

Just download the file and run:
```bash
python password_generator.py
```

That's it! You'll get something like:
```
your password is: K7#mP9$qL2@x
```

## The code breakdown

It's pretty straightforward:
- I set the password length to 12 (seemed like a good balance)
- Grabbed all possible characters using Python's string module
- Used a simple loop to randomly pick characters and build the password
- Print it out

## Want to customize it?

Feel free to mess around with:
- `pass_len` - change this number to make longer/shorter passwords
- `char_choices` - modify what types of characters to include

## Stuff I learned

This was actually my first time using:
- The `string` module (pretty cool that Python has all these character sets built-in)
- `random.choice()` function
- Basic string concatenation in a loop

## Known issues

Yeah, I know using `random` isn't the most secure for real applications. If you're planning to use this for anything important, you should probably use Python's `secrets` module instead. But for learning purposes and generating quick passwords, this works fine!

## Future improvements

Maybe I'll add:
- Command line arguments for custom length
- Option to exclude certain characters
- Multiple password generation at once
- GUI interface (when I learn tkinter)

## Installation

No special setup needed! Just make sure you have Python installed and run the script.

```bash
git clone https://github.com/yourusername/random_password_generator.git
cd random_password_generator
python password_generator.py
```

---

This is part of my journey learning Python. Feedback welcome! 


# 2) Guess the Number

Just a simple number guessing game I threw together while learning Python. Nothing fancy, but it works!

## What it does

The computer picks a random number between 1 and 100, and you try to guess it. That's it. You get hints along the way to help you out.

## How to run it

Make sure you have Python installed, then just run:

```bash
python guess_the_number.py
```

## Playing the game

- Enter your guess when prompted
- If you're too low, it'll tell you to guess higher
- If you're too high, it'll tell you to guess lower  
- Keep going until you get it right
- To quit, just enter something that's not a number

## Sample run

```
Guess the Target or Quit: 50
take a bigger guess... your number is too small
Guess the Target or Quit: 80  
take a smaller guess... your number is too bigger
Guess the Target or Quit: 65
take a bigger guess... your number is too small
Guess the Target or Quit: 72
CORRECT GUESS!!
---GAME OVER---
```

## Known issues

Yeah, there's a small bug with the quit function - working on fixing that. The game logic itself works fine though.

## Why I made this

Started learning Python recently and wanted to practice basic stuff like loops, conditionals, and user input. This seemed like a good first project to get my feet wet.

Feel free to fork it or suggest improvements if you want. Still figuring out this whole coding thing!

*P.S. - Yes, I know there are probably a million password generators out there, but building your own stuff is half the fun of programming, right?*
