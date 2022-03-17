# HW01_CodeRefactor

In this refactoring assignment, most changes were made in the css stylesheet. The HTML file is already concise, it was just lacking comments to make quickly understanding difficult. The stylesheet, however, contained many repetitive classes that were easily consolidated. The webpage uses the same fonts and font sizes throughout, so having a different class for every single page aspect was redundant. The CSS code was cut down from 200 lines to 127.

**Link to deployed application:**
>https://autumnlf.github.io/HW01_CodeRefactor/

## Changes Made to HTML
* Added comments throughout to explain what the code was creating and to denote different sections.

* Class names changed to match refactored CSS stylesheet.

## Changes Made to CSS
* Reordered IDs and Classes to align with order of HTML. Body style and styles that were consistent throughout page (like text style for paragraphs) are at the top of stylesheet, then ordered as they appear within HTML.
* I consolidated styles that were the same but given different class names. For example:

    this code below
    ```
    .benefit-lead img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
    }
    
    .benefit-brand img {
        display: block;
        margin: 10px auto;
        max-width: 150px;
    }

    .benefit-cost img {
        display: block;
        margin: 10px auto;
        max-width: 150px;
    }
    ```
    becomes
    ```
    .benefit-info {
    margin-bottom: 32px;
    color: #ffffff;
    }
    ```
* For the "Hero" image portion of the webpage, I made a few changes to help with consistency. The image source was originally referenced in the CSS file. I changed this to be in the HTML as this is where all other images are referenced. 

## Screenshots:

![Capture of deployed application](./images/screencap%20of%20full%20site.png)

![Screen capture of desktop](./images/Screenshot%20on%20desktop.png)

