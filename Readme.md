# The Monkees website

Stream One Project: User-Centric Frontend Development - Code Institute

Website about band The Monkees. History of band, some pictures, music and videoclip as well as contact form to message group regarding events. 

## DEMO

Live demo you will found [here](https://mafiu84.github.io/milestone-project-01-cloned/)

## UX

### User stories

* Fan of group who wants to see news about group and listen to their music, see and/or download videoclip.

* Event organizer who wants to contact regarding organization of a concert or cooperation.  

* Person who wants to know more about band, see pictures, read history.

* Fan who wants to find links to social media accounts of group to connect with other fans.

### Approach

* Main - Landing page with picture of band with few words about them.

* About - More story of group with links to wikipedia to read articles about group and all artists separately as well.

* Pictures - Gallery with 4 pictures of band toghether and another 4 with artists separately.

* Music - Site with 4 of their most popular songs to listen.

* Video - Site where you can watch and/or download videoclip.

* Contact - Contact form to group manager and social media accounts links.

On sticky footer on every page there is link to Youtube subscription account of band. 
Navigation bar on the top of each page is sticky as well for quicker navigation. 
For mobile view instead of navbar there is drop down menu sticky on top right side.

### Strategy

My goal was to build mobile friendly, responsive website with all the information easily accessible from navbar on large screens and drop down menu on mobile devices.

### Scope

For fans, I wanted to provide them with all the news about group, and media to look at.

For people interested in cooperation, I wanted to provide possibility to contact group.

### Structure

In contact page I wanted to provide not only contact form but links to all social media accounts to maximize the fan base. YouTube subscription link is provided in footer on every page  and footer stays collapsed regardless to screen size for easy acces.

### Surface

Background pictures in landing page, music, video and contact page were edited in fotor app that they would not distract attention from the content. Theme is dark to conserve power on battery powered devices.

## TECHNOLOGIES

HTML - Hypertext Markup Language - used for building basic structure of website, allows to view it on modern web brosers [official description](https://whatwg.org/)

CSS - Cascading Style Sheets - adding styles to website like fonts, colours, layout etc. [official description](https://www.w3.org/Style/CSS/)

Bootstrap 3.3.7 - library that I've used to build responsive grid layout and as base for some smaller elements available [here](https://getbootstrap.com/)

Font Awesome - I've used this library to get icons and social websites logos available [here](https://fontawesome.com/)

Additional fonts from Google Fonts library (Carter One, Source Sans Pro) available [here](https://fonts.google.com/)

Fotor - photo editing app, to edit background pictures, downloaded from [here](https://www.fotor.com/windows/index.html)

## FEATURES

YouTube link is implemented on every site in container on bottom and its always visible as it scrolls with website. On contact page there are all link to social media of the band. Sites are responsive and on mobile screens there is drop down menu instead of navbar to get better clarity of content.

### Features left to implement

In future I would like to add online shop to sell items related to the group.

## TESTING

* HTML tested in validator - https://www.freeformatter.com/html-validator.html
* HTML also tested in validator - https://validator.w3.org/nu/ with one warning (wrong, about aria-label misuse).
* CSS tested in validator - http://csslint.net/ - Warnings:
    1.Beware of broken box size - Using width with border can sometimes make elements larger than you expect.
    2.Beware of broken box size - Using height with border can sometimes make elements larger than you expect.
    3.Beware of broken box size	- Using width with padding can sometimes make elements larger than you expect.
    4.Beware of broken box size	- Using height with padding can sometimes make elements larger than you expect.
    5.Disallow IDs in selectors	- Don't use IDs in selectors. #nav
    6.Disallow universal selector - The universal selector (*) is known to be slow.
    7.Disallow use of box-sizing - The box-sizing property isn't supported in IE6 and IE7. box-sizing: border-box;
    8.Too many floats (14), you're probably using them for layout. Consider using a grid system instead.
    9.Too many font-size declarations (77), abstraction needed.
* CSS tested also in validator - https://jigsaw.w3.org/css-validator/validator - passed with 12 warnings.
* Respoinsivity checked on multiple mobile devices with - https://www.responsinator.com/, working fine
* Tested for performance, accessibility, best practices and SEO for mobile and desktop machines in chrome dev tools-Lighthouse.\
* Also I've tested website in chrome devtools for responsiveness and on multiple browsers and mobile devices.\


## DEPLOYMENT

This site is hosted using GitHub pages.  
The live site updates automatically each time there is a new push to the repository. 

First you need to created github account. Project is deployed from master branch.

Project is hosted at:

<https://mafiu84.github.io/milestone-project-01-cloned/>

You can clone the code to run it locally on your machine from my github:

https://github.com/mafiu84/milestone-project-01-cloned

To clone it simply type in terminal "<code>git clone</code> https://github.com/mafiu84/milestone-project-01-cloned"

## CREDITS

### Content

As content i used Lorem ipsum text to complete the contents if necessary. 

### Media

All photos re from stock libraries and edited in Fotor app to keep the color theme of the page. Theme is dark bacause it reduces the luminance emitted by device screens, while still meeting minimum color contrast ratios. It helps improve visual ergonomics by reducing eye strain, adjusting brightness to current lighting conditions, and facilitating screen use in dark environments – all while conserving battery power.

### Acknowledgements

Band logo working as link to landing page was inspired by official website of group [official site](https://www.monkees.com/).



