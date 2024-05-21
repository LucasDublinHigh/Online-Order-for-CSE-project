total = 0.00
sandwich = 0.00
salad = 0.00
pizza = 0.00
chicken = 0.00

selected_a_sandwich = True
selected_a_salad = True
selected_a_pizza = True
selected_chicken = True

customer_order = []

chicken = input("Its Lunch Time!!! What would you like to eat\n1. .... Chicken Sandwich\n2. .... Chicken Tacos\n3. .... Chicken Waffles\n4. .... Spicy Chicken Fillet Sandwich\n5. .... Popcorn Chicken")
if (chicken == "Chicken Sandwich"):
  customer_order.append("Chicken Sandwich")
  total += 0.00
  print("Cool! You chose a chicken sandwich!")
elif (chicken == "Chicken Tacos"):
  customer_order.append("Chicken Tacos")
  total += 0.00
  print("Nice you got a chicken taco!")
elif (chicken == "Chicken Waffles"):
  customer_order.append("Chicken Waffles")
  total += 0.00
  print("Sick! You got chicken waffles")
elif (chicken == "Spicy Chicken Fillet Sandwich"):
  customer_order.append("Spicy Chicken Fillet Sandwich")
  total += 0.00
  print("Cool, you ordered a Spicy Chicken Fillet Sandwich")
elif (chicken == "Popcorn Chicken"):
  customer_order.append("Popcorn Chicken")
  total += 0.00
  print("Wonderfull, you ordered Popcorn Chicken")
else:
  print("Dang, You didn't order any Chicken???")
  customer_order.append("No chicken")
  selected_chicken == False
salad = input("Oy, Would you like some salad or fruit as well?")
if (salad == "sure"):
  salad = input("Would you like\n1. .... Ceasar Salad\n2. .... Vegetable variety\n3. .... Assorted fresh fruit\n4. .... Apple Juice")
  if (salad == "Ceasar Salad"):
    customer_order.append("Ceasar Salad")
    total += 0.00
    print("Nice you got a Ceasar Salad")
  elif (salad == "Vegetable variety"):
    customer_order.append("Vegetable variety")
    total += 0.00
    print("Nice you got the Vegtable variety!")
  elif (salad == "Assorted fresh fruit"):
    customer_order.append("Assorted fresh fruit")
    total += 0.00
    print("Alright! you got some Assorted fresh fruit!")
  elif (salad == "Apple Juice"):
    customer_order.append("Apple Juice")
    total += 0.00
    print("Cool You ordered Apple Juice")
  else:
    print("Dang You didn't order any salad nor fruit????")
    customer_order.append("No salad/fruit")
    selected_a_salad = False
pizza = input("Hey you want pizza?")
if (pizza == "sure"):
    pizza = input("Alright would you like\n1. .... Peperoni Pizza\n2. .... Cheese Pizza\n3. .... Vegetarian Pizza")
    if (pizza == "Peperoni Pizza"):
      customer_order.append("Peperoni Pizza")
      total += 0.00
      print("Nice, you got Peperoni Pizza!")
    elif (pizza == "Cheese Pizza"):
      customer_order.append("Cheese Pizza")
      total += 0.00
      print("Alright! you ordered a cheese pizza!")
    elif (pizza == "Vegetarian Pizza"):
      customer_order.append("Vegetarian Pizza")
      total += 0.00
      print("Wonderful, you got a vegetarian pizza!")
    else:
      print("Dang... No pizza???")
      customer_order.append("No pizza")
      selected_a_pizza = False
sandwich = input("Ok, you want a sandwich???")
if (sandwich == "sure"):
  sandwich = input("What sandwich would you like to eat??? We only have one sandwich.\n1. .... Turkey and Cheese Hogie Sandwich")
  if (sandwich == "Turkey and Cheese Hogie Sandwich"):
    customer_order.append("Turkey and Cheese Hogie Sandwich")
    total += 0.00
    print("Cool you ordered a Turkey and Cheese Hogie Sandwich")
  elif (sandwich == "nope"):
    customer_order.append("nope")
    total += 0.00
    print("No Turkey and Cheeze hogie Sandwich....")
print("Chips cost $1.00 each, so you want some or not? ")
chips = input("Ok, So chips cost $1.00 each, how much do you want.")
if chips.isnumeric():
  chips = int(chips)*1.00
print("Your total is",total,"dollars")
print("Your order is...", customer_order)
