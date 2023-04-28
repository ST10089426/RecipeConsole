# RecipeConsole
RECIPE CONSOLE
THIS IS A CONSOLE APPLICATION THAT ALLOWS USERS TO CREATE, DISPLAY, AND MODIFY A RECIPE BY ADDING INGREDIENTS AND STEPS. USERS CAN ALSO SCALE THE RECIPE, RESET QUANTITIES, AND CLEAR THE RECIPE DATA.
INSTRUCTIONS
TO COMPILE AND RUN THE SOFTWARE, FOLLOW THE STEPS BELOW:
1.	OPEN VISUAL STUDIO OR ANY C# COMPILER.
2.	CREATE A NEW CONSOLE APPLICATION PROJECT.
3.	COPY THE CODE ABOVE AND REPLACE THE DEFAULT CODE IN THE PROGRAM.CS FILE OF THE NEW PROJECT.
4.	BUILD AND RUN THE APPLICATION.
UPON RUNNING THE APPLICATION, THE USER WILL BE PROMPTED TO ENTER THE NUMBER OF INGREDIENTS AND STEPS FOR THE RECIPE. THE USER WILL THEN BE PROMPTED TO ENTER THE NAME, QUANTITY, AND UNIT OF MEASUREMENT FOR EACH INGREDIENT AND EACH STEP.
AFTER THE RECIPE IS CREATED, THE USER CAN ENTER ONE OF FOUR COMMANDS: "SCALE", "RESET", "CLEAR", OR "EXIT".
⦁	THE "SCALE" COMMAND ALLOWS THE USER TO SCALE THE RECIPE BY A FACTOR OF 0.5, 2, OR 3.
⦁	THE "RESET" COMMAND RESETS THE QUANTITIES OF ALL INGREDIENTS TO THEIR ORIGINAL VALUES.
⦁	THE "CLEAR" COMMAND CLEARS THE RECIPE DATA.
⦁	THE "EXIT" COMMAND ENDS THE PROGRAM.
HOW TO USE
BELOW IS AN EXAMPLE ON HOW TO USE THE CONSOLE
Welcome to the Recipe Console!
Please enter the number of ingredients:
3
Enter the name of ingredient 1:
flour
Enter the quantity of ingredient 1:
2
Enter the unit of measurement for ingredient 1:
cups
Enter the name of ingredient 2:
sugar
Enter the quantity of ingredient 2:
1
Enter the unit of measurement for ingredient 2:
cup
Enter the name of ingredient 3:
butter
Enter the quantity of ingredient 3:
0.5
Enter the unit of measurement for ingredient 3:
cups
Please enter the number of steps:
2
Enter step 1:
Preheat oven to 350 degrees F.
Enter step 2:
Mix all ingredients together.
Recipe:
Ingredients:
1. 2 cups flour
2. 1 cup sugar
3. 0.5 cups butter
Steps:
1. Preheat oven to 350 degrees F.
2. Mix all ingredients together.
Enter a command (scale, reset, clear, exit):
scale
Enter a scaling factor (0.5, 2, 3):
2
Ingredients:
1. 4 cups flour
2. 2 cups sugar
3. 1 cups butter
Steps:
1. Preheat oven to 350 degrees F.
2. Mix all ingredients together.
Enter a command (scale, reset, clear, exit):
reset
Ingredients:
1. 2 cups flour
2. 1 cup sugar
3. 0.5 cups butter
Steps:
1. Preheat oven to 350 degrees F.
2. Mix all ingredients together.
Enter a command (scale, reset, clear, exit):
clear
Recipe data cleared.
Enter a command (scale, reset, clear, exit):
exit
Goodbye!

