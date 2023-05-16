# Snake-in-the-House
This is a Typical Snake game where snake enlarges whenever it eats food and game overs if snake bump into itself or into the wall.
This Snake int the House game is developed using HTML, CSS and JavaScript. In the HTML file I used 1 class namely body and 3 ids board, scoreBox, HiScoreBox which are there within the class.
Class body is used as CSS flex box.
Id board is used to display the food and snake by making it CSS Grid of 18X18.
scoreBox and HiScoreBox is used to render the score of a player playing the and highest score in the device till now.
The main logic of the game is written in JavaScrip.
To render the style of the game continuously I used window.requestAnimation(), which takes a main function in it.
In main function gameEngine funcion is written which is used to update the snake array, generation food, check whether snake has collided with itself or wall i.e. whether the game is over or not.
The gameEngine is also to render the food and snake head and body on display.
