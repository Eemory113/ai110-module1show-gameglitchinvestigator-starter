# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- I expeted the game to reset after guessing the correct number but new game does not function at all, the messege instructing me to reset the game does not go away, I also noticed on the debug log the only numbers that show up are outside the scope of the game, in my case "1111" while inputs that should be in the debug log does not log at all unless i input twice. Inputting a number above 100 should give me a error and a messege instead it lets me input any number i want, it should give me a error. changing the diffculty does not change the target number, i expected it to change when changing the diffculy 

---

## 2. How did you use AI as a teammate?

The AI suggested for the new game bug that i change the logic for new game unfortunatly my copilot was running into issues and i had to close VS code then close that chat tab so i lost the exact suggestion.
For the debug commands the AI simply suggested that the debug extender be moved to the bottom of the script, applying this fix made it work, now each number logs the moment i pressed it, it told me it was a issue with streamlet and how it worked.
I Tested both fixes by restarting the app itself then running it, for each error i got for the new game bug from the AI's fixes i pasted the error into chat and asked the AI what the issue could of been, it eventully managed to get it correct after two revisions.
---

## 3. Debugging and testing your fixes

- I decided it was fixed after running tests in the app at least five times at a miniumum
- for the new game bug, I simply inputted the right number then hit "new game" if no errors popped up then I simply won again then tested to see if it still worked. 
  and what it showed you about your code.
- It did a fairly good job at explaining why it fixed certian things, i appracated that it explained that some issues such as the debug issue was a streamlit specfic issue.

---

## 4. What did you learn about Streamlit and state?

- In your own words, explain why the secret number kept changing in the original app.
- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?
- What change did you make that finally gave the game a stable secret number?

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code.
