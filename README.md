# Your life in weeks! Tim Urban Article - https://waitbutwhy.com/2014/05/life-weeks.html

This project is based on an article by Tim Urban laying out how many weeks someone has if they life until 90. 

Initially, you think that this graph would have minuscule little dots, but no. 
You can really see all the dots.


age = input("What is your age?\n")
ageInt = int(age)
daysLeft = 32850 - (ageInt * 365)
weeksLeft = 4680 - (ageInt * 52)
monthsLeft = 1080 - (ageInt * 12)
yearsLeft = 90 - ageInt

print(f"You have {daysLeft} days, {weeksLeft} weeks, {monthsLeft} months, and {yearsLeft} years left.")

