# Live Zen




This website was created for a fictitious Yoga and Meditation school located in Vienna, Autria. Live Zen is a place, built to satisfy the needs and requests of everyone dealing with a busy schedule, looking for a moment on their days to work on their bodies and minds.
 
The site contains the home page, a meditation page in which is possible to see a description of meditation, a yoga page in which is possible to see a yoga description, a sign up page where the user can sign up to the school, and the congrats page to which the user is redirected after filling out and sending the form.

The target audience is everyone who wants to practice yoga and meditation.

This website is the first of five projects that needs to be completed in order to receive a diploma in Software Development from The Code Institute.

Requirements for the project is that the website has to be static and responsive using HTML5 and CSS3.

A live version of the project can be found here - https://cosmin2002trusca.github.io/Live-Zen/

# Table of Content

+ [UX](#ux "UX")
  + [User Demographic](#user-demographic "User Demographic")
  + [User Stories](#user-stories "User Stories")
    + [Existing Members](#existing-members "Existing Members")
    + [New Users](#new-users "New Users")
  + [User Goals](#user-goals "User Goals")
  + [Requirements](#requirements "Requirements")
  + [Design](#design "Design")
    + [Colors](#colors "Colors")
    + [Typography](#typography "Typography")
    + [Images](#images "Images")
+ [Features](#features "Features")
  + [Existing Features](#existing-features "Existing Features")
    + [Header With Logo and Navigation Bar Section](#header-with-logo-and-navigation-bar-section "Header With Logo and Navigation Bar Section")
    + [Home Page Hero Image Section](#home-page-hero-image-section "Home Page Hero Image Section")
    + [About Us Section](#about-us-section "About Us Section")
    + [About Yoga and Meditation Section](#about-yoga-and-meditation-section "About Yoga and Meditation Section")
    + [Footer Section](#footer-section "Footer Section")
    + [Classes Hero Image Section](#classes-hero-image-section "Classes Hero Image Section")
    + [About Classes section](#about-classes-section "About Classes Section")
    + [Classes Time Table Section](#classes-time-table-section "Classes Time Table Section")
    + [Contact Hero Image Section](#contact-hero-image-section "Contact Hero Image Section")
    + [Contact Form Section](#contact-form-section "Contact Form Section")
    + [Contact Detail Section](#contact-details-section "Contact Details Section")
    + [Thankyoupage Hero Image Section](#thankyoupage-hero-image-section "Thankyoupage Hero Image Section")
    + [Tankyou Section](#thankyou-section "Thankyou Section")
+ [Technologies used](#technologies-used "Technologies used")
+ [Testing](#testing "Testing")
  + [Validator Testing](#validator-testing "Validator Testing")
  + [Unfixed Bugs](#unfixed-bugs "Unfixed Bugs")
+ [Development and Deployment](#development-and-deployment "Development and Deployment")
+ [Content](#content "Content")
+ [Media](#media "Media")
+ [Credits](#credits "Credits")

## UX

### User Demographic

This website is ment for:

 - Residents in Vienna who want to know more about yoga and meditation.
 - Residents in Vienna who want to practice yoga and meditation.
 - Travelers who are in Vienna and want to practice yoga and meditation.

### User Stories

#### Existing Members

 - As a Member: I want to be able to see whether the Studio has new activities to offer me.
 - As a Member: I want to be able to know more about it by reading the descritions.

#### New Users

 - As a new User: I want to know what the Studio has to offer me.
 - As a new User: I want to feel whether the Studio has the right atmosphere for me.

### User Goals

 - Find information about yoga and meditation
 - Find information about how to get in contact with the Studio
 - Send a request to the Studio via the contact form
 - Book a class or an appointment to make a visit to the Studio

### Requirements

A static responsive website that incorporates the technologies I have learned so far that contains some advanced functionality. The development process needs to be well documented through a version controls system such as GitHub.

Required technologies: HTML, CSS

### Design

Since this is my first HTML/CSS project, the design has been influenced by the ”Love Running” project.

My goal was to create a website that could transmit to the users, the calm atmosphere of the Studio and, at the same time, how serious they take teaching the art of yoga and meditation, all of that, working with a balance between colors, images and functionality.

The Live Zen website is a four page website divided into sections. Menu is fixed on top in order to ensure easy navigation between the pages.


#### Typography

The [Google Font Volkhov and Odor MeanChey] was chosen as the main font with a fallback of Sans-Serif.

#### Images

Images have been chosen in accordance to color and content. The purpose of the website is to give a calm look and express quality. Images have been sized in order to match design.

[Back to top](#Live-Zen)

## Features 

The Magnolia Tree website is a three-page website plus a Thank You Page that consists of the following sections:

 - Header (Logo/Navigation Bar)
 - Home Page Hero Image
 - About Us
 - About Yoga and Meditation
 - Footer
 - Thankyoupage Hero Image
 - Thankyou Section

In order to make navigation easier between the pages, the navigation bar is fixed on top when the user scrolls up an down.

### Existing Features

#### Header Navigation Bar Section

  - Featured on all four pages, the navigation bar includes links to the Home page, Classes page and Contact page and is identical in each page to allow for easy navigation.
  - The Header is at a fixed position on top and follows the user as the user scrolls down the page.

![Header and navigation](/assets/images/screenshot-navbar.png)

#### Footer Section

  - The Footer contains four social media links (Facebook, Instagram, twitter and youtube). 
  - The purpose of the Footer is to provide easy access for the user to the different social media platforms were Magnolia Tree has a presence.

![Footer](/assets/images/screenshot-footer.png)


[Back to top](#Live-Zen)

## Technologies used

- [HTML](https://en.wikipedia.org/wiki/HTML)
- [CSS](https://en.wikipedia.org/wiki/CSS)

## Testing 

Test has been conducted using Google Chrome, Mozilla Firefox and Safari. Testing different devices and screen resolutions has been conducted using Google DevTools.

Listed is the main issues discovered.

1. Home page Hero-Image was not staying on the right place after addding the Hero-Image Text.
 - Solution: Removed it as a background-image from the style.css and moved it to index.html.
2. First colum of the Meditation Group Table shrinked after inserted the data.
 - Solution: Adjusted the data inserted.
3. Hero-Image were not taking 100% of the screen's width.
 - Solution: Resized the images to a larger size.
4. When tested in Lighthouse the website received a low score on performance, 73. The reason for thas was that the images size were too big.
 - Solution: Resized all the images and score increased to 99.
5. Poor performance on smaller screens. About Us and 2022 Events sections did not place them selfs properly.
 - Solution: Solved this by using media queries and now the elements are displayed as they should.
6. Menu not properly aligned with header on small screens and it gets cropped and divided.
 - Solution: Added new values in the existing media queries.
7. Menu still gets cropped on screens with resolutions below 320px. It looks good using Google DevTools but not on a physical device
 - Solution: Solved 20220325 - Removed from Unfixed bugs. Changed View Port Width on fonts in menu.

Apart from these issues there have been several minor issues. The majority of these has been due to miss spelled tags, attributes and other mistakes. 


### Unfixed Bugs

- All the bugs were fixed and moved to the section Testing.

 [Back to top](#Live-Zen)

## Development and Deployment

The development environment used for this project was GitPod. To track the development stage and handle version control regular commits and pushes to GitHub has been conducted. The GitPod environment was created using a template provided by Code Institute.

The live version of the project is deployed at GitHub pages.

The procedure for deployment followed the "Creating your site" steps provided in [GitHub Docs.](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)

1. Log into GitHub.
2. Locate the GitHub Repository that shall be deployed live.
3. At the top of the repository, select Settings from the menu items.
4. Scroll down the Settings page to the ”GitHub Pages" section and click on the ”Check it out here!”
5. At the ”Source” section choose ”main” as Branch and root as folder and click ”Save”
6. The website will deploy and the pages refreshes to provide the live link to the project.

The live link can be found here - https://cosmin2002trusca.github.io/Live-Zen/
## Content 

- All text content on this site has been produced by the author of the project and is fictional. Individuals mentioned do not exist in real life and there is no Live Zen.
- The design of the project is inspired by Code Institutes ”Love Running” project. Code has been borrowed from that project, the Footer. It is commented in index.html and styles.css were the the borrowed code is applied. 
- The icons were taken from [Font Awesome](https://fontawesome.com/)

## Media

- All images were downloaded from google.

## Credits 

### For code inspiration, design inputs, help and advice. Many thanks to:

Martina Terlevic
 - My awesome mentor at Code Institute: Thank you for your help during crisis!

### Great sources

Sites that have provided me with knowledge and information that has been vital to this project:

- https://www.w3schools.com/
- https://stackoverflow.com
- https://www.developerdrive.com/
- https://www.freecodecamp.org/


And all the content in HTML-Essentials, CSS-Essentials and the Walkthrough project ”Love Running” that has provided inspiration and knowledge.

Best regards

[Back to top](#Live-Zen)