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

- [The games purpose is to be a guessing game where the player has to guess a number between 1 to 100] Describe the game's purpose.
- [I expeted the game to reset after guessing the correct number but new game does not function at all, the messege instructing me to reset the game does not go away, I also noticed on the debug log the only numbers that show up are outside the scope of the game, in my case "1111" while inputs that should be in the debug log does not log at all unless i input twice. Inputting a number above 100 should give me a error and a messege instead it lets me input any number i want, it should give me a error. changing the diffculty does not change the target number, i expected it to change when changing the diffculy ] Detail which bugs you found.
- [ I applied the AI suggested fixes for the new game glitch but had to ask the AI to fix some minor mistakes it made for that, for the debug output i asked it to fix it that and it fixed it no issue the first time] Explain what fixes you applied.

## 📸 Demo

- [ ] [Insert a screenshot of your fixed, winning game here]

## 🚀 Stretch Features

- [ ] [If you choose to complete Challenge 4, insert a screenshot of your Enhanced Game UI here]
