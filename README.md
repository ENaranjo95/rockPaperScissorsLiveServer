# rockPaperScissorsLiveServer
Rock Paper and Scissors application contains a Local Server 8000, with the JavaScript written between the script tags on the index.html.

## How It's Made:

**Tech used:** HTML, CSS, JavaScript, Node-Js

I set up the index.html to have a heading tag for the name of the application, a score counter, display of the result and three button tags for the user to interact with. Between the script tag is our JavaScript. I set up the script to have one global variable, three event listeners for each respective button, and higher order functions. One function to assign the global variable to the respective button clicked on, one function to randomly select the bot a weapon of choice, passing that choice as a parameter, another function to compare the bot weapon's choice to the user's choice using a conditional statement for a win for the user, tie or a win for the computer. In each respective conditional statement calls on two other functions that display a point and message on the DOM, a tie message on the DOM, and a point and message on the DOM for the bot.

## Optimizations
Still need styling!

## Lessons Learned:
What is awesome about this project is limiting the global variables I need to make this project work. I was passing arguements as parameters to other functions when they were called on and then using the data as arguements in the other function to make it successful run how the project was intended. As you look in my computerChoice function, I passed the botChoice arguement after it was assigned a data and using the parameter botWeapon in my comparison function to make the arguement if the point was for the user, the computer or ending in a tie.
