print("What generation are you a part of?")
yearBorn = int(input("What is a year when you born? - "))
if yearBorn <= 1946:
  print("Oh, you are Traditionalist!")
elif yearBorn >= 1947 and yearBorn <= 1964:
  print("Oh, you are from Baby Boomers!")
elif yearBorn >= 1965 and yearBorn <= 1981:
  print("Aah, generations X!")
elif yearBorn >= 1982 and yearBorn <= 1995:
  print("We call you Millenials ")
elif yearBorn >= 1996 and yearBorn <= 2015:
  print("Fucking generation Z!")
else:
  print("I saw on TV, they call you Indigo children")
