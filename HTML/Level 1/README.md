
1.0 Framework of HTML

    1. Structure: Sets up the layout and barebone of any web page
    2. Content: All contents in a web page are HTML components(tags) eg. text, images, links etc.
    3. Tags: HTML uses tages to represent components. eg. <a>, <h1> etc.
    4. Hierarchy: Everything in HTML is organized by a component and layout hierarchy. 


1.1 TASK 1-
    1. Create a folder with some name
    2. Open notepad.
    3. Create a file and save it as index.html
    4. write anything.
    5. Open it in browser and check.


1.2 file extension confusion
    HTML = HTM (older)


1.3 TASK 2- Open Project/folder in VSCODE

1.4 Importance of index.html 
    1. Default name of a website's homepage.
    2. Starting point of any website. (but we can do it in other ways explicitly but implicitly index.html is considered the first page by and browser.)
    3. Importanrt for SEO. (contents in index is considered most important)
    4. Serves as fallback when no file os specified in URL.



2.0 Components/Elements/Tags in HTML

2.1 What are tags?
    1. ELements that are used to create a website are called HTML tags.
    2. Tags can contain content or other HTML tags.
    3. Define elements lile text, images, links.
    4. Structure of an HTML tag - <openingTag attributes>Content comes here<closingTag/>

2.2 Emmet plugin (!)

2.3 Basic HTML page structure
<!DOCTYPE html>     // defines the html version of the document
<html lang="en">    // root element

<head>              // head tag containes all meta data tags
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>    // title of the webpage
</head>

<body>              // body tag is parent of all content tags
    <!-- some text 
    127.0.0.1:5000 (localhost ip : port address) -->
    <h1>Hello World</h1>
    
</body>
</html>


2.4 MDN documnetation (TASK 3 - visit mdn) 

2.5 Comments
    1. Used to add notes along with your code.
    2. Not displayed (not rendered or compiled).
    3. Syntax: <!-- COmment -->
    4. Helpful for code organization and also debugging.
    5. Can be used to temporarily disable selected code.
    6. it can be multiline or single line.

2.6 HTML is Case-insensitive. BEST PRACTICE - use lowercase

# CHECKPOINT- PROJECT LEVEL 1
    1. Create a new project with index.html
    2. Generate boilerplate code using emmet
    3. show a text "I am learning HTML ...boi" using h1 tag
    4. use comments to describe what you did in your code
    5. also use case insensitive tags. (<h1> and <H1>) 