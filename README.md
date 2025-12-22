
# Piggy before the infection started.

Piggy before the infection started is a TV show which has been running for over four years and has been published over YouTube.

His creator, SuperJakeJoseCat, started a YouTube channel when he was 8 and has been adding content to it since. As the years went by, the content in the channel has become very varied and sometimes it is difficult to find specific videos.

With this in mind, SuperJakeJoseCat would like to have a platform in which fans of Piggy before the infection started can find the content they search for easily.

However, due to the amount of content that SuperJakeJoseCat has produced in these four years and the need for the webpage to be updated very regularly, it was soon clear that the task ahead may be better suited for a framework such as Django.

With this in mind, it was decided that the scope of this project will be on providing a prototype of what will eventually become the website and its scope will be reduced to the first three seasons of the main Piggy before the infection started series.

## Contents.

1. [Business goals](#1-business-goals)

2. [User needs](#2-user-needs)

3. [User stories](#3-user-stories)

4. [Design](#4-design)

5. [Changes to the design](#5-changes-to-the-design)

6. [Typography and colour scheme](#6-typography-and-colour-scheme)

7. [Features](#7-features)

8. [Deployment](#8-deployment)

9. [Testing](#9-testing)

     - [Manual testing](#manual-testing)

     - [Bugs](#bugs)

     - [User stories](#user-stories)

     - [Validation](#validation)

     - [Lighthouse](#lighthouse)

 10. [Languages used](#10-languages-used)

 11. [Frameworks, libraries and programs](#11-frameworks-libraries-and-programs)

 12. [Media](#12-media)

 13. [Acknowledgements](#13-acknowlegments)

## 1. Business goals.

- To increase visibility of the series and gain new viewers.
- To make it easy for fans to navigate to the episode they desire.
- To inform fans of facts they may not know about the series.
- To put out news of upcoming Piggy events.
- To have a platform from which to launch Piggy before the infection started spin offs.
- To showcase animating skills for potential commissions.

## 2. User needs.

- To be able to easily navigate to a specific episode.
- To have a platform where they can follow the latest developments in the series.
- To be able to get their opinions and questions to SuperJakeJoseCat.
- To be able to contact SuperJakeJoseCat about his interest in collaborating in their projects.

## 3. User stories.

- As the animator, 

    - I want a platform which shows all that the series can offer so that my fans are up to date with new developments. 
    - I want to be able to showcase my series so that prospective clients can see my work before they give me a commission. 

- As a new user, 

    - I want clear information about the series so that I know what the series has to offer.

- As a fan, 

    - I want to be able to easily find my favourite episode so that I do not have to waste time searching through lots of other videos.
    - I want to be able to get all the news as quick as possible so I don’t miss any upcoming events/ premieres.
    - I want to be able to send messages to SuperJakeJoseCat so that I can feel my opinions are valued by the creator.

- As a prospective client, 
    - I want to be able to see SuperJakeJoseCat's animations in an easy and organised way so that I know what he could do for my business.
    - I would like a form to contact SuperJakeJoseCat so that I can ask all the information I need.

## 4. Design.

The web page will consist of three pages. They will all be responsive to large, medium and small screen sizes.

All the pages will contain a navigation bar which link to each of the pages and a footer with links to the series social media.

### The home page.

The home page will contain a brief introduction to the series, a section in which users can find out more about the series by going on to its Wikipedia pages or play the associated Roblox game, a section to show the award nominations the series has received, a news section, and a section to go to the gallery or send a message to the creator.

[Wireframe for the home page.](assets/images/readme-images/wireframes/home-wireframe.jpg)

### The gallery.

The gallery will contain the links to all the episodes in the series. It will have three sections, one for each season. Each of the sections will have links to the other two sections, a subsection in which a synopsis of the season will be given, as well as a gallery of auto rotating images. The other subsection will contain a the thumbnail for each episode as well as a link to watch it.

The page will finish with a link to send a message to SuperJakeJoseCat.

[Wireframe for the gallery.](assets/images/readme-images/wireframes/gallery-wireframe.jpg)

### The ‘Talk to the creator’ page.

The talk to the creator page will contain a form to enter name, e-mail address and message area as well as a submit button. It will also have a link to the gallery.

[Wireframe for the Talk to the creator page](/assets/images/readme-images/wireframes/contact-wireframe.jpg)

## 5. Changes to the design.

### Home page.

The original layout for medium screens for the description of the series was similar as that for small screens. It was found that the layout adopted for larger screens was more adequate.

The order of the elements in the series description section were swapped around to make it more appealing in small screens (so that the series carousel did not appear directtly on top of the news pictures.)

The original image for the description was substituted with a carousel of images from the series.

[New wireframe for the home page](/assets/images/readme-images/wireframes/home-wireframe-new.jpg)

### Gallery page.

For larger and medium screens, it was decided that six episodes per line, instead of the original four (for larger screens) and two(for medium screens) was more suitable.

For smaller screens, it was found that a vertical approach would make the page far too long and create user frustration. Instead, a horizontal scroll bar for the episodes in each season was adopted.

The order of the elements inside the season description section were also swapped.

In addition, it was decided that buttons to navigate to each of the seasons in the page would look too chunky, so they were transformed into more discrete links at the top and bottom of each of the page.

The name of the page was also changed to 'Episodes' to make its contents easier to understand.

[New wireframe for the episodes page](/assets/images/readme-images/wireframes/episodes-wireframe-new.jpg)

Links to the other two visible pages were also added to the footer.

### Success page.
A  success page was created to be shown on successful submission of the form.

[Wireframe for the feedback page](/assets/images/readme-images/wireframes/success-wireframe-new.jpg)

## 6. Typography and colour scheme.

The bangers type was chosen for the titles, while risque will be used for the main text. Both fonts were obtained from [Google Fonts](https://fonts.google.com/).

The colour scheme was selected with purple as the main tone to keep in line with SuperJakeJoseCat’s branding, while the complementary forest green and mint green were chosen for the text in order to provide adequate contrast while being gentle in the eye for users with light sensitivity.




![Piggy before the infection started Wikipedia|1902x1125,10%](/assets/images/readme-images/wiki-page.png)
 ![SuperJakeJoseCat logo ](/assets/images/readme-images/SJJS.png)

The colour palette chosen was:

![Colour palette](/assets/images/readme-images/colour-palette.png)


This is what the page will look like (measurements not to scale)

![Colour scheme for a page](/assets/images/readme-images/colour-scheme.png)

## 7. Features.

All pages contain a responsive navigator with links to the home, episodes and contact pages. In small screens, the navigator collapses.

![Navigator for large screens](/assets/images/readme-images/nav-large.jpg)
![Navigator collapsed for small screens](/assets/images/readme-images/nav-small.jpg)
![Navigator extended for small screens](/assets/images/readme-images/nav-small2.jpg)

They also contain a footer with links to social media and to the other two pages.

![Footer for large screens](/assets/images/readme-images/footer-large.jpg)
![Footer for small screens](/assets/images/readme-images/footer-small.jpg)

The home page contains a brief introduction to the series, a section with news about upcoming episodes and a section with links to other interesting websites dedicated to the series, namely the Wikipedia pages and Roblox game. Both the introduction and one of the news items contain a carousel of related images.

![Home page for large screens](/assets/images/readme-images/home-large.jpg)
![Home page for small screens](/assets/images/readme-images/home-small.jpg)

The episodes page contains three sections each containing a brief explanation of the season with a caruosel of images, and a section containing links to each of the episodes in the season. In small screens, the last section converts to a horizontal scroll bar.
At the top and bottom of the page there are links to navigate to each of the sessions.

![Episodes page for large screens](/assets/images/readme-images/episodes-large.jpg)
![Episodes page for small screens](/assets/images/readme-images/episodes-small.jpg)

The contact page contains fields for the user to introduce their name and e-mail address as well as an area where the user can write their message. On successful submission of the form, the user is directed to a feedback page.

![Contact page for large screens](/assets/images/readme-images/contact-large.jpg)
![Contact page for small screens](/assets/images/readme-images/contact-small.jpg)

The feedback page contains a thank you message.

![Feedbak page for large screens](/assets/images/readme-images/success-large.jpg)
![Feedback page for small screens](/assets/images/readme-images/success-small.jpg)

## 8. Deployment.

The project was deployed in [GitHub](https://github.com/).

The process followed was:

- On GitHub, navigate to the project page: https://github.com/louisae452/piggy-before-the-infection-started .
- Go to settings.
- On the general menu on the left, go to pages.
- Select main branch and save.
- To access the deployed site, click on the deployments section on the right side of the main project page.

The site can be accessed from: https://louisae452.github.io/piggy-before-the-infection-started/

### Local deployment.

To fork the project:

- On Github, mavigate to the project page: https://github.com/louisae452/piggy-before-the-infection-started .
- Click on the fork icon.
- Select new branch.
- Give the branch a name and save.

To clone the project:

- On Github, navigate to the project page: https://github.com/louisae452/piggy-before-the-infection-started
- Click on the code button.
- Copy the address shown.
- Open your code editor.
- On the terminal, navigate to the desired directory.
- Type 'git clone' followed by the address you copied.
- Press enter.

## 9. Testing.

### Manual testing.

Tests were performed in all the links in all the pages. Also, form validation was tested in the contact pages. Two tests failed, when the links to both the large and small screen for season 3 episode 6 failed to open in a new window. This was fixed and re-tested.
These are the logs of the manual tests performed:

[Log of tests done to home page.](/assets/images/readme-images/test-home.pdf)

[Log of tests done to episodes page.](/assets/images/readme-images/test-gallery.pdf)

[Log of tests done to contact page.](/assets/images/readme-images/test-contact.pdf)

[Log of tests done to feedback page.](/assets/images/readme-images/test-success.pdf)

### Bugs.

- Early on the development, it was found that the navigator had stopped underlining the active page. Eventually, it was found that the use of !important while setting the colour of the text in the navigator had overriden the text decoration. A new text decoration rule had to be written to overcome this problem. (Credit to my tutor).

- The carousel in the episodes page was showing the first picture twice. It was found that, when adding cards to the carousel, the active card had been used to be copied over a number of times so that several cards were set to active at the same time. Once this was corrected, the carousel worked as expected. (Again, credit to my tutor)

### User stories.

- From the animator's point of view, the site provides  a platform to show the series were both fans and prospective clients can easily browse through their work.

- New users can find the information they need to get to know the series. They can view the different episodes in the episodes page and they can access the series Wikipedia to find more information and play the Roblox game from the home page.

- Fans can easily access their favoutite episodes. They can also make sure they don't miss any upcoming events in the news section in the home page. They also have an easy way to message the creator from the contact page.

- Prospective clients can easily review SuperJakeJoseCat's work and message him if needed.


### Validation.

Validation for the HTML code was done using the [w3 HTML validator](https://validator.w3.org/#validate_by_upload).

No errors were found.

![Validation for index.html](/assets/images/readme-images/automated-tests/w3validator-index.jpg)
![Validation for gallery.html](/assets/images/readme-images/automated-tests/w3validator-gallery.jpg)

![Validation for conatact.html](/assets/images/readme-images/automated-tests/w3validator-contact.jpg)
![Validation for success.html](/assets/images/readme-images/automated-tests/w3validator-success.jpg)

Validation for the CSS code was done with the [w3 CSS validator](https://jigsaw.w3.org/css-validator/validator)

No errors were found.

![Validation for styles.css](/assets/images/readme-images/automated-tests/w3validator-styles.jpg)

### Lighthouse.

Lighthouse was run on all pages on Google Dev Tools. On the initial run, the performance score for the mobile pages was around 40% due to the size of the images. Following its recommendation, the images were reduced in size, which increased the performace on mobile to 53-62% but reduced the score for best practices in desktop as the image quality had been reduced. It was decided that, given the high volume of images on the site, a compromise had to be reached. As a future improvement to the site, responsive images could be added to the site.

Scores for the home page on mobile and desktop.

![lighthouse score for home page in mobile](/assets/images/readme-images/automated-tests/home-mobile.jpg)
![Lighthouse score for home page in desktop](/assets/images/readme-images/automated-tests/home-desktop.jpg)

Scores for the episodes page on mobile and desktop.

![lighthouse score for episodes page in mobile](/assets/images/readme-images/automated-tests/gallery-mobile.jpg)
![lighthouse score for episodes page in desktop](/assets/images/readme-images/automated-tests/gallery-desktop.jpg)

Scores for  the contact page on mobile and desktop.

![Lighthouse score for contact page in mobile](/assets/images/readme-images/automated-tests/contact-mobile.jpg)
![Lighthouse score for contact page in desktop](/assets/images/readme-images/automated-tests/contact-desktop.jpg)

Scores for the feedback page on mobile and desktop.

![Lighthouse score for success page in mobile](/assets/images/readme-images/automated-tests/success-mobile.jpg)
![lighthouse score for success page in desktop](/assets/images/readme-images/automated-tests/success-desktop.jpg)

## 10. Languages used.

HTML, CSS.

## 11. Frameworks, libraries and programs.

[GitHub](https://github.com/).

[Bootstrap v 5.3](https://getbootstrap.com/).

To make favicon: [favicon.io](https://favicon.io/).

To make logo: [Adobe converter](https://www.adobe.com/express/feature/image/convert/svg?mv=search&mv2=paidsearch&sdid=SGDJM6ML&ef_id=Cj0KCQiArt_JBhCTARIsADQZayn4D9tYeU0TeGOOGjxEMTT5AJ9WFg_qnTrQjpdmYaL7geI1eEu6ER4aAnBcEALw_wcB:G:s&s_kwcid=AL!3085!3!761188290457!b!!g!!!22715185416!187202596488&gad_source=1&gad_campaignid=22715185416&gbraid=0AAAAADraYsI-nxMEG6yyI05o5YKLar7nv&gclid=Cj0KCQiArt_JBhCTARIsADQZayn4D9tYeU0TeGOOGjxEMTT5AJ9WFg_qnTrQjpdmYaL7geI1eEu6ER4aAnBcEALw_wcB).

To find the correct purple colour (From wikipedia image): [Image color picker](https://imagecolorpicker.com/).

To choose colours for the colour palette: [Canva](https://www.canva.com/colors/color-wheel/).

To choose fonts: [Google Fonts](https://fonts.google.com/).

To choose icons: [Font Awesome](https://fontawesome.com/).

To manipulate pictures: Microsoft photos.

To convert pictures: [Towebp](https://towebp.io/).

To write the readme file: [Markdown Guide: Basic Syntax.](https://www.markdownguide.org/basic-syntax/#links).

To test the site: Google Dev Tools.

For general information: [w3schools](https://www.w3schools.com/).

Bootstrap horizontal scroll cards: [codeply](https://www.codeply.com/go/PF4APyGj7F).

To get round edges on the images of the carousel: [stack overflow](https://stackoverflow.com/questions/60680676/how-can-i-use-rounded-images-in-carousel-bootstrap).

While woking on the initial stages of planning and design, the following  streaming platforms were visited: [BBC iplayer](https://www.bbc.co.uk/iplayer), [ITVX](https://www.itv.com/), [Channel 5](https://www.channel5.com/), [Netflix](https://www.netflix.com/gb/), [Prime video](https://www.amazon.co.uk/s/?ie=UTF8&keywords=primevideo&index=instant-video&tag=googhydr-21&ref=pd_sl_4qt8mi5j5m_b&adgrpid=122874515649&hvpone=&hvptwo=&hvadid=606073882920&hvpos=&hvnetw=g&hvrand=2693765614447736146&hvqmt=b&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9046767&hvtargid=kwd-301037023401&hydadcr=28129_2308171&mcid=6ef92a59b27b3bc095f71f55f965df25&hvocijid=2693765614447736146--&hvexpln=0&gad_source=1).

## 12. Media.

All the content, images and videos used on the site were created by SuperJakeJoseCat.

## 13. Acknowlegments.

I Would like to thank the following people:

My tutor, Kevin Loughrey for his help and encouragement through the development of the project.

My friend and colleague Veronica Teodorof for being a step ahead of me and sharing the tips she found on her journey.

To my family for their unconditional support. 

Very special thanks to SuperJakeJoseCat whithout whom this project would not have been possible.






















