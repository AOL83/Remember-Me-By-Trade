![Office pic!](assets/images/RMBT.png)
# Remember Me By Trade IT & Office Support Solutions Agency
This website is aimed mainly at Companys that have IT issues or need a position permanently or temporarily filled with a skilled member of staff based in London, the South of England. The aim is to give enough information about the site's owner - their experience and the services provided. Users of the site will be able to gain contact information, location and also submit a request for RMBT to contact them back.

From the perspective of the site owner, the aim of this website is to generate customer interaction which will generate revenue by providing information about services, showcasing skills through the company's experience in the field and encouraging potential clients to get in touch.

![Am I Responsive screeshot!](assets/images/website-pic.png)

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

The site's owner wanted a modern 2022-style website. They decided on a six-color scheme incorporating a pastel tone colour pallet from [ColorSpace](https://mycolor.space/), we checked the colour pallet using [EigthShapes Contrast Grid](https://contrast-grid.eightshapes.com/?version=1.1.0&background-colors=&foreground-colors=%23faf8f6%2C%0D%0A%2300a4fcd9%0D%0A%234244b9%0D%0A%23191641%0D%0A%23536075de&es-color-form__tile-size=compact&es-color-form__show-contrast=aaa&es-color-form__show-contrast=aa&es-color-form__show-contrast=aa18&es-color-form__show-contrast=dnp) So I decided to go with a simple design as thy chose an eight colour palette scheme of an off-white, a shade of gray (used only on styling the navbar and footer) and these were used in contrast with a light blue for the hover state. The dark blue colour and off-white combination for the button's statics state gives the buttons the highest rating in compliance with [WCAG 2.0 minimum contrast](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html) for text/background.

![Contrast Grid](assets/images/contrast-grid.png)

All the images used on site have been sourced from Pexels https://www.pexels.com/  who do not require attribution or compensation to the content creator as part of the licencing conditions (https://www.pexels.com/terms-of-service/. 

Google Fonts was used to select a modern and stylish looking font for the this websit.

## Features 
----

### Existing Features



* Navigation Menu 
    - This features on all pages of this website. The position and style is consistent across all pages to allow the user to intuitively navigate each section of the main landing page, and its content as well as intuitively navigate to other pages like the contact form.  The navigation menu has been styled with html and css only on large screens the nav will display the page links and the logo inline at the top of the page and on small devices the nav will change in to a working hambeurger drop down menu that is still usable without when hoverd over links will change colour with a indicator line letting you know that the is usable.
![Navigation Menu Desktop](assets/images/nav1.png)

![Closed Navigation Menu Mobile](assets/images/NAV_mobile-closed.png)

![Open Navigation Menu Mobile](assets/images/NAV-mobile-open.png)

* Footer 
    - Social Media Links to Facebook, Instagram and twitter with active transitions in color allow the user to know the link is active so they can stay connected to the companys activities and see regular posts.
    - Telephone number and email address in footer on every page.  This means that the user does not have to navigate to a different page to have access to this information if they decide they want to email or telephone. 

![Footer](assets/images/Responcive-footer-A.png)
![Footer](assets/images/Responcive-footer-B.png)   
  

* Home Page Features
    -The hero-image on landing page is quite eye catching with the contrast between the bright colours natural tones it become very striking. but leaves out enough information to entice the site user to make an enquiry.
    - There is also a contact button within the navbar which links directly to the contact form page.  This acts as a call to action to encourage the site user to submit their details to arrange a callback.  The contact button has a hover effect applied so the button background changechanges when it is hovered over to draw attention to itself. The same effect is used on all buttons across the site.

![Hero Image and Overlay Text](assets/images/Hero-img.png)
![Main Page and Overlay Text](assets/images/services-section.png)
![Services Images and Overlay Text](assets/images/about.png)
![Ifram Location Image with Overlay Text And Social Links](assets/images/iframe.png)   


* Home Page Features Continued...
    - The home page consists of the following one landing page with an image a welcome message in the head, beneath that is an infomaiton section with a small brief then another section containing three further images and infomation about services. Then the first information box provides the site user with introduction about RMBT IT & Office suppsupport Solutions Agency, their training, experience, and work ethos. There is also a links at the bottom of the page that encourage the user to visit us on our socila networks.  
    - The second information box provides brief contact information.
    - The information boxes are styled with a darker colour so that text is aloud to stand out.
    - As a decorative feature for this section. These are displayed next to eath other on larger screens, but stacked on top of each other when on smaller screens, such as mobile phones. 


* Contact Form
    - Input fields to submit name, company name, phone, and email address.
    - Text area to add information for a message to RBMT.
    - Submit button - With background effect. This button currently links to a thank-you page where a thank you message will be displayed to let the user know their information has been submitted and we will be in contact in due course. 
    - Each field has a ```required``` attribute applied to ensure users input all fields before submiting, the contact form is responsive on desktop devices the contact content is shifted to the left of the form and on smaller devices the contact content is stacked. 

![Contact Form Screenshot](assets/images/contact-form.png)


* Thank-you Page
    -Thank-you page will only appear when the contact form has been fully completed and submitted.  It will display a short message to thank the users for getting in contact and confirming the RMBT will be in contact in due course.

![Thank You Page Screenshot](assets/images/thank-you.png)
<br/>



## Testing
----

I have tested all aspects of the site functionality including all links as best as possible, inputs and responsiveness through Dev Tools in Chrome & lighthouse for the following devices. (I would of liked a more extensive and in depth testing scrip but with the little time i had left to submit my testing is as follows):-

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

* CSS file has been run through W3C CSS Validator and no errors have been found.  One warnings have been found but relates to the way i mad my nav operate which are not checked by the validator.
* All HTML files have been passed through the W3C HTML Validator and no errors have been found. 



