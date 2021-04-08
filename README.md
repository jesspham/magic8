# magic8
Codecademy ComSci101 pathway - Magic 8 Ball project

import random

name = "Jessica"
question = "Will we go to the beach today?"
answer = ""

random_number = random.randint(1, 10)

#print(name + " asks: " + question)
#print("Magic 8-Ball's answer: " + answer)

if name == "":
  print("Question: " + question)
else:
  print(name + " asks: " + question)

if question == "":
  print("Sorry, please ask something.")
else:
  print("Magic 8-Ball's answer: " + answer)

if random_number == 1:
  print("Yes - definitely.")
elif random_number == 2:
  print("It is decidedly so.")
elif random_number == 3:
  print("Without a doubt.")
elif random_number == 4:
  print("Reply hazy, try again.")
elif random_number == 5:
  print("Ask again later.")
elif random_number == 6:
  print("Better not tell you now.")
elif random_number == 7:
  print("My sources say no.")
elif random_number == 8:
  print("Outlook not so good.")
elif random_number == 9:
  print("Very doubtful.")
elif random_number == 10:
  print("When pigs fly.")
else:
  print("Error")
