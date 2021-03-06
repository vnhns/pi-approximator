# pi-approximator

View the project here: https://vnhns.github.io/pi-approximator/

This is a mini app built using vanilla JavaScript, HTML, and CSS. It approximates pi using randomly placed points on a circle of radius r and a square of sidelength 2*r. The intuition behind this is simple but perhaps not so obvious. Here's how it works.

Let's start with a ratio. We need to compare the area of the circle to the area of the square. Luckily, we should know the formulas for this...

![Ratio of Areas](images/formulas.png)

Ideally, we would create an equation in which we could solve for pi. This is where the random points come in. By randomly placing points on the circle and square, we can approximate their areas by summing the number of points in each shape. This gives use a second ratio.

![Ratio of Points](images/points.png)

All we need now is some simple algebra and we find that we can approximate pi as follows:

![PI Approximation](images/pi_approx.png)
