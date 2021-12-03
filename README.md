# CSE20
README


Class description- My class is supposed to represent a sandwich, and the user (the “customer”) can choose their own ingredients they want to use in the functions. The idea is that they choose from the menu and use those ingredients as inputs for the methods in the class.

Class/data variables- The food_type variable is representative of the type of food that is being used. It is set to ‘Sandwich’ and is accessed when the return_food_type method is called. The self.__name and self.__name2 variables of the __init__ function are representative of the user’s first and last names. They both have two underscores in front of them because they are private data attributes. They are accessed when the get_name method is called. 

The methods-

Get_name- returns the user’s name, which they input as data variables in the __init__ function.

Return_food_type: this method returns the food_type which is a class variable that is set to ‘Sandwich’. The only argument needed is self so the user doesn’t need to input anything when calling it.

Set_calories- this method allows the user to set the numerberf calories that are in their sandwich. It takes in self and x, x is the amount of calories that is inputted.

Get_calories- this method returns the number of calories that were inputted using set_calories. The only needed input is self so the user does not need to input anything as an argument.

Set_weight- this method allows the user to set the weight in oz that their sandwich is. It takes in self and x, x is the weight in oz that is inputted.

Get_weight- this method returns the weight of the sandwich that was inputted using set_weight. The only needed input is self so the user does not need to input anything as an argument.

Return_animal_type- this method tells the user what type of animal their selected meat comes from. The needed inputs are self and ‘meat’ which is the meat that the user has chosen. Each meat returns a different type of animal.

Calorie_per_oz- this method returns the number of calories per oz are in the sandwich, using the inputs from the two previous set methods. It uses division to figure it out, no input is needed from the user because it takes the two variables from previous methods.

Get_veggie_info- this method opens a Wikipedia page based on whatever veggie is chosen. Only one input argument is needed, the ‘veggie’ name. It uses webbrowser to open the page.

get_price_of_sandwich - this method returns the price of the sandwich, and takes in the arguments that represent the meat, veggie, and bread. It adds up all the prices based on the price assigned to each ingredient and displays it along with a string message.

Text_food- this method prints out whatever ingredients are chosen on a canvas using the turtle method. It takes in self and an ingredient, so one argument is required to be inputted by the user.

Demo Program Documentation

In my demo program,  each method is tested and used. The user can input their arguments for each of the methods. Each place where an argument is required will have a comment as a placeholder (telling the user to replace said comment with their desired argument). There are instructions at the top of my code that describe the menu to the user (what arguments are and aren’t valid). The methods also print error messages if the arguments are not valid.

To run the program, the user just has to input their arguments where directed (there will be comments telling the user where to input arguments).
