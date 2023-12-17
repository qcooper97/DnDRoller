#importing random to allow us to grab random numbers with random. for things like rolling a die
import random

#my list of skills for my DnD character. I made each of them a variable with a value so that when we "roll" the dice we know which number to add to our outcome. These can also be changed as my character levels up and the code still works
strength = 6
dexterity = 4
con = 7
intelligence = 4
wisdom = 8
charisma = 11
acrobatics = 0
animalHandling = 1
arcana = 0
athletics = 2
deception = 4
history = 0
insight = 4
intimidation = 7
investigation = 3
medicine = 1
nature = 0
perception = 1
performance = 4
persuasion = 4
religion = 3
sleightOfHand = 0
stealth = 0
survival = 1
initiative = 0

#this while statement lets us create a loop to START the program since 1 will always equal 1
while 1 == 1:
  #this is our input to check if we are rolling with advantage or disadvantage
  adDisadCheck = input("Advantage or disadvantage? Type a + for advantage or a - for disadvantage. Leave blank for a straight roll: ")
  #rollA and rollB are our 2 dice. Both will always roll, in case we need 2 for an advantaged or disadvantaged roll, but we will always default to the first one if we are doing a "straight" roll. That is why roll = rollA until it is modified later in the body, if conditions are met. 
  rollA = random.randrange(1, 20)
  rollB = random.randrange(1, 20)
  roll = rollA
  #this straightRollCheck gives us a default. This value is always 0 UNLESS we are rolling advantage or disadvantage where it will change to 1. This value of this variable will come into effect later. 
  straightRollCheck = 0
  #if we put + in the input to roll with advantage, we check both dice rolls and change the value of "roll" to the higher of the 2 since thats what advantage is. 
  if "+" in adDisadCheck:
      #here is where we changed the value of that straightRollCheck variable IF we are rolling with advantage or disadvantage. Like I said, this will matter later but it makes sense to change that value here. 
      straightRollCheck = 1
      if rollA > rollB:
        roll = rollA
      if rollA < rollB:
        roll = rollB
      if rollA == rollB:
        roll = rollA
  #this does the opposite for disadvantage rolls
  elif "-" in adDisadCheck:
      straightRollCheck = 1
      if rollA > rollB:
        roll = rollB
      if rollA < rollB:
        roll = rollA
      if rollA == rollB:
        roll = rollA
  #this clarifies that if both rollA and rollB are the same number, just use the first one. 
  else:
      roll = rollA
  #skillCheck asks us what skill we are rolling with, or in easier terms, which number we are adding to our dice roll for our total. 
  skillCheck = input("What skill are you rolling with?: ")
  #this is where typing in your skill lets the program grab the skill value. The code is the same for 200 lines, just with different skills as the conditions. 
  if "strength" in skillCheck:
      #here that default for the advantage or disadvantage comes in. If we rolled with advantage or disadvantage, straightRollCheck's value changed from 0 to 1. I wanted to add this so that the program would tell you both of your rolls, just because I wanted to know. 
      if straightRollCheck == 1:
        #this prints out what your 2 dice rolls were
        print("You rolled", +rollA , "and", +rollB)
      #if we just do a straight roll with no advantage or disadvantage, there is no reason to print both rolls since in real life you wouldn't roll the 2nd one. This is the baseline. I put this conditional statement in here so that if your roll included 2 dice, you saw both outcomes, but if you did a straight roll, you only see the one. 
      if straightRollCheck == 0:
        print("You rolled", +roll)
      #this is just added to verify with your stat sheet if there is question. the + strength allows us to always insert whatever value this variable has, even if it is changed later. 
      print("Your strength modifier is", +strength)
      #this changes the value of the variable "roll" to whatever it already is, the dice outcome, PLUS the value of the variable listed. In this instance, strength. 
      roll += strength
      #break lets us skip the rest of the body to save time and processing power. If the condition of strength is met in the input, none of the other options will apply so there is no need to check the other conditions. Break lets us skip the rest and push right to the end of the body for our final output. 
      break
  elif "dexterity" in skillCheck:
      if straightRollCheck == 1:
        print("You rolled", +rollA , "and", +rollB)
      if straightRollCheck == 0:
        print("You rolled", +roll)
      print("Your dexterity modifier is", +dexterity)
      roll += dexterity
      break
  elif "charisma" in skillCheck:
      if straightRollCheck == 1:
        print("You rolled", +rollA , "and", +rollB)
      if straightRollCheck == 0:
        print("You rolled", +roll)
      print("Your charisma modifier is", +charisma)
      roll += charisma
      break
  elif "constitution" in skillCheck:
      if straightRollCheck == 1:
        print("You rolled", +rollA , "and", +rollB)
      if straightRollCheck == 0:
        print("You rolled", +roll)
      print("Your constitution modifier is", +con)
      roll += con
      break
  elif "intelligence" in skillCheck:
      if straightRollCheck == 1:
        print("You rolled", +rollA , "and", +rollB)
      if straightRollCheck == 0:
        print("You rolled", +roll)
      print("Your intelligence modifier is", +intelligence)
      roll += intelligence
      break
  elif "wisdom" in skillCheck:
      if straightRollCheck == 1:
        print("You rolled", +rollA , "and", +rollB)
      if straightRollCheck == 0:
        print("You rolled", +roll)
      print("Your wisdom modifier is", +wisdom)
      roll += wisdom
      break
  elif "acrobatics" in skillCheck:
      if straightRollCheck == 1:
        print("You rolled", +rollA , "and", +rollB)
      if straightRollCheck == 0:
        print("You rolled", +roll)
      print("Your acrobatics modifier is", +acrobatics)
      roll += acrobatics
      break
  elif "animal handling" in skillCheck:
      if straightRollCheck == 1:
        print("You rolled", +rollA , "and", +rollB)
      if straightRollCheck == 0:
        print("You rolled", +roll)
      print("Your animal handling modifier is", +animalHandling)
      roll += animalHandling
      break
  elif "arcana" in skillCheck:
      if straightRollCheck == 1:
        print("You rolled", +rollA , "and", +rollB)
      if straightRollCheck == 0:
        print("You rolled", +roll)
      print("Your arcana modifier is", +arcana)
      roll += arcana
      break
  elif "athletics" in skillCheck:
      if straightRollCheck == 1:
        print("You rolled", +rollA , "and", +rollB)
      if straightRollCheck == 0:
        print("You rolled", +roll)
      print("Your athletics modifier is", +athletics)
      roll += athletics
      break
  elif "deception" in skillCheck:
      if straightRollCheck == 1:
        print("You rolled", +rollA , "and", +rollB)
      if straightRollCheck == 0:
        print("You rolled", +roll)
      print("Your deception modifier is", +deception)
      roll += deception
      break
  elif "history" in skillCheck:
      if straightRollCheck == 1:
        print("You rolled", +rollA , "and", +rollB)
      if straightRollCheck == 0:
        print("You rolled", +roll)
      print("Your history modifier is", +history)
      roll += history
      break
  elif "insight" in skillCheck:
      if straightRollCheck == 1:
        print("You rolled", +rollA , "and", +rollB)
      if straightRollCheck == 0:
        print("You rolled", +roll)
      print("Your insight modifier is", +insight)
      roll += insight
      break
  elif "intimidation" in skillCheck:
      if straightRollCheck == 1:
        print("You rolled", +rollA , "and", +rollB)
      if straightRollCheck == 0:
        print("You rolled", +roll)
      print("Your intimidation modifier is", +intimidation)
      roll += intimidation
      break
  elif "investigation" in skillCheck:
      if straightRollCheck == 1:
        print("You rolled", +rollA , "and", +rollB)
      if straightRollCheck == 0:
        print("You rolled", +roll)
      print("Your investigation modifier is", +investigation)
      roll += investigation
      break
  elif "medicine" in skillCheck:
      if straightRollCheck == 1:
        print("You rolled", +rollA , "and", +rollB)
      if straightRollCheck == 0:
        print("You rolled", +roll)
      print("Your medicine modifier is", +medicine)
      roll += medicine
      break
  elif "nature" in skillCheck:
      if straightRollCheck == 1:
        print("You rolled", +rollA , "and", +rollB)
      if straightRollCheck == 0:
        print("You rolled", +roll)
      print("Your nature modifier is", +nature)
      roll += nature
      break
  elif "perception" in skillCheck:
      if straightRollCheck == 1:
        print("You rolled", +rollA , "and", +rollB)
      if straightRollCheck == 0:
        print("You rolled", +roll)
      print("Your perception modifier is", +perception)
      roll += perception
      break
  elif "performance" in skillCheck:
      if straightRollCheck == 1:
        print("You rolled", +rollA , "and", +rollB)
      if straightRollCheck == 0:
        print("You rolled", +roll)
      print("Your performance modifier is", +performance)
      roll += performance
      break
  elif "persuasion" in skillCheck:
      if straightRollCheck == 1:
        print("You rolled", +rollA , "and", +rollB)
      if straightRollCheck == 0:
        print("You rolled", +roll)
      print("Your persuasion modifier is", +persuasion)
      roll += persuasion
      break
  elif "religion" in skillCheck:
      if straightRollCheck == 1:
        print("You rolled", +rollA , "and", +rollB)
      if straightRollCheck == 0:
        print("You rolled", +roll)
      print("Your religion modifier is", +religion)
      roll += religion
      break
  elif "sleight of hand" in skillCheck:
      if straightRollCheck == 1:
        print("You rolled", +rollA , "and", +rollB)
      if straightRollCheck == 0:
        print("You rolled", +roll)
      print("Your sleight of hand modifier is", +sleightOfHand)
      roll += sleightOfHand
      break
  elif "stealth" in skillCheck:
      if straightRollCheck == 1:
        print("You rolled", +rollA , "and", +rollB)
      if straightRollCheck == 0:
        print("You rolled", +roll)
      print("Your stealth modifier is", +stealth)
      roll += stealth
      break
  elif "survival" in skillCheck:
      if straightRollCheck == 1:
        print("You rolled", +rollA , "and", +rollB)
      if straightRollCheck == 0:
        print("You rolled", +roll)
      print("Your survival modifier is", +survival)
      roll += survival
      break
  elif "initiative" in skillCheck:
      if straightRollCheck == 1:
        print("You rolled", +rollA , "and", +rollB)
      if straightRollCheck == 0:
        print("You rolled", +roll)
      print("Your initiative modifier is", +initiative)
      roll += initiative
      break
  #else is if, by some chance, we misspell our skill variable name or just happen to not be rolling with a skill stat modifier. It will still print out what the roll was so you can add your skill stat modifier manually. 
  else:
    print("Oops! That isn't a skill on your sheet. Your roll was", +roll)

#this final line does the math for us and takes whatever the dice roll was and adds the selected modifier for the total value of the roll
print("Your roll is", +roll)




