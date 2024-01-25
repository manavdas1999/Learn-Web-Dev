
# Browser Tools

1.0 Browser Tools
    1.1 view page source (ctrl + U)
        - Displays raw HTML and CSS
        - Useful for debugging and learning
        - shows external files like javascript links
# Task: copy source (view page source) html of a website and paste in into you local index.html

    1.2 Inspect Element (ctrl + shift + I)
        - Allows real-time editing of HTML/CSS.
        - Useful for debugging and testing.
        - Shows element hierarchy and layout.
        - Includes console for javascript.
        - * Highlights selected elements on page.


    1.3 HTML without CSS (using chrome extension)
# Task: use a chrome extension to disable CSS on any website


2.0 Responsive Design *
    2.1 Different Screen Sizes (toggle device toolbar / ctrl + shift + M)
        - Adapts layout for different screen sizes
        - Flexible layouts.
        - Optimizes images and assets (makes no sense to show high res assets on smaller devices)
        - Enhances user experience on mobile and desktop.
# Task: Open responsive screen tool and check website on different screens.

3.0 Live Edit code
# Task:  
1. change any text on wikipedia.
2. change subscriber count on any youtube channel.
3. change channel name color. (CSS)
4. hide the entire channel info using JS (hint: console > document.getElementById > set visibility to hidden)

NOTE: changes happening at client side only
1. Changes made are temporary.
2. Affect only the current session.
3. Not saved to the server.
4. Reset upon page reload.
5. Useful for testing, not permanent fixes.
6. sometimes html and css is dynamic and cannot be inspected.

4.0 Validating webpages 
Need: modern web browsers are very forgiving and handles most of the HTML errors easily but its not a good practice to write such code, hence we should check validity of our html code.

    4.1 Using validator.w3.org
        1. Ensures HTML adheres to standards.
        2. Minimizes cross-browser issues.
        3. Helps in achieving better SEO results.
        4. Easier to debug and maintain.
        5. Optimizes performance by reducing parsing errors.
# Task: copy your HTML code and paste it into validator. Add some errors then check validator response.

# Task: Project Level 3: 
1. Save source markup of instagram in a file and check the render.
2. Inspect the likes element on the page and read the code to understand.
3. Change number of likes on your instagram post.
4. Validate the page we created in last project.