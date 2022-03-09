# Stirling Golf Community

Stirling Golf Community was created for the golf club members in the area of Stirlingshire. The website creates a platform for members, of 3 clubs (Stirling Golf Club, Bridge of Allan Golf Club, Dunblane Golf Club), to interact and play golf together.  

The website provides a Sign-Up form for the members to get involved in the community and pick and choose when they would be able to play. From there the organisers will select people from different handicap groups to play with each other. This gives everyone the opportunity to learn and feel like part of a local community.

A live link to the page can be found here - https://dandon1990.github.io/stirling-golf-community/

![Responsive image for multiple devices](/assets/images/responsive-image.jpg)

## Features 

### Navigation Bar
* The navigation bar is present throughout the 3 pages and gives the user and clear way to naviagte through the website.
* It has 3 links to the **Home**, **About** and **Sign-Up** pages. This will allow the user to switch between pages without the use of back or forward buttons.
* The website **Logo** also links back to the website home page making for friendly user experience.

![Navigation bar and logo ](/assets/images/navigation-image.jpg)


### Landing Page
*  The landing page includes an image of a golf hole with a contrasting text which allows the user know what the site is about and where it will take place.
* The picture in this section let's the user know straight away that it is a golf website.

![Hero image](/assets/images//landing-image.jpg)

### Home Page

* The home page gives a brief introduction to the golf community and what it is about.
* The image selected for the home page shows two golfers together helping each other putting. This displays the environment the user will be experincing on participation.
* There has been a link inserted at the bottom of the page for easy navigation on where the customer can find out more information on the times and loactions of the community. This is good user experience as they don't have to scroll to the top of the page to find out more. 

![Golfers putting](/assets/images/home-image.jpg)


### About Page

* The About page gives the user more information about when and where they would be playing golf.
* The different sections give a short description of each golf course.
* Each section also contains external links to the websites of the individual golf courses. All links open in a new tab for optimal user experience. 
* All links were placed at the end of each section in a new paragraph to make them stand out to the user.

![About Page](/assets/images/about-top.jpg)
![About Golf Courses](/assets/images/about-bottom.jpg)
![External Link ABout](/assets/images/about-external-link.jpg)

* An internal link has been placed at the bottom of the About Page which leads the user to the Sign-Up page. This allows the user to go to the sign up page without having to scroll back to the top of the page.
* The link is displayed in yellow to let user know that is different from the rest of the text and more appealing to click.


![Sign up Link](/assets/images/signup-link.jpg)

### The Footer

* The footer section appears on all the pages and contains the scoaial media links for Stirling Golf Community. All links will be opened in a new tab for a better user experience and easier navigation.
* All of the links change colour when hovered over to let the user know that they are click-able links.
* The footer provides value to the user as it allows them to be consistently connected to the Community through social media. 

![Footer](/assets/images/footer.jpg)

### Sign-Up Page

* The Sign-Up Page allows the user to sign up to the Stirling Golf Community and begin participating in their golf days/evenings. 
* The user will be able to specify what days they can play as well as their playing ability so that the community can pair them with the appropriate playing partners.
* Contact details will be taken from the user to allow the community contact with any relevant news about the organisation of the event.
* All information will be filled out in a form with a **Join Now** button which increases in size when hovered over. The form cannot be submitted unless all fields are filled out. 

![Form Image](/assets/images/form-image.jpg)

## Testing

### Navigation Bar and Logo

* All pages were visited from each page to make sure all links in the navigation bar function correctly.
* Logo link was tested from each page to make sure it would always link to the Home Page.
* All links were tested to make sure they were opened internally and not externally.
* All links in the Navigation bar were tested on smaller screens where the navigation bar would move with media queries.

### Footer
* Ensure all links functioned by opening the relevant social media websites or applications if opened on a mobile device.
* Ensure all links opened the relevant websites in a new tab to help the user navigate more easily.
* Ensure that all links worked on all the pages (**Home, About and Sign-Up!**)
* Ensure that all links worked across different browsers.
* Ensure all links worked on different screen sizes.

### About Page 

* All links for the 3 different golf courses were tested to open in new tabs making for better user experience.
* All links were tested across different screen sizes to make sure they maintained functionality.
* Sign-Up link was tested to make sure to navigate to  the Sign-Up page.

### Sign-Up Form
* The form was tested to make sure it couldn't be submitted without having all areas filled out or selected.
* The form was tested and was successful with the Form dump page provided by Code Institute.
![Failed Form](/assets/images/form-fail.jpg)
![Filled Form](/assets/images/filled-form.jpg)
![Form Success](/assets/images/form-dump.jpg)

### Responsive Design
* Ensure all features across the three pages maintain functionality across different screen sizes.
* Ensure page layouts are maintained maintained across different screen sizes.


### Browser Testing 
* The site and all features were tested across different web browsers. 
* The browsers used for testing: 
    * Google Chrome
    * Firefox
    * Microsoft Edge
    * Safari
* Google Chrome 
    * Navigation Bar and Logo links all worked and opened across different screen sizes.
    * All social media links opened externally in a new tab.
    * The internal link at he bottom of the **Home Page** leads to the **About Page** as expected.
    * The internal link at the bottom of the **About Page** leads to the **Sign-Up Page** as expected.
    * All pages maintained the layout across different Viewports. 
        * Desktop (1600x992px)
        * Laptop (1280x802px)
        * Tablet & Mobile (All devices listed on Dev Tools)

* Results were the same for **Firefox and Microsoft Edge**
* Safari was tested on smaller screen sizes as I don't have access to a larger screen size but all functionality worked across the smaller screen sizes (Tablet & Mobile).

### Code Validators

* HTML was ran through [W3 Markup Vaildation](https://validator.w3.org/) to check for any errors in the code.
    * No errors were found.

* CSS was ran through [W3 Jigsaw](https://jigsaw.w3.org/css-validator/) to check for any erros in the code.
    * No errors were found.

### Google Lighthouse

* [Google Lighthouse](https://developers.google.com/web/tools/lighthouse) was used to check the accesibility, performance, progressive web apps and SEO of the pages.

    * Home Page 

    ![Lighthouse Home](/assets/images/lighthouse-home.jpg)
    * About Page

    ![Lighthouse About](/assets/images/lighthouse-about.jpg)
    * Sign-Up Page
    
    ![Lighthouse Sign-Up](/assets/images/lighthouse-signup.jpg)


## Deployment

This site was deployed using Github Pages using the following steps:
1. Log in to [GitHub](https://github.com/).
2. From the list of Repositories, select [stirling-golf-community](https://github.com/dandon1990/stirling-golf-community).
3. Navigate to [Settings](https://github.com/dandon1990/stirling-golf-community/settings). 
4. Scroll down through the options to [GitHub Pages](https://github.com/dandon1990/stirling-golf-community/settings/pages).
5. From the source section drop-down menu, select the **Master Branch**.
6. The second drop-down menu value should remain as **/(root)**
7. Press Save
8. Refresh the page, scroll back down to **GitHub Pages**, the link to the deployed site will be available in a green sub-section with a tick icon next to it.

Live link can be found here - https://dandon1990.github.io/stirling-golf-community/signup.html

## Credits
### Content
* Content for the about page was taken from the golf course websites 
    * https://www.stirlinggolfclub.com/
    * http://www.dngc.co.uk/
    * https://www.bofagc.com/

### Images
* All images were taken from royalty free website [Pexels](https://www.pexels.com/).
### Fonts and Icons
* Fonts were used from [Google Fonts](https://fonts.google.com/).
* Icons for social media links were taken from [Font Awesome](https://fontawesome.com/).
### Colours 
* The colour scheme throughout was thought of by using Colour Palette Generator [Coolors](https://coolors.co/).
### Code 
* Code throughout the site has been helped by various different sources including:
    * The [Love Running](https://code-institute-org.github.io/love-running-2.0/index.html) project.
    * [CSS Tricks](https://css-tricks.com/) 
    * [Stackoverflow](https://stackoverflow.com/)
    * [W3schools](https://www.w3schools.com/default.asp)



