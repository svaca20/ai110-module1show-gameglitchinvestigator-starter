# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
The first time I ran the game it looked like a solid game that had everything it needed to get the game started. Right from the start I did notice the game to be a little confusing. Was not sure if I had to press enter on my keyboard and press the submit button afterwards. 
- List at least two concrete bugs you noticed at the start  
  (for example: "the secret number kept changing" or "the hints were backwards").
Bug 1: Hints worked backwards. When guess was below secret, the hint indicated to go lower and vice versa. 
Bug 2: When difficulty is changed, range changes accordingly, but the blue box indicating to guess between a range does not match with difficulty range. 

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?

The tools I used was Copilot with Claude.

- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).

Both AI suggestions I recieved were correct. When I tried to fix the hints and macthing the difficulty to the blue box, I asked AI to find where the errors lie and help me figure out how to fix the issue. Both times the suggestions were good and I checked the results by running the game again with the updates. 

- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).

This time around I did not recieve a misleading suggestion. Though I did not attempt to refactor due to not being aware of what that entails or what it is. Will look into it. 

---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?

I decided how a bug was really fixed by saving changes and running the game again. 

- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.

One test I ran was by saving changes and running the game again.

- Did AI help you design or understand any tests? How?

Not necessarily. Looking back I think I did not test properly. I only saved changes and ran the game to check. 
---

## 4. What did you learn about Streamlit and state?

- In your own words, explain why the secret number kept changing in the original app.

The secret number did not continue to change for me. 

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?

Reruns are consistently applied whenever we interact with an app. It restarts back from the topline of our code.

Session state is a way of keeping necessary values intact without being erased by reruns. 


- What change did you make that finally gave the game a stable secret number?

It has been stable. 
---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.

  Testing and refactoring code to ensure code is trabslating directly to what we intend to do. 

- What is one thing you would do differently next time you work with AI on a coding task?

Give it more contect and more information right from the start. 

- In one or two sentences, describe how this project changed the way you think about AI generated code.

It made me realize that AI can do more than just answer questions. 
