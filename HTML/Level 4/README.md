
# LEVEL 4: HTML and Project structure

1.0 Sementic Tags
    1.1 Sementic VS Non Sementic tags
        1. Meaningful: Describes content | Generic: No specific meaning
        2. SEO: Good for search engines. | No SEO: not SEO-friendly.
        3. Accessibility: Useful for screen readers. | For styling: used for layout.
        4. examples: <header>, <footer>, <article>, <em>, <strong>  | <div>, <span>, <i>, <b> etc
NOTE: learn this in depth from mdn. (IMP for placement and viva)

2.0 Body tags
    2.1 Header tag
        1. Purpose: Used to contain introductory content or navigation links.
        2. Semantic: It's a semantic tag, providing meaning to the enclosed content.
        3. Location: Commonly found at the top of web pages, but can also be in <article> or <section> tags.
        4. Multiple instances: can be used more than once on a page.
    
    2.2 Main tag
        1. Purpose: Encloses the primary content of the webpage.
        2. Semantic: Adds meaning, including the main content area.
        3. Unique: Should appear only once per page.
        4. Accessibility: Helps screen readers identify key content.
        
        2.2.1 Section Tag
            1. Purpose: Groups related content in a distinct section.
            2. Semantic.
            3. Headers: Often used with a heading <h1> to <h6> to indicate 
            4. Nested: Can be nested within other <section> or <article> tags.
        
        2.2.2 Article Tag
            1. Purpose: Encloses content that stands alone, like a blog posts (or any long text)
            2. Semantic.
            3. Independence: Content should make sense even if taken out of the page. (not specifically dependent on the page to convey its meaning)
            4. Multiple Instances.
        
        2.2.3 Aside Tag
            1. Purpose: Contains sidebar or supplementary content.
            2. Semantic.
            3. Not crucial: Content is not that essential to understand the main purpose or content of the webpage.
            4. Examples: could hold widgets, quotes or ads.
    
    2.3 Footer Tag
        1. Purpose: For footer content like extra info or links.
        2. Semantic.
        3. Location: Typically at the bottom of pages or sections.
        4. Content: Includes copyrights, contact info, social links etc.
        5. Multiple instances.
    
    2.4 Nav Tag
        1. Purpose: Encloses navigation links or menus.
        2. Semantic: Signals that the content is meant for navigating the site.
        3. Content: Usually contains lists of links.
        4. Accessibility: Aids screen readers in identifiying site navigation.
        5. Location: usually located in <header> section of the page.

3.0 Folder/project structure
    3.1 Recommended Folder structure
        1. Root Directory(/.): Main folder containes all website files.
        2. HTML files(/pages or /.): main .html files are stored at the root level for easy access.
        3. CSS folder (/css): Create a css/folder for all CSS files.
        4. JS folder (/scripts): Used to store all JS scripts.
        5. Images folder(/images): stores images
        6. Assets(/assets): stores all non image assets like fonts, media etc.
        7. NOTE: more subdirectories can be created according to need.

4.0 Block elements VS Inline elements
    Block elements:
        - New line: Starts on new line.
        - Full width: Take up all horizontal space.
        - Styling: Can have margins and padding.
        - Size: Width and height can be set through CSS.
        - Examples: <div>, <p>, <h1> etc.

    Inline elements:
        - Flow: Stay in line with text.
        - Width: Just as wide as the content.
        - No line break: No new line between elements.
        - Different Styling: different options to style through CSS.
        - Example: <span>, <em>, <img>, <a> etc.
    
    4.1 Div Tag
        1. Purpose: Acts as a container for other HTML elements.
        2. Non Semantic: Doesn't provide inherent meaning to enclosed content.
        3. Styling: Commonly used for layout and styling via CSS.
        4. Flexibility: Highly versatile and can be customized using classe and Id selectors in CSS.
        5. Block element
    
    4.2 Span Tag
        1. Purpose: Used for inline elements to style or manipulate a portion of text.
        2. Non-semantic.
        3. Styling: Commonly used to change color, font, or add effects to visible text.
        4. Inline element.

# Task PROJECT level 4:
1. Create a page with header, footer, main(section, article, aside tag).
2. Make sure the project from LEVEL 2 have correct folder structure.
3. Create groupings of multiple tags using div.
4. Create navigation to important section of your page.