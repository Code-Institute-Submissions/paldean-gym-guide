# Paldean Gym Guide

This website provides a guide for players of Pokémon Violet and Pokémon Scarlet on how to successfully defeat the eight gym leaders. It will be of benefit and value to players that are new to the Pokémon universe that are not fully versed in the type matchups as the weaknessess and resistances of each gym leader Pokémon are discussed on the site. In addition to this recommended Pokémon to use for each gym are included in the tips section.

## User experience

### User Stories

- #### First Time Visitor Goals

1. I want to gain insight into defeating the gym leaders of the Pokémon generation 9 games Violet and Scarlet.
2. I want to ensure the author of the site is a trusted source and is knowledgeable about the Pokémon universe.
3. I want to be able to navigate the site with ease.

- #### Returning Visitor Goals

1. I want to read about the Pokémon listed in the tips section on which the author recommends for each gym leader.
2. I want to visit the Gallery page and see the images taken by the author throughout their journey in the Paldean landscape.
3. I want to check any social media links included to see other sites and pages the author has.

- #### Frequent User Goals

1. I want to check in to see if any additional content has been added for guides on how to defeat the Titan Pokémon and the Team Star bases.
2. I want to contact the author with questions and feedback on their recommendations using the Contact Us page.
3. I want to check the social media links to see are there any updated blogs posts regarding timelines for planned future implemented features for the site.

- #### Owner goals

1. To develop an online presence.
2. To demonstrate extensive knowledge of the Pokémon universe.
3. To contribute positively to the vast and passionate online Pokémon community.

### Design

#### Color Scheme

![Chosen palette](assets/images/palette%20paldea.png)

The main colors chosen are Tuscany, Russian Green and Deep Taupe.

#### Typography

I used fontjoy.com to choose a pairing of fonts and googlefonts for the import link. The fonts chosen are Arima Madurai for the body and Fanwood Text for the headings. I used sans- serif as the backup text font for accessibiliy.

#### Imagery

All images included in the website have been taken by the author from the Nintendo Switch Pokémon Violet game. The hero image chosen is that of a landscape in the game a player encounters early on with the university in the center of the image and the lush greens and browns of the beautiful nature of Paldea at the forefront. I chose this image as the hero image as I believe it is a very aesthetically pleasing for the user and evokes a positive emotive response from the user.

### Wireframes

- Desktop wireframe -[View](https://)
- Mobile wireframe - [View](https://)
- Tablet wireframe - [View](https://)

## Existing features

- Navigation bar on each of the pages to allow the user to navigate with ease. This avoids the use of any back buttons and allows for a more user friendly site.
- The hero image is aesthetically pleasing with the main aim of the site overlayed on the image to grab the users attention immediately.
- The Home page section guide on the gym leaders and the additional Tips section clickable from all pages with information for the user on how to successfully defeat all gyms leaders. Both of these sections encourage the user to use a variety of Pokémon and strategies to gain success in the challenge.
- The Footer section contains social media links which are clickable and allow access to sites that provide additional information for the user about the Pokémon universe and information about the author to aim for the owner to create a possible online following.
- Video footage of battling a gym leader included in the Tips section which provides excitement and enthusiasm for users and players.
- A gallery for users to experiences some of the adventures the author had while playing the game. This provides value to the user as they can compare and contrast their own experiences while adventuring through Paldea or spark interest in those hoping to play.
- A Contact Us page for players to contact the author with specific questions about the games or with feedback and user experiences of the site.
- A fully responsive site that can be navigated with ease on desktop, laptop and mobile devices.

## Acessibility
- Using the semantic header, section and footer elements to aid screen readers.
- Including aria labels for the social media clickable links.
- Using alt attributes for all image elements used.
- Using sans-serif fonts.

## Languages
HTML5 and CSS3

## Framesworks, Libraries and Programs

1. [Coolors](https://coolors.co)
- Coolors was used to upload the hero image and choose a design palette for the website based on the colors in the chosen hero image.
1. [Fontjoy](https://fontjoy.com)
- Fontjoy was used to choose a font pairing.
2. [Google Fonts](https://googlefonts.com)
- Googlefonts was used to access the import link for the chosen fonts.
3. [Font Awesome](https://fontawesome.com)
- Font Awesome was used to choose icons and use the html code displayed to insert the chosen icons into the footer and contact us sections of the site.
4. [Balsamiq](https://balsamiq.com)
- Balsamiq was used for designing the wireframes for desktop, tablet and smart phone screen sizes.
5. [Git](https://gitpod.io)
- Gitpod was used for adding commits each time a new feature was added to the project and for pushing the commits to Github.
6. [Github](https://github.com)
- Github was used for storing projects after being pushed from gitpod and for deploying the website.

## Future Features

Pokémon Violet and Pokémon Scarlet are very expansive open world games with endless possibilities on the route to take and the areas to explore. I have chosen to focus on one of the possible routes a player can take however there are many more other challenges in store for the player throughout the world of Paldea. 
- In future I would like to include sections with information on battlng the five Titans and the five Team Star leaders. 
- Additionally I would like to include a section on the new Pokémon that have been introduced in generation 9 with users having the facility to vote for their new favourite Pokémon.
- To implement a quiz for users to particpate in with questions regarding the games and the new generation Pokémon.

### Validation & Testing

![W3C HTML Validator](https://validator.w3.org/#validate_by_input)
- No errors were found when the html code for the home page was passed through the official html validator.
![HTML Validator](assets/images/html-checker-home.PNG)

- There were errors on the tips, gallery and contact us section as a width attribute was included for the logo image whereas the image was styled in the css document.
- On the contact us page width and height attributes were also included in the iframe element.
![Errors on contact us page](assets/images/html-checker-contact-us.PNG)

![W3C CSS Validator (Jigsaw)](https://jigsaw.w3.org/css-validator/#validate_by_input)
- No errors were found when the css code was passed through the official validator.
![CSS Validator](assets/images/css-checker.PNG)

### Testing User Stories

### Testing on Browers and Devices

### Bugs

#### Unfixed bugs

- When testing on the html validator the following errors were returned. 
![Error message gallery](assets/images/html-checker-gallery.PNG)
- I wrapped the image elements in a div container however the error message still appeared.
![error message gallery](assets/images/html-checker-gallery-unfixed.PNG)

## Deployment

Github was used to deploy the site.
### Instructions
1. Login to github.com
2. Click the project title under the list of repositories.
3. Click on the settings option.
4. Click on pages on the left hand side under the code and automation heading.
5. Under the heading of build and deployment click the branch drop down menu and select main and click save.
6. Refresh the page and a notification will display that your site is now live and click the visit site option.
![Instructions](assets/images/github-pages.PNG)
### First Deployment
- After the first deployment of the site the following actions needed to be taken:
1. the bulbapedia link is listed as .com but its the .net sited I wanted to link to
1. The height of the ghost gym clip needed to be increased for the 750px - 800 px screen sizes as there is overlap with the footer.
1. On mobile screen sizes the cover text over the hero image needs a margin left property to be added.
![Ghost Gym Overlap](assets/images/ghost-gym-clip-overlap.PNG)
![Hero Image Text Hidden](assets/images/hero-image-text-hidden.PNG)
![Contact Us Gap](assets/images/contact-us-gaps.PNG)

- Forking
- Cloning

## Credits

### Code
- The love running code layout for arranging the navigation layout and social media layout.
- The love running walkthrough project code for designing the club ethos section inspired the 33% division of my gym section on the home page.
- The sample readme file for the love running project and the code institute page was used to help with headings and layout for the readme file.

### Content

- All content was written by the developer.

### Media
- All images were taken by the developer using the screenshot feature on the Nintendo Switch while playing the Game Freak Pokémon Violet game.

### Acknowledgements

- Thank you to my mentor for feedback on planning and completing the project.
- Thank you to the facilitator for including useful video links on how to use Balsamiq and how to write a good README file.
