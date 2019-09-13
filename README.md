I figure out that "createCanvas()" decide the screen size.

"i" means bubble, "i < 10" means no more than 10 bubbles.

"radius random" change the bubbles size.

"background()" is the color which the background is.

"if (dist(mouseX, mouseY, bubble.x, bubble.y) < bubble.radius) {
   if (mouseIsPressed) {
     bubbles.splice(i, 1); // remove this bubble!
   }
   fill(115, 200, 220, 200);
 } else {
   fill(115, 220, 220, 200);
 }" This part means when mouse moves on a bubble, the bubble will change the color, and if muose kicks the bubble, the bubble will disappear.
    
"ellipse(bubble.x, bubble.y, bubble.radius * 2);
 bubble.x += random(-1, 1);
 bubble.y += random(-2, 1);" means how the bubbles will move in the screen.
