![Office pic!](assets/images/RMBT.png)
# Remember Me By Trade IT & Office Support Solutions Agency
This website is aimed mainly at Companys that have IT issues or need a position permanently or temporarily filled with a skilled member of staff based in London, the South of England. The aim is to give enough information about the site's owner - their experience and the services provided. Users of the site will be able to gain contact information, location and also submit a request for RMBT to contact them back.

From the perspective of the site owner, the aim of this website is to generate customer interaction which will generate revenue by providing information about services, showcasing skills through the company's experience in the field and encouraging potential clients to get in touch.

![Am I Responsive screeshot!](assets/images/responsive.png)

Link to deployed site:

[Remember Me By Trade IT & Ofice Support Solutions Agency](https://aol83.github.io/Remember-Me-By-Trade/)


## Strategy
----

### User Stories

This site's srategy is based on satisfying the below user scenario's:-

* As the user I need to be able to navigate around the website intuitively.

* Being the website's user, I want to find out insightful information about the company's background, their training and experience, Services and location.

* As a user of the website I want to be able to view infomation about the copmanys work ethics and reputation.


* As a user of the website I want access to contact information and be able to submit a request for a callback from the Company to show I am interested in their services.



## Structure
----

The site will consist of a Home landing page with a navigation bar and five sections, those sections consist of information on skills, services, and work history reputation with a contact form; with a thank you page which will only show when the contact form has been completed and submitted:-

<details>
<summary>Desktop Wireframes</summary>
<br>

![Wireframes](assets/wireframes/RMBT-DESKTOP.png)
![Wireframes](assets/wireframes/RMBT-TABLET.png)

</details>

<br>

<details>
<summary>Mobile Wireframes</summary>
<br> 

![wireframes](assets/wireframes/New-Wireframe-1.png)
</details>

<br>

## Design
----

The site's owner wanted a modern 2022-style website. They decided on a six-color scheme incorporating a pastel tone colour pallet from [ColorSpace](https://mycolor.space/), we checked the colour pallet using [EigthShapes Contrast Grid](https://contrast-grid.eightshapes.com/?version=1.1.0&background-colors=&foreground-colors=%23faf8f6%2C%0D%0A%2300a4fcd9%0D%0A%234244b9%0D%0A%23191641%0D%0A%23536075de&es-color-form__tile-size=compact&es-color-form__show-contrast=aaa&es-color-form__show-contrast=aa&es-color-form__show-contrast=aa18&es-color-form__show-contrast=dnp) So I decided to go with a simple design as they had chosen an eight colour palette scheme of an off-white, a shade of gray (used only on styling the navbar) these were used in contrast with a light blue for the hover state of the buttons. The dark blue colour and off-white combination for the button's statics state this gives the buttons the highest rating in compliance with [WCAG 2.0 minimum contrast](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html) for text/background.

![Contrast Grid](assets/images/contrast-grid.png)

All the images used on site have been sourced from Pexels https://www.pexels.com/  who do not require attribution or compensation to the content creator as part of the licencing conditions (https://www.pexels.com/terms-of-service/. 

Google Fonts was used to select a modern and stylish looking font for the this websit.

## Features 
----

### Existing Features



* Navigation Menu 
    - This features on all pages of this website. The style is consistent across all pages to allow the user to intuitively navigate each section of the main landing page, and its content as well as intuitively navigate to other pages like the contact form.  The navigation menu has been styled with html and css only on large screens the nav will display the page links and the logo inline at the top of the page and on small devices the nav will change in to a hambeurger drop down menu that is still usable, when hoverd over the links will change colour with a indicator line letting you know that the button is actionable.
![Navigation Menu Desktop](assets/images/nav1.png)

![Closed Navigation Menu Mobile](assets/images/NAV_mobile-closed.png)

![Open Navigation Menu Mobile](assets/images/NAV-mobile-open.png)

* Footer 
    - Social Media Links to Facebook, Instagram and twitter with active transitions in color allow the user to know the link is active so they can stay connected to the companys activities and see regular posts.
    - Telephone number and email address in footer on every page.  This means that the user does not have to navigate to a different page to have access to this information if they decide they want to email or telephone. 

![Footer](assets/images/Responcive-footer-A.png)
![Footer](assets/images/Responcive-footer-B.png)   
  

* Home Page Features
    -The hero-image on landing page is quite eye catching with the contrast between the bright colours natural tones it become very striking. the about section leaves out enough information to entice the site user to make an enquiry.
    - There is also a contact button within the navbar which links directly to the contact form page.  This acts as a call to action to encourage the site user to submit their details to arrange a callback.  The contact button has a hover effect applied so the buttons background changes when it is hovered over to draw attention to itself. The same effect is used on all buttons across the site.

![Hero Image and Overlay Text](assets/images/Hero-img.png)
![Main Page and Overlay Text](assets/images/services-section.png)
![Services Images and Overlay Text](assets/images/about.png)
![Ifram Location Image with Overlay Text And Social Links](assets/images/iframe.png)   


* Home Page Features Continued...
    - The home page consists of the following one landing page with an image a welcome message in the head, beneath that is an information section with a small brief then another section containing three further images and information about services. Then the first information box provides the site user with introduction about RMBT IT & Office Support Solutions Agency, their training, experience, and work ethos. There is also a links at the bottom of the page that encourage the user to visit us on our socila networks.  
    - The second information box provides brief contact information.
    - The information boxes are styled with a darker colour so that text is allowed to stand out.
    - As a decorative feature for this section. These are displayed next to each other on larger screens, but stacked on top of each other when on smaller screens, like mobile phones.
     - The iframe map feature is to show the companys location I felt adding this was important. 


* Contact Form
    - Input fields to submit name, company name, phone, and email address.
    - Text area to add information for a message to RBMT.
    - Submit button - With background effect. This button currently links to a thank-you page where a thank you message that will be displayed to let the user know their information has been submitted and RMBT will be in contact in due course. 
    - Each field has a ```required``` attribute applied to ensure users input all fields before submitting.The contact form is responsive on desktop devices and on smaller devices the contact content is stacked. 

![Contact Form Screenshot](assets/images/contact-form.png)


* Thank-you Page
    -Thank-you page will only appear when the contact form has been fully completed and submitted.  It will display a short message to thank the users for getting in contact and confirming the RMBT will be in contact in due course.

![Thank You Page Screenshot](assets/images/thank-you.png)
<br/>



## Testing
----

I have tested all aspects of the site functionality including all links, inputs and responsiveness  as best as possible through Dev Tools, Chrome & lighthouse for the following devices. (I would have liked a more extensive and in depth testing script but with the little time I had left my testing is as follows):-

* LG G6
* iPhone 5/SE
* iPhone 6/7/8
* iPhone 6/7/8 Plus
* iPhone X
* iPhone 11 Pro
* iPad
* iPad Pro
* Surface Due


I tested the site physically on the below devices:

* iPhone 13 pro
* iPhone 11 Pro
* Mac Book Pro 
* HP (Laptop)

I have also tested the site using the following browsers:-

* Chrome
* Safari
* Edge
* Brave


### Validator testing 

* CSS file has been run through W3C CSS Validator and no errors have been found.  Two warnings have been found although these related to imported stylesheets which are not checked by the validator.
* All HTML files have been passed through the W3C HTML Validator and no errors have been found. 

<details>

![W3C CSS Validator Results (Jigsaw)](assets/testing/CSS-W3C-PASS.png)
![W3C CSS Validator Warnings (Jigsaw)](assets/testing/W3C-CSS-WARNINGS.png)

<summary>CSS (W3C Validator)</summary>

</details>

<br>

<details>

![W3C Validator Testing - Home Page](assets/testing/INDEX.HTML-W3C-PASS.png)
![W3C Validator Testing - Contact](assets/testing/CONTACT.HTML-W3C-PASS.png)
![W3C Validator Testing - Thank-you Page](assets/testing/THANKYOU.HTML-W3C-PASS.png)


<summary>HTML (W3C Validator)</summary>

</details>

<br>

<details>

![Lighthouse Testing - Home Page](assets/testing/index-lighthouse-scoure.png)
![lighthouse Testing - Contact](assets/testing/contact.html-lighthouse-scoure.png)
![lighthouse Testing - Thank-you age](assets/testing/THANKYOU-lighthouse-scoure.png)

<summary>Lighthouse Testing</summary>

</details>

### Accessibility Testing

The full site has been passed through wave.webaim.org to check for accessibility the only error found was for a span that is necessary for my nav to work so error could not be resolved and the full report can be found  [here.](https://wave.webaim.org/report#/https://aol83.github.io/Remember-Me-By-Trade/)


### Bugs
---

* One of the issues I had from the beginning of this project was getting my nav to be responsive, and to change into a working hamburger drop down menu when on small devices, and a positon inconsistency i found but after talking to fellow students and mentors adding a position of fixed and text align of center got it resolved.  

* The responsive contact form was the biggest issue i hand on this project, because when i had originally put my contact form together, it was styled desktop first instead of mobile first, so i struggled to get my media quires to work, in the end i had to strip back, and start again with mobile first, and work up from there. Doing this resolved many styling issues i had encountered.


## Deployment 
----
 This site was depoloyed to GitHub pages.  The steps taken to deploy the site are as follows:

 * In the GitHub respository, select the settings menu
 * Choose the pages tab on the left hand side menu
 * From the source section drop-down menu, select the 'Main' branch
 * Once the page has automatically refreshed, the link to the successfully deployed page will be displayed.

Live link found here:  [RMBT SUPPORT SOLUTIONS](https://aol83.github.io/Remember-Me-By-Trade/)

## Credits
----

* I used similarly structured code for my home page, nav bar and footer as taught in the 'Love Running Walkthrough Project' on the [Code Institute's](https://codeinstitute.net/) Full Stack Web Development course and then made my changes from there as i wanted to add a bit of my own artistic flare to it. I did change somemof the styling, but ultimately I was aiming for a simliar layout for my main page and navigation links/footer and as this was my first project this code helped me to get off to a good start.

* [CSS-Tricks](https://css-tricks.com/) has been an invaluable resource and I have read many articles relating to positioning, flexbox, and styling my contact form.

* [W3 Schools](https://www.w3schools.com/) - Again a valuable resource for consolidating what I had already learned and finding out more about HTML and CSS properties.

* [ColorSpace](https://mycolor.space/) - I used this website to select a color pallete, I started with a natural dark purple similar to that and used that to generate a pallette of complementing colors.  From a selection of pastel palettes generated, I chose the 'Classy Palette'.

* [StackOverflow](https://stackoverflow.com/) - Good resource for finding answers to problems I was having that other coders had similar experiences of.

* [Google](http://google.com) - Grate source of infomation?!

* [Online Convert](https://image.online-convert.com/convert-to-webp) - used to convert images from jpeg to webp for better performance.

* [Tinypng](https://tinypng.com/) used to compress images for better performance.

* Thanks to Pexels - for providing all images.

## Technologies Used
----
* HTML
* CSS

## Frameworks and Libraries

* FontAwesome
* Google Fonts
* GitHub
* GitPod
* GitPages
* Am I Responsive
* Dev Tools

### Acknowledgments

* Firstly I would like to say, that this has been a brilliant, and unforgettable learning experience for me, as a person with multiple learning issues like dyslexia and others, I decided to take the chance at doing something I have found a massive love for, which has revived my thrust for learning so win, loose, or draw i can come away knowing i have learned key skills i definitely didn't know before.
I would like to take a minute to thank everyone that has been involved in my coding journey especially Scott Clarke
Education Adviser who help me after taking the five-day coding challenge and encourage me to take the leap, and I'm glad I did so a big thanks to him.
Also, I would like to thank the following people that have found the time to teach an old dog new tricks these people where very friendly, and made me feel right at home. 

* Huge thanks to Shellie Downie who invested more than a lot of time helping me and gave me the idea for my thank you page as well as helping me understand a few of the (Obvious) issues I was having and generally just being a great port of support when I needed the help so a BIG THANKS to her.
* Thanks to Matt Bodden who took time to teach a brick wall like me thanks to him and his advice i was able to grasp a more rounded understanding of flexbox. 
* My mentor Reuben Ferrante for his great feedback, support and input Big big thanks.
* My mentor Narender Singh who managed to help me understand areas of css and html i hand not fully understood.
* The brilliant Slack community for their encouragement, motivation and assistance.
* Maggie Jury who help me with feedback and testing big thanks.
* Liz Conway who also help with feedback and testing thank you.
* Kevin Powell for his help and tuition in understanding responcive hamburger navigation layouts big thanks to him.
* Traversy Media for his help and tuition in understanding responsive pages, and form stylings so a big thanks as well.