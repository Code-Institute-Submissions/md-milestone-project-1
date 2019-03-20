# 21W8Y - Photography Creative Agency - Responsive Website - Code Institute Milestone Project 1

## What does it do and what need does it fulfill?

This project is a mobile-first, responsive website for 21W8Y Creative Photography Agency. It fulfills the need of potential clients to get familiar with 21W8Ys work, team members, work process and enquire about a possible project through a contact form.

## UX

[UX Documentation](https://www.figma.com/file/SQ2KrW652jyEjfDJc4JcxaC6/Untitled?node-id=1%3A2)

## Features

The website uses mobile-first design and is fully responsive. It's mosty a one page design. The first section (Hero) of the website displays an interactive photo on larger screen sizes. Navigation is functional and uses Bootstraps JavaScript for displaying navigation as a hamburger menu on smaller screen sizes. The website uses [lighboxgallery](https://github.com/kawshar/lightboxgallery) for displaying portfolio as a gallery with a lightbox. The website uses custom JavaScript to provide users with 'Go back to top' button [Source](https://www.w3schools.com/howto/howto_js_scroll_to_top.asp). The Website uses javascript for smooth animation on auto-scroll from navigation [Source](https://stackoverflow.com/questions/50709873/smooth-scroll-for-link-with-anchor) (*modified for purposes of this project). This website also provides users with: (for now) not functional contact form. Contact form provides validation and feedback on interaction.                       
### Existing Features   
- Contact Form - allows users to contact the agency via email, by having them filling out the contact form on /contact.html
- Back to top button - allows users to go back to the top of the page when using one-page navigation
- Lightbox Gallery - allows users to view, and switch between photographs

- Contact From yet to be connected to the server to be functional

### Features Left to Implement
- Pictures of team members to be displayed on hover following the cursor

## Technologies Used

- HTML5
- CSS3
- [JQuery](https://jquery.com)
    - The project uses **JQuery** for Gallery: [lighboxgallery](https://github.com/kawshar/lightboxgallery)
- JavaScript 
    - Project uses **JavaScript** for **Bootstrap** proposes, Smooth Scrool [Source](https://stackoverflow.com/questions/50709873/smooth-scroll-for-link-with-anchor) and Back to top button [Source](https://www.w3schools.com/howto/howto_js_scroll_to_top.asp)
- Bash
- Git
    - Project uses **Git** for version controll and backup
- Bootstrap 
    - Project uses **Bootstrap 4** for navigation and layout of the pages
- Google Chrome Dev Tools
- Microsoft VisualCode

## Testing

Mobile-first responsiveness was tested on all available resolutions/devices in Google Dev tools. It was also tested on 2 separate devices iPhone X, and iPhone XR. Contact Forms validation and functionality was tested and reported working correctly.
All of the links are connected and social links are opening in new tabs.
All tests were conducted 2 times once locally and remotely on Github Pages.


### Bugs

1. Back to top button was displayed on top of gallery element. Clicking on an overlayed part, would engage a lightbox instead of the button.

    - Fixed by applying z-index 99 to back to top button and z-index 0 to lightbox trigger

2. Console displayed An Error with tooltip.js 
    -   Fixed by removing tooltips function as it was redundant.

3. Console displayed a JQuery Error not recognizing lighboxgallery as a class
    -   Fixed by repositioning JQuery CDN link to the top part of HTML code

## Deployment

The project was developed locally using Microsoft VisualCode. Git was used for version control and backup. It was then pushed to remote depository and published to Git Pages through bash.

### Credits

## Content
- Copy was written by me. Inspired by [Ueno](https://ueno.co) 

## Media
- All phots are mine and can be downloaded for free, via [Unsplash](https://unsplash.com/@21w8y)
   
## Acknowledgements

### Code

- [Navbar](https://getbootstrap.com/docs/4.1/examples/navbars/) 
- [Lightbox Gallery](https://github.com/kawshar/lightboxgallery) 
- [Smooth Scrool](https://stackoverflow.com/questions/50709873/smooth-scroll-for-link-with-anchor) 
- [Back to Top Button](https://www.w3schools.com/howto/howto_js_scroll_to_top.asp)

### Inspiration

- [Ueno](https://ueno.co) 
- [84.Paris](https://www.84paris.com/en) 
- [Aristide Benoist](https://www.aristidebenoist.com/)