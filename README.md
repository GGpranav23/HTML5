# HTML5
HTML5 is the fifth revision of the HTML.


# How HTML works in the browser?

1. *Request and Fetch:* The Browser requests an HTML file from a server

2. Parsing: The Browser Parses the HTML into DOM (Document Object Model), a tree-like structure representing the page's content.

3. Rendering: 

    a. CSSOM (CSS Object Model): Linked CSS is parsed into CSSOM, which determines styling.
    b. Render Tree: The DOM and CSSOM combine to form a render tree.
    c. Layout: The browser calculates position and size of elements 
    d. Paint: Pixels are drawn to the screen 

4. JavaScript Execution: Scripts Modify the DOM/CSSOM, potentially triggering re-rendering.

5. APIs: HTML5 Introduces APIs (eg. Geolocation, Web Storage, Canvas) that browser implements for enhanced functionality.