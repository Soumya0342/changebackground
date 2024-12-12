# Element Selection and Color Change

This simple webpage allows users to change the background and text colors of various HTML elements (paragraphs, headings) dynamically by clicking a button. The colors are randomly generated each time the button is pressed.

## Features
- Randomly changes the background and text color of all `<p>`, `<h1>`, and `<h2>` elements on the page.
- The button itself also changes color when clicked.

## How it Works
1. The page contains three types of elements: `<h1>`, `<h2>`, and `<p>`.
2. The button with the id `changeBG` listens for a `click` event.
3. When the button is clicked, a JavaScript function generates random RGB values for the background and text colors of all paragraphs, headings, and the button.
4. These random colors are applied using inline CSS styles, modifying the colors of the elements on the page dynamically.

## Code Structure
- **HTML**: Basic structure of the page with headings, paragraphs, and a button.
- **CSS**: Inline styles are used dynamically in JavaScript to change the colors.
- **JavaScript**: 
  - `querySelectorAll` is used to select all paragraphs, headings, and the button.
  - A helper function `getRamdomColor` generates a pair of complementary random colors.
  - The `changecolor` function changes the background and text color of the selected elements.
  - The event listener on the button triggers the color change.

## How to Run
1. Download the code or clone the repository.
2. Open the HTML file in a browser to see the elements and click the button to change colors.

## License
This project does not have a formal license. Feel free to use and modify the code at your own discretion.

## Credits
This project was created by **Soumya Chatterjee**.
