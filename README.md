## Website Performance Optimization portfolio project
Open the index.html in your favorite web browser and navigate.
or open https://brewso.github.io/frontend-nanodegree-mobile-portfolio
To inspect the site on your phone, you can run a local server
 
   ```bash
   $> cd /path/to/your-project-folder
   $> python -m SimpleHTTPServer 8080
   ```
 
 Open a browser and visit localhost:8080
 Download and install [ngrok](https://ngrok.com/) to make your local server accessible remotely.
 
   ``` bash
   $> cd /path/to/your-project-folder
   $> ngrok http 8080
   ```

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