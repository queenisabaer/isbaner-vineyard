# Isbaner vineyard

_HTML and CSS Essentials Project Portfolio - Code Institute_

View deployed site [here.](https://queenisabaer.github.io/isbaner-vineyard/)

Isbaner vineyard is a site dedicated to the vineyard of the Isbaner family. The site is targeted towards interested parties, friends and family who want to know more about the vineyard, stay in touch with the owners or visit them and keep updated through the year. Furthermore it will be useful for people who want to know something about the Gutedel grape and the region Wethau, Saale-Unstrut.  

![Responsive Mockup](documentation/readme/am-i-responsive.png)

## Table of contents

* [User Experience (UX)](#user-experience) 
* [Design](#design)
* [Features](#features)
* [Technologies Used](#technologies-used)
* [Testing](#testing)
* [Deployment](#deployment)
* [Credits](#credits)

## User Experience (UX)

### User stories

Goals for:
-   **First time visitor:** 
An overview of the vineyard should be given to first-time visitors. Especially when the owners meet new people and tell them about their hobby, they are of course very curious and want to learn more about the vineyard, the grapes that are planted and the winegrowers association of which the owners are member of. Furthermore it's common for them to ask for pictures of the vineyard and garden. Quick access to the most important information is therefore essential. On the homepage, the three image boxes symbolize the components of the homepage. Clicking on the buttons takes you to the corresponding content. 
-   **Returning visitor:** 
Returning visitors may want to visit the vineyard or get in touch with the Isbaner family. So the contact area allows them to contact the owners and, for instance, book a wine tasting or a guided tour.
-   **Frequent user:** 
Frequent users are interested in staying in touch with the owners or want to know what it looks like on the vineyard and what’s new, especially the gallery is interesting for them.

## Design

-   **Imagery:**
All photos were taken by the owners within the last years and were provided for the project. They reflect the daily reality on the vineyard with all of its beauty. 
-   **Colour Scheme:**
The color scheme should match the vineyard theme and the fact that sandstone is mined in the region, which is also used in the garden. Therefore, with the pipette function on [coloors.co](https://coolors.co/), green and brown shades were chosen, which were taken from the photograph of the background image at contact.html. Since green also dominates in the vineyard, the shade #295900 has become the primary color. The brown shades set accents primarily as a background for buttons and text fields. 
![Color palette](documentation/readme/grapes-coloors-palette.png)
-   **Typography:** 
The font [Nobile](https://fonts.google.com/specimen/Nobile?query=nobile) was selected for text content. It was important that this font creates a contrast to logo and heading. It should therefore be clear, simple and easy to read on all screen sizes. 
Since growing wine is a very old and respected tradition, a handwritten-looking font was chosen as the font for the logo and headings: [Tangerine](https://fonts.google.com/specimen/Tangerine?query=tangerine)
>
> Tangerine is a calligraphic typeface inspired by many italic chancery hands from the 16th and 17th centuries. *(Google Fonts)*
> 

### Wireframes

<details>
<summary> index.html </summary>
<br>
For simplicity's sake the logo has been left in the navigation bar. In addition, the buttons have been moved to the top left of the images to avoid covering the photos. 

![Desktop wireframe](documentation/wireframes/isbaner-vineyard-desktop-index.png)
![Mobile wireframe](documentation/wireframes/isbaner-vineyard-mobile-index.png)
</details>

<details>
<summary> about-us.html </summary>
<br>
Since i've learned that buttons and links have different roles, I did not design the links as a button. especially since this design also resulted in a warning in the html validator.

![Desktop wireframe](documentation/wireframes/isbaner-vineyard-desktop-about-us.png)
![Mobile wireframe](documentation/wireframes/isbaner-vineyard-mobile-about-us.png)
</details>

<details>
<summary> gallery.html </summary>
<br>

The gallery was created without caption. This is a feature I would like to integrate in the future. 
![Desktop wireframe](documentation/wireframes/isbaner-vineyard-desktop-gallery.png)
![Mobile wireframe](documentation/wireframes/isbaner-vineyard-mobile-gallery.png)
</details>

<details>
<summary> contact.html </summary>
<br>

![Desktop wireframe](documentation/wireframes/isbaner-vineyard-desktop-contact.png)
![Mobile wireframe](documentation/wireframes/isbaner-vineyard-mobile-contact.png)
</details>

## Features

### Existing Features

All the pages were created with a mobile first approach and are made responsive. To ensure that the layout of the pages remains consistent even on very large screens, the text body has been given a maximum width and a margin on both sides.  
Every page contains a responsive navigation bar on the top with a logo on the left side and the navigation on the right that supports easy navigation. On small screens (e.g. mobile devices) the navigation will become a clickable burger toggler. To make it easier for users to know where they are on the website, the current page is underlined. 

![Navbar on mobile devices](documentation/readme/navigation-mobile.png)
![Navbar when clicked on hamburger menu on a mobile device](documentation/readme/navigation-mobile-toggle.png)
![Navbar ob tablets and larger screens](documentation/readme/navigation-desktop.png)

The footer stays on the bottom of every page and features clickable social media icons and the coordinates of the vineyard, which act as a link to google maps. All links on the footer are opened in a new tab.
![Footer on mobile devices](documentation/readme/footer-mobile.png)
![Footer on desktop](documentation/readme/footer-desktop.png)

- __Hero image__

The hero image on the main page shows a lovely view over the vineyard. This is intended to convey the beauty of the vineyard directly to the user. In the upper left corner there is a link button that points to the about us page. The button was moved to the side, unlike originally planned, so that the image is not disturbed to.
![Hero image](documentation/readme/hero-image.png)<br>
Below the hero image there are two image containers that refer to the other subpages of the website. They were adapted to the layout of the hero image. 
![Image container main page](documentation/readme/image-container-main.png)

- __About us Page__

The *About us* page consists of three parts. The first part tells the short story about the owners of the vineyard, the second gives some information about the grape chasselas and the third part highlights the region where the vinyard is located. Each section contains an image, a heading, some text and a link. When viewed on a mobile phone the image will be placed on top of the heading. The links change their apperence when hovered. 

![About us Page](documentation/readme/about-section.png)

- __Gallery Page__

The Gallery page will provide users with photographs to see what happens on the vineyard spread over a year. It has two main sections. The first contains horizontal photographs and the second vertical ones. 
To create the responsive gallery I used the tutorial and css code for a grid gallery by [Rüdiger Alte](https://www.imarketinx.de/artikel/responsive-image-gallery-with-css-grid.html)
![Gallery Page](documentation/readme/gallery.png)

- __Contact Page__

The contact page contains two areas. The first offers a contact form that users can complete to get in touch with the owners of the vineyard. The user is asked to enter their first name, last name and e-mail address when sending a message. This information is mandatory. After submitting the form, a new tab with the results are displayed. Currently it shows the formdump.codeinstitute.net page with the determined form data. 
![Contact fieldset](documentation/readme/contact-fieldset.png)<br>
The second area provides directions to the vineyard. Both images are screenshots from google as in germany it is not permitted to use the interactive google map due to data security concerns. However, clicking on the images takes the user to the Google Maps page in a new tab.
![Find us fieldset](documentation/readme/find-us-fieldset.png)

### Features, which I would like to implement in the future

- As the gallery is currently very simple, I would like to improve it in the future. I could imagine a different design with enlargeable images and subtitles. Furthermore I would create tags with categories for spring, summer, autumn & winter. 
- I would like to create my personal page after submitting the form and of course use a corresponding data processing programm. 
- Since German is my native language, I would love to make a german version of the website.
- Add a favicon. 

## Technologies Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
-   [Google Fonts](https://fonts.google.com/) was used to import fonts into the style.css.
-   [Font Awesome](https://fontawesome.com/) was used to add icons.
-   [Git](https://git-scm.com/) was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub. 
-   [GitHub](https://github.com/) was used to save and store the files for the website.
-   [Balsamiq](https://balsamiq.com/) was used to design the wireframes.
-   [Coloors](https://coolors.co/image-picker) was used to create the color scheme.
-   [iLoveIMG](https://www.iloveimg.com/) was used to cropp and resize the images.
-   [Am I Responsive](https://ui.dev/amiresponsive) was used to display the website on different devices. 

## Testing

1. Validator Testing

- [HTML Validator](https://validator.w3.org/)

    - result for index.html<br>
      First I had an error because my semantics of the h2/button element weren't correct. No errors or warnings were found after fixing this problem.
      ![HTML results index with errors](documentation/readme/html-validator-errors-index.png)
      ![HTML results index](documentation/readme/html-validator-index.png)
    - result for about.html<br>
      I made a mistake because I used a link within a button element, which is semantically wrong. I deleted the button and styled the link instead and no more errors were found.
      ![HTML results about us with errors](documentation/readme/html-validator-errors-about.png)
      ![HTML results about us](documentation/readme/html-validator-about.png)
    - result for gallery.html<br>
      ![HTML results gallery](documentation/readme/html-validator-gallery.png)    
    - result for contact.html<br>
      On the contact page I forgot to delete a paragraph tag and incorrectly assigned an ID to two other elements. After I individualized them, no further errors were found.
      ![HTML results contact with error](documentation/readme/html-validator-errors-contact2.png)
      ![HTML results contact with error](documentation/readme/html-validator-errors-contact1.png)
      ![HTML results contact with error](documentation/readme/html-validator-error-contact.png)
      ![HTML results contact](documentation/readme/html-validator-contact.png)<br>

I also checked all pages in the validator via text-input and likewise no errors were detected in this way. 
        
2. [CSS Validator](https://jigsaw.w3.org/css-validator/)

    - result for styles.css <br>
    The only warning I received initially was the use of a text wrap property. I could easily fix this by changing it into the white-space property. 
      ![CSS results](documentation/readme/css-validator.png)
      The warning is due to import of the Google fonts.

3. Lighthouse Test<br>
To measure the website against performance, accessibility, SEO and best practice I used [Lighthouse](https://chromewebstore.google.com/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk?hl=de).<br>
I could improve the accessibility by changing the quotation marks, which are a part of the coordinates and can not be used in the aria-label, into two single quotes. 
![Lighthouse with warning](documentation/readme/lighthouse-accessibility-coordinates.png)
![Lighthouse with correction](documentation/readme/lighthouse-after-correction.png)


4. Manual testing <br>



5. Browser Compatibility<br>
The tests were conducted using the following browsers:
- Google Chrome Version 120.0.6099.71
- Safari on Mac Version 17.0 (17616.1.27.111.22, 17616)
- Safari on iOS 17.1.2 
- Edge Version 120.0.2210.61
  
6. Bugs

- No bugs were found.

## Deployment

- xxx

## Credits 

### Content 

- I used for information about chasselas and the winegrowers association: [Weinlaube](https://www.weinlaube.de/weinwissen/rebsorten/weisse/gutedel/) and the website of the [Winzervereinigung Freyburg-Unstrut](https://www.winzervereinigung-freyburg.de/en/15/winzervereinigung/winzervereinigung)

### Code

- The css code for the responsive picture gallery grid was taken from the tutorial bei [Rüdiger Alte](https://www.imarketinx.de/artikel/responsive-image-gallery-with-css-grid.html)
- To understand more about the concepts of html and css fundamentals such as float-property, flexbox and grid, I used the udemy course: [The complete 2023 Web Development Bootcamp by Dr. Angela Yu](https://www.udemy.com/course/the-complete-web-development-bootcamp/)
- The following websites were used as a source of knowledge: <br>
  - [Google](www.google.com)
  - [mdn](https://developer.mozilla.org/en-US/)
  - [W3C](https://www.w3.org/)
  - [W3schools](https://www.w3schools.com/) 
  - [DevDocs](https://devdocs.io/)
  - [Stack Overflow](https://stackoverflow.com/)
  - Slack Community

### Media 

- Icons on the footer, the header and for links were taken from [Font Awesome](https://fontawesome.com/)
- The fonts were imported from [Google Fonts](https://fonts.google.com/)

### ReadMe

- A big thank you to [Kera Cudmore](https://github.com/kera-cudmore) and all of her tips on what makes a good README. 


### Acknowledgments

- I would like to thank my wonderful mentor Brian Maccheria for his numerous tips and great assistance during the creation of this project.

__This is for educational use.__
