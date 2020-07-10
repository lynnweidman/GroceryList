# GroceryList
Make a grocery list by your weekly meal plan

fruits = {1: "apples", 2: "avocados", 3: "bananas", 4: "berries", 5: "melons", 6: "peaches", 7: "pears", 8: "pineapple",}

veggies = {1: "asparagus", 2: "broccoli", 3: "brussel sprouts", 4: "cabbage", 5: "carrots", 6: "cauliflower", 7: "celery", 8: "corn", 9: "cucumbers", 10: "green beans", 11: "hummus", 12: "lettuce", 13: "mushrooms", 14: "onions", 15: "peas", 16: "peppers", 17: "potatoes", 18: "squash", 19: "spinach", 20: "tomatoes", 22: "zucchini",}

dairy = {1: "butter", 2: "cheese", 3: "cream", 4: "cream cheese", 5: "eggs", 6: "milk", 7: "sour cream", 8: "yogurt",}

meatFish = {1: "bacon", 2: "chicken", 3: "fish", 4: "ground beef", 5: "ham", 6: "hot dog", 7: "lamb", 8: "lobster", 9: "pork", 10: "salmon", 11: "sausage", 12: "scallops", 13: "shrimp", 14: "steak", 15: "turkey",}

grains = {1: "bread", 2: "bulgar", 3: "cereal", 4: "flour", 5: "quinoa", 6: "pasta", 7: "rice",}

pet = {1: "dog food",}

drinks = {1: "apple juice", 2: "broth", 3: "orange juice", 4: "milk", 5: "lemon juice",}

condiments = {1: "capers", 2: "ketchup", 3: "mustard", 4: "mayo", 5: "olive oil", 6: "spaghetti sauce", 7: "worcestershire sauce",}

herbs = {1: "basil", 2: "cilantro", 3: "cumin", 4: "garlic", 5: "parsley", 6: "rosemary",}

#meals

def stuffedMushroom(): 
    print(veggies[13], veggies[14], dairy[8], dairy[2], meatFish[4])
    
def meatPasta(): 
    print(condiments[5], grains[5], meatFish[4], veggies[16], veggies[13], herbs[4])
    
def squashTomatoSoup(): 
    print(veggies[18], veggies[20], drinks[4], herbs[2], herbs[3], herbs[4], drinks[2])
    
def chickenPiccata():
    print(meatFish[2], grains[4], dairy[1], condiments[5], drinks[4], drinks[2], condiments[1], herbs[5]) 
    
def salmonCakes():
    print(meatFish[10], condiments[5], dairy[1], veggies[14], veggies[7], veggies[16], condiments[1], herbs[5], condiments[7], condiments[4], condiments[3], dairy[5]) 

#enter meals in myList to create a grocery list.

myList =[]
