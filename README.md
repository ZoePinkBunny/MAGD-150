# MAGD-150
MAGD 150 Repository! :D

### moserZLab6
The goal was to create a p5js project with a Halloween theme.

Requirements:
* 400 by 400 canvas _(minimum)_
* The use of arrays, assigning values using a for loop
* Using console.log to show the values in the array(s)
* Create motion using a for loop, with shapes using the array values as position values

For the assignment, I created a house filled with **ghosts**!  
The ghosts would be randomly placed with the use of arrays, and move around in random directions to create a jittering effect.  
I also added text to give the player more sense of what to do, as well as making the text disappear when you clicked. The text reads:
>"Find the Ghost who wants Candy!"

When you hover over a curtain ghost, another text will appear saying:
>"You found the Ghost!"

### moserZLab7
The assignment was to further learn about arrays. Specifically array manipulation methods, info methods, and the text function.

Requirements:
* 400 by 400 canvas _(minimum)_
* Use at least 2 arrays and a for() loop to populate them with 5 valuse _(minimum)_ and use console.log to show results
* Use only array manipulation methods to populate or pull values from arrays
* Create that combines the values of 2 arrays and show the array in the console
* Create text listing the values of 2 arrays, as well as a random value from each array and from both arrays

For my assignment, I decided to use money values for the arrays. One array, **allMoney**, included all the money values, with another array, **myMoney**, pushing random values from _allMoney_ into it and removing the value from _allMoney_  
For the lists, I displayed values from _allMoney_ and _myMoney_ as well as a random value from each list and both lists combined.  
I also displayed the chosen values pushed into _myMoney_ as actual rectangle or dollars.  
For this, I also used arrays to randomly place rectangles within a curtain area, mainly so they wouldn't overlap with the lists.

### moserZLab8
In this assignment, we learned how to use and add images to our p5js projects and how to check our projects are working from the files using [Simple Web Server](https://simplewebserver.org/)

Requirements:
* 400 by 400 canvas _(minimum)_
* Create a holiday, get well, or seasonal greeting card
* Import at least 2 images and assign a variable to each of them.
* Use the scale function to change the size of an image
* Use mouseX and mouseY to change an images location or size
* Use the text function in draw(), use textFont, change the stroke and fill, and limit the area the text can be drawn in using width and height measurments


I decided to create a holiday card for this assignment! I used images I made which included a Gnome, a Snowy background, and snow particles.
I used scale to change the images size, and had the Gnome follow your mouse.  
For the text, I made two different texts. One was bigger with a red stroke and green fill saying:
>"Happy Holidays!"

Another text was able to move around a bit near the big text, as it is much smaller. It has a white stroke with red fill and says:
>"Fill the Holidays with Sugar Gnome Delights!"

As for the snow particles, I wanted to create the effect of snow falling. So, I had two snow particles, one right above the other, and had them move downward. _(adding +1 to the Y axis)_  
When they reached a curtain point at the bottom, they would reset back at the top, creating a seamless loop of falling snow.
