# 🎮 Game Glitch Investigator: The Impossible Guesser

## 🚨 The Situation

You asked an AI to build a simple "Number Guessing Game" using Streamlit.
It wrote the code, ran away, and now the game is unplayable. 

- You can't win.
- The hints lie to you.
- The secret number seems to have commitment issues.

## 🛠️ Setup

1. Install dependencies: `pip install -r requirements.txt`
2. Run the broken app: `python -m streamlit run app.py`

## 🕵️‍♂️ Your Mission

1. **Play the game.** Open the "Developer Debug Info" tab in the app to see the secret number. Try to win.
2. **Find the State Bug.** Why does the secret number change every time you click "Submit"? Ask ChatGPT: *"How do I keep a variable from resetting in Streamlit when I click a button?"*
3. **Fix the Logic.** The hints ("Higher/Lower") are wrong. Fix them.
4. **Refactor & Test.** - Move the logic into `logic_utils.py`.
   - Run `pytest` in your terminal.
   - Keep fixing until all tests pass!

## 📝 Document Your Experience

- [ ] Describe the game's purpose.

The purpose of the game is to guess the secret number that is between a range based on difficulty. 
- [ ] Detail which bugs you found.

Bug 1: Hints worked backwards. When guess was below secret, the hint indicated to go lower and vice versa. 
Bug 2: When difficulty is changed, range changes accordingly, but the blue box indicating to guess between a range does not match with difficulty range. 
The bugs that were found are: 
- [ ] Explain what fixes you applied.

Fixed the hints to accurately represent direction of guess. Also ensured the blue box matched the the range based on the difficulty choosen. 

## 📸 Demo

- [ ] [Insert a screenshot of your fixed, winning game here]

![alt text](<Screenshot 2026-03-15 at 2.44.00 PM-1.png>) 




## 🚀 Stretch Features

- [ ] [If you choose to complete Challenge 4, insert a screenshot of your Enhanced Game UI here]
