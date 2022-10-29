# Magic-8-Ball
# next ideas make the name an input and make ramdom questions with random answers about your future ex: will i win the lottery?
# 
import random

name = ""
question = "Yes" or "Not"
answer = ""

random_number = random.randint(1, 9)
print(random_number)
if random_number == 1:
  answer = "Yes - definitely"
elif random_number == 2:
  answer = "It is decidedly so"
elif random_number == 3:
  answer = "Without a doubt"
elif random_number == 4:
  answer = "Reply hazy, try again"
elif random_number == 5:
  answer = "Ask again later"
elif random_number == 6:
  answer = "Better not tell you now"
elif random_number == 7:
  answer = "My sources says no"
elif random_number == 8:
  answer = "Outlook not so good"
elif random_number == 9:
  answer = "Very doubtful"
else:
  answer = "Error"
print(name + " asks: " + question)
print("Magic 8-Ball's answer: " + answer)
