
# Introduction to HTML  

## What is HTML?  
HTML (HyperText Markup Language) is the foundation of web development.  
It defines the structure and content of a webpage using various tags and elements.  

## Why Use HTML?  
- HTML is the standard language for creating web pages.  
- It works on all modern web browsers.  
- It supports multimedia elements like images, videos, and audio.  
- It is easy to learn and widely used in web development.  
- It forms the basis of front-end web development.  

## When to Use HTML?  
- When building static or dynamic web pages.  
- When creating structured content for the web.  
- When developing web applications along with CSS and JavaScript.  
- When designing emails, documents, or other web-based content.  

## How to Use HTML?  
- Create an HTML file with a `.html` extension.  
- Use HTML tags to define elements such as headings, paragraphs, links, and images.  
- Structure content using elements like `<head>`, `<body>`, `<h1>`, `<p>`, `<a>`, etc.  
- Open the HTML file in a web browser to view the rendered output.  
- Combine HTML with CSS for styling and JavaScript for interactivity.  

## Features of HTML  
- Simple and easy to learn.  
- Supports multimedia integration.  
- Allows hyperlinking between different pages.  
- Responsive design capabilities with meta tags and CSS.  
- Supports form handling for user input.  

## Limitations of HTML  
- Cannot provide dynamic behavior without JavaScript.  
- Requires CSS for advanced styling and layout.  
- Lacks built-in security features.  
- Cannot interact with databases directly without backend support.  

## IN short 
HTML is the foundation of web development and is essential for creating web pages.  
It provides a structured way to present content online.  
Learning HTML is the first step toward becoming a web developer.  



# Explanation of Basic HTML Structure  

## 1. `<!DOCTYPE html>`  
- Declares the document type as HTML5.  
- Ensures that the browser interprets the document as modern HTML.  

## 2. `<html lang="en">`  
- The root element of the HTML document.  
- The `lang="en"` attribute specifies that the content is in English.  

## 3. `<head>` Section  
- Contains metadata and links to external resources.  
- Metadata includes the title of the page and stylesheets.  

### a) `<title>Page Title</title>`  
- Defines the title of the webpage.  
- Appears on the browser tab and in search engine results.  

### b) `<link rel="stylesheet" href="styles.css">`  
- Links an external CSS file (`styles.css`) for styling.  
- `rel="stylesheet"` specifies that the linked file is a stylesheet.  
- `href="styles.css"` provides the path to the CSS file.  

## 4. `<body>` Section  
- Contains the visible content of the webpage.  

### a) `<h1>Hello, World!</h1>`  
- A heading element, defining the main title of the page.  
- `<h1>` is the largest heading in HTML, used for main titles.  

### b) `<p>Welcome to HTML basics.</p>`  
- A paragraph element, used to display text content.  
- `<p>` is used for regular text or descriptions.  

## 5. `</html>`  
- Closes the `<html>` element, marking the end of the document.  


'''html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Example Page</title>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <h1>Welcome to My Website</h1>
    <p>This is a sample paragraph demonstrating HTML structure.</p>
  </body>
</html>

'''
## Summary  
- `<!DOCTYPE html>` ensures HTML5 compatibility.  
- `<html>` wraps the entire document.  
- `<head>` contains metadata like the title and CSS links.  
- `<body>` holds the content displayed on the webpage.  
- `<h1>` and `<p>` are used to structure text content. 



# Types of HTML Tags: 

## 1. Block-Level Tags
- Block-level tags typically take up the full width of their container and start on a new line after the previous element.
- These tags define larger structural elements on the page.

### a) `<h1>` - `<h6>`
- Header tags used to define headings. 
- `<h1>` is the largest heading, and `<h6>` is the smallest. 
- These tags are used to define the hierarchy of titles on the page, with `<h1>` being the most important.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Header Tags Example</title>
  </head>
  <body>
    <h1>This is a Heading 1</h1>
    <h2>This is a Heading 2</h2>
    <h3>This is a Heading 3</h3>
    <h4>This is a Heading 4</h4>
    <h5>This is a Heading 5</h5>
    <h6>This is a Heading 6</h6>
  </body>
</html>

```

### b) `<p>`
- Used for paragraphs.
- The `<p>` tag wraps text to create a block of text, generally representing a paragraph.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Paragraph Example</title>
  </head>
  <body>
    <p>This is the first paragraph of text.</p>
    <p>This is the second paragraph. The <p> tag is used to group text into separate blocks, each representing a new paragraph.</p>
  </body>
</html>

```
### c) `<div>`
- A generic block-level container used for grouping content or applying styles.
- Commonly used for layout purposes or when applying a shared style to multiple elements.


```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Div Example</title>
  </head>
  <body>
    <div>
      <h2>This is a Heading Inside the Div</h2>
      <p>This is a paragraph inside the div element. The div is used here to group the heading and paragraph together.</p>
    </div>

    <div>
      <h2>Another Heading Inside a Different Div</h2>
      <p>This is another paragraph inside a separate div. Each div groups content for layout or styling purposes.</p>
    </div>
  </body>
</html>

```
### d) `<ul>`
- Defines an unordered (bulleted) list.
- Used when the order of list items is not important, typically with `<li>` tags inside it.


```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Unordered List Example</title>
  </head>
  <body>
    <ul>
      <li>First item in the list</li>
      <li>Second item in the list</li>
      <li>Third item in the list</li>
    </ul>
  </body>
</html>

```
### e) `<ol>`
- Defines an ordered (numbered) list.
- Used when the order of list items matters, with `<li>` tags to define each item in the list.


```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ordered List Example</title>
  </head>
  <body>
    <ol>
      <li>First step in the process</li>
      <li>Second step in the process</li>
      <li>Third step in the process</li>
    </ol>
  </body>
</html>

```
### f) `<li>`
- Defines a list item inside a `<ul>` (unordered list) or `<ol>` (ordered list).
- This tag is used to create individual items within a list.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>List Item Example</title>
  </head>
  <body>
    <h2>Unordered List (Bulleted)</h2>
    <ul>
      <li>First item in the list</li>
      <li>Second item in the list</li>
      <li>Third item in the list</li>
    </ul>

    <h2>Ordered List (Numbered)</h2>
    <ol>
      <li>First step in the process</li>
      <li>Second step in the process</li>
      <li>Third step in the process</li>
    </ol>
  </body>
</html>

```

### g) `<header>`
- Represents the header section of a page or section.  
- Typically contains the introductory content or navigation links.


```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Header Example</title>
  </head>
  <body>
    <header>
      <h1>Welcome to My Website</h1>
      <nav>
        <ul>
        <!-- Do not need to worry about a tag-->
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </header>

    <p>This is the main content of the page.</p>
  </body>
</html>

```
### h) `<main>`
- Represents the main content of the webpage.
- Typically contains the primary content and is distinct from header, footer, and navigation sections.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Main Content Example</title>
  </head>
  <body>
    <header>
      <h1>Welcome to My Website</h1>
      <nav>
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </header>

    <main>
      <h2>Main Content Section</h2>
      <p>This is the primary content of the webpage. It’s distinct from the header, footer, and navigation sections.</p>
    </main>
  </body>
</html>

```

### i) `<footer>`
- Represents the footer section of a page.
- Typically contains copyright information, links, or additional navigation.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Main Content Example</title>
  </head>
  <body>
    <header>
      <h1>Welcome to My Website</h1>
      <nav>
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </header>

    <main>
      <h2>Main Content Section</h2>
      <p>This is the primary content of the webpage. It’s distinct from the header, footer, and navigation sections.</p>
    </main>

    <footer>
      <p>© 2025 My Website</p>
    </footer>
  </body>
</html>

```
### j) `<section>`
- Used to define sections of content that are thematically related. 
- Commonly used to group content into different sections, making it easier to organize and style.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Section Example</title>
  </head>
  <body>
    <header>
      <h1>Welcome to My Website</h1>
    </header>

    <main>
      <section>
        <h2>About Us</h2>
        <p>We are a company that specializes in web development and design.</p>
      </section>

      <section>
        <h2>Our Services</h2>
        <p>We offer a range of services including web development, SEO, and digital marketing.</p>
      </section>

      <section>
        <h2>Contact Us</h2>
        <p>If you would like to get in touch, please reach out via email or phone.</p>
      </section>
    </main>

    <footer>
      <p>© 2025 My Website</p>
    </footer>
  </body>
</html>

```
## Example Usage:
```html
<h1>This is a Heading</h1>  # A header tag to define a title
<p>This is a paragraph.</p>  # A paragraph tag to display text
```

## Summary
- Block-level tags help structure the content into large sections.
- Tags like `<div>`, `<header>`, `<main>`, and `<footer>` are essential for organizing page structure.
- Headings (`<h1>` - `<h6>`) define content hierarchy, while lists (`<ul>`, `<ol>`, `<li>`) organize content.
- Tags like `<p>` and `<section>` provide clarity and structure to textual and grouped content.



# Inline-Level Tags:

## 2. Inline-Level Tags
- Inline-level tags typically sit around their content and do not start a new line after the element. 
- These tags define smaller parts of the content, often used within block-level tags like paragraphs.

### a) `<a>`
- Used to create hyperlinks.
- The `<a>` tag allows you to link to other web pages, files, or sections within the same page.
- Example: `<a href="https://example.com">This is a link</a>` will create a clickable link.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anchor Tag Example</title>
  </head>
  <body>
    <a href="https://www.example.com">Click here to visit Example.com</a>
  </body>
</html>

```

### b) `<span>`
- A small inline container used for styling or grouping content.
- It does not create any additional space, and it is mainly used for applying styles to specific parts of the content within a block.
- Example: `<span>This is inline text</span>`.


```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Span Tag Example</title>
  </head>
  <body>
    <p>This is a <span>simple</span> example using the <span>span</span> tag.</p>
    <p>We can <span>group</span> text without adding extra space.</p>
  </body>
</html>

```
### c) `<strong>`
- Used to indicate strong importance or emphasize the text.
- It usually renders the text in bold style.
- Example: `<strong>This text is important</strong>`.


```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Strong Tag Example</title>
  </head>
  <body>
    <p>It is <strong>important</strong> to follow the instructions carefully.</p>
    <p><strong>Warning:</strong> Do not attempt this at home!</p>
  </body>
</html>

```
### d) `<em>`
- Used to indicate emphasized text or to give text a sense of importance.
- It typically renders the text in italic style.
- Example: `<em>This text is emphasized</em>`.


```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Em Tag Example</title>
  </head>
  <body>
    <p>Please <em>read carefully</em> before proceeding.</p>
    <p><em>Note:</em> The deadline for submission is tomorrow.</p>
  </body>
</html>

```
### e) `<img>`
- Used to insert images into a webpage.
- The `<img>` tag is self-closing and typically requires attributes like `src` (source) and `alt` (alternative text).
- Example: `<img src="image.jpg" alt="An example image">`.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Tag Example</title>
  </head>
  <body>
    <h1>Image Example</h1>
    <p>Here is an image of a beautiful landscape:</p>
    <img src="https://via.placeholder.com/300" alt="Placeholder Landscape" />
  </body>
</html>

```
### f) `<input>`
- Used to create an input field for user interaction.
- Often used in forms for users to provide data.
- Example: `<input type="text" placeholder="Enter your name">` creates a text field for input.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Input Tag Example</title>
  </head>
  <body>
    <h1>Input Field Example</h1>
    <label for="username">Username:</label>
    <input type="text" id="username" name="username" />
  </body>
</html>

```
### g) `<button>`
- Used to create clickable buttons.
- The `<button>` tag allows you to trigger actions like submitting a form or running JavaScript functions.
- Example: `<button>Click Me</button>` creates a clickable button.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Button Tag Example</title>
  </head>
  <body>
    <h1>Button Example</h1>
    <button>Click Me</button>
  </body>
</html>

```

## Example Usage:
```html
<a href="https://example.com">This is a link</a>    link to another page
<span>This is inline text</span>  # Inline text for styling or grouping
```

## Summary:
- Inline-level tags are used for smaller content pieces within block-level elements.
- Tags like `<a>`, `<span>`, `<strong>`, and `<em>` are used for linking, styling, and emphasizing text.
- `<img>`, `<input>`, and `<button>` are commonly used for media, user input, and actions.




 # Empty Tags:

## 3. Empty Tags
- Empty tags are tags that do not contain any content.
- These tags do not require a closing tag. Only the opening tag is sufficient to represent the element.

### a) `<img>`
- Used to insert an image into the webpage.
- The `<img>` tag is self-closing and does not require a closing tag.
- It typically includes attributes like `src` (source of the image) and `alt` (alternative text to describe the image).
- Example: `<img src="image.jpg" alt="A sample image">` inserts an image with a description.


```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Tag Example</title>
  </head>
  <body>
    <h1>Image Example</h1>
    <img src="https://via.placeholder.com/300" alt="Placeholder Image" />
  </body>
</html>

```
### b) `<br>`
- Used to create a line break, meaning it starts a new line in the content.
- Often used within paragraphs or other inline content to break the text into multiple lines.
- Example: `<br>` adds a break and moves the content after it to the next line.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Line Break Example</title>
  </head>
  <body>
    <h1>Line Break Example</h1>
    <p>This is the first line.<br>And this is the second line after the break.</p>
    <p>Here is another example<br>with a line break in between.</p>
  </body>
</html>

```
### c) `<hr>`
- Used to create a horizontal rule (a line) across the page.
- The `<hr>` tag is typically used to separate sections visually, often in the middle of content.
- Example: `<hr>` creates a horizontal line across the webpage.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Horizontal Rule Example</title>
  </head>
  <body>
    <h1>Horizontal Rule Example</h1>
    <p>This is the first section of content.</p>
    <hr>
    <p>This is the second section of content, separated by a horizontal line.</p>
  </body>
</html>

```

## Example Usage:
```html
<img src="image.jpg" alt="A sample image">  # Inserts an image into the page
<br>  # Creates a line break
<hr>  # Creates a horizontal line
```

## Summary:
- Empty tags are self-closing and do not require closing tags.
- Tags like `<img>`, `<br>`, and `<hr>` serve specific purposes such as adding images, line breaks, and horizontal lines.
- These tags help with formatting and structuring the content on a webpage.


 # Self-closing Tags:

## 4. Self-closing Tags
- Self-closing tags do not require a closing tag. 
- These tags work by including specific attributes and are used to define elements that do not need content inside.

### a) `<input>`
- Used to create an input field for user interaction.
- The `<input>` tag is self-closing and is commonly used in forms for taking user input.
- It is often paired with attributes like `type`, `placeholder`, `value`, etc., to define the behavior of the input field.
- Example: `<input type="text" placeholder="Enter your name">` creates a text input field.



```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Input Tag Example</title>
  </head>
  <body>
    <h1>Input Field Example</h1>
    <label for="username">Username:</label>
    <input type="text" id="username" name="username" />
  </body>
</html>

```

### b) `<meta>`
- Used to provide meta-information about the HTML document.
- Commonly used to specify the character set, author, or description of the document.
- It is placed inside the `<head>` section of the document.
- Example: `<meta charset="UTF-8">` specifies the character encoding for the document.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Input Tag Example</title>
  </head>
  <body>
    <h1>Meta tag Example</h1>
  </body>
</html>

```

### c) `<link>`
- Used to link external resources, such as stylesheets, to the HTML document.
- Commonly used to link CSS files to style the page.
- The `<link>` tag is placed inside the `<head>` section and requires attributes like `rel` and `href`.
- Example: `<link rel="stylesheet" href="styles.css">` links an external CSS file to the page.


```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Link Tag Example</title>
    <!-- Linking an external CSS file -->
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <h1>Welcome to My Webpage</h1>
    <p>This page is styled using an external CSS file.</p>
  </body>
</html>

```
## Example Usage:
```html
<input type="text" placeholder="Enter your name">  # Creates a text input field
<meta charset="UTF-8">  # Specifies the character encoding of the document
```

## Summary:
- Self-closing tags like `<input>`, `<meta>`, and `<link>` are used to define elements that don't require a closing tag.
- These tags typically have attributes to define their behavior, such as `type`, `charset`, and `rel`.
- They are crucial for taking user input, defining document metadata, and linking external resources like stylesheets.


# Attribute Tags:

## 5. Attribute Tags
- HTML tags often come with attributes that help customize or configure their behavior and appearance.
- Attributes provide additional information about the element, such as defining links, images, and styles.

### a) `href`
- Used to define the URL of a link in the `<a>` tag.
- The `href` attribute specifies the destination of the link.
- Example: `<a href="https://example.com">This is a link</a>` creates a link that points to a URL.

### b) `src`
- Used to specify the source of an image in the `<img>` tag.
- The `src` attribute tells the browser where to find the image file.
- Example: `<img src="image.jpg" alt="A sample image">` displays an image from the specified file.

### c) `alt`
- Used to provide alternative text for an image.
- The `alt` attribute describes the image in case it cannot be displayed (e.g., broken image link or for screen readers).
- Example: `<img src="image.jpg" alt="A sample image">` gives a description of the image for accessibility purposes.

### d) `class`
- Used to assign a class name to an element.
- The `class` attribute is commonly used for applying CSS styles or targeting the element with JavaScript.
- Example: `<div class="container">` assigns a class named `container` to a `div` element for styling.

### e) `id`
- Used to assign a unique identifier to an element.
- The `id` attribute is used to target specific elements within the document, often for styling, scripting, or linking.
- Example: `<div id="main-header">` assigns a unique `id` of `main-header` to the `div` element.

## Example Usage:
```html
<a href="https://example.com">This is a link</a>  reates a clickable link
<img src="image.jpg" alt="A sample image">  # Displays an image with alternative text
```

## Summary:
- Attribute tags provide essential information to modify or configure the behavior and appearance of HTML elements.
- Attributes like `href`, `src`, `alt`, `class`, and `id` are used for creating links, displaying images, applying styles, and identifying elements uniquely.



 # Header Section:

## 1. Header Section (Header Tags: `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`)
- Header tags are used to define headings and subheadings on a webpage.
- They help in organizing content hierarchically, with `<h1>` being the most important heading and `<h6>` the least.
- These tags also help search engines understand the structure of the content.

### a) `<h1>` to `<h6>` Tags
- The `<h1>` tag is used for the main, most important heading on the page. 
- The `<h2>` to `<h6>` tags are used for subheadings, with `<h2>` being the next level of importance and so on.
- These header tags are commonly used for page titles, section titles, and subsection titles.

### b) `id` Attribute
- The `id` attribute is used to uniquely identify an element.
- It allows you to reference a specific header, either for styling or linking within the page.
- Example:
  ```html
  <h1 id="main-title">Welcome to My Website</h1>  
  ```
  This `<h1>` tag has an ID "main-title" that can be targeted by CSS or JavaScript.

### c) `class` Attribute
- The `class` attribute is used to assign a class name to the header element.
- This allows multiple elements to share the same styling or functionality.
- Example:
  ```html
  <h2 class="section-title">About Us</h2>  
  ```
  This `<h2>` tag has a class "section-title" for CSS styling.

### d) `style` Attribute
- The `style` attribute allows you to add inline CSS styles to the header.
- It is typically used for quick and specific styling of a particular element.
- Example:
  ```html
  <h3 style="color: red;">This is a red heading</h3>
  ```
  This `<h3>` tag will display the heading in red color due to the inline style.

## Example Usage:
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Header Tags Example</title>
    <!-- Title for the page -->
  </head>
  <body>
    <h1 id="main-header">Welcome to My Website</h1>  <!-- Main heading for the webpage, uniquely identified with 'main-header' -->
    <h2 class="section-title">About Us</h2> <!--Subheading for a section, styled with class 'section-title'-->
    <h3 style="color: red;">This is a red heading</h3> <!-- Inline style for red-colored heading-->
  </body>
</html>
```

## Summary:
- The `<h1>` to `<h6>` tags are used for headings and subheadings, with `<h1>` being the most important and `<h6>` the least.
- The `id`, `class`, and `style` attributes can be used to identify, group, and style header elements, respectively.
- These tags help with the organization and visual hierarchy of the webpage content, enhancing both user experience and SEO.



 # Container Section:

## 2. Container Section (Container Tags: `<div>`, `<span>`)
- The **`<div>`** and **`<span>`** tags are commonly used container elements in HTML. 
- These elements help group other elements together for layout or styling purposes.
- **`<div>`** is a block-level container used to group larger chunks of content, whereas **`<span>`** is an inline container used for small pieces of content, often for styling purposes.

### a) `<div>` (Division Tag)
- The `<div>` tag is a block-level element that is used for grouping content together. It is commonly used when you want to apply specific styles, layouts, or group elements together logically.
- The **`id`** attribute can be used to uniquely identify the `<div>` tag, the **`class`** attribute allows grouping multiple elements, and the **`style`** attribute lets you apply inline styles.
- Example:
  ```html
  <div id="container" class="content-container" style="background-color: lightgray;">
    <p>This is a paragraph inside a div container.</p>
  </div>
  ```
  In this example, the `<div>` tag groups a paragraph inside it. The `id` is used for identification, the `class` allows for multiple elements to share the same style, and the `style` applies a background color to the container.

### b) `<span>` (Inline Container)
- The `<span>` tag is an inline element used to group small pieces of content for styling or for applying specific behaviors.
- It is used when you need to style specific parts of a sentence, phrase, or text without breaking the flow of inline content.
- Example:
  ```html
  <p>My <span style="color: blue;">favorite</span> color is blue.</p>
  ```
  Here, the **`<span>`** is used to highlight the word "favorite" in blue color within the paragraph. The `style` is applied inline for that specific word without breaking the paragraph flow.

## Example Usage:
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Container Section Example</title>
  </head>
  <body>
    <!-- Using the <div> tag as a container -->
    <div id="container" class="content-container" style="background-color: lightgray;">
      <h2>About Me</h2>
      <p>Welcome to my website. This is a <strong>container</strong> for the content.</p>
    </div>
    
    <!-- Using the <span> tag to style specific content inline -->
    <p>My <span style="color: blue;">favorite</span> color is blue.</p>
  </body>
</html>
```

## Summary:
- The `<div>` tag is used as a block-level container to group elements and can have an `id`, `class`, and `style` for custom identification and styling.
- The `<span>` tag is used for inline grouping of small content and can be styled or modified without breaking the inline flow.
- Both tags help in organizing content and applying styles or behaviors, improving the overall structure and readability of a webpage.



# Listing Section:

## 3. Listing Section (List Tags: `<ul>`, `<ol>`, `<li>`)
- The **`<ul>`**, **`<ol>`**, and **`<li>`** tags are used to create lists in HTML.
- **`<ul>`** is used to create unordered (bulleted) lists, while **`<ol>`** creates ordered (numbered or roman) lists.
- The **`<li>`** tag is used to define individual list items within both **`<ul>`** and **`<ol>`**.

### a) `<ul>` (Unordered List)
- The **`<ul>`** tag creates an unordered list. Each item in the list is preceded by a bullet point by default.
- The **`id`** attribute can be used to uniquely identify the list, the **`class`** attribute is used for CSS styling, and each item within the list is defined with the **`<li>`** tag.
- Example:
  ```html
  <ul id="fruits-list" class="list-items">
    <li>Apple</li>
    <li>Banana</li>
    <li>Cherry</li>
  </ul>
  ```
  In this example, the **`<ul>`** tag creates an unordered list with three items: Apple, Banana, and Cherry.

### b) `<ol>` (Ordered List)
- The **`<ol>`** tag creates an ordered list, where items are automatically numbered or use Roman numerals, depending on the `type` attribute.
- You can also specify the **`start`** attribute to define where the numbering begins.
- Example:
  ```html
  <ol start="5" type="I">
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
  </ol>
  ```
  This **`<ol>`** will start numbering from 5 and use Roman numerals.

### c) `<li>` (List Item)
- The **`<li>`** tag is used to define an item in both unordered and ordered lists.
- Each list item is enclosed within an opening and closing **`<li>`** tag and is part of either an **`<ul>`** or **`<ol>`** tag.
- Example:
  ```html
  <ul>
    <li id="item1" class="item-class">First item</li>
#      <li id="item2" class="item-class">Second item</li>
  </ul>
  ```
  Here, two list items are defined, each with an `id` and `class` for styling or identification purposes.

## Example Usage:
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Listing Section Example</title>
  </head>
  <body>
    <!-- Unordered List -->
    <ul id="grocery-list" class="shopping-list">
      <li>Milk</li>
      <li>Bread</li>
      <li>Eggs</li>
    </ul>
    
    <!-- Ordered List -->
    <ol start="1" type="1">
      <li>First item</li>
      <li>Second item</li>
      <li>Third item</li>
    </ol>
    
    <!-- Another Unordered List -->
    <ul>
      <li>Apple</li>
      <li>Banana</li>
    </ul>
  </body>
</html>
```

## Summary:
- The **`<ul>`** tag creates an unordered (bulleted) list, and the **`<ol>`** tag creates an ordered (numbered) list.
- The **`<li>`** tag is used to define list items in both types of lists.
- The **`id`**, **`class`**, and **`start`** attributes help identify, group, and control the behavior of the lists and their items.
- Lists are an essential part of organizing content, and these tags are widely used for navigation menus, itemized content, and steps in a process.


# Image & Video Section:

## 4. Image & Video Section (Image & Video Tags: `<img>`, `<video>`)
- The **`<img>`** and **`<video>`** tags are used to display images and videos on a webpage.
- The **`<img>`** tag is used for embedding images, while the **`<video>`** tag is used for displaying videos.
- Both tags can accept various attributes to control the display and behavior of the media.

### a) `<img>` (Image Tag)
- The **`<img>`** tag is used to display images on a webpage.
- The **`src`** attribute specifies the URL of the image, and the **`alt`** attribute provides an alternative text if the image fails to load.
- The **`width`** and **`height`** attributes allow you to control the size of the image.
- Example:
  ```html
  <img src="image.jpg" alt="Description of image" width="300" height="200">
  ```
  This **`<img>`** tag will display an image with the given source, alternative text, and specified size.

### b) `<video>` (Video Tag)
- The **`<video>`** tag is used to display videos on a webpage.
- The **`src`** attribute specifies the video URL, and the **`controls`** attribute enables video controls (such as play, pause, and volume).
- The **`autoplay`** attribute automatically starts playing the video when the page loads.
- Example:
  ```html
  <video src="video.mp4" controls autoplay>
    Your browser does not support the video tag.
  </video>
  ```
  This **`<video>`** tag will display a video with controls, and the video will play automatically when the page loads.

## Example Usage:
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image & Video Section Example</title>
  </head>
  <body>
    <!-- Image -->
    <img src="image.jpg" alt="Beautiful landscape" width="500" height="300">
    
    <!-- Video -->
    <video src="video.mp4" controls autoplay>
      Your browser does not support the video tag.
    </video>
  </body>
</html>
```

## Summary:
- The **`<img>`** tag is used to display images, with attributes like **`src`**, **`alt`**, **`width`**, and **`height`** to control the image's appearance.
- The **`<video>`** tag is used to display videos, and attributes like **`src`**, **`controls`**, and **`autoplay`** control the video behavior.
- Both tags help add rich media content to a webpage, enhancing the user experience with visuals and videos.


 # Form Section:

## 5. Form Section (Form Tags: `<form>`, `<input>`, `<button>`)
- The **`<form>`**, **`<input>`**, and **`<button>`** tags are essential for creating forms in HTML.
- Forms allow users to input data, which can then be submitted to a server for processing.
- These tags are used to collect data from users, such as text, passwords, and other information.

### a) `<form>` (Form Tag)
- The **`<form>`** tag is used to create a form that collects user input and sends it to a specified URL.
- The **`action`** attribute specifies the URL where the form data will be sent after submission.
- The **`method`** attribute defines the HTTP method (usually GET or POST) used to send the form data.
- The **`enctype`** attribute specifies the encoding type for form data, especially for file uploads.
- Example:
  ```html
  <form action="/submit-form" method="POST" enctype="multipart/form-data">
    <!-- Form elements here -->
  </form>
  ```
  This **`<form>`** tag will send form data to the "/submit-form" URL using the POST method with appropriate encoding.

### b) `<input>` (Input Field)
- The **`<input>`** tag is used to create various types of input fields, like text boxes, password fields, and more.
- The **`type`** attribute defines the type of input (e.g., "text", "password", "email").
- The **`value`** attribute sets the initial value of the input field.
- The **`placeholder`** attribute provides helpful text within the input field before the user types.
- The **`required`** attribute ensures the field must be filled out before the form can be submitted.
- Example:
  ```html
  <input type="text" name="username" placeholder="Enter your username" required>
  ```
  This **`<input>`** field is for entering a username, with a placeholder text and a required field condition.

### c) `<button>` (Button Tag)
- The **`<button>`** tag is used to create clickable buttons within a form.
- The **`type`** attribute defines the button's action, such as "submit" to submit the form or "reset" to clear the form.
- The **`disabled`** attribute disables the button, preventing users from clicking it.
- Example:
  ```html
  <button type="submit">Submit</button>
  ```
  This **`<button>`** tag will create a button that submits the form when clicked.

## Example Usage:
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form Section Example</title>
  </head>
  <body>
    <form action="/submit-form" method="POST" enctype="multipart/form-data">
      <input type="text" name="username" placeholder="Enter your username" required>
      <input type="password" name="password" placeholder="Enter your password" required>
      <button type="submit">Submit</button>
    </form>
  </body>
</html>
```

## Summary:
- The **`<form>`** tag is used to collect and send user data to a server.
- The **`<input>`** tag creates various input fields, with attributes to define their behavior and appearance.
- The **`<button>`** tag is used to create buttons for form submission or resetting the form.
- These tags are fundamental in collecting user input and submitting it for processing.


 # Links & Navigation Section:

## 6. Links & Navigation Section (Link Tags: `<a>`, `<link>`)
- The **`<a>`** and **`<link>`** tags are used to create links for navigation and external resource linking in HTML.
- The **`<a>`** tag is used to create hyperlinks to other pages or websites, while the **`<link>`** tag is used to link external resources like stylesheets.

### a) `<a>` (Anchor Tag)
- The **`<a>`** tag is used to create a hyperlink to another webpage or website.
- The **`href`** attribute specifies the destination URL of the link.
- The **`target`** attribute defines where the linked document will open, such as in a new tab (`_blank`).
- The **`title`** attribute provides a tooltip when hovering over the link.
- Example:
  ```html
  <a href="https://www.example.com" target="_blank" title="Go to Example Website">Visit Example</a>
  ```
  This **`<a>`** tag creates a link that opens "https://www.example.com" in a new tab with a tooltip that appears when hovered over.

### b) `<link>` (Link Tag)
- The **`<link>`** tag is used to link external resources to the HTML document, such as stylesheets or icon files.
- The **`rel`** attribute specifies the relationship between the current document and the linked resource (e.g., "stylesheet").
- The **`href`** attribute specifies the URL of the linked resource.
- Example:
  ```html
  <link rel="stylesheet" href="styles.css">
  ```
  This **`<link>`** tag connects an external CSS stylesheet to the HTML document.

## Example Usage:
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Links & Navigation Section</title>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <a href="https://www.example.com" target="_blank" title="Go to Example Website">Visit Example</a>
  </body>
</html>
```

## Summary:
- The **`<a>`** tag is used for creating hyperlinks, allowing navigation between web pages or websites.
- The **`<link>`** tag is used for linking external resources like CSS files to the HTML document.
- These tags are essential for linking to other pages and incorporating external resources in your web projects.


 # Tables Section:

## 7. Tables Section (Table Tags: `<table>`, `<tr>`, `<th>`, `<td>`)
- The **`<table>`** tag is used to create a table structure in HTML.
- The **`<tr>`** tag defines a row in the table.
- The **`<th>`** tag defines a header cell in the table (the text inside is bold).
- The **`<td>`** tag defines a standard cell that holds data.

### a) `<table>` (Table Tag)
- The **`<table>`** tag is used to define the overall table structure.
- The **`border`** attribute specifies the border around the table.
- The **`cellspacing`** attribute defines the space between the cells.
- The **`cellpadding`** attribute defines the space between the cell content and the cell borders.
- Example:
  ```html
  <table border="1" cellspacing="5" cellpadding="10">
    <!-- Table Content Here -->
  </table>
  ```

### b) `<tr>` (Table Row)
- The **`<tr>`** tag is used to define a row in the table.
- Each **`<tr>`** contains **`<th>`** (header) or **`<td>`** (data) tags.
- Example:
  ```html
  <tr>
    <td>Row Data 1</td>
    <td>Row Data 2</td>
  </tr>
  ```

### c) `<th>` (Table Header Cell)
- The **`<th>`** tag is used for header cells in the table.
- The text inside a **`<th>`** tag is typically bold by default.
- Example:
  ```html
  <th>Column Header</th>
  ```

### d) `<td>` (Table Data Cell)
- The **`<td>`** tag is used to define data cells within the table.
- Example:
  ```html
  <td>Table Data</td>
  ```

## Example Usage:
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tables Section</title>
  </head>
  <body>
    <table border="1" cellspacing="5" cellpadding="10">
      <tr>
        <th>Header 1</th>
        <th>Header 2</th>
      </tr>
      <tr>
        <td>Data 1</td>
        <td>Data 2</td>
      </tr>
      <tr>
        <td>Data 3</td>
        <td>Data 4</td>
      </tr>
    </table>
  </body>
</html>
```

## Summary:
- The **`<table>`** tag is used to create a table structure, while the **`<tr>`**, **`<th>`**, and **`<td>`** tags define the rows, header cells, and data cells, respectively.
- The **`border`**, **`cellspacing`**, and **`cellpadding`** attributes allow for customization of the table's appearance.
- Tables are essential for displaying data in an organized, tabular format, and these tags provide a flexible way to structure and style the table.




# Media Section:

## 8. Media Section (Media Tags: `<audio>`, `<iframe>`)
- The **`<audio>`** tag is used to embed and play audio files.
- The **`<iframe>`** tag is used to embed external content such as web pages, videos, or maps.

### a) `<audio>` (Audio Tag)
- The **`<audio>`** tag is used to add audio to a web page.
- The **`src`** attribute specifies the audio file URL.
- The **`controls`** attribute displays play, pause, and volume controls.
- The **`autoplay`** attribute makes the audio play automatically when the page loads.
- Example:
  ```html
  <audio src="audio.mp3" controls autoplay></audio>
  ```

### b) `<iframe>` (Inline Frame)
- The **`<iframe>`** tag is used to embed external content, such as:
  - Another web page.
  - A YouTube video.
  - Google Maps.
- The **`src`** attribute specifies the source URL.
- The **`width`** and **`height`** attributes define the iframe dimensions.
- The **`title`** attribute provides an accessible name for the iframe.
- Example:
  ```html
  <iframe src="https://www.example.com" width="600" height="400" title="Embedded Page"></iframe>
  ```

## Example Usage:
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Media Section</title>
  </head>
  <body>
    <h2>Audio Example</h2>
    <audio src="audio.mp3" controls autoplay></audio>

    <h2>Iframe Example</h2>
    <iframe src="https://www.example.com" width="600" height="400" title="Embedded Page"></iframe>
  </body>
</html>
```

## Summary:
- The **`<audio>`** tag allows embedding audio files with playback controls.
- The **`<iframe>`** tag enables embedding of external content, such as web pages and videos.
- These media elements enhance user experience by integrating multimedia content into a webpage.



 # HTML-এ ID এবং CLASS কী? (MOST IMPORTANT)

- **ID (আইডি)** এবং **CLASS (ক্লাস)** হল HTML এলিমেন্টকে নির্দিষ্টভাবে স্টাইল বা নিয়ন্ত্রণ করার জন্য ব্যবহৃত দুটি গুরুত্বপূর্ণ অ্যাট্রিবিউট।

## 1️⃣ ID (আইডি) কী?
- ID হল একটি **ইউনিক বা অনন্য নাম**, যা একটি নির্দিষ্ট HTML এলিমেন্টের জন্য নির্ধারিত হয়।
- একটি **ওয়েব পেজে একই ID একাধিকবার ব্যবহার করা যায় না**।

👉 **ID এর বৈশিষ্ট্য:**
✔ একটি এলিমেন্টের জন্য শুধুমাত্র **একটি ID থাকতে পারে**।
✔ **একই ID নাম দিয়ে একাধিকবার ব্যবহার করা যাবে না**।
✔ **CSS বা JavaScript-এ `#id_name` ব্যবহার করে** স্টাইল বা ম্যানিপুলেশন করা হয়।

## ✅ ID এর উদাহরণ:
```html
<!DOCTYPE html>
<html lang="bn">
<head>
    <title>ID উদাহরণ</title>
    <style>
        #myHeading {
           

        }
    </style>
</head>
<body>
    <h1 id="myHeading">এটি একটি ID এর উদাহরণ</h1>
</body>
</html>
```

🔹 **উদাহরণ ব্যাখ্যা:** এখানে `id="myHeading"` দেওয়া হয়েছে, এবং CSS-এ `#myHeading` ব্যবহার করে সেটির রঙ **সবুজ** করা হয়েছে।



 ## 2️⃣ CLASS (ক্লাস) কী?
- CLASS হল **একটি গ্রুপের মতো**, যা **একাধিক এলিমেন্টকে একই স্টাইল বা ফাংশনালিটি** দিতে ব্যবহার করা হয়।
- **একাধিক এলিমেন্ট একই CLASS ব্যবহার করতে পারে।**

👉 **CLASS এর বৈশিষ্ট্য:**
✔ একটি **CLASS একাধিক HTML এলিমেন্টে ব্যবহার করা যায়**।
✔ **একটি এলিমেন্টের একাধিক CLASS থাকতে পারে**।
✔ **CSS বা JavaScript-এ `.class_name` ব্যবহার করে** স্টাইল বা ম্যানিপুলেশন করা হয়।

## ✅ CLASS এর উদাহরণ:
```html
<!DOCTYPE html>
<html lang="bn">
<head>
    <title>CLASS উদাহরণ</title>
    <style>
        .highlight {
           
           
        }
    </style>
</head>
<body>
    <p class="highlight">এটি একটি CLASS এর উদাহরণ</p>
    <p class="highlight">এই CLASS একাধিকবার ব্যবহার করা হয়েছে</p>
</body>
</html>
```

🔹 **উদাহরণ ব্যাখ্যা:** এখানে `class="highlight"` ব্যবহার করা হয়েছে, যা **CSS-এ `.highlight` দিয়ে স্টাইল** করা হয়েছে।

---

# ✅ ID এবং CLASS এর পার্থক্য (Difference between ID & CLASS)
| **পার্থক্য**  | **ID** | **CLASS** |
|--------------|--------|----------|
| **প্রয়োগ** | একটি নির্দিষ্ট এলিমেন্টে **একবার ব্যবহার করা যায়** | একাধিক এলিমেন্টে **ব্যবহার করা যায়** |
| **লিখার ধরন** | `#id_name` (CSS-এ) | `.class_name` (CSS-এ) |
| **প্রধান ব্যবহার** | নির্দিষ্ট **একটি এলিমেন্টের জন্য** | একই স্টাইল **একাধিক এলিমেন্টে প্রয়োগ করতে** |
| **JavaScript ব্যবহার** | `document.getElementById("id_name")` | `document.getElementsByClassName("class_name")` |

---

## 🚀 সংক্ষেপে মনে রাখার উপায়:
- যদি **একটি নির্দিষ্ট এলিমেন্টকে টার্গেট** করতে চান, **ID ব্যবহার করুন**।
- যদি **একাধিক এলিমেন্টকে একই স্টাইলে রাখতে চান, CLASS ব্যবহার করুন**।
- ✅ **ID ইউনিক এবং CLASS শেয়ারেবল!**