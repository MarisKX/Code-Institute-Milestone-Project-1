 ![Optional Text](https://raw.githubusercontent.com/MarisKX/Code-Institute-Milestone-Project-1/master/assets/images/logo-full.png)

**<h1 align="center">Zandbergen Transport Website</h1>**

This is the main website for Zandbergen Transport company, designed
to be responsible and accessible in wide range of modern devices, making
it easy to navigate and submit price request for curent and future customers.

# User Experience (UX) and main design.

## Colors and other design elements
To make website easily recognizable and to make navigation simpler, website uses 2 Zandbergen brand colors - 
black and red in combination with white as a background throughout all sections. 
The Arvo font is the main font used in website with Sans Serif as the fallback font 
in case for any reason the font isn't being imported into the site correctly.

## Structure
Website structure is made from 3 main sections, keeping in mind 3 questions that potential customers may have:
- What we are?
- What we do?
- How do we do that?

Answers to these questions can be found on landing page 3 sections as well as other sections - Services answers to question 'What we do?' while fleet section gives answer to question 'How do we do that?'

## Images

All images are set as a background with fading effect in the way they blend with respective background color including the hero image above navigation.

## User stories

### First Time Visitor Goals

        1. As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the organisation.
        2. As a First Time Visitor, I want to be able to easily navigate throughout the site to find content.
        3. As a First Time Visitor, I want to find how long they are in bussiness and how experienced they are with service they provide. I also want to locate their social media links to see their followings on social media to determine how trusted and known they are.

### Returning Visitor Goals

        1. As a Returning Visitor, I want to find information about new services, that fits my needs.
        2. As a Returning Visitor, I want to find the best way to get in contact with the organisation with any questions I may have.
        3. As a Returning Visitor, I want to request pricing for my next cargo tranportation.

### Frequent User Goals
        1. As a Frequent User, I want to check to see if there are any newly added services.
        2. As a Frequent User, I want to easily request pricing and get price offer in my email.

## Wireframes

While the finished website slightry varies from initial wireframes, the main structure and idea stays the same:

- Home page - [View](https://github.com/MarisKX/Code-Institute-Milestone-Project-1/blob/master/documentation/wireframes/Home.pdf)
- Services page - [View](https://github.com/MarisKX/Code-Institute-Milestone-Project-1/blob/master/documentation/wireframes/Services-section.pdf)
- Fleet page - [View](https://github.com/MarisKX/Code-Institute-Milestone-Project-1/blob/master/documentation/wireframes/Fleet-section.pdf)
- Contact us (price request) - [View](https://github.com/MarisKX/Code-Institute-Milestone-Project-1/blob/master/documentation/wireframes/Contact-section.pdf)

## Features 
- Responsive on all device sizes (made up in 4 steps):
    - Mobile device 
    - Tablet 
    - Laptop (screen size up to 17")
    - Full size PC screen (19" and above)
- When navigating to contact section, it goes directy to price request form.
- Price request is accessible directly from home page by clicking on company moto text
- Company logo acts like home button on every page/screen.

# Technologies used

### Languages used
- [HTML5](https://en.wikipedia.org/wiki/HTML5) 
- [CSS3](https://en.wikipedia.org/wiki/CSS#CSS_3) 
- [JavaScript](https://en.wikipedia.org/wiki/JavaScript)

### Frameworks, Libraries & Programs used

1. [Bootstrap 5.0.0](https://getbootstrap.com/docs/5.0/getting-started/introduction/)
   - Bootstrap was used to assist with the responsiveness and styling of the website.
1. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Arvo' font into the style.css file which is used on all pages throughout the project.
1. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.
1. [Balsamiq:](https://balsamiq.com/)
    - Balsamiq was used to create the [wireframes](https://github.com/MarisKX/Code-Institute-Milestone-Project-1/tree/master/assets/wireframes) during the design process.
1. [Atom](https://atom.io/)
    - Atom text editor was used at initial stage of development to test various aspects and functions of website as well as main structure layout.

# Testing

### Initial Testing (before deployment)

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.
- [W3C Markup Validator](https://validator.w3.org/#validate_by_input)
    - [Home](https://raw.githubusercontent.com/MarisKX/Code-Institute-Milestone-Project-1/master/documentation/validation/Home.png)
    - [Services](https://raw.githubusercontent.com/MarisKX/Code-Institute-Milestone-Project-1/master/documentation/validation/Services.png)
    - [Fleet](https://raw.githubusercontent.com/MarisKX/Code-Institute-Milestone-Project-1/master/documentation/validation/Fleet.png)
    - [Contact](https://raw.githubusercontent.com/MarisKX/Code-Institute-Milestone-Project-1/master/documentation/validation/Contact.png)
    - [ThankYou](https://raw.githubusercontent.com/MarisKX/Code-Institute-Milestone-Project-1/master/documentation/validation/ThankYou.png)
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)
    - [Style.css](https://raw.githubusercontent.com/MarisKX/Code-Institute-Milestone-Project-1/master/documentation/validation/Style%20CSS.png)

### Futher Testing (after depleoyment)

-   The Website was tested on Google Chrome, Microsoft Edge, Safari and Firefox browsers.
-   The website was viewed on a variety of devices such as Desktop (Linux Ubuntu 20.04LTS and Win10), Laptop (Win10 and Mac), iPhone 5S, iPhone X and Samsung S20.
-   A large amount of testing was done to ensure that all pages were linking correctly.
-   Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

### Testing User Stories from User Experience (UX) Section

-   #### First Time Visitor Goals

    1. As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the organisation.

        1. Upon entering the site, users are automatically greeted with a clean and easily readable navigation bar to go to the page of their choice. 
            Above there is a Hero Image with Text and a company moto with phrase "Do You want to know how do we do that?" that links directly to price rwequest form
        2. The main points are made immediately clear with the hero image representing main service of company - cargo transportation.

    2. As a First Time Visitor, I want to be able to easily be able to navigate throughout the site to find content.

        1. The site has been designed to be fluid and never to entrap the user. At the top of each page there is a clean navigation bar, each link describes what the page they will end up at clearly.
        2. At the bottom of all pages there are contact details as well as social media links.
        3. On the Contact Us Page, after a form is submitted, the page refreshes and the user is brought to the thanks you page confirming, that the form was submitted succesfully.

    3. As a First Time Visitor, I want to look for testimonials to understand what their users think of them and see if they are trusted. I also want to locate their social media links to see their following on social media to determine how trusted and known they are.
        1. Once the new visitor has read the short company history, they can learn more details about services and our fleet.
        2. The user can also scroll to the bottom of any page on the site to locate social media links in the footer.

-   #### Returning Visitor Goals

    1. As a Returning Visitor, I want to find the information about new services.

        1. Service section as well as fleet section was made flexible, so new content can be added later.

    2. As a Returning Visitor, I want to find the best way to get in contact with the organisation with any questions I may have.

        1. Fast way to navigate to price request is made possible thru moto text link.
        2. Here they can fill out the form on the page or can contact company by phone number and/or email provided in footer section.
        3. The footer contains links to the organisations Facebook, Twitter, LinkedIn and Instagram page.
        4. Whichever link they click, it will be open up in a new tab to ensure the user can easily get back to the website.

-   #### Frequent User Goals

    1. As a Frequent User, I want to check to see if there are any newly added services.

        1. The user would already be comfortable with the website layout and can easily click the services section.

    2. As a Frequent User, I want to easily request pricing and get price offer in my email.

        1. The user would already be comfortable with website layout to easily navigate to price request page using moto text link or by clicking on contact section.


#### Known bugs

- On iPhone 5, using Safari browser, navigation links are pushed slightly lower from 'burger menu', than expected, such problem does not occure on other devices, who are using Safari browser or iPhone5 with Chrome browser.

#### Future improvements plans

- Language option - user can choose between dutch and english for content.

# Deployment

## GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://mariskx.github.io/Code-Institute-Milestone-Project-1/index.html) in the "GitHub Pages" section.

# Credits

### - [Bootstrap5](https://getbootstrap.com/docs/5.0/getting-started/introduction/): Bootstrap Library used throughout the project mainly to make site responsive using the Bootstrap Grid System.
### - Much of the content was taken from Zandbergen original website and translated from Dutch to English by developer. 
### - All Images (incl. full and small-size logo) were taken from Zandbergen original [website](https://www.zandbergentransport.nl/) or their social media accounts.
