This is an assignment for The Odin Project. What follows is a paraphrasing of the instructions given for this assignment.

General
- mimic the given design, but don't worry about getting it pixel-perfect.
- Feel free to substitute your own content.
- Ensure any images are free for you to use, and credit the image creator (put the creator’s name and contact info in you README file AND find free images @Pexels, Pixabay, and Unsplash)

Assignment
- The font that’s being used in the images is roboto.
- Hero text is the statement that appears at the top of a web page.
- 4 main sections and a footer
- Don't worry about optimizing for mobile

Publishing
- name the main HTML file index.html
- odin-landing-page repo > Settings
-  Pages (left side bar)
- Change source from "none" to "main branch" >  Save

The lines below are my notes for the structure of the html, including some odin css requirements.

basic HTML structure
- header div 
- content div
    - hero div - background-color: #1F2937 
        - text div
        - image div
    - tiles div
        - heading div
        - tile container div
            - 4 divs rounded tile w/text beneath
    - quote div
        - quote div
    - call to action div
        - call to action div
- footer div
    height: 5vh;
    background-color: #1F2937 



Basic Css plan
body{
    font-family: roboto, Nunito, sans-serif
}

header div 
    height: 6vh;
    background-color: #1F2937
    font-size: 24px;
    color: #F9FAF8;

header links (a), 
hero secondary text,
text beneath tiles, /* color might be wrong */
call to action subtext,
footer text
    font-size: 18px;
    color: #E5E7EB;


content div (container)
    height: 90vh;

first div (containing two divs, one with "this website is awesome")
    background-color: #1F2937 
    height: 25vh;
    display: flex;
    justify-content: center;
    align-content: center;

"This website is awesome
    font-size: 48px;
    font-weight: extra-bold;
    color: #F9FAF8;

button
    rounded edges
    background-color: #3882f6
    font-size: 18px;
    font-weight: bold;
    color: #F9FAF8;
    border: none;

second div (flex)
    height: 26vh;

centered text div nested within second div
    font-size: 36px;
    font-weight: extra-bold;
    color: #1F2937

4 divs nested within second div (housing 4 centered, rounded tiles w/text beneath)
    display: flex;
    justify-content: center;
    align content: center;

4 centered, rounded tiles
    border: 1px solid #3882f6;

third div
    height: 21vh;
    background-color: #E5E7EB;
    display: flex;
    justify-content: center;
    align content: center;
    color: #1F2937

quote
    font-size: 36px;
    font-weight: light;
    /* italics */

attribution /* float right? */
    font-size: 24px;
    font-weight: bold;

fourth div
    display: flex;
    justify-content: center;
    align content: center;
    height: 17vh;

call to action div nested within 4th div
    height: 6vh;
    background-color: ;
    /* rounded edges */
    font-size: 24px;
    font-weight: bold;
    color: #F9FAF8;

- footer div
    height: 5vh;
    background-color: #1F2937 
    justify-content: center;
    align content: center;

