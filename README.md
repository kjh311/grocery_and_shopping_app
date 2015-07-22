#GROCERY STORE APP

This app is designed to save time making grocery lists and meal plans.


##User Stories

###Minimum Viable Product

- As a user I want to be able to easily add, romove, and edit items in a grocery list.  Items will have attributes: NAME, QUANTITY, and maybe COST.

- As a user I want to be able to easily add, romove, and edit items in a pantry list. Items will have attributes: NAME, QUANTITY. Optional: Expiration date.

- As a user I want to be able to easily add, romove, and edit recipes. Items will have attributes: NAME, PICTURE, RECIPE STEPS, CALORIES, PREP TIME, CATEGORY(breakfast, lunch, dinner, snack), INGREDIENTS, and LIKE/DISLIKE. Might need a different table for each CATEGORY.

- Once items are added to the panty list, I want to hit a "WHAT CAN I MAKE?" button, that will check the items in my pantry against recipe INGREDIENTS, if I have the necessary items it will show a list of recipes that I can make.

- It will also allow me to select the number of people I'm cooking for and multiply the recipe by that number.

- I want to be able to add to my shopping list directly, as well as based on which recipes I want for the week.  I choose my meal plan for the week and it adds the necessary INGREDIENTS to the shopping list.

### Icebox Features

- If multiple users, will need a user table.

- I want to be able to share data between multiple users.

- Once I select "USE THIS RECIPE" it will subtract the ingredients from my pantry list if it has a quantity, it will not subtract certain items, like salt, if the recipe requires a teaspoon of salt.  Salt will just have to be manually added to the shopping list when it runs out.

- Once the QUANTITY of a pantry item reaches 0, it will ask if I want to add this item to the shopping list.

- The recipe list will include a slider for CALORIES that will filter recipes based on max calories.

- The recipe list will include a slider for PREP TIME that will filter recipes based on max prep time.

- Recipes that I've LIKEd will appear near the top of the list, disliked near the bottom.

- If I see a recipe that I want to make but I don't have the necessary ingredients, it will tell me: "You need eggs." "Add to grociery list?

- After going to the store the shopping list items gets transfered to the pantry list.

- I want a randomizer meal plan, that shuffles through possible recipes for the week and adds the necessary INGREDIENTS (if they aren't already in the pantry) to the shopping list, to maximize time saved.  Or I can pick a few and randomize the rest.  As before I can choose the max CALORIES, PREP TIME, and number of people for the randomizer.

- Optional: if COST is added to shopping list, perhaps MAX COST could be a slider for the meal plan randomizer.

- Meal plan recipes get added to a MY RECIPES FOR THE WEEK page, and get deleted when they are used.

- If I have DISLIKEd a recipe, it doesn't get added into the randomizer.

- Optional: allergy to ingredient. Don't show recipes with that ingredient.

- Optional: Authentication for individual users

##Layout Design:

Computer Layout Wireframe:
"https://drive.google.com/thumbnail?id=0B6z5p82sidMKcHBRN3V5cEFYN0k&authuser=0&v=1437599143460&sz=w1256-h582"

Cell Phone Layout WireFrame 1:
https://drive.google.com/thumbnail?id=0B6z5p82sidMKVkVHUHl6ZW15ZUk&authuser=0&v=1437599148636&sz=w1256-h582

Cell Phone Layout WireFrame 2:
https://drive.google.com/thumbnail?id=0B6z5p82sidMKSXlEZTg1NmhNTHc&authuser=0&v=1437599155101&sz=w1256-h582

ERD:
"https://drive.google.com/thumbnail?id=0B6z5p82sidMKcHBHUFIxMkgxVGs&authuser=0&v=1437599159366&sz=w1256-h582"
