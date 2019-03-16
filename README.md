# 21W8Y - Photography Creative Agancey - Responsive Website - Code Institute Milestone Project 1

## What does it do and what need does it fulfil?

This project is mobile-first responsive website for 21W8Y Creative Photography Company
It fulfils the need for potential clients to get familiar with comapnys work, team, process and also enquire through a contact form about the project.

## UX

[UX Documentation](https://www.figma.com/file/SQ2KrW652jyEjfDJc4JcxaC6/Untitled?node-id=1%3A2)

## Features

The website is mobile-first fully reseponsive. Mosty one page design. First section (Hero) of the websites displays interactive photo on larger screen sizes. Navigation is functional and uses Bootstaps JavaScript code for displaying navigation as a hamburger menu on smaller screen sizes. Website uses [lighboxgallery](https://github.com/kawshar/lightboxgallery) for displaying portfolio as gallery with lightbox. Website uses custom JavaScript to provide users with 'Go back to top' button [Source](https://www.w3schools.com/howto/howto_js_scroll_to_top.asp). This Website also uses JavaSript for smooth animation on autoscroll from navigation [Source](https://stackoverflow.com/questions/50709873/smooth-scroll-for-link-with-anchor) (*modified for pourpuses of this project). This website also provides users 
with, for now not functional contact form. Contact form also provides validation and feedback on interaction.                        

### Existing Features   
- Contact Form - allows users to achieve contact the company, by having them fill out contact from on /contact.html
- Back to top button - allows users to go back to top of the page when using one page navigation
- Lightbox Gallery - allows users to view, and switch between photographs on interaction

- Contact From have yet to be connected to server to be functional

### Features Left to Implement
- Pictures of team members to be displayed on hover follwing cursor

## Technologies Used

- HTML5
- CSS3
- [JQuery](https://jquery.com)
    - The project uses **JQuery** for Gallery [lighboxgallery](https://github.com/kawshar/lightboxgallery)
- JavaScript 
    - Project uses **JavaScript** for **Bootstrap** poropuses, Smooth Scrool [Source](https://stackoverflow.com/questions/50709873/smooth-scroll-for-link-with-anchor) and Back to top button [Source](https://www.w3schools.com/howto/howto_js_scroll_to_top.asp)
- Bash
- Git
    - Project uses **Git** for version controll and backup
- Bootstrap 
    - Project uses **Bootstrap 4** for navigation and layout of the pages
- Google Chrome Dev Tools
- Microsoft VisualCode

## Testing

Mobile-first responsivness was tested on avaiable resolutions/devices in Google Dev tools. It was also testes on 2 seprate devices iPhone X, and iPhone XR. Contact Forms validation and functionaly was tested and reported working correctly.
All the links are connected and social links are opening in new tabs.
All tests were conducted 2 times once localy and in Github Pages.


### Bugs

1. If Back to top button was displayed on top of gallery element clicking on overlayed part, would engage a lightbox instead of the button

    - Fixed by appling z-index 99 to back to top button and z-index 0 to lighbox trigger

2. Console displayed An Error with tooltip.js 
    -   Fixed by removing tooltips function as it was redundant.

3. Console display and JQuery Error not recognizing lighboxgallery as a class
    -   Fixed by repositioning JQuery CDN link to top position in html code.

## Deployment

Project was developed locally using Microsoft VisualCode, Git was used for version controll and backup. it for pushed to remote depository and then published using Git Pages through bash

## Credits

## Content
- Copy is written by me: inspired by [Ueno](https://ueno.co) 

## Media
- All phots are mine, and can be downloaded for free via [Unsplash](https://unsplash.com/@21w8y)
   

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