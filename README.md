# Landing-page-odin
An Odin Project practice exercise: Landing Page. In this project I am to replicate a landing page based on an image of the page from scratch.

This project will conclude the HTML an CSS overview sections of the Foundations course.

For the header section, I added a column flexbox divided between the header log and links, and the impact font, text, button and image. Then each of those sections was turned into a row flex box. Still needs some fine tuning, but I'm happy overall.

The information is a simple and pretty straightforward flex box. The quote and signup are equally simple. The signup box does use a flexbox for the text on the left and the button on the right. I overthought the whitespace on the sides. I set a margin initially, but it didn't collapse when the screen size was more narrow. I then though of adding white flex containers. That (obviously) didn't work. The solution (again, an obvious one) was to set a min and max width, no side margin, and the margins set to auto. Now it works.

