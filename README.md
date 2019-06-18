# Memory Game Project

## Table of Contents

-   [Instructions](#instructions)
-   [Contributing](#contributing)

## Instructions

The starter project has some HTML and CSS styling to display a static version of the Memory Game project. You'll need to convert this project from a static project to an interactive one. This will require modifying the HTML and CSS files, but primarily the JavaScript file.

To get started, open `js/app.js` and start building out the app's functionality

For specific, detailed instructions, look at the project instructions in the [Udacity Classroom](https://classroom.udacity.com/me).

## Contributing

This repository is the starter code for _all_ Udacity students. Therefore, we most likely will not accept pull requests.

## For details, check out [CONTRIBUTING.md](CONTRIBUTING.md).

## I did the following steps in order to develop this game.

+   Downloaded the skeleton project from GitHub link which is given by udacity in rubric structure.
+   After extracting the downloaded zip file , I  understood that most of the modifications would happen in `app.js`.
+   Examined `shuffle` function which is which was  developed by Stack Overflow in `app.js`.And create an array for listing all the cards named it as `childsList`.
+   shuffle function will be triggered when the window is loaded.
+   I use spread operator (`[...]`) to convert HTML collections into an array.
+   I got new shuffle array after setting the `childsList` and array as a parameter in `shuffle` function.
+   Added a `click` EventListener to each card with a function name `displayCard`.
+   I concentrated on timer function, added time function(`startTimer`) definition in `displaycard` function.
+   I increased moves when `cardStore` has reached to 2 and when the two cards are same then it will be displayed as matched are otherwise it will be displayed as unmatched.
+   If the cards are matched then it will be appeared with pink color.
+   Then I introduced`Swal` function, it will be popped up on the screen when the length of matchedCards is 16. And this popup menu consists of title as congratulations, and also shows how many stars the player earned and time taken to earn those stars.
+   I wrote styles of unmatched cards in `app.css` file, if they are unmatched they will be closed indicating with black color.
+ Finally I had concentrated on starRating, and if the moves were present between 13 and 17 pop up menu will be appeared with 2 stars and if it is greater than 17 it will be appeared with one star.
