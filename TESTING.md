# Testing

## Contents 
   - [Automated Testing](#automated-testing)
   - [Testing User Stories](#testing-user-stories)
   - [Manual testing](#manual-testing)
   - [Bugs](#bugs)
      * [Found and Fixed](#found-and-fixed)
      * [Existing](#existing)


## Automated Testing

The W3C Markup Validator and W3C CSS Validator were used to validate every page of the project to ensure there were no 
syntax errors in the project.

-   [W3C Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) 

    Initial testing
    - index.html

    ![Initial index html test](assets/testing-images/initial-html-test.png)

    From this I removed the aria label from the badges, reformatted my comment and removed figcaption from my 
    picture. Changed the figcaption to paragraph, but did not like either so just made it an img element with a 
    paragraph below for the attribute.

    - evidence.html

    ![Initial evidence html test](assets/testing-images/initial-html-test2.png)

    I had missed a bracket in the media attribute of a few source elements so I added them in.
    
    ![Initial evidence html test](assets/testing-images/initial-html-test3.png)

    I had put paragraph elements in my iframes to give a message with a link to the video in the event that
    the video would't load. This isn't allowed so I put the paragraph below the iframe and encased them both
    in a div. Styled with media queries to be responsive.
    Near the end of the project I re-ran it through and I had to remove loading, width and height attributes from 
    the source elements. 
    
    - contact.html

    ![Initial contact html test](assets/testing-images/initial-html-test4.png)
    
    Final testing (for those that needed fixed)
    - index.html

    ![Final html text](assets/testing-images/final-html-test.png)

    - evidence.html

    ![Final html text](assets/testing-images/final-html-test2.png)


-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) 
    
    Initial testing

    ![Initial css test](assets/testing-images/initial-css-test2.png)

    Had wrote display:relative instead of position: relative for an image.
    Had also put text-decoration: 0 instead of none.

    ![Initial css test](assets/testing-images/initial-css-test.png)

    Ran again near end of project and I hadn't put px in some of the font-size styles.

    Final testing

    ![Final css text](assets/testing-images/final-css-test.png)

-   Lighthouse in devtools
    
    Landing page

    Initial lighthouse score for landing page was Performance 77, Accessible 92, Best Practices 87 and SEO 91
    From this I added in meta description, keywords and author. rel:noopener to my links and changed an h2 to an h5. 
    I had used in the h2 in my fact-box where I should have used the h5 and styled the font-size. I also had skipped 
    h3 so I changed the h4's to h3's.

    

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