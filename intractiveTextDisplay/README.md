This project is an interactive web page that allows users to input text, customize its styling, and view the styled text in real-time in a read-only text area. 

1. Project Structure
   Files Included:   - HTML (index.html):  The structure of the webpage.   - CSS (style.css): The styling and layout for the webpage.   - JavaScript (script.js): The interactivity and functionality.

2. Features
   1. Input Text Area:
     - Users can write text in the input box.
     - Clicking the "Add" button transfers the text to a read-only box.

   2. Font Customization:
     - Font Size: An input field to adjust font size (12px to 40px).
     - Font Weight: A "Bold" button to toggle bold styling.
     - Font Style: An "Italic" button to toggle italic styling.
     - Underline: An underline button for text decoration.

   3. Text Alignment:
     - Buttons to align text to the left, center, or right.

   4. Color Customization:
     - Background Color: A color picker to change the background color of the text box.
     - Font Color: A color picker to change the text color.


3. Code Explanation
   HTML:
       The main structure of the web page.
       Includes buttons, input fields, and two text areas.
       Utilizes Font Awesome icons for styling buttons.
       Links external CSS and JavaScript files.

   CSS:
        Defines the layout, dimensions, and overall appearance.
        Custom styles like shadows, transitions, and hover effects enhance usability.
        Contains utility classes for dynamic styling (e.g., .select, .boldFont).

   JavaScript :

     Handles interactivity with these functions:
    - addText(): Transfers text from the input area to the read-only area.
    - fontSize(): Adjusts the font size of the text dynamically.
    - fontBold(): Toggles bold styling using CSS classes.
    - fontItalic(): Toggles italic styling using CSS classes.
    - fontUnderLine(): Toggles underline styling.
    - Alignment Functions:
           textAlignLeft(), textAlignCenter(), textAlignRight(): Adjust text alignment and manage button states.
    - Color Functions:
           changeBgColor(): Changes the background color of the read-only text box.
           changeFontColor(): Adjusts the font color.

5. Preview

   The interface includes:
   - A text input field for entering messages.
   - Buttons and controls for text formatting.
   - A read-only box displaying the styled text.
  
WebSite Link : https://turbo-pancake-56pvqrv949x2pgp4-5500.app.github.dev/intractiveTextDisplay/
