## Website Performance Optimization portfolio project

####Part 1: Optimize PageSpeed Insights score for index.html

############################   STEPS TAKEN  #######################################

I used mspaint to resize the images and a web app to compress the images. I resized to the largest necessary size.

I used a script to defer the loading of the main style sheet.

I used async on all render blocking scripts.

I used all of the optimized files profided from PageSpeed insights.

##################################################################################

####Part 2: Optimize Frames per Second in pizza.html

############################   STEPS TAKEN  #######################################

I adjusted the resizePizza javascript by combining a for loop to resize every pizza within the switch case statement
which eliminated the second switch case and for loop.

In the function that produces the movers i calculate how many pizzas are needed based on the height of the screen

In the css file I added will-change: transform to the mover element in order to make the moving pizzas on their own layer.

I used a webAPP to minify the main.js file in order to reduce the load times.

##################################################################################