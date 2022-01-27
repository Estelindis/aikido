# MU Aikido Club
## by Siobhán Mooney

### [Click here to view the site.](https://estelindis.github.io/aikido/)
### [Click here to view the repository.](https://github.com/Estelindis/aikido)

# Table of Contents:
1. [About the project](#about-the-project)
    1. [User Goals](#user-goals)
    2. [Owner Goals](#owner-goals)
2. [Website structure](#website-structure)
    1. [Navigation](#navigation)
    2. [Header](#header)
    3. [Index Main Article and Hero Image](#index-main-article-and-hero-image)
	4. [Training Times Sidebar](#training-times-sidebar)
	5. [News Sidebar](#news-sidebar)
    6. [Footer](#footer)
    7. [FAQ Main Article and Image](#faq-main-article-and-image)
    8. [Gallery](#gallery)
    9. [Join](#join)
3. [Wireframes](#wireframes)
4. [Design](#design)
    1. [Colours](#colours)
    2. [Typography](#typography)
    3. [Imagery](#icons-and-images)
5. [Testing](#testing)
    1. [HTML Validator](#html-validator)
    2. [Jigsaw CSS Validator](#jigsaw-css-validator)
    3. [Lighthouse accessibility (Chrome DevTools)](#lighthouse-accessibility-chrome-devtools)
    4. [Manual testing](#manual-testing)
6. [Bugs and fixes](#bugs-and-fixes)
7. [Deployment](#deployment)
    1. [GitHub Pages](#github-pages)
    2. [Forking Repository](#forking-the-github-repository)
    3. [Cloning the project](#cloning-the-project)
8. [Used technologies and credits](#used-technologies-and-credits)
    1. [Languages](#languages)
    2. [Content](#content)
    3. [Media](#media)
    4. [Other technologies](#other-technologies)
    5. [Credits](#credits)


# About the project
The MU Aikido Club website is designed to inform users about aikido broadly and the MU Aikido Club specifically.  Ideally, a user who was not interested in aikido before visiting the site might become interested via browsing it. 

## User Goals
- Navigate easily through a clear, readable website with attractive colours and images.
- Learn what aikido is.
- Learn who can join the MU Aikido Club and where else one might practise aikido if not eligible to join MUAC.
- Find training times and locations.
- See what aikido practice is like and what other club activities take place. 
- Join the club.

## Owner Goals
- Explain what aikido is.
- Emphasize that MU Aikido Club is a beginners' club with no experience required.
- Display club experiences (training, courses, and social events). 
- Communicate when the club trains, how to get to the training venue, and who is eligible to join.
- Provide a way for interested users to join immediately.
- For users who are not eligible to join the MUAC, but still wish to learn aikido, provide information about other aikido opportunities.
- Convey aspects of the culture of aikido and its wider international framework without overwhelming the user.

# Website structure
The website is divided into four pages: index, FAQ, gallery, and the join page.

![Index look on multiple devices.](/assets/image-readme/responsive-index.jpg)

## Navigation 
- The club logo navigates back to the index. 
- The nav bar allows the user to navigate between all pages of the website.
- The nav bar uses the same font as the logo and headings: Yuji Syuku.  This font is also used for the aikido kanji displayed on the index hero image.  This provides a unified look.  At the same time, the choice of a serif font for  logo, nav bar, and headings clearly distinguishes them from the rest of the content (which uses a sans serif font).   
- The font colour used in navigation contrasts with the background.  On the FAQ page, when a small screen would cause the nav bar to float above a different background colour, the font colour is reversed to maintain contrast.
- Additionally, the index's main article links to the Join page under the heading "How Do I Join?" and to the Gallery page under "What kind of events can I expect?"

## Header
- The club logo is clear and simple: text without any icons or images.   
- Excluding the Gallery, each page has a single main image directly below the logo.  Each image is chosen to complement the logo rather than distracting from it.

## Index Main Article and Hero Image
- The index main article is divided with the following headings: "Learn Aikido at Maynooth"; "Why Aikido?"; and "How Do I Join?"  These were chosen as the most important pieces of information to communicate to a new user of the site.
- Under "Learn Aikido at Maynooth" .
- Under "Why Aikido?" .
- Under "How Do I Join?" .

## Training Times Sidebar
- This sidebar contains the days and times for MU Aikido Club training sessions, as well as the location of these sessions.  Further information about how to reach the location is found in the FAQ, but this basic information is placed prominently due to its importance.  It will be relevant both to new users and returning users who may have attended some training sessions previously but forgotten the place and/or time.  
- This sidebar is present both on the Index page and the FAQ page, due to the importance of the information therein.

## News Sidebar
- This sidebar contains updates, such as COVID-19 protocols and upcoming courses.  It is intended primarily for returning users, but may be of interest to new users. 
- This sidebar is present both on the Index page and the FAQ page, due to its importance.

## Footer
- The footer section on each page contains a quote from aikido founder Morihei Ueshiba.  These quotes communicate essential qualities of the spirit of aikido.  They are chosen to encourage prospective members that everyone can learn something from aikido and that perfection is neither expected nor demanded.
- Social media icons in the footer link to Facebook, Twitter, and YouTube.  Specific rather than general placeholder links were chosen because the MU Aikido Club is a real, living organization that is part of a wider infrastructure of organizations.  
- At the MU Aikido Club Facebook page, users can see more photos and find updates on additional practice sessions.  
- At the MU Twitter page, users can see if the sports facilities used by the MU Aikido Club have been closed due to any emergency.  
- At the International Aikido Federation YouTube page, users can see examples of aikido practice.  This page is affiliated with the Aikikai Foundation.  By linking to this page, the site communicates to those aware of multiple aikido organizations that MU Aikido Club practises Aikikai (the original school of aikido), without going into details that might confuse or alienate a new user.  
- The colour scheme of the footer is inverted compared with the rest of the website, to provide a pleasing element of contrast.

## FAQ 
![The FAQ on multiple devices.](/assets/image-readme/responsive-faq.jpg)
- The FAQ answers common questions that users may have about the MU Aikido Club.  It is intended mainly for new users, but may be of some help to returning users.
- The first questions are meant to address urgent concerns of new users, especially worries that may lead users to disengage from the site.  At first, users may be intimidated by the thought of trying a martial art, or wearing specific clothing that may seem strange.  As the answers to these questions hopefully assuage users' concerns, questions turn to more tangible issues, like who qualifies to join the club and how to get to the training venue.
- The accordion style of the FAQ follows the method laid out at [W3 Schools](https://www.w3schools.com/howto/howto_js_accordion.asp).  While the style is adapted to suit the look of the MU Aikido Club site, the JavaScript for the accordion script comes directly from W3 Schools.
- The accordion hides FAQ answers by default.  This functions to conceal the video from the user on loading the page.  By clicking on the video FAQ entry, the user signals an interest in watching a video of aikido.  Consequently, the video autoplays on being revealed by pressing/clicking the video FAQ entry.  To preserve a good user experience and avoid unpleasant surprises, this video is automatically muted.
- The aikido video is provided by Guillaume Erard, shared on [Wikimedia](https://commons.wikimedia.org/w/index.php?title=File%3AUeshiba_Mitsuteru_(Nippon_Budokan%2C_2017).webm) via Creative Commons and converted to mp4 to improve browser compatibility.  This specific video is chosen both as an excellent example of aikido and because it takes place at the headquarters of the worldwide aikido organization of which the MU Aikido Club is a small part. 
- Code for the Google Maps iFrame was initially generated at [Maps.ie](https://www.maps.ie/create-google-map/).  As this generated bugs on the W3 Validator, the styling of the iFrame was then moved to the css file.

## Gallery
![The Gallery on multiple devices.](/assets/image-readme/responsive-gallery.jpg)
- The Gallery page follows a simple masonry style inspired by the gallery of the Code Institute Love Running project.
- Excluding the heading elements used in the logo in the shared header, the gallery does not use headings.  This is an aesthetic choice, to present a clean user experience that favours images over text, allowing the pictures to speak for themselves.  Alt text is provided for all gallery images, to ensure accessibility.  

## Join
![The Join page on multiple devices.](/assets/image-readme/responsive-join.jpg)
- The Join page is inspired by the sign-up page of the Code Institute Love Running project.  CI students write this code themselves rather than being shown it directly.  I have included my version of this code as a framework for the MU Aikido Club Join page, while changing elements of the style and making further additions.
- A tooltip is implemented to show which fields of the form are required.  
- The student number of prospective members is useful information for club records, but not all those wishing to join may have a student number.  As such, the student number field is not required.
- Similarly, not all prospective members may wish to leave questions or comments, so this field is also not required.
- The tooltip styling follows a tutorial at [W3 Schools](https://www.w3schools.com/css/css_tooltip.asp).

# Wireframes
The index page was prototyped in GIMP using the chosen colours, fonts, and hero image.  These visual elements were decided as the first step of the project.  Once they were chosen, determining a layout became easier.  Using multiple layers with transparency, elements were moved around in GIMP and changed with ease.
## Desktop
![Initial mock-up of the desktop site.](/assets/image-readme/wireframe-desktop.jpg)
- The overall look of the desktop concept was largely maintained in the final site.  Later, heading text was given the bold format to make it more readable compared to this initial concept.

## Mobile
![Initial mock-up of the mobile site.](/assets/image-readme/wireframe-mobile.jpg)
- Taking into account the typically vertical orientation of phone screens during web browsing, I moved away from the layout of this initial mobile concept.  Rather than reorienting the kanji box horizontally, I kept it vertical.  Consequently, it made more sense to keep the nav bar horizontal.  In this revised design, the kanji box would not be moving aside for a vertical nav menu on smaller screens.

# Website Surface
## Colours
![Initial mock-up of the mobile site.](/assets/image-readme/aikido-palette.jpg)
- A colour scheme of creams and browns was chosen for the website.  These tones evoke a traditional look of parchment and ink, while maintaining a level of contrast suitable for a fresh, modern website.  White is not used in the styling but appears as a pop of contrast in the hero image of the index.  

## Typography
Two fonts are used throughout the website.  These fonts are unified by their clear legibility, with differences in the serif font that draw attention to headers and other important elements.
- [Yuji Syuku](https://fonts.google.com/specimen/Yuji+Syuku) - logo, navigation, headers, and kanji.  Of the Google fonts that include kanji, this one most closely resembles the brush style seen on Aikido scrolls in dojos around the world.  It is somewhat artistic but still clear to read.  A subtle inked look carries over to the logo, nav bar, and headings, unifying them with the kanji reading "aikido" on the index page.
- [Barlow Semi Condensed](https://fonts.google.com/specimen/Barlow+Semi+Condensed) - an elegant, easy-to-read sans-serif font.

## Icons and images
- The source for the icons used in the footer is [Font Awesome](https://fontawesome.com/).
- The source for the hero image in the index page is [Pexels](https://www.pexels.com/photo/red-and-gray-pagoda-temple-3408354/).  Tomáš Malík's photo of Mt. Fuji was chosen to represent the Japanese origin of aikido.  It further implies that practising a martial art is like climbing a mountain.  Using GIMP, I edited the photo to replace the sky with a solid fill of the main background colour of the website, for a cleaner look.  Editing Pexels photos is permitted by their terms of use.   
- The source for the main FAQ image is [Shutterstock](https://www.shutterstock.com/image-vector/aikido-dojo-asian-style-flat-vector-1196646862).  Natamura's vector image evokes a typical Japanese dojo as well as the main aikido dojo in Dublin on Macken Street.  I edited the image to replace the tatami with the main background colour of the website, as well as somewhat extending the picture to the sides for very wide screens.  I licensed this image via free trial, which allows usage rights to be retained after the trial ends, even if the trial is cancelled immediately.  [Editing licensed content is permitted by Shutterstock.](https://support.shutterstock.com/s/article/Can-I-edit-the-content-I-license?language=en_US)
- The main Join image was also licensed from [Shutterstock](https://www.shutterstock.com/image-photo/white-judogi-folded-tied-belt-1688098678).  The photo of a white suit and belt by maRRitch was chosen to encourage prospective members to put on a suit and join the club (since many members choose to wear the suits, even if they are not required).  The white belt communicates that all club members train together with a "beginners' spirit," including those with the right to wear a black belt.
- The image of the Sports Centre floor map was created from scratch by me in GIMP.

# Testing
## [HTML Validator](https://validator.w3.org/)
No errors were returned when passing through the official W3C validator. 

## [Jigsaw CSS Validator](https://jigsaw.w3.org/css-validator/validator)
No errors were returned when passing through the official Jigsaw validator. 

## [Lighthouse accessibility (Chrome DevTools)](https://developers.google.com/web/tools/lighthouse/)
Running all site pages through Lighthouse in DevTools, checking both mobile and desktop versions, I obtained the following results.
![Index Lighthouse report.](/assets/image-readme/lh-index.jpg)
![FAQ Lighthouse report.](/assets/image-readme/lh-faq.jpg)
![Gallery Lighthouse report.](/assets/image-readme/lh-gallery.jpg)
![Join page Lighthouse report.](/assets/image-readme/lh-join.jpg)

## Manual testing
- I tested that the site works in different browsers: Edge, Chrome, Firefox.  Additionally, I shared the site with users of Safari who reported it as working, some of whom provided screencaps and videos of their experiences.  This feedback was helpful in identifying bugs.
- Via Chrome DevTools, I tested the responsiveness of the site across a range of screen sizes, from phone to tablet to desktop.  Additionally, I shared the site with people using a range of different devices, who reported the site as responsive (in their view).

# Bugs and fixes
## Solved bugs
- Initially, the video in the FAQ page was only provided in webm format.  However, in a video capture from a Safari user, this embedded video seemed broken.  I converted the webm to mp4 and uploaded a copy to the repository, providing an additional video source in a second format to address this compatibility issue.  

# Deployment 
## GitHub pages

The steps to deploy via GitHub pages:

1. Log into Github account.
2. Navigate to the [Repository](https://github.com/Estelindis/aikido).
3. Click the 'Settings' option at the top of the repository.
4. Click the 'Pages' option on the left-hand menu, located near the bottom.
5. Within the 'Source' tab Select the drop-down titled 'None'.
6. Select the branch named 'main' (it is sometimes named 'Master').
7. Click 'Save'.
8. You will be prompted with a URL to your deployed site.
9. The site is now deployed.

Once these steps have been followed, it can take a few minutes for the deployed site to appear at its URL. Once deployment has been completed, refreshing the page will show the full site.

## Forking The GitHub Repository

By forking the GitHub repository, we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository.  Follow these steps:

1. Log into your GitHub account.
2. Navigate to the [Repository](https://github.com/Estelindis/aikido) that you want to fork.
3. In the upper right of the repository, click the 'Fork' button.
4. A copy of the repository will now be available within your repositories.

This copy of the code can be edited without affecting the original code.

## Cloning the Project.

To make a local clone of the project follow these steps:

1. Log into your GitHub account.
2. Navigate to the [Repository](https://github.com/Estelindis/aikido).
3. In the upper section of the repository click the dropdown named 'Code'.
4. Copy the SHH address.
5. Open GitBash
6. Navigate to the correct directory.
7. Create a new directory named 'aikido'.
8. CD into 'aikido'.
9. Enter 'git clone SSH_ADDRESS'
10. GitBash will clone the repository into this directory.
11. enter 'code .' and this will open VS CODE and happy coding.

# Used technologies and credits
## Languages
- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- [CSS3](https://en.wikipedia.org/wiki/CSS)
- [JavaScript](https://en.wikipedia.org/wiki/JavaScript)

## Content
- Code inspiration for the header, footer, gallery layout, join form, and index kanji box came from the CI Love Running project.
- The flexbox layout of the Index and FAQ pages followed a tutorial from [CSS Coder on YouTube](https://www.youtube.com/watch?v=S0a7PEOi0do).

## Media 
- Background images were taken from [Pexels](https://www.pexels.com/) and [Shutterstock](https://www.shutterstock.com/).
- Gallery images were provided by the MU Aikido Club, and can also be seen on the club Facebook page.
- [Bulk Resize Images](https://bulkresizephotos.com/en) was used to resize all gallery photos to a width of 1000 pixels, as several were originally much wider than this, leading to an initially lower Lighthouse report score.  
- Images compression was done via [Tiny PNG](https://tinypng.com/).
- Image editing, including site prototyping, was performed using GIMP 2.10.24.
- The icons used in the footer come from [FontAwesome](https://fontawesome.com/).
- Fonts used throughout the website were imported from [Google Fonts](https://fonts.google.com/).
- Colours were chosen and checked for contrast on [Contast Grid](https://contrast-grid.eightshapes.com/).
- A palette for easy viewing in this readme was generated at [Coolors](https://coolors.co/ffffff-ecd8d1-c7aea7-3f3130-2b1212).

## Other technologies
- [GitHub](https://github.com/) provided a repository for the website.

## Credits
- [Code Intitute Slack](https://slack.com/) Fellow members of the CI on Slack provided an invaluable database of information and community of support.  I am particularly grateful to the msletb-nov-2021 cohort, our facilitator Kasia, and my mentor Darío.