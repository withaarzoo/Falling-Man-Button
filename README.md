# Falling Man Button
This is a simple web page that shows a button which, when clicked, triggers an animation that makes a man fall out of a door. The door is placed on the button.

## Technologies Used
The project uses the following technologies:

- HTML
- CSS
- JS
- SVG

## How to Use
To use this project, simply open the `index.html` file in a web browser.

When the page loads, you will see a button with the text "Logout". Click on this button to trigger the animation. The animation will make a man fall out of a door that is placed on the button.

## Code Description
The `index.html` file contains the HTML code for the web page. It includes a `div` element with the class `background`, which is used to create the background for the page. Inside this `div` element, there is a `button` element with the classes `logoutButton` and `logoutButton--dark`. This is the button that triggers the animation.

The button includes two SVG elements:

* The first SVG element, with the class `doorway`, is used to create the door that the man falls out of. It contains two `path` elements that define the shape of the door and the "bang" that appears when the man hits the ground.

* The second SVG element, with the class `figure`, is used to create the man that falls out of the door. It contains a `circle` element that defines the head of the man and several `path` elements that define the body, arms, and legs of the man.

The `style.css` file contains the CSS code for the web page. It is used to style the button and the SVG elements.

## Preview
<img width="960" alt="Screenshot 2023-03-01 205245" src="https://user-images.githubusercontent.com/59678435/222183695-35ff9070-4001-4c7f-a483-5cb3e4792641.png">
