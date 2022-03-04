# Honeycomb
(Developer: Lateefat Babalola)

![Mockup image](docs/am-i-responsive.png)

[Live website](https://zee-37.github.io/CI_PP1_Honeycomb/)

## Table Of Content

1. [Project Goals](#project-goals)
    1. [User Goals](#user-goals)
    2. [Site Owner Goals](#site-owner-goals)
2. [User Experience](#user-experience)
    1. [Target Audience](#target-audience)
    2. [User Requrements and Expectations](#user-requirements-and-expectations)
    3. [User Stories](#user-stories)
3. [Design](#design)
    1. [Design Choices](#design-choices)
    2. [Colour Scheme](#colours)
    3. [Fonts](#fonts)
    4. [Structure](#structure)
    5. [Wireframes](#wireframes)
4. [Technologies Used](#technologies-used)
    1. [Languages](#languages)
    2. [Frameworks & Tools](#frameworks-&-tools)
5. [Features](#features)
6. [Validation](#validation)
    1. [HTML Validation](#HTML-validation)
    2. [CSS Validation](#CSS-validation)
    3. [Accessibility](#accessibility)
    4. [Performance](#performance)
    5. [Device testing](#testing-on-different-devices)
    6. [Browser compatibility](#browser-compatability)
    7. [Testing user stories](#testing-user-stories)

## Project Goals

### User goals
- Finding a cafe/wine bar with an eccentric atmosphere, an affordable menu, venue-for-hire
- To find relevant information about cafe such as location, opening times and pricing
- Enquire about venue for hire
- To gain a visual experience of the cafe and see customer’s reviews.

### Site owner goals
- To promote the cafe
- To gain more customers and clients through venue for hire.
- To provide essential information about the cafe to customers
- To introduce new menu
- To allow customers to be able to contact cafe via social media or email

## User experience 

### Target audience
- Locals looking for space to hire
- Couples or groups looking for a nice spot to hang during the day or drink at night
- People who like working at cafe
- Coffee lovers

### User requirements and expectations
- Visually appealing design on all screens
- Accessibility
- Content that is simple and easy to follow
- Functional links and intuitive navigation system
- Clear and easy to find menu

### User stories

#### First-time users
1. I want to know the price on the menu
2. I want to know where the menu is located
3. I want to be able to visualise what it would be like to visit the cafe
4. I want to know about previous customers’ experiences.

#### Returning users
5. I want to find the business on social media
6. I want to leave a review 
7. I want to find a phone number for reservations
8. I want to hire the venue
9. I want to know more about the cafe
10. I want to see opening and closing times

#### Site owner
11. I want users to see opening and closing times
12. I want users to be able to contact us
13. I want users to know about our extended hours
14. I want users to be able to enquire about venue bookings

## Design

### Design Choices
The website was designed to have a uniform yet playful feel, with warm and rich block colours and accent colours dotted all over the web pages. This was done to portray the atmosphere that the user can expect when visiting the cafe.

### Colour Scheme
To choose a colour scheme, I used a coolors to generate a palette

![Colour scheme](docs/features/colour-scheme.png)

### Fonts
I mostly used web safe sans-serif font-families and serif fonts for the paragraphs.

### Structure
The website consists of five separate pages: 
- A homepage with a brief introduction section and two columned section of news about the cafe.
- An about page with customer reviews and a section about the owners.
- A menu page
- A gallery with images showcasing the atmosphere of the cafe
- A contact page with general information such as opening times and contact details; a contact form for enquiries; and an embedded map

### Wireframes
<details><summary>Home</summary>
<img src="docs/wireframes/home-wf.jpg">
</details>
<details><summary>About</summary>
<img src="docs/wireframes/about-wf.jpg">
</details>
<details><summary>Menu</summary>
<img src="docs/wireframes/menu-wf.jpg">
</details>
<details><summary>Gallery</summary>
<img src="docs/wireframes/gallery-wf.jpg">
</details>
<details><summary>Contact</summary>
<img src="docs/wireframes/contact-wf.jpg">
</details>
<details><summary>404</summary>
<img src="docs/wireframes/404-wf.jpg">
</details>

## Technologies Used

### Languages
- HTML
- CSS

### Frameworks & Tools
- Balsamiq
- Github
- GitPod
- VSCode
- Bootsrap v5.1
- Coolors
- Font Awesome
- Favicon

## Features
This website consists of five pages and nine features.

### Logo and Responsive Navigation Bar
- Featured on all pages, the navigation bar becomes a toggler on smaller screens.
- The navbar includes fully functional links for the home, about, menu, gallery and contact pages. 
- It allows for easy navigation through the website. 
- The active page link is highlighted and a link that is hovered over is also highlighted in a different colour.
- User stories covered: 2, 3, 10, 13

![Logo and navbar](docs/features/ft-header.png)

![Logo and navbar](docs/features/ft-header-toggle.png)

### Homepage information
- This section of the homepage contains news about the cafe that is meant to catch the user's attention such as the introduction of cocktails to the menu and venue for hire.
- User stories covered: 8, 10, 14, 15

![Homepage information](docs/features/ft-homepage-info.png)

### Footer
- Featured on all pages
- Consists of three sections: contact information, opening hours and social media links.
- User stories covered: 5, 7, 11, 12, 13

![Footer](docs/features/ft-footer.png)

![Social media icons](docs/features/ft-sm-icons.png)

### Reviews
- Highlighted on the about page
- Contains reviews from previous customers
- User stories covered: 4

![Reviews](docs/features/ft-reviews.png)

### Menu
- Separated in two sections: drinks menu and food menu
- Displays pricing of items
- User stories covered: 1, 9

![Menu](docs/features/ft-menu.png)

### Gallery
- Images portraying the atmosphere of the cafe displayed in columns
- User stories covered: 3

![Gallery](docs/features/ft-gallery.png)

### Information
- Provides necessary information for the cafe such as address, opening hours, email and phone number
- User stories covered: 7, 11, 12, 13

![Cafe Information](docs/features/ft-cafe-info.png)

### Contact Form
- Allows users to be able to leave reviews and enquire about venue hiring.
- User stories covered: 6, 8, 15

![Contact Form](docs/features/ft-contact-form.png)

### Map
- Google maps embedded on contact page to show cafe location
- User stories covered: 8

![Map](docs/features/ft-map.png)

## Validation

### HTML
The W3C Markup Validation Service was used to validate HTML, no errors found on all pages.
<details><summary>Home</summary>
<img src="docs/validation/val-html-home.png">
</details>
<details><summary>About</summary>
<img src="docs/validation/val-html-about.png">
</details>
<details><summary>Menu</summary>
<img src="docs/validation/val-html-menu.png">
</details>
<details><summary>Gallery</summary>
<img src="docs/validation/val-html-gallery.png">
</details>
<details><summary>Contact</summary>
<img src="docs/validation/val-html-contact.png">
</details>

### CSS
W3C Jigsaw CSS Validation Service was used to validate css style sheet. Errors found relating to root variables.
<details><summary>style.css</summary>
<img src="docs/validation/val-css.png">
</details>

### Accessibility
WAVE Web Accessibility Evaluation Tool was used to validate the accessibility of the site. Initially, the website displayed contrast errors, primarily between text colour and background colour. CSS was editted to meet validation criteria.
<details><summary>Home</summary>
<img src="docs/validation/accessibility-home.png">
</details>
<details><summary>About</summary>
<img src="docs/validation/accessibility-about.png">
</details>
<details><summary>Menu</summary>
<img src="docs/validation/accessibility-menu.png">
</details>
<details><summary>Gallery</summary>
<img src="docs/validation/accessibility-gallery.png">
</details>
<details><summary>Contact</summary>
<img src="docs/validation/accessibility-contact.png">
</details>

### Performance
Google chrome's Lighthouse in Chrome Developer's Tools was used to test the performance of the site.
<details><summary>Home</summary>
<img src="docs/validation/lh-performance-home.png">
</details>
<details><summary>About</summary>
<img src="docs/validation/lh-performance-about.png">
</details>
<details><summary>Menu</summary>
<img src="docs/validation/lh-performance-menu.png">
</details>
<details><summary>Gallery</summary>
<img src="docs/validation/lh-performance-gallery.png">
</details>
<details><summary>Contact</summary>
<img src="docs/validation/lh-performance-contact.png">
</details>

### Device Testing
Website was tested on the following devices:
- Laptop: MacBook Air
- Mobile: Galaxy Z Flip 3, iPhone 8 Plus
- Tablet: iPad 7th generation

### Browser Compatibility
The website was tested on the following browsers:
- Safari
- Google Chrome
- Microsoft Edge

### Testing User Stories

1. I want to know the price on the menu

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
| ----------- | ---------- | ----------- | -----------|
| Menu | Go to menu page from navbar | See price range | works as expected |
<!--add screenshots-->

2. I want to know where the menu is located

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
| ----------- | ---------- | ----------- | -----------|
| Navbar | Go to navbar and click menu link | menu page will display | works as expected |
<!--add screenshots-->

3. I want to be able to visualise what it would be like to visit the cafe

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
| ----------- | ---------- | ----------- | -----------|
| Gallery | Go to navbar and click gallery link | images showcasing the cafe will appear | works as expected |
<!--add screenshots-->

4. I want to know about previous customers’ experiences.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
| ----------- | ---------- | ----------- | -----------|
| Reviews | Select about from navbar | reviews visible in section section of about page| works as expected |
<!--add screenshots-->

5. I want to find the business on social media

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
| ----------- | ---------- | ----------- | -----------|
| Footer | Clink on social media links in footer | social media page to open in new tab| works as expected |
<!--add screenshots-->

6. I want to leave a review

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
| ----------- | ---------- | ----------- | -----------|
| Contact Form | enter name, email and message in form and press send | message will be sent to server | works as expected |
| Information | navigate to contact page | find email address | works as expected |
<!--add screenshots-->

7. I want to find a phone number for reservations

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
| ----------- | ---------- | ----------- | -----------|
| Footer | Scroll to footer | Find phone number in contact information | works as expected |
| Information | navigate to contact page | find phone number | works as expected |
<!--add screenshots-->

8. I want to hire the venue

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
| ----------- | ---------- | ----------- | -----------|
| Homepage information | Go to "venue for hire" section and clink "contact us" link | Takes user to contact page with enquiry form | works as expected |
<!--add screenshots-->

9. I want to know more about the cafe

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
| ----------- | ---------- | ----------- | -----------|
| Homepage information | locate text areas | information provided about services offered | works as expected |
| About page | go to about in navbar | read description of cafe as well as reviews from customers | works as expected |
<!--add screenshots-->

10. I want to see opening and closing times

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
| ----------- | ---------- | ----------- | -----------|
| Footer | scroll down to footer | opening hours information provided | works as expected |
| Information | go to contact page in navbar | locate opening hours on page | works as expected |
<!--add screenshots-->

11. I want users to see opening and closing times

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
| ----------- | ---------- | ----------- | -----------|
| Footer | scroll down to footer | opening hours information provided | works as expected |
| Information | go to contact page in navbar | locate opening hours on page | works as expected |
<!--add screenshots-->


12. I want users to be able to contact us

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
| ----------- | ---------- | ----------- | -----------|
| Footer | scroll down to footer | find phone number | works as expected |
| Contact page | go to contact page in navbar and locate contact| locate phone number, email, address and contact form | works as expected |
<!--add screenshots-->

13. I want users to be able to locate the cafe

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
| ----------- | ---------- | ----------- | -----------|
| Map | go to contact page from navbar and scroll to end of page | find embedded map with address | works as expected |
<!--add screenshots-->

14. I want users to be able to enquire about venue bookings

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
| ----------- | ---------- | ----------- | -----------|
| Contact form | Scroll to form section on contact page | Find form for enquiry | works as expected |
<!--add screenshots-->


## Bugs

| **Bug** | **Fix** |
| ----------- | ----------- |
| Toggle bar would not expand on menu page| script blocking rendering removed |
| images appearing as their original size, too big on small screens| targeted in css with object-fit |
| Contact form sticking to image on medium screens | added flex attributes to position properly and media queries to set specific rules for different screens |
| form label input not aligned with textarea | same width given in css |
| social media icons not showing on contact page footer | font awesome script labeled correctly|

## Deployment
Website was deployed using the following steps:
1. Go to settings tab in the GitHub repository
2. From the menu on the left, select 'Pages'
3. Select 'Branch: main'
4. Weboage will refresh with the message "Your site is published at https://zee-37.github.io/CI_PP1_Honeycomb/" highlighted in green

To fork this repository:
1. Go to repository
2. Click the fork button in the upper right corner of page

To clone repository:
1. Go to repository
2. Select the 'code' button above the list of files
3. Choose between HTTPS, SSH, or GitHub CLI and copy URL.
4. Open Git Bash
5. Change current working directory to cloned directory
6. Enter 'git clone' and past URL ($ git clone https://github.com/username/repository)
7. Press 'enter' and create cloned repository.

## Credits
Images not referenced below are owned by the developer. 

### Media

In order of appearance:
- [img1](assets/images/img1.jpg): Photo by <a href="https://unsplash.com/photos/IkOXmuqeOZo">Abdalla M</a> on <a href="https://unsplash.com/">Unsplash</a>
- [img2](assets/images/img2.jpg): Photo by <a href="https://unsplash.com/photos/pe5D2RleK6E">Kike Salazar N</a> on <a href="https://unsplash.com/">Unsplash</a>
- [img3](assets/images/img3.jpg): Photo by <a href="https://unsplash.com/photos/21tOEaJPM_o">Sung Jin Cho</a> on <a href="https://unsplash.com/">Unsplash</a>
- [a-img1](assets/images/a-img1.jpg): Photo by <a href="https://unsplash.com/photos/_qADvinJi20">John Arano</a> on <a href="https://unsplash.com/">Unsplash</a>
- [a-img2](assets/images/a-img2.jpg): Photo by <a href="https://unsplash.com/photos/23KdVfc395A">Thought Catalog</a> on <a href="https://unsplash.com/">Unsplash</a>
- [g-img1](assets/images/g-img1.jpg): Photo by <a href="https://unsplash.com/photos/71u2fOofI-U">
Nathan Dumlao</a> on <a href="https://unsplash.com/">Unsplash</a>
- [g-img2](assets/images/g-img2.jpg): Photo by <a href="https://unsplash.com/photos/aEiCpMq9fxU">
Nick Fewings</a> on <a href="https://unsplash.com/">Unsplash</a>
- [g-img3](assets/images/g-img3.jpg): Photo by <a href="https://unsplash.com/photos/pnkJ_5PDmKI">
Kwon Junho</a> on <a href="https://unsplash.com/">Unsplash</a>
- [g-img4](assets/images/g-img4.jpg): Photo by <a href="https://unsplash.com/photos/wm0BNnUfXmU">
Kwon Junho</a> on <a href="https://unsplash.com/">Unsplash</a>
- [g-img5](assets/images/g-img5.jpg): Photo by <a href="https://unsplash.com/photos/XPxWx8-Q49U">
Alejandro Sotillet</a> on <a href="https://unsplash.com/">Unsplash</a>
- [g-img6](assets/images/g-img6.jpg): Photo by <a href="https://unsplash.com/photos/cUFli52JBoo">
Walter Lee Olivares de la Cruz</a> on <a href="https://unsplash.com/">Unsplash</a>
- [g-img7](assets/images/g-img7.jpg): Photo by <a href="https://unsplash.com/photos/XdgC1Qo9uVc">
Kwon Junho</a> on <a href="https://unsplash.com/">Unsplash</a>
- [g-img8](assets/images/g-img8.jpg): Photo by <a href="https://unsplash.com/photos/lRc-HSvFqbY">
Kwon Junho</a> on <a href="https://unsplash.com/">Unsplash</a>
- [g-img9](assets/images/g-img9.jpg): Photo by <a href="https://unsplash.com/photos/nuyCCp8jleU">
Brooke Cagle</a> on <a href="https://unsplash.com/">Unsplash</a>
- [g-img10](assets/images/g-img10.jpg): Photo by <a href="https://unsplash.com/photos/4xWsYn3XtvQ">
Maria Avdeeva</a> on <a href="https://unsplash.com/">Unsplash</a>
- [g-img11](assets/images/g-img11.jpg): Photo by <a href="https://unsplash.com/photos/OxKFC5u0980">
Sérgio Alves Santos</a> on <a href="https://unsplash.com/">Unsplash</a>
- [g-img12](assets/images/g-img12.jpg): Photo by <a href="https://unsplash.com/photos/jODz47eM1w8">
frank mckenna</a> on <a href="https://unsplash.com/">Unsplash</a>
- [g-img13](assets/images/g-img13.jpg): Photo by <a href="https://unsplash.com/photos/wiOEVPVRfW4">
GC Libraries Creative Tech Lab</a> on <a href="https://unsplash.com/">Unsplash</a>
- [c-img1](assets/images/c-img1.jpg): Photo by <a href="https://unsplash.com/photos/2AerW-ZnWCI">
Hatfields London</a> on <a href="https://unsplash.com/">Unsplash</a>

## Acknowledgements
