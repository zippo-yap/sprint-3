#Skeleton
###What happens to the layout when you resize the screen to less than 550px. 
* The layout grid of the page shrinks with the browser once the screen gets smaller than 550px. It goes from having multiple columns to a single column layout.
* The image of the iphone(s) on the page also changes based on screen size.
###How do you think that works?
The layout is built with a mobile first approach, so the grid system displays the elements as full-width block elements initially and as the screen width increases min-width media queries are used to specify percentages for each column width class. Media queries are also used to change how the images of the iphones are displayed on the screen.