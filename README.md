# Isbaner vineyard

_HTML and CSS Essentials Project Portfolio - Code Institute_

View deployed site [here.](https://queenisabaer.github.io/isbaner-vineyard/)

Isbaner vineyard is a site dedicated to the vineyard of the Isbaner family. The site is targeted towards interested parties, friends and family who want to learn more about the vineyard, stay in touch with the owners or visit them and keep updated through the year. In addition, it will be useful for people who want to know something about the chasselas grape and the region Wethau, Saale-Unstrut.

![Responsive Mockup](documentation/readme/am-i-responsive.png)

## Table of contents

- [User Experience (UX)](#user-experience)
- [Design](#design)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Testing](#testing)
- [Deployment](#deployment)
- [Credits](#credits)

## User Experience (UX)

### User stories

Goals for:

- **First time visitor:**
  An overview of the vineyard should be given to first-time visitors. Especially when the owners meet new people and tell them about their hobby, they are naturally very curious and want to find out more about the vineyard, the grapes planted and the winegrowers' association of which the owners are member of. Furthermore, it's common for them to ask for pictures of the vineyard and garden. Therefore, quick access to the most important information is essential. On the main page, the three image boxes symbolize the components of the homepage. Clicking on the buttons takes you to the corresponding content.
- **Returning visitor:**
  Returning visitors may want to visit the vineyard or get in touch with the Isbaner family. So the contact area allows them to contact the owners and, for instance, book a wine tasting or a guided tour.
- **Frequent user:**
  Frequent users are interested in staying in touch with the owners or want to know what it looks like on the vineyard and what’s new, especially the gallery is interesting for them.

## Design

- **Imagery:**
  All photos were taken by the owners within the last years and were provided for the project. They reflect the daily reality of the vineyard with all of its beauty.
- **Colour Scheme:**
  The color scheme should match the vineyard theme and the fact that sandstone is mined in the region, which is also used in the garden. Therefore, with the pipette function on [coloors.co](https://coolors.co/), green and brown shades were chosen, which were taken from the photograph of the background image at contact.html. Since green also dominates in the vineyard, the shade #295900 has become the primary color. The brown shades set accents, primarily as a background for buttons and text fields.<br>
  ![Color palette](documentation/readme/grapes-coloors-palette.png)
- **Typography:**
  The font [Nobile](https://fonts.google.com/specimen/Nobile?query=nobile) was selected for text content. It was important that this font created a contrast to the logo and heading. It should therefore be clear, simple and easy to read on all screen sizes.
  Since wine-growing is a very old and respected tradition, a handwritten-looking font was chosen as the font for the logo and headings: [Tangerine](https://fonts.google.com/specimen/Tangerine?query=tangerine)
  > Tangerine is a calligraphic typeface inspired by many italic chancery hands from the 16th and 17th centuries. _(Google Fonts)_

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
Since I've learned that buttons and links have different roles, I did not design the links as a button. Especially since this design also resulted in a warning in the HTML validator.

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
Every page contains a responsive navigation bar on the top with a logo on the left side and the navigation on the right that supports easy navigation. On small screens (e.g. mobile devices) the navigation will become a clickable burger toggle. To make it easier for users to know where they are on the website, the current page is underlined.<br>
![Navbar on mobile devices](documentation/readme/navigation-mobile.png)
![Navbar when clicked on hamburger menu on a mobile device](documentation/readme/navigation-mobile-toggle.png)
![Navbar ob tablets and larger screens](documentation/readme/navigation-desktop.png)

The footer stays on the bottom of every page and features clickable social media icons and the coordinates of the vineyard, which act as a link to google maps. All links on the footer are opened in a new tab.<br>
![Footer on mobile devices](documentation/readme/footer-mobile.png)
![Footer on desktop](documentation/readme/footer-desktop.png)

- **Hero image**

The hero image on the main page shows a lovely view over the vineyard. This is intended to convey the beauty of the vineyard directly to the user. In the upper left corner, there is a link button that points to the about us page. Contrary to what was originally planned, the button was moved to the side so that the image was not disturbed.<br>
![Hero image](documentation/readme/hero-image.png)<br>
Below the hero image, there are two image containers that refer to the other subpages of the website. They were adapted to the layout of the hero image. <br>
![Image container main page](documentation/readme/image-container-main.png)

- **About us Page**

The _About us_ page consists of three parts. The first part tells a short story about the owners of the vineyard, the second gives some information about the grape chasselas and the third part highlights the region where the vineyard is located. Each section contains an image, a heading, some text and a link. When viewed on a mobile phone, the image will be placed on top of the heading. The links change their appearence when hovered.<br>
![About us Page](documentation/readme/about-section.png)

- **Gallery Page**

The Gallery page will provide users with photographs to see what happens on the vineyard spread over a year. It has two main sections. The first contains horizontal photographs and the second vertical ones.
To create the responsive gallery, I used the tutorial and CSS code for a grid gallery by [Rüdiger Alte](https://www.imarketinx.de/artikel/responsive-image-gallery-with-css-grid.html) <br>
![Gallery Page](documentation/readme/gallery.png)

- **Contact Page**

The contact page contains two areas. The first offers a contact form that users can complete to get in touch with the owners of the vineyard. The user is asked to enter their first name, last name and e-mail address when sending a message. This information is mandatory. After submitting the form, a new tab with the results are displayed. Currently, it shows the form dump.codeinstitute.net page with the determined form data. Unfortunately, the Code Institute formdumb is not designed to display multiple entries in checkboxes, which is why only the first one is displayed as value. <br>
![Contact fieldset](documentation/readme/contact-fieldset.png)<br>
The second area provides directions to the vineyard. Both images are screenshots from Google as in Germany it is not permitted to use the interactive Google map due to data security concerns. However, clicking on the images takes the user to the Google Maps page in a new tab. <br>
![Find us fieldset](documentation/readme/find-us-fieldset.png)

- **404 Page**<br>
The 404 page is a simple page with a heading and a sentence, including a link back to the main page. It was created to provide a better user experience. <br>
![404 page on desktop](documentation/readme/404-page-desktop.png)<br>
![404 page on desktop](documentation/readme/404-page-mobile.png)<br>

### Features, which I would like to implement in the future

- As the gallery is currently very simple, I would like to improve it in the future. I could imagine a different design with enlargeable images and subtitles. Furthermore, I would create tags with categories for spring, summer, autumn & winter.
- I would like to create my personal page after submitting the form and of course use a corresponding data processing programm.
- Since German is my native language, I would love to make a German version of the website.
- Add a favicon.

## Technologies Used

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
- [Google Fonts](https://fonts.google.com/) was used to import fonts into the style.css.
- [Font Awesome](https://fontawesome.com/) was used to add icons.
- [Git](https://git-scm.com/) was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
- [GitHub](https://github.com/) was used to save and store the files for the website.
- [Balsamiq](https://balsamiq.com/) was used to design the wireframes.
- [Coloors](https://coolors.co/image-picker) was used to create the color scheme.
- [iLoveIMG](https://www.iloveimg.com/) was used to cropp and resize the images.
- [Pixelied](https://pixelied.com/) was used to convert images from jpg to webp
- [imgtools](https://www.imgtools.co/) was used to resize webp images
- [Am I Responsive](https://ui.dev/amiresponsive) was used to display the website on different devices.
- [beautifier](https://beautifier.io/) to beautify the code

## Testing

1. **Validator Testing**

- **[HTML Validator](https://validator.w3.org/)**

  - result for index.html<br>
    First, I had an error because my semantics of the h2/button element weren't correct. No errors or warnings were found after fixing this problem.
    1. result with error<br>
    ![HTML results index with errors](documentation/readme/html-validator-errors-index.png)
    2. final result<br>
    ![HTML results index](documentation/readme/html-validator-index.png)<br>
  - result for about.html<br>
    I made a mistake because I used a link within a button element, which is semantically wrong. I deleted the button and styled the link instead, and no more errors were found.
    1. result with error<br>
    ![HTML results about us with errors](documentation/readme/html-validator-errors-about.png)
    2. final result<br>
    ![HTML results about us](documentation/readme/html-validator-about.png)<br>
  - result for gallery.html<br>
    ![HTML results gallery](documentation/readme/html-validator-gallery.png)<br>
  - result for contact.html<br>
    On the contact page, I forgot to delete a paragraph tag and incorrectly assigned an ID to two other elements. After I individualized them, no further errors were found.
    1. result with error<br>
    ![HTML results contact with error 1](documentation/readme/html-validator-errors-contact2.png)
    ![HTML results contact with error 2](documentation/readme/html-validator-errors-contact1.png)
    ![HTML results contact with error 3](documentation/readme/html-validator-error-contact.png)
    2. final result<br>
    ![HTML results contact](documentation/readme/html-validator-contact.png)<br>
  - result for 404.html<br>
  ![HTML results 404 page](documentation/readme/html-validator-404.png)

I also checked all pages in the validator via text-input, and likewise no errors were detected in this way. All I got was an information to avoid trailing slashes in void elements.

- **[CSS Validator](https://jigsaw.w3.org/css-validator/)**
   - result for styles.css <br>
     The only warning I received initially was the use of a text wrap property. I could easily fix this by changing it into the white-space property.
     ![CSS result](documentation/readme/css-validator.png)
     The warning is due to import of the Google fonts.

2. **Lighthouse Test** <br>
   To measure the website against performance, accessibility, SEO and best practice I used [Lighthouse](https://chromewebstore.google.com/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk?hl=de).<br>
   I was able to improve the accessibility by changing the quotation marks (which are a part of the coordinates and can not be used in the aria-label) into two single quotes.

- result for index.html:<br>
  1. with warning for accessibility(desktop version)<br>
  ![Lighthouse report for index with warning](documentation/readme/lighthouse-accessibility-coordinates.png)<br>
  2. desktop after correction<br>
  ![Lighthouse report for index with correction on desktop](documentation/readme/lighthouse-index-dektop.png)<br>
  3. mobile<br>
  ![Lighthouse report for index on mobile screens](documentation/readme/lighthouse-index-mobile.png)<br>
  ![Lighthouse report for index on mobile screens](documentation/readme/lighthouse-index-cache-policy.png)<br>
- result for about.html:<br>
  1. mobile <br>
  ![Lighthouse report for about page on mobile screens](documentation/readme/lighthouse-about-mob.png)<br>
  2. desktop<br>
  ![Lighthouse report for about page on desktop](documentation/readme/lighthouse-about-desktop.png)<br>
- result for gallery.html:<br>
  1. mobile<br>
  ![Lighthouse report for gallery page on mobile devices](documentation/readme/lighthouse-gallery-mobile.png)<br>
  2. desktop<br>
  ![Lighthouse report for gallery page on dektop](documentation/readme/lighthouse-gallery-desktop.png)<br>
- result for contact.html:<br>
  1. mobile<br>
  ![Lighthouse report for contact page on mobile screens](documentation/readme/lighthouse-contact-mobile.png)<br>
  2. desktop<br>
  ![Lighthouse report for contact page on desktop](documentation/readme/lighthouse-contact.png)<br>
- result for 404.html:<br>
  1. mobile<br>
  ![Lighthouse report for 404 page on mobile screens](documentation/readme/lighthouse-404-mobile.png)<br>
  2. desktop<br>
  ![Lighthouse report for 404 page on desktop](documentation/readme/lighthouse-404-desktop.png)<br>

3. **Manual testing** <br>

To ensure the pages are responsive, I used the Google Chrome developer tools.
| **Test** | **Test Description** | **Expected Outcome** | **Result**|
|:---|:---|:---|:---|
| Header - Logo | Click on the logo to return to main page | Clicking on the logo on each page will return you to the main page | Pass |
| Header - Navbar toggler in mobile view | Click in mobile view on the burger icon to open the navigation | When the burger icon in mobile view is clicked, the navigation should open | Pass |
| Header - Navigation underline | The page you are currently on should be underlined in the menu | After reaching "Home", "About", "Gallery" or "Contact" the corresponding navigation item should be underlined | Pass |
| Header - Navigation link | Click on a term in the navigation bar to go to the corresponding page | Clicking "Home", "About", "Gallery" or "Contact" should take the user to the corresponding page | Pass |
| Footer - Coordinates | Click on the coordinates in the footer and a new tab with Google Maps opens | After clicking on the coordinates, a new tab with Google Maps should open with the coordinates already located | Pass|
| Footer - Social Media icons | Click on the logo of Facebook or Instagram and a new tab with Facebook page or Instagram page opens | After clicking on the logo of Facebook it should open a new tab with the Facebook page, and after clicking on the Instagram logo, Instagram should open in a new tab as well | Pass |
| Main page - Text hover | Hover over the text in the buttons to change its color | When you hover over the text on the buttons on the main page, they should change color | Pass |
| Main page - Text links| Click on the text in the buttons to reach the corresponding page | When the text on the buttons on the main page is clicked, the corresponding page should open | Pass |
| About-us page - Links hover | Hover over the link-text on the about us page | When you hover over the links on the about page, they should change color | Pass |
| About-us page - Links | Click on the links on the about us page to open the corresponding page | When you click on the links on the about page, the corresponding pages should open. | Pass |
| About-us page - Links Winzervereinigung /region | Click on the links to the *Winzervereinigung Freyburg-Unstrut* or the region on the about us page to open the corresponding page in a new tab | When you click on the links to the *Winzervereinigung Freyburg-Unstrut* or the region on the about page, the corresponding pages should open in a new tab. | Pass |
| Gallery responsiveness | Change the size of the screen | The images should load nicely and depending on the screen width in one, two, three or four columns | Pass |
| Contact page - form, name input | Try to submit form with no value in input field first name or last name | Form is not submitted and user is asked to enter the first name and last name | Pass |
| Contact page - form, no email input | Try to submit form with no value in input field email | Form is not submitted and user is asked to enter an email address | Pass |
| Contact page - form, wrong email input | Try to submit form without an actual email address in input field email | Form is not submitted and user is asked to enter a valid email address | Pass |
| Contact page - form submission | Click on the "cheers and submit" button. A new page with Code Institute form dumb should open | After all required contact fields have been filled out, click on the cheers and submit button. A new page with Code Institute form dumb should open | Pass |
| Contact page - images with links | Click on the images in the "How to find us" section and a new tab with Google Maps opens | After clicking on the images in the "How to find us" section", a new tab with Google Maps should open with the coordinates already located | Pass |
| 404 page | Request a page that doesn't exist | Users will be redirected to the 404-page | Pass |
| 404 page - link | Click on the word homepage to go back to main page | After clicking on the word homepage, you will be redirected to the main page | Pass |
| Responsiveness mobile - navigation | Open website on mobile | On mobile screens the navigation should be a first seen as burger icon | Pass |
| Responsiveness 4K+ | Open the website on 4K or larger screen | The website should have a maximum width and stay in the middle. The background color should be a light green, according to the color scheme | Pass |

4. **Browser Compatibility**<br>
   The tests were conducted using the following browsers:

- Google Chrome Version 120.0.6099.71
- Safari on Mac Version 17.0 (17616.1.27.111.22, 17616)
- Safari on iOS 17.1.2
- Edge Version 120.0.2210.61

5. **Bugs**

- No bugs were found.

## Deployment

This site is deployed using GitHub Pages. To deploy it from its GitHub repository to GitHub Pages, I took the following steps:
1. Log in (or sign up) to GitHub.
2. Navigate to the repository for this project by selecting [*queenisabaer/isbaner-vineyard*](https://github.com/queenisabaer/isbaner-vineyard)
3. Click the *Settings* tab above the repository 
4. In the left-hand menu, select *Pages*
5. In the section **"Build and deployment"** under *Source* select *Deploy from a branch* 
6. In the section **"Build and deployment"** under *Branch* select in the first area *main* and in the second *root*
7. Click the *Save* Button<br>
After refreshing the settings site for this repository above the **"Build and deployment"** section, you will see the GitHub Pages area with the link to the [view of the live site](https://queenisabaer.github.io/isbaner-vineyard/)

- Forking this GitHub repository
1.  Log in to GitHub.
2.  Navigate to the repository for this project by selecting [*queenisabaer/isbaner-vineyard*](https://github.com/queenisabaer/isbaner-vineyard)
3. Click at the top of the repository on the **Fork** button on the right side

- Clone this repository
1.  Log in to GitHub.
2.  Navigate to the repository for this project by selecting [*queenisabaer/isbaner-vineyard*](https://github.com/queenisabaer/isbaner-vineyard)
3. In the top right corner, click on the green *Code* button
4. Copy the HTTPS URL in the tab *Local*
5. Go to the code editor of your choice and open the terminal
5. Type `git clone` and paste the URL you copied into your terminal
6. Press the enter key

## Credits

### Content

- I used for information about chasselas and the winegrowers' association: [Weinlaube](https://www.weinlaube.de/weinwissen/rebsorten/weisse/gutedel/) and the website of the [Winzervereinigung Freyburg-Unstrut](https://www.winzervereinigung-freyburg.de/en/15/winzervereinigung/winzervereinigung)

### Code

- The CSS code for the responsive picture gallery grid was taken from the tutorial by [Rüdiger Alte](https://www.imarketinx.de/artikel/responsive-image-gallery-with-css-grid.html)
- To understand more about the concepts of HTML and CSS fundamentals such as float-property, flexbox and grid, I used the udemy course: [The complete 2023 Web Development Bootcamp by Dr. Angela Yu](https://www.udemy.com/course/the-complete-web-development-bootcamp/)
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

- I would like to thank my wonderful mentor Brian Macheria for his numerous tips and great assistance during the creation of this project.

**This is for educational use.**