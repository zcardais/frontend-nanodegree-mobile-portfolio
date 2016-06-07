## Website Performance Optimization portfolio project

Welcome to my web optimization project for Udacity's Front-end Developer Nanodegree program (project 4).

To run this application, open index.html in your browser. Navigate to the Zach's Pizzeria page to view pizzas. Marvel in the smooth movement of the background pizzas as you scroll through my pizzas! Finally, use the slider to change the pizza size.

Here's a log of the significant performance optimizations made to this site/project:
- Resized images (made them smaller) to match how they were being used in the code
- Stripped images of unnecessary metadata
- Inserted Internal CSS Style via the style tag in index.html to score 90 or higher on Google's PageSpeed
- In js/main.js, substituted a formula that calculates the minimum number of pizzas to display based on user's viewport in place of a hard coded value of number of pizzas to generate
- In js/main.js, subbed all instances of querySelectorAll with getElementsByClassName
