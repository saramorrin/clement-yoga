# Clement Yoga

The Clement Yoga website is a website for people looking to practice yoga, either in a class environment, online at home or in a private one to one setting.  
Clement Yoga also offers personalised meditation techniques and yoga retreats to its clients.

Users of the site will be able to see the services which Clement Yoga offer, along with a step by step simple meditation technique to follow at home and a contact page to get in touch for further details.

A live website can be found [here](https://saramorrin.github.io/clement-yoga/index.html)

![Website Preview](assets/images-readme/responsive-image.jpg)

# Site Design Considerations

### Client Expectations

The basic functions requested by the client were:
- Picture examples of the kinds of practices offered
- A simple meditation demonstration to give potential clients some information to take away from the site which could be built upon should they wish to join
- Convey a message of offering a way to deliver a more balanced, tranquil and mindful way of life through the practices and meditation techniques on available
- Links to all social media channels, as currently most clients are directed to the business from these
- Contact page where clients can get in touch with the company for further information

The client would like to have the ability to add further functionality at a later point to include a class timetable for yoga classes, an online booking form for yoga classes and a dedicated retreat page to showcase past retreat events. 

The client would like the website to convey a welcoming, serene and tranquil tone, focusing on using cool pink and grey based hues.

### User Expectations
- User to be able to quickly and easily understand to purpose of the site
- User to be able to find simple navigation around the website
- User to be able to locate business contact details
- User to be able to locate business social media links
- User to be able to contact the business without leaving the site and using an external source
- User to be able to view the site across an array of devices without loss of functionality
- A user with disabilities will be able to navigate the site freely without obstruction

## Colour Scheme and Font

[My Color Space](https://mycolor.space/?hex=%23D9BDB2&sub=1) was used to choose a complimentary colour pallet based on the images selected. The aim was to ensure the best use of contrasting colours inline with accessibility guidelines.  
The colours used were:
- #D9BDB2 background colour for site header and footer
- #FFE9E5 background colour for site paragraph text and images

The initial heading font chosen was [Dancing Script](https://fonts.google.com/specimen/Dancing+Script?query=danc). However upon testing the font was not that clear to read and did not make enough of an impact for a logo text.
Instead, [Amatic SC](https://fonts.google.com/specimen/Amatic+SC?query=amatic) was picked as this provided a bolder look while still in keeping with the overall vision of the site. Of the fonts suggested by Google Fonts for appropriate pairings, [Open Sans](https://fonts.google.com/specimen/Open+Sans?query=open) was chosen for the paragraph text. It is a clean legible font, which sits nicely of the page alongside the heading text. Sans-serif was added as a backup option for those browsers that do not support some of the modern typefaces.  

## Site Skeleton

[Balsamiq](https://balsamiq.com/) was used to create wireframes of the website. This was very useful as it gives the template of the UI. Wireframes were designed for web browser and a mobile browser format. 

![Balsamiq Mobile Image](assets/images-readme/balsamiq-mobile.jpg)

![Balsamiq Desktop Image](assets/images-readme/balsamiq-desktop.jpg)

# Features

Navigation Bar and Landing Page
- The navigation bar features at the top of all three pages of the site and is fully responsive
- The uniform styling aims to link all pages together for a seamless, fluid feel
- The bar contains links to all other pages across the site
- The landing page image has been used to immediately demonstrate what the website can offer and a circle image of text has also been added to summarise all services available
- Further down the page there are three images to promote the three types of services available to the user. Each image has been picked as it provides a clear visual description of the service along with a brief text underneath. Each image has a hover effect which when clicked directs the user to the contact page form

![Landing Page](assets/images-readme/landing-page.jpg)

![Yoga Style Image](assets/images-readme/yoga-landing-page.jpg)

![Retreats Style Image](assets/images-readme/retreats-landing-page.jpg)

![Meditation Style Image](assets/images-readme/meditation-landing-page.jpg)

### Techniques Page
- The technique page provides a simple step by step mediation practice for the user to copy at home. There are five images each with accompanying text detailing how to carry out the individual technique
- Going forward, this could be regularly updated and changed to different techniques to provide newness to the site

![Techniques Page](assets/images-readme/techniques-screenshot.jpg)

### Contact Page
- The contact page has a contact form for users to input their name and email address. Users must also choose which service they are interested in being contacted about by selecting either Yoga, Meditation or Retreat
- The page also features a background image with a zoom effect to add another level of interest for the user and to provide a point of difference

![Contact Form](assets/images-readme/contact-form-screenshot.jpg)

### Footer
- The footer contains icons to the company's social media pages which all open in a separate window. They also have a hover effect to improve the user experience
- The footer contains contact details for the company, including a location address and telephone number

![Footer](assets/images-readme/footer-screenshot.jpg)

# Testing
- I have confirmed that all headings in the navigation bar direct the user to the relevant page when clicked
- I have confirmed that all social media links open in a new tab when clicked and redirect to the relevant website
- I have confirmed that the form works correctly. All entry fields must be completed before the form can be submitted
- I have confirmed that all images on the homepage direct the user the contact page when clicked
- [EightShapes](https://contrast-grid.eightshapes.com/?version=1.1.0&background-colors=&foreground-colors=%23FFFFFF%2C%20White%0D%0A%23000000%2C%20Black%0D%0A%23D9BDB2%0D%0A%23FFE9E5%0D%0A%23B17067%0D%0A%0D%0A&es-color-form__tile-size=compact&es-color-form__show-contrast=aaa&es-color-form__show-contrast=aa&es-color-form__show-contrast=aa18&es-color-form__show-contrast=dnp) was used to check that text was compliant on both foreground and background colour combinations

# Bugs
- I found that a few spelling errors stopped my code from working at times. These were identified and correct.
- I noticed that the media query was not responsive on the home page. The circle text over the hero image would not scale down correctly. This was because there was a high width on the element forcing it to move. This was rectified by adjusting the width to allow the image to become visible.

# Validator Testing
## HTML

[W3C Markup](https://validator.w3.org/#validate_by_input) was used to check for any errors within my HTML pages.
I had a warning to consider changing some of the h1 elements to enable better use for screen readers . I actioned this by changing any h1 elements outside of the header sections to h2.

![W3C Validator](assets/images-readme/html-checker-error.jpg) 

![W3C Validator](assets/images-readme/html-checker-no-error.jpg) 

![W3C Validator](assets/images-readme/html-checker-full-site.jpg) 

## CSS

[W3C CSS Validator](https://validator.w3.org/#validate_by_uri) was used to check for any error within my CSS stylesheet. No errors were found.

![W3C Validator](assets/images-readme/css-validator.jpg)

## Accessibility

Google Dev Tools Lighthouse was used to check for any accessibility issues.

Landing Page

![Landing Page](assets/images-readme/lighthouse-homepage.jpg)

Techniques Page

![Techniques Page](assets/images-readme/lighthouse-techniques-page.jpg)

Contact Page

![Contact Page](assets/images-readme/lighthouse-contact-page.jpg)

# Deployment

The site was deployed to GitHub pages.

The steps to deploy are as follows:

In the GitHub repository, navigate to the Settings tab
Select the Pages sub-menu
From the source section drop-down menu, select the Master Branch, and then hit save
Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.  

The live link can be found here - (https://github.com/saramorrin/clement-yoga)

# Credits
- I viewed the following tutorials on YouTube to further help me expand my knowledge on how to align text next to images [EZ Tutorials](https://www.youtube.com/watch?v=IDcf8Ig-05Y)
- I used W3Schools Tutorial pages to help further my understanding of coding media queries, hero image text placement and zoom effects.

# Media
 - All fonts came from [Google Fonts](https://fonts.google.com/) 
 - All images came from [Pexels](https://www.pexels.com/)
 - All icons came from [Font Awesome](https://fontawesome.com/)
