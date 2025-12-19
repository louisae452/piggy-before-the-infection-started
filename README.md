
# Piggy before the infection started.

Piggy before the infection started is a TV show which has been running for over four years and has been published over YouTube.

His creator, SuperJakeJoseCat, started a YouTube channel when he was 8 and has been adding content to it since. As the years went by, the content in the channel has become very varied and sometimes it is difficult to find specific videos.

With this in mind, SuperJakeJoseCat would like to have a platform in which fans of Piggy before the infection started can find the content they search for easily.

However, due to the amount of content that SuperJakeJoseCat has produced in these four years and the need for the webpage to be updated very regularly, it was soon clear that the task ahead may be better suited for a framework such as Django.

With this in mind, it was decided that the scope of this project will be on providing a prototype of what will eventually become the website and its scope will be reduced to the first three seasons of the main Piggy before the infection started series.

## Business goals.

- To increase visibility of the series and gain new viewers.
- To make it easy for fans to navigate to the episode they desire.
- To inform fans of facts they may not know about the series.
- To put out news of upcoming Piggy events.
- To have a platform from which to launch Piggy before the infection started spin offs.
- To showcase animating skills for potential commissions.

## User needs.

- To be able to easily navigate to a specific episode.
- To have a platform where they can follow the latest developments in the series.
- To be able to get their opinions and questions to SuperJakeJoseCat.
- To be able to contact SuperJakeJoseCat about his interest in collaborating in their projects.

## User stories.

- As the animator, 

    - I want a platform which shows all that the series can offer. 
    - I want to be able to showcase my series so that prospective clients can see my work before they give me a commission. 

- As a new user, 

    - I want clear information about the series.

- As a fan, 

    - I want to be able to easily find my favourite episode.
    - I want to be able to get all the news as quick as possible so I don’t miss any upcoming events/ premieres.
    - I want to be able to send messages to SuperJakeJoseCat.

- As a prospective client, 
    - I want to be able to see SuperJakeJoseCat animations in an easy and organised way.
    - I would like a form to contact SuperJakeJoseCat where I can ask all the information I need.

## Design.

The web page will consist of three pages. They will all be responsive to large, medium and small screen sizes.

All the pages will contain a navigation bar which link to each of the pages and a footer with links to the series social media.

### The home page.

The home page will contain a brief introduction to the series, a section in which users can find out more about the series by going on to its Wikijpedia pages or play the associated Roblox game, a section to show the award nominations the series has received, a news section, and a section to go to the gallery or send a message to the creator.

[Wireframe for the large screen version of the home page.](assets/images/readme-images/home-wire-large.png)

[Wireframe for the medium and small screen versions of the home page.](assets/images/readme-images/home-wire-small.png)


### The gallery.

The gallery will contain the links to all the episodes in the series. It will have three sections, one for each season. Each of the sections will have links to the other two sections, a subsection in which a synopsis of the season will be given, as well as a gallery of auto rotating images. The other subsection will contain a the thumbnail for each episode as well as a link to watch it.

The page will finish with a link to send a message to SuperJakeJoseCat.

[Wireframe for the large screen version of the gallery.](assets/images/readme-images/gallery-wire-large.png)

[Wireframe for the medium and small screen versions of the gallery.](assets/images/readme-images/gallery-wire-small.png)

### The ‘Talk to the creator’ page.

The talk to the creator page will contain a form to enter name, e-mail address and message area as well as a submit button. It will also have a link to the gallery.

[Wireframe for the large screen version of the ‘Talk to the creator’ page.](assets/images/readme-images/form-wire-large.png)

[Wireframe for the small and medium screen versions of the ‘Talk to the creator’ page.](assets/images/readme-images/form-wire-small.png)

## Changes to the design.

### Home page.

The original layout for medium screens for the description of the series was the similar as that for small screens. It was found that the layout adopted for larger screens was more adequate.

The order of the elements in the series description section were swapped around to make it more appealing in small screens (so that the series carousel did not appear directtly on top of the news pictures.)

INSERT NEW WIREFRAME

### Gallery page.

For larger and medium screens, it was decided that six episodes per line, instead of the original four (for larger screens) and two(for medium screens) was more suitable.

For smaller screens, it was found that a vertical approach would make the page far too long and create user frustration. Instead, a horizontal scroll bar for the episodes in each season was adopted.

The order of the elements inside the season description section were also swapped.

In addition, it was decided that buttons to navigate to each of the seasons in the page would look too chunky, so they were transformed into more discreate links at the top and bottom of each of the season sections.

INSERT NEW WIREFRAME

All the pages got the addition of two buttoms at the end of the page to navigate to the other two pages easily.

### Success page.
A  success page was created to be shown on successful submission of the form.

INSERT WIREFRAME.


## Typography and colour scheme.

The bangers type was chosen for the titles, while risque will be used for the main text.

The colour scheme was selected with purple as the main tone to keep in line with SuperJakeJoseCat’s branding, while the complementary forest green and mint green were chosen for the text in order to provide adequate contrast while being gentle in the eye for users with light sensitivity.




![Piggy before the infection started Wikipedia|1902x1125,10%](/assets/images/readme-images/wiki-page.png)
 ![SuperJakeJoseCat logo ](/assets/images/readme-images/SJJS.png)

The colour palette chosen was:

![Colour palette](/assets/images/readme-images/colour-palette.png)


This is what the page will look like (measurements not to scale)

![Colour scheme for a page](/assets/images/readme-images/colour-scheme.png)

## Features.

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

![Episodes page for large screens](/assets/images/readme-images/episodes-large.jpg)
![Episodes page for small screens](/assets/images/readme-images/episodes-small.jpg)

The contact page contains fields for the user to introduce their name and e-mail address as well as an area where the user can write their message. On successful submission of the form, the user is directed to a feedback page.

![Contact page for large screens](/assets/images/readme-images/contact-large.jpg)
![Contact page for small screens](/assets/images/readme-images/contact-small.jpg)

The feedback page contains thank you message.

![Feedbak page for large screens](/assets/images/readme-images/success-large.jpg)
![Feedback page for small screens](/assets/images/readme-images/success-small.jpg)

## Deployment.

The project was deployed in GitHub.

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
- Type 'git clone' and the address you copied.
- Press enter.

## Testing.

### Manual testing.

Tests were performed in all the links in all the pages. Also, Form validation was tested in the contact pages. Two tests failed, when the links to both the large and small screen for season 3 episode 6 failed to open in a new window. This was fixed and re-tested.
These are the logs of the manual tests performed:

[Log of tests done to home page.](/assets/images/readme-images/test-home.pdf)

[Log of tests done to episodes page.](/assets/images/readme-images/test-gallery.pdf)

[Log of tests done to contact page.](/assets/images/readme-images/test-contact.pdf)

[Log of tests done to feedback page.](/assets/images/readme-images/test-success.pdf)



[w3 HTML](https://validator.w3.org/#validate_by_upload)

[w3 CSS validator](https://jigsaw.w3.org/css-validator/validator)


## Credits.
[w3schools](https://www.w3schools.com/)

Readme file: [Markdown Guide: Basic Syntax.](https://www.markdownguide.org/basic-syntax/#links)

To find the correct purple colour (From wikipedia image): [Image color picker](https://imagecolorpicker.com/)

To choose colours for the colour palette: [Canva](https://www.canva.com/colors/color-wheel/)

To choose fonts: [Google fonts](https://fonts.google.com/)

To make logo: [Adobe converter](https://www.adobe.com/express/feature/image/convert/svg?mv=search&mv2=paidsearch&sdid=SGDJM6ML&ef_id=Cj0KCQiArt_JBhCTARIsADQZayn4D9tYeU0TeGOOGjxEMTT5AJ9WFg_qnTrQjpdmYaL7geI1eEu6ER4aAnBcEALw_wcB:G:s&s_kwcid=AL!3085!3!761188290457!b!!g!!!22715185416!187202596488&gad_source=1&gad_campaignid=22715185416&gbraid=0AAAAADraYsI-nxMEG6yyI05o5YKLar7nv&gclid=Cj0KCQiArt_JBhCTARIsADQZayn4D9tYeU0TeGOOGjxEMTT5AJ9WFg_qnTrQjpdmYaL7geI1eEu6ER4aAnBcEALw_wcB)

To make favicon: [favicon.io](https://favicon.io/)
Icons: [Font Awesome](https://fontawesome.com/)

Bootstrap horizontal scroll cards [codeply](https://www.codeply.com/go/PF4APyGj7F)

To get round edges on the images of the carousel: [stack overflow](https://stackoverflow.com/questions/60680676/how-can-i-use-rounded-images-in-carousel-bootstrap)

To manipulate pictures: Microsoft photos.
To convert pictures:[Towebp](https://towebp.io/)






