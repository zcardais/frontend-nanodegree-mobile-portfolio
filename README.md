## Website Performance Optimization portfolio project

Welcome to my web optimization project for Udacity's Front-end Developer Nanodegree program (project 4). View this project in your browser by opening index.html.

Here's a log of the significant performance optimizations made to this site/project:
- Resized images (made them smaller) to match how they were being used in the code
- Stripped images of unnecessary metadata
- linked to minified style-minify.css in index.html instead of inserting directly into the <head> via <style> tag
- In js/main.js, substituted a formula that calculates the minimum number of pizzas to display based on user's viewport in place of a hard coded value of number of pizzas to generate
- In js/main.js, subbed all instances of querySelectorAll with getElementsByClassName
