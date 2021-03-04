## Welcome to my AWS re/Start GitHub Page

Welcome to my first AWS re/Start GitHub page.

This is a portfolio of my first foray in Python as part of the AWS re/Start course.

### Python

Below are some examples of the Python I have coded using the hands on labs during this course:

```markdown
#FunWIthStrings.py

first_str = "I love dogs"

second_Str = " and cats"

newstr = first_str + second_str

print(newStr) 

```
```markdown
#HelloWorld.py
import json

filename = 'userName.json'
name = ''
#check for a history file
try:
    with open(filename, 'r') as r:
        #load the user's name from the history file
        name = json.load(r)
except IOError:
        print("First-time login")

# If the user was found in the history file, welcome them back
if name != "":
    print("Welcome back, " + name + "!")
else:
    # If the history file doesn't exist, ask the user for their name
    name = input("Hello! What's your name? ")
    print("Welcome, " + name + "!")

# Save the user's name to the history file
try:
    with open(filename, 'w') as f:
        json.dump(name, f)
except IOError:
    print("There was a problem writing to the history file.")
```


### Some quiz results from my time on the course
[Reading and Writing CSV Files in Python](https://realpython.com/quizzes/python-csv/results/?t=eyJjIjo3LCJuIjo3LCJxIjozNCwic2lnIjoiempFM1k1MV8kZE5XUEg2IX4oaXNDUE9gdXc1WXVadyNSaXtnezFuKyIsInQiOjc2LCJ2IjozfQ==)


### My Background

I have always been curious about new technology - furthering my understanding of these and constantly enhancing my skill set were key when undertaking this course.  I don't come from a traditional tech background.  I have a background based in media, having previously worked in broadcast TV production in London, followed by a stint in post-Production - onboarding media to aircraft.  Perhaps most notably, I spent 3 and half years working on 7 series of the BAFTA winning format 'Taskmaster', progressing into a senior Researcher role.  I'm now looking to transform my career into something with longevity that is constantly challenging and makes the most of my experiences working as an integral team member.



### Contact

I'm available now to discuss entry level roles on stevie.saponja@gmail.com

My full job history, experience and skills can be explored on my LinkedIn profile at: [HERE](https://www.linkedin.com/in/stevie-saponja-4161531a/)

I look forward to hearing from you!
