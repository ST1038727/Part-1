# Recipe Application

This is a command-line application written in C# using Visual Studio that allows users to enter, display, scale, reset, and clear recipes.

## How to use

1. Run the application.
2. Follow the prompts to enter the details for a recipe, including the number of ingredients, each ingredient's name, quantity, unit measurement, the number of steps, and each step's description.
3. Once the recipe is entered, the application will display the full recipe in a neat format.
4. You can request to scale the recipe by a factor of 0.5 (half), 2 (double), or 3 (triple). All ingredient quantities will be adjusted accordingly when displaying the scaled recipe.
5. You can request to reset the quantities to their original values.
6. You can clear all the data to enter a new recipe.
7. The data is stored in memory while the application is running and is not persisted between runs.

## Code Structure

The application consists of the following classes:

- `Ingredient`: Represents an ingredient with properties for name, quantity, and unit measurement.
- `Step`: Represents a step in the recipe with a description.
- `Recipe`: Represents a recipe with arrays to store ingredients and steps, and methods for entering, displaying, scaling, resetting, and clearing the recipe.

## Functions

- `EnterRecipe()`: Prompts the user to enter the details of the recipe, including ingredients and steps.
- `DisplayRecipe()`: Displays the full recipe, including ingredients and steps, in a neat format.
- `ScaleRecipe(double factor)`: Scales the recipe by the given factor, adjusting all ingredient quantities accordingly.
- `ResetQuantities()`: Resets all ingredient quantities to their original values.
- `ClearRecipe()`: Clears all data to enter a new recipe.

## Coding Standards

- The code follows internationally acceptable coding standards.
- Comprehensive comments are included to explain variable names, methods, and the logic of programming code.
