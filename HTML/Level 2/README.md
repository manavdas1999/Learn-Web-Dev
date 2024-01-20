
# HTML tags and attributes

1.0 HTML attributes
    1. What are html attributes?
    - provides additional information about elements.
    - placed within opening tag
    - syntax: attribute-name =  value
    - eg: href, src, height, width etc
    - each html element has its own set of attributes.

    2. ID property
    - unique identifier: each id given to an element within a page.
    - Anchoring: allows for direct links to sections using #id syntax in href/URLS.
    - CSS & javascript: used as a selector for styling and scripting.


2.0 HTML TAGS

2.1 Heading tags-
    1. defines headings in a webpage
    2. ranges from <h1> to <h6>
    3. <h1> is most important, <h6> is least. (importance matters not size)
    4. Important for SEO
    5. helps in structuring content.

2.2 Paragraph tag-
    1. Used for defining paragraphs.
    2. Enclosed within <p></p>
    3. Its a block level element.
    4. Adds automatic spacing before and after.
    5. Text wraps to next line inside tag if text is too long.
    6. Used for long text contents.
    NOTE: lorem text generator

2.3 Line Breaker tag-
    1. <br> adds a line break(newline) within text.
    2. Its a self closing tag. no need of closing tag as it does not contain anything.
    3. <br> or <br/> both are valid.

    Horizontal Rule tag-
    1. <hr> creates a horizontal rule or line.
    2. <hr> also empty, acts as a section divider.

2.4 Image tag-
    1. Used to embed images.
    2. Utilizes the "src" attribute of <img> or <image>
    3. "alt" attribute - to display an alternative text in case image cannot be rendered.
    4. resized using attributes - "height" and "width".
    5. Self closing, inline element
NOTE- by default, sizing is done in px (pixels) 
    - mentioning only height or only width will auto adjust the image to its aspect ratio.

# absolute path and relative path

2.5 Video tag-
    1. Embeds video files on a page
    2. uses "src" attribute.
    3. Supports multiple formats like MP4, webm etc.
    4. Allows for built-in controls via attributes like autoplay, controls, loop etc. 

2.6 Anchor tag-
    1. used for creating hyperlinks
    2. requires "href" attribute for url.
    3. can link to external sites or internal pages.
    4. Supports "target" attributes to control link behavior.

2.7 text styles
    1. <b></b> for bold text.
    2. <i></i> for italic text.
    3. <u></u> for underline text.
    4. <s></s> for strikethrough text.
Alternative:
    1. <strong></strong>
    2. <em></em>

# 2.8 Pre tag-
    1. Preserves text formatting.
    2. maintains whitespace, linebreaks etc.
    3. useful for display text as it is. eg- code.
    4. syntax: <pre>content here</pre>

2.9 Big and Small text 
    1. <big></big> comparatively larger text
    2. <small></small> comparatively smaller text
    3. Very uncommon as we prefer CSS for styling

2.10 Superscript and Subscript tag-
    1. <sup></sup> makes text superscripted.
    2. <sub></sub> makes text subscripted.
    3. used for mathematical equations, foornotes etc.
    4. does not change font size, just the positions.


3.0 Character Entity Reference
    1. Used to display reserved or special characters.
    2. Syntax: &name;
    3. eg- &reg; &copy; etc

# CHECKPOINT Project LEVEL 2
    1. Create a page with heading, paragraph, line breaks and separators.
    2. Use an image with height 300, which is a link to another page.
    3. use bold, italic, underline and strikethrough in one line.
    4. Write some equations using superscript and subscript.
    5. create a clickable link image.