<p align="center">
 <img src="https://github.com/user-attachments/assets/784c1a3e-f470-4234-ac8f-d98ff29eff9c" alt="Python Logo" width=20%/>
 </p>

 <h1>"Magic" 8-Ball</h1>
 Using Python to make a "magic" 8-ball to give you 8 random possible answers to your question.   
 
 <h2>Code</h2>
 
```python
import random
question = input("Ask Magic 8 Ball a question: ")
answer = random.randint(1, 9)
if answer == 1:
    print("It is certain")
elif answer == 2:
    print("Outlook good")
elif answer == 3:
    print("You may rely on it")
elif answer == 4:
    print("Ask again later")
elif answer == 5:
    print("Concentrate and ask again")
elif answer == 6:
    print("Reply hazy, try again")
elif answer == 7:
    print("My reply is no")
elif answer == 8:
    print("That's not a question")
elif answer == 9:
    print("You are in imminent danger of spontaneous human combustion (3..2..1)")
print("The end")
```
 
 <h2>Example Gameplay</h2>

- Initially, you will be prompted ask a question. There are 9 possible answers to your question that can be given. Using the import random module, the program picks a number from 1 to 9 and then has a pre-assigned answer corresponding to each number. 

- You can keep re-running the program to test out getting different answers.  

![image](https://github.com/user-attachments/assets/974e727c-41f1-487a-a2c9-f3760dcf5aec)

- To see other projects click here: https://github.com/brandenoz. 
