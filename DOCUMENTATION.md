# What i learned:

## what is the life cycle of a website:

- Zoning: is the process of sketching a webpage’s basic layout by dividing it into functional blocks, such as headers, navigation bars, hero sections, and footers—before adding colors, images, or detailed text.
- Wireframing: the process of creating a basic, skeletal blueprint of a website that maps out its layout, content hierarchy, and core functionality before any visual design or coding begins.
- Mockup: a static, high-fidelity visual representation of a web page that shows how the final site will look, including colors, typography, layout, and images, but it is not functional or clickable.
- Prototyping: is the process of creating an early, clickable, or visual model of a website before writing heavy production code.
- Development:  is the technical process of building, coding, and maintaining websites and web applications that run on the internet or private networks.

## UX & UI Design:

- UX design: is about a user’s overall experience with a product. This involves thorough research and testing to pinpoint exactly what users expect from a product. UX designers use these findings to design intuitive and enjoyable products.
- UI design: focuses on the visual elements, the buttons, colors, and layouts that users interact with. It’s about creating interfaces that are aesthetically pleasing and easy to navigate.

## SEO (Search Engine Optimization):

- SEO is the process of improving a website's visibility in search engine results to attract organic traffic.
- by: 

    - Optimize the page title.
    - Write a relevant meta description.
    - Use a clear heading hierarchy.
    - Add descriptive alternative text to images.
    

## HTML5 (HyperText Markup Language):

### why we need to declare Doctype?

- The <!DOCTYPE> declaration is an instruction to browsers to tell them which version of html we use.
- Ensure the browser to use standards mode for rendering the page indtead of quirks mode.


### Html tags:

- Types of HTML elements:

    - Closing tags: elements that have an opening tag and a closing tag, with content between them (ex: h1... ).
    - Void elements: elements cannot contain child elements and do not require closing tags (ex: input... ).

- Semantic and non-semantic elements:

    - Semantic elements: communicate the meaning or purpose of their content to browsers, developers, search engines, and assistive technologies. (ex: header... ).
    - Non-semantic elements: do not describe the specific meaning of their content. They are mainly used as generic containers or for styling and grouping (ex: div... ).

## Basic HTML Structure:

- An HTML document follows a standard structure that organizes content and helps browsers interpret the page correctly.
```html
<!DOCTYPE html>
<html ...>
    <head>
        <meta ...> 
        <title>...</title> 
    </head> 
    <body> 
        <header> 
            <!-- content --> 
        </header> 
        <nav> 
            <!-- content --> 
        </nav> 
        <main> 
            <!-- content --> 
        </main> 
        <footer> 
            <!-- content --> 
        </footer> 
    </body> 
</html>
```
## css3 (Cascading Style Sheets):

### css rules:

- CSS rule consists of a selector and a declaration block.

``` css
h1 { 
    color: #C2410C; 
    font-size: 32px; 
    text-align: center; 
}
```
- Selector (h1): identifies the HTML elements to style.
- Property (color): specifies what to change.
- Value (#C2410C): specifies how the property should appear.
- Declaration: a property and its value, ending with a semicolon.

### Ways to Apply CSS:

- Inline CSS: uses the `style` attribute directly on an HTML element.
- Internal CSS: uses a `<style>` element inside the HTML `<head>`.
- External CSS: uses a separate `.css` file linked through `<link rel="stylesheet" href="style.css">`.

### CSS Selectors:

| Selector     | Example   | Purpose                                  |
| ------------ | --------- | ---------------------------------------- |
| Element      | `p`       | Selects all paragraphs                   |
| Class        | `.card`   | Selects elements with the class `card`   |
| ID           | `#header` | Selects the element with the ID `header` |
| Universal    | `*`       | Selects all elements                     |
| Descendant   | `.card p` | Selects paragraphs inside `.card`        |
| Pseudo-class | `a:hover` | Styles a link when hovered               |
| Grouping     | `h1, h2`  | Applies styles to both headings          |

### The Cascade, Specificity and Inheritance:

- the 3 rules to decide how styles are applied:

    - Cascade: When different CSS rules conflict, the browser decides which rule to apply.
    - Specificity: Some selectors have more priority than others. For example, an ID selector `#header` usually has higher priority than a class selector `.card`.
    - Inheritance: Some styles, such as `color` and `font-family`, pass from a parent element to its children automatically.

### The CSS Box Model:

- Every element is represented as a box composed of:

    - Content: text, images, or other content.
    - Padding: space between the content and border.
    - Border: the boundary around the element.
    - Margin: space outside the border.

### Typography, Colors and Spacing:

- CSS controls visual identity through properties such as:

    - Typography: font-family, font-size, font-weight, line-height.
    - Colors: color, background-color.
    - Spacing: margin, padding, gap.
    - Borders: border, border-radius.
    - Effects: box-shadow, opacity, transition.

### Layout and Positioning:

- Flexbox: Used mainly for arranging elements along one axis: a row or a column.

``` css
.container {
     display: flex; 
     justify-content: space-between; 
     align-items: center; 
     gap: 20px; 
}
```

### Positioning:

- The position property controls how an element is positioned:

    - static: normal document flow.
    - relative: positioned relative to its normal position.
    - absolute: positioned relative to its containing block.
    - fixed: positioned relative to the viewport.
    - sticky: switches between normal flow and sticking to a scroll position.



