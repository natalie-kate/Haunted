# Testing

## Contents 
   - [Automated Testing](#automated-testing)
   - [Testing User Stories](#testing-user-stories)
   - [Manual testing](#manual-testing)
   - [Bugs](#bugs)
      * [Found and Fixed](#found-and-fixed)
      * [Existing](#existing)


## Automated Testing

The W3C Markup Validator and W3C CSS Validator were used to validate every page of the project to ensure there were no syntax errors in the project.

-   [W3C Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) 

    Initial testing
    ![Initial html test](assets/testing-images/initial-html-test.png)
    Final testing
    ![Final html text](assets/testing-images/final-html-test.png)
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) 
    
    Initial testing
    ![Initial css test](assets/testing-images/initial-css-test.png)
    Final testing
    ![Final css text](assets/testing-images/final-css-test.png)
-   Lighthouse in devtools

-   Chrome Dev tools for responsiveness


## Testing User Stories 

- ### First Time Visitor 

 1. As a first time visitor, I want to easily understand the main purpose of the site. 
   <span style="color: grey;">The content overlay has a ghost icon that links to ghost stories, slogan of "Do you
    believe in Ghosts", and directly below is an About paragraph with the first sentence 
    explaining the purpose of the site.</span>
 2. As a first time visitor, I want to be able to easily navigate throughout the site to find content.<br>
   <span style="color: grey;">The nav menu is at the top of all pages with drop down menus to find and jump to the section of 
   interest. The brand name is also a link back to home.
   In addition a "back to top" link is present in the footer meaning the user doesn't have to scroll back up to 
   the top, which is especially important for the mobile site.</span>
3. As a first time visitor, I expect to see an attractive, visually appealing site.
    <span style="color: grey;">Used blocks of colour as the background colours for section headings to break up the page,
    and highlight a new section. Information is presented in different formats and hover effects draw attention to links 
    and call to action buttons. The same colours were consistantly used across the site for predicatability and simplicity 
    and doesn't look too busy which can be off putting.</span>
4. As a first time visitor, I expect an accessible site.
   <span style="color: grey;">Aria labels, screen reader only text and alternative text have been used throughout the site. 
   Styled the outline of keyboard focus making it more obvious as to where they are on the page and colour ties in with the 
   other colours on the screen. All colour contrast scores were a pass in chrome dev tools and accessibility score was 100%.
   As the buttons have an animation hover effect added in code in the case of user prefers reduced motion to turn the animation 
   off but to change colour instead so they still see clickable elements. </span>
5. As a first time visitor, I expect the site to look good on any device I choose to use.
   <span style="color: grey;">Designed with mobile first in mind, using bootstrap and media queries to ensure that on all screen 
   sizes that the site looks good with no escaping contents or horizontal scrolling and that the hero and header images are positioned 
   correctly as these are what people see first upon loading so they have to be perfect. As mobile users can't see hover effect on 
   buttons, gave them a border colour to make it clearer that they are clickable.</span>


- ### Returning Visitor Goals

1. As a returning visitor, I want to easily identify new content.
   <span style="color: grey;">Bright badges have been used to highlight in the nav which page contains new 
   content, in the dropdown menu the section also has a badge and when you are taken to this section the new content
    itself is highlighted with the badge.</span>
2. As a returning visitor, I want to see social media links so that I can follow on my chosen platforms.
    <span style="color: grey;">At the bottom of each page is the social platform icons with links to the pages. Only 
    takes you to the social media platform itself as accounts for this website don't exist in real life.</span>
3. As a returning visitor, I want to see recommended resources to learn more.
    <span style="color: grey;">This is one of the main nav menu items and therefore easy to find and navigate to.</span>
4. As a returning visitor, I want to be able to contact the owner with comments or questions.
    <span style="color: grey;">The contact page is one of the main nav items so is easy to find and navigate to. The 
    form has a text box to enter commentsand/or questions.</span>

- ### Frequent Visitor Goals

1. As a frequent visitor, I want to easily identify new content.
    <span style="color: grey;">Bright badges have been used to highlight in the nav which page contains new 
   content, in the dropdown menu the section also has a badge and when you are taken to this section the new content
    itself is highlighted with the badge. </span>
2. As a frequent visitor, I want to sign up to the mailing list so that i'm informed of new content or features.
    <span style="color: grey;">Contact is one of the main nav items so its easy to find and navigate to and there is a 
    checkbox to select to be added to the mailing list.</span>
3. As a frequent visitor, I want to send stories, pictures or videos to be added to the page. 
    <span style="color: grey;">Contact is one of the main nav items so it is easy to find and navigate to. There is a 
    text box to add a story and a file upload input for pictures and videos. There is also a call to action button in the 
    landing page container to "Tell us your true stories", and two in the evidence page to "Share your experiences" and 
    "Share your photos and pictures"</span>

   

## Manual Testing

-   The website was viewed with browsers: Internet explorer, Google chrome, Safari, Microsoft Edge, Chrome for 
    android, Firefox and Opera. Viewed all three pages on each and checked the links. Found that the contact form 
    link to resource section was wrong so that was amended.
-   Viewed manually on Macbook air 13", Dell 21" HD screen, iphone 11, Dell 17" laptop and Pixel 4XL phone.
-   Friends, family and slack peer review reported no issues. One commment was to increase spacing after 
    picture section and video heading which I did. 
-   Chrome devtools used to test responsiveness, viewed all pages on all of the available devices.
-   Links 

## Bugs

   ### Found and Fixed

   ### Existing