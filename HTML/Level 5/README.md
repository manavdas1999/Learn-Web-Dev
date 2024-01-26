
# Lists, Tables & Forms.

1.0 Lists
    1.1 Ordered Lists
        1. Purpose: Used for creating lists with items that have a specific ordering.
        2. Default: Items are automatically numbered.
        3. Nesting: Can be nested within other lists.
    1.2 Types of ordered lists (attribute - type="value")
        - Numeric: (default) 1,2,3,4.. (type="1")
        - Uppercase Letters: A,B,C,D.. (type="A")
        - Lowercase Letters: a,b,c,d.. (type="a")
        - Uppercase Roman: I, II, III.. (type="I")
        - LowerCase roman: i, ii, iii.. (type="i")
    1.3 Unordered Lists
        1. Purpose: Used for lists where the order of items doesn't matter.
        2. Default: Items are usually bulleted.
        3. Nesting: Can be nested within other lists.
    1.4 Types of unordered lists (attribute - type="value")
        1. disc (default)
        2. circle
        3. square
        4. none

2.0 Tables
    2.1 table tags
        1. <tr> Table row: used to define a row in an html table.
        2. <th> Table Header: used for header cells within a row. (text is bold and centered by default)
        3. <td> Table data: Holds the actual data.
        4. <caption>
            1. Purpose: Provides a title or description for a table
            2. Placement: Must be inserted immediately after the opening <table> tag.
            3. Alignment: Centered above the table by default.
            4. Accessibility: Helps screen readers to understand the table's purpose.
        5. colspan attribute:
            1. Purpose: Allows a cell to span multiple columns horizontally.
            2. Attribute: use the colspan attribute in <td> or <th> tags.
            3. Value: takes the specific no. of columns to span over.
            4. Layout: useful for combining cells to create complex table layouts.
    Syntax:
    <table>
        <tr>
            <th><th>...
        </tr>
        <tr>
            <td></td>...
        </tr>
    </table>
NOTE: There are some more tags related to table which you can check out in MDN

3.0 Forms
    3.1 Input tag
        1. Purpose: Used within a <form> element to collect user input.
        2. Self closing.
        3. Attributes: 
            1. name: to identify the particular input field among others upon submittion. It must be unique for each input element.
            2. value: sets initial value for input elements. This is the data sent when form is submitted.
            3. placeholder: text for placeholder
            4. required: to make it necessary to be filled.
            5. type: (IMP) describes the type of input. eg- text, password, date, checkbox etc.
    3.2 Label tag
        1. Purpose: Adds a text description to form elements.
        2. "for" attribute: Connects the label to a specific input element using the element's ID.
        3. Assessibility: Makes the form more accessible.
        4. Readability: Enhances form readability and usability.
        5. Semantic tag, Inline element
    3.3 Action attribute
        1. Purpose: Specifies the URL to which the form data should be sent when submitted.
        2. Default: If not specified, the form will be submitted to the current page's URL.
        3. Server-side: Usually points to a server side script(like PHP, python, JS etc) that processes the form data.
        4. trigger: action is triggered when submit button is clicked. (form is submitted)
    3.4 Some common Input Types: (explore all of these from MDN for important attributes)
        1. text *
        2. password *
        3. date
        4. file
        5. color
        6. range *
        7. button
        8. submit *
        9. radio *
        10. reset *
        11. checkbox *
        12. select * (and option)
        13. number
        14. textarea * (a completely different tag)
            1. Purpose: used for multi-line text input in forms.
            2. rows attribute: specifies the visible no. of rows in a textarea (can be extended).
            3. cols attribute: specifies the visible no. of characters per row.
            4. Resizable: some browsers allow users to manually resize the textarea.

4.0 iFrame Tag
    1. Purpose: Embed content. Allows you to embed another webpage or multimedia content within a webpage.
    2. "src" attribute: Specifies the url of the content to be embedded.
    3. Dimensions: "width" and "height" can be used to set.
    4. Security: lots of websites/content does not allow to embed themselves.

# PROJECT level 5:
1. Create a page with all type of ordered list and one unordered list.
2. Create a table with headings, captions and a few rows. One of the heading should take at least 3 columns.
3. Create a "contact me" form with relevant details for your resume website.
4. Use iFrame to add a youtube video to your page.


        






