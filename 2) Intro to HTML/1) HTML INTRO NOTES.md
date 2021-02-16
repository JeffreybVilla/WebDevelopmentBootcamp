# 1) Introduction to HTML
https://codepen.io/jeffrey-villalobos/pen/MWKEXWp
## HTML (HyperText Markup Language)
    - HTML is the main structure to a website.
    - You can create a website with only HTML code, can't do that with CSS or Javascript.
    - You can specify the layout and structure of the website using HTML Tags.
### Markup Languages
    - These langauges are based off the markup that used to be put into manuscripts where editors would mock up the manuscript.
    - The editors would specify changes to the author or specify structure and layout to the publishers.
    HTML- HyperText Markup Language
    XML - Extensible Markup Language
    GML - Generalised Markup Language
## Book Example
https://www.gutenberg.org/ebooks/1661
https://codepen.io/jeffrey-villalobos/pen/gOLLYdW
Try to format the heading the same way.

    <hr>
    <h1>The Adventures of Sherlock Holmes</h1>
    <br>
    <h3>by</h3>
    <br>
    <h2>Arthur Conan Doyle</h2>
    <hr>










# 2) The Anatomy of an HTML Tag
## Tags
    - Some tags require opening and closing tags like heading elements.
      - <h1> </h1>
    - Other tags like the line break do not need to be closed. 
      - <br>
      
## HTML Elements & Attributes
    <hr size="3">
    hr: HTML element
    size="3": HTML attribute
    size="3 noshade": HTML attribute
    
    
    
    
    
    
    
    
    
# 4) HTML Boilerplate
    <!DOCTYPE html>
    <html lang="en" dir="ltr">
      <head>
        <meta charset="utf-8">
        <title></title>
      </head>
      <body>

      </body>
    </html>

## Meta element
    - Character set is utf-8.
    - All the text in this website is encoded in UTF-8 system. 

    <head>
      <meta charset="UTF-8">
      <meta name="description" content="Free Web tutorials">
      <meta name="keywords" content="HTML, CSS, JavaScript">
      <meta name="author" content="John Doe">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
    </head>

    - These meta tags tell the browser how it should render/display the page.
    - The tags also give info to search engines about the content on website. 








# 5) How to Structure Text in HTML
     - We want to give meaning to the text not stylize it. 
         - Better to use <em> </em> than <i> </i>
         - Better to use <strong> </strong> to make bold text
     <h2><em>Software <strong>developer.</strong></em></h2>









# 6) HTML Lists
## Ordered List
    An ordered list starts with the <ol> tag. 
    Each list item starts with the <li> tag.
    The list items will be marked with numbers by default:

    <ol>
      <li>Coffee</li>
      <li>Tea</li>
      <li>Milk</li>
    </ol>  
## Unordered Lists
    An unordered list starts with the <ul> tag. 
    Each list item starts with the <li> tag.
    The list items will be marked with bullets (small black circles) by default.

    <ul>
      <li>Coffee</li>
      <li>Tea</li>
      <li>Milk</li>
    </ul>

## Nested Lists
    - A Nested List
    - Lists can be nested (list inside list)

        <ul>
          <li>Coffee</li>
          <li>Tea
            <ul>
              <li>Black tea</li>
              <li>Green tea</li>
            </ul>
          </li>
          <li>Milk</li>
        </ul>
