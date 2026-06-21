# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
- The program starts by opening a new tab in my browser and displaying the game. At first glance, the game has a developer debug info with a dropdown button, which displays a secret guess number, how many attempts I have tried, the score, the difficulty level, and a list with all the numbers I have entered. On the left side, there is the setting of the game to select the level of difficulty with the range of numbers allowed.
- List at least two concrete bugs you noticed at the start  
  (for example: "the hints were backwards").
  - After running the program, I discovered that the program displays the secret guess number while if entered a wrong number, it will indicate hint backwards. I also discovered the game refuses to start a new game either if the user wins or loses.

**Bug Reproduction Log**

Document at least 3 bugs you found. Add rows as needed.

| Input | Expected Behavior | Actual Behavior | Console Output / Error |
|-------|-------------------|-----------------|------------------------|
|Guess 99| "Go Higher" hint    Go lower          None
| | | | |
| | | | |

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
- The AI tool that i used was claude code
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
- After looking for the problem I had figured out where the bugs I had discovered. The AI suggested to modify the code to reflect the correct hint indicator.
- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).


---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
- To test the program actually behave the way that I had expected, I reran the program and then tested out the behavior that I had previously recorded, such as the hint backwards.
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
  - To test the code, I ran the Streamlit and tested if the program can start a new game and if a wrong answer would display the correct hint.
- Did AI help you design or understand any tests? How?

---

## 4. What did you learn about Streamlit and state?

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?
- I would explain that streamlit behave like a website that forgets everything each time you click a button. 

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
- One habit that I would want to reuse in future labs is how to first start to understand the problem before starting prompting. Then have the AI explain the parts that are confusing, before making changes to the code.
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task? 
- I now know how to better establish a plan before starting prompting and coding my program.
- In one or two sentences, describe how this project changed the way you think about AI generated code.
- I discovered how to be more efficient using prompting.
