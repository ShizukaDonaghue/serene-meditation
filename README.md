# Serene Meditation

Welcome to Serene meditation. This is a website that introduces meditation to those who are new to meditation and aims to help them get started with their meditation practice.

The users of this website will become familiar with what meditation is, benefits of meditation, meditation techniques and tips and tricks to start their meditation journey.

<img src="docs/images/responsive-view.png" alt="Image showing how the website looks on different screen sizes"/>

## Live Website
[Serene Meditation](https://shizukadonaghue.github.io/serene-meditation/)

## Repository
https://github.com/ShizukaDonaghue/serene-meditation


## Table of Contents


## UX: User Experience
### User Stories
As a user, 
* I would like the website to be visually appealing and gives me a sense of peace and calm.
* I would like to understand what meditation is and its benefits.
* I would like to be able to learn meditation techniques and how to get started.
* I would like to be inspired to start meditation.
* I would like to be able to ask questions or provide feedback.

### Initial Concept
The initial concept was to create a website that would inspire users to start meditation practice and help them get started. Therefore, the website would explain what benefits they could expect and what types of techniques were available, so that users could try different techniques to start their journey. 

### Wireframes

### Website Structure
Serene Meditation consists of two HTML pages. The main page is the default landing page and the second page is accessible when the user submits a message from the main page to thank them for their message. 

The layout of the website is simple and consistent full page scroll with a fixed navigation bar at the top. There are five sections within the main page and they are also accessible from the navigation bar to bring the user to a specific section of the page. 

In addition to the navigation bar, the second page includes a "Home" button, so that the user can easily navigate back to the main page after submitting a message. The logo is linked to the top of main page to delivery the same effect and the user can also choose to navigate to a specific section of the main page from the navigation bar on the second page. 

The website is responsive to different viewport sizes and the layout is the same in all sizes with images spanning across the full width of the page. All images are adjusted to the full width of the viewport, and they are displayed in the same size across the website for consistency. 

Each of these images includes an inspiration quote to suit the content of the section that they are in. These images and quotes are designed to generate a positive emotional response in the user and aim to inspire them to start their journey, and therefore, the images are the integral part of the website.

### Imagery
The images are carefully chosen to set the calm and peaceful tone for the website. They are beautiful images of sunrise to signify the start of a meditation journey. 

Detailed alt attribute is included for each image to describe the scenery. The intention for this is to improve accessibility so that the images will deliver the same effect for all users.

### Colour Scheme
The colour scheme for the website has taken inspiration from the hero image of Mt. Fuji at sunrise in which the morning sun is turning the top of the mountain and surrounding sky pink. The colours chosen are calming and relaxing to enhance user experience. 

The background colour for the website is pale pink F3E4E4 and the font for the main contents is dark grey 01212F to ensure sufficient contrast for accessibility. The navigation bar is in dark blue 092039 with contrasting font in white FFFFFF. Dark pink C98282 is used for the social media icons in the footer, and light blue 68A5BF is used for hover effects within the website.

Colour palette generated using [Coolors.co](https://coolors.co/):

<img src="docs/images/colour-palette.jpg" alt="Image showing the colours used for the website"/>

### Typography
There are two fonts used in the website and they are imported from [Google Fonts](https://fonts.google.com/). For the main body of the text, EI Messiri was chosen as it has a calming flow which suits the image of the website. For the inspirational quotes, Alex Brush was chosen, which is a beautiful handwriting style to suit the images.

## Features
### Existing Features
* Navigation Bar    
Featured on both HTML pages, the fully responsive navigation bar includes the logo which links to the top of the main page, and a link to each section within the main page. This will allow the user to easily navigate to their desired section without having to use the "back" button each time.

    Navigation bar for smaller viewport sizes:

   <img src="docs/images/navigation-bar-for-smaller-viewports.png" alt="Image showing the navigation bar for smaller viewport sizes" height="38">

    Navigation bar for larger viewport sizes:

   <img src="docs/images/navigation-bar-for-larger-viewports.png" alt="Image showing the navigation bar for larger viewport sizes" height="40">

* The Landing Page Image 
The landing page includes a photograph of Mt. Fuji at sunrise with an inspirational quote, aiming to inspire the user to start meditation practice.

   <img src="docs/images/landing-page-image.png" alt="Image showing the landing page image"/>

The website also includes four other images of sunrise and inspirational quotes to 


* Footer
The footer section includes links to the social media sites as well as my own GitHub and Linkedin accounts. The links will open to a new tab to allow easy navigation for the user. The footer is available on both HTML pages.





### Future Features
* The drop down menu from the navigation bar for smaller viewport sizes currently stays open after the user selects one of the sections and navigates to the desired section. The drop down menu is only closed by clicking or tapping on the "X" in the navigation bar. If the drop down menu disappers once the user selects one of the sections, or taps outside of the drop down menu, it would help to improve user experience. This is something that can be implemented once I learn JavaScript.   

* The navigation bar currently does not have a drop down menu for "Techniques" section. A drop down menu will enable users to select a specific technique from the navigation bar. XXXXX EXPLAIN WHY THIS WAS NOT IMPLEMENTED  

## Technologies Used
* The fonts used in the website are imported from [Google Fonts](https://fonts.google.com/) 
* The colour scheme ideas and actual colour palette were generated with [Coolors.co](https://coolors.co/)
* Images within the website were compressed with [Compressor.io](https://compressor.io/) so that the website will load quickly
* The website uses icons from [Font Awesome](https://fontawesome.com/)
* The website uses [cdnjs.com](https://cdnjs.com/) for Font Awesome icons so that the website will load quickly
* [Chrome Dev Tools](https://developer.chrome.com/docs/devtools/) were used extensively while adjusting the objects in the website for different screen sizes. 
* The website was validated using [W3C HTML Validation Service](https://validator.w3.org/) and [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/).
* [Am I responsive?](https://ui.dev/amiresponsive) was used to generate the mockup image showing the website on various screen sizes.
* Balsamic

## Testing

### Bugs 
#### Resolved
Scroll-padding-top property is applied to this website so that when the link to each section is selected from the navigation bar, the desired section moves to the top of the screen below the fixed navigation bar (not hidden under the navigation bar), however, in Safari for Apple Devices, the padding was applied larger than the rem unit set and the section above was visible. The issue was not seen in the developer tools during the design phase. 

The issue was resolved by changing the scroll-padding-top property from rem to px.

Image showing scroll-padding not applied correctly before the issue was resolved:

<img src="docs/images/scroll-padding-error.png" alt="Image showing scroll-padding-top issue" width="300"/>

Image showing scroll-padding applied correctly after the fix:

<img src="docs/images/scroll-padding-fixed.png" alt="Image showing scroll-padding-top after the fix" width="300"/>

#### Unresolved

## Deployment


## Credits
### Contents
* Contents for "What is Meditation?" section was sourced from [verywellmind](https://www.verywellmind.com/what-is-meditation-2795927)
* Contents for "Benefits of Meditation" section was sourced from [WebMD](https://www.webmd.com/balance/video/daily-meditation-benefits)
* Contents for "Meditation Techniques" section was sourced from [INSIDER](https://www.insider.com/guides/health/mental-health/types-of-meditation)
* Contents for "Tips & Tricks" section was sourced from [verywellmind](https://www.verywellmind.com/what-is-meditation-2795927)
* Inspirational quotes were sourced from [PositivePsychology](https://positivepsychology.com/mindfulness-quotes/), [Parade](https://parade.com/1066461/nicolepajer/meditation-quotes/), and [Keepinspiring.me](https://www.keepinspiring.me/25-meditation-quotes/)
* README.md was inspired by [TashaTJ's repository](https://github.com/TashaTJ/pawsome-portraits-v4)

### Media
* Images used were sourced from [pxhere.com](https://pxhere.com/) and [pixabay.com](https://pixabay.com/)
### Codes
* The responsive navigation bar was inspired by YouTube tutorial by [Kevin Powell](https://www.youtube.com/watch?v=8QKOaTYvYUA)

## Acknowledgements
* 