# Rick Mansfield's Portfolio Site v2.0

- [Rick Mansfield's Portfolio Site v2.0](#rick-mansfields-portfolio-site-v20)
  - [Contents](#contents)
  - [My Favorite Tricks](#my-favorite-tricks)
    - [Key Codes By Wes Bos](#key-codes-by-wes-bos)
  - [Responsivness (Advanced CSS)](#responsivness-advanced-css)
  - [Accessibility](#accessibility)

## Contents

- [Rick Mansfield's Portfolio Site v2.0](#rick-mansfields-portfolio-site-v20)
  - [Contents](#contents)
  - [My Favorite Tricks](#my-favorite-tricks)
    - [Key Codes By Wes Bos](#key-codes-by-wes-bos)
  - [Responsivness (Advanced CSS)](#responsivness-advanced-css)
  - [Accessibility](#accessibility)

## My Favorite Tricks

-

### Key Codes By Wes Bos

- [KeyCodes](keycodes <http://keycode.info/>) qKeyCodesq qqqq
## Responsivness (Advanced CSS)
- __OBJECTIVE__ - The objective in this project was to build a moder responsive layout for a wide variety of screen sizes to optimize device presentation for as large an audience as possible. 

- __WIDTH__ - note this project used a max-width approach or desktop-first design and "scaled down." Alternatively we could have used min-width/mobile/scale up. The decision was simply personal preference. 
  - __META TAG__ - the viewport meta tag was used at the top of the index.html file to set up mobile browser reading of media queries at the bottom of the /style/index.css file. Hence, I've incorporated @media quieries for tablet <800px and mobile <500px.

- __UNITS__ - Efforts were maid to utilize rem, %, vh, and vw consistently throught the project so support the objective. Few if any static choices were applied in this "responsive" project with preference to % and rem. 
  
## Accessibility 

- __SEMANTIC TAGS__  - are used throughtout this project.

  - A semantic tag in HTML is a tag whose name clearly describes its purpose and its content. HTML5 introduced several new semantic tags. Semantic tags: these clearly define their content.
  
  ```javascript
  <form>, <header>, <table>, and <article> 
  ```
  - Non-Semantic examples include:
  ```javascript
  <div>, <span> <p>
  ``` 
