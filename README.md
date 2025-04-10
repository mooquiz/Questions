# Questions

Questions are stored in a repository here so that I don't have to write a whole interface for adding and ediing questions, yet. In the future there will be a back end which serves up on the current questions to the app but this will get us going.

There can be as many or few questions as you like. Each question may have as many or as few answers as you like. The number on the
line after the question points to which answer is correct.

If the format is incorrect, behaviour is currently undefined. It will probably fail to load the day's questions and crash when the day turns over. In the future I will build validation to esnsure that doesn't happen. 

## How to add questions

1. Go to https://github.com/mooquiz/Questions

2. Press `+` button:

   ![Screenshot 2025-04-10 9 14 20 AM](https://github.com/user-attachments/assets/55bc7925-5f12-4246-8574-2e68cb84e1a1)

3. Select **Create New File**

   ![Screenshot 2025-04-10 9 17 37 AM](https://github.com/user-attachments/assets/ba9de7a4-62f9-4ef1-8a99-beb4d5954c4b)


4. Add a file named after the date you wish the questions to appear, in the format `YYYYMMDD.txt`
   
5. The questions are in the the current format:
  ```
  Quiz Title

  Question One
  1
  Correct Answer
  Incorrect Answer
  Incorrect Answer 2
  Incorrect Answer 3

  Question Two
  4
  Incorrect Answer
  Incorrect Answer 2
  Incorrect Answer 3
  Correct Answer
  ````

6. Press **Commit Changes...**
   
7. In the popup which appears, press **Commit Changes...**
