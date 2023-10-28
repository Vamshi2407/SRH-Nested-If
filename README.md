# SRH-Nested-If
Briefing of Sun Risers Hyderabad Team


## Below is the Nested Ifs code

print("Hello, Welcome to the Sun Risers Hyderabad (SRH)!!!!!!!!!!!! \n#Orange Army")
##print("What is your Name?")

name = input ("What is your Name? \n")
# Give Input as David Warner

if name == "David Warner" or name == "david warner":
 print ("Hello " + name + ", Thank you for Enrolling with us as a Captian")

 players = "David Warner, Jonny Bairstow, Kane Williamson, Bhuvaneswar Kumar, Heinrich Klassen"

 print (name + ", These are the SRH Players who are waiting for you, Captain! \n")

 print (players)

 print ("Can we know with which team the Match is today? \n")
 match = input ()
 ## Give input as RCB

 print ("Sounds good " + name + ", We will arrange " + players + " ready for the match with " + match + " today\n")
 print ("SRH will win the match against "+ match +" today !!!!!!\n")

 players_name = input(name + ", Who would you like to play in the team today? These are the players picked from the Auction!\n" + players +"\n")
 
 

 ## Setting the price of the Players
 if players_name == "David Warner":
   price = 16
   
 elif players_name == "Jonny Bairstow":
   price = 15
   
 elif players_name == "Kane Williamson":
   price = 14
   
 elif players_name == "Bhuvaneswar Kumar":
   price = 12
   
 elif players_name == "Heinrich Klassen":
   price = 15
   
 else:
   print ("Sorry, we don't have that players here.")
   price = 0
  exit ()
   
 print ("What is the cost of " + players_name + "?")
 print (price)
 print ("Is " + players_name + " ready to play the game?")
 print ("Yes," + players_name + " is ready to play the game against "+  match + " today\n")
 
else:
 print ("Hi " + name + ", We are waiting for our captain David Warner for team briefing. Please wait in line until our caps arrives")
 
