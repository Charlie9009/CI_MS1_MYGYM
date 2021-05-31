
# MyGym

<img src="docs/mockups/mockup.jpg">
<hr>

## Welcome to my site [MyGym](https://charlie9009.github.io/CI_MS1_MYGYM/)!
<br>

<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-refresh-toc -->
# Table of Content

1. [Project goals](#project-goals)

2. [User experience](#user-experience)
    1. [Target audience](#target-audience)
    2. [User stories](#user-stories)
    3. [Design](#design)
    4. [Wireframes](#wireframes)
3. [Features](#features)
4. [Technologies used](#technologies-used)
    1. [Languages](#languages)
    2. [Libraries and programs](#libraries-and-programs)
5. [Testing](#testing)
    1. [HTML](#html)
    2. [CSS](#css)
    3. [Accessibility](#accessibility)
    4. [Performance](#Performance)
    5. [Further testing](#further-testing)
    6. [Testing user stories](#testing-user-stories)
6. [Bugs](#bugs)
7. [Deployment](#deployment)
8. [Credit](#credit)
    1. [Media credit](#media-credit)
    2. [Acknowledgement](#acknowledgement)

## Project goals
* MyGym is a site that wants to increase peoples wellbeing and motivate others by offering personal trainers and online videos. Due to Covid, MyGym wants to help people who now struggle with working out. Either by not working out at all, or alone in the wrong way not getting the help needed. By using MyGym they will be able to work out from home in a safe and effective way. <br>
What makes MyGym special is that we do not allow more than 10 people per personal trainer. This makes it possible for the trainer to tailor the best workout for every customer.

## User experience

### Target audience

The site is targeted towards everyone that wants to increase their health and/or wants help to get started with their training. The site is also for people who wants to explore new ways of working out by not being able to go to the gym. MyGym offers a wide variation of group training which can be booked from the site. 

### User stories

#### First time user

1. As a first time user I want to find out what the membership costs.

2. As a first time user I want to be able to find the location of the gym.

3. As a first time user I want to be able to find the schedule to see what kinds of group workouts are offered and when.

4. As a first time user I want to know where I can find workout videos online.

5. As a first time user I need to come in contact with a personal trainer.

6. As a first time user I want to find MyGyms social media accounts so I can see how often they update their content.

#### Regular user

7. As a regular user I want to be able to book group workouts.

8. As a regular user I want to have easy access to workout videos when I am ready to workout.

9. As a regular user I want to find the contact info to be able to speak to a personal trainer.

10. As a regular user I want to be able to ask MyGym questions.

11. As a regular user I want to find out more about Athlean X.

12. As a regular user and want to have easy access to MyGyms social media so I can see when they release a new video.

#### Site owner goals

13. As a site owner I want the customer to trust the brand.

14. As a site owner I want to offer the customer a good service.

15. As a site owner I want the customer to feel happy using my service.

16. As a site owner I want the customer to be able to easily book workout sessions.

17. As a site owner I want the customer to tell their friends and family how much they enjoy my MyGym.

18. As a site owner I want the customer to feel it is worth signing up for the service.

### Design

* Most of my design choices came early on in the developement, I tested quite a bit in Balsamiq and got a core design with four pages. Two of my design choices in the beginning was a big hero image with a lot of information and a login page, so my Mentor suggested to make a carousel for the hero image and a modal for the login which I thought sounded challenging but a very good idea.<br>
Some of my choices came in the end of my project when I started experimenting because I did not like some things and that led to me changing more.
One of those things was the Logo, Navigation bar and login button. I had a more split version for a long period where the elements were far away from eachother and did not really go together. So I started experimenting and got a better result.<br>
I struggled for a time with the contrast of the colors as well, but after some trial and error I managed to put my vision together.

#### Colors

* I did not want a white background so I tested a couple of colors and landed on a greyish blue. I chose that because it felt like it did not take to much attention but still gave the background a little personality.

* I gave the logo and the navigation bar a black color, they were big and visual already. Then I also gave the reading material a black color to make it easy to read.

* I gave the login button both in the top right corner and in the carousel a different styling to make it easy to spot. The top right corner has a black container and the text is white. The login button in the Carousel has a white container and black text.

* In the Carousel I gave the text for the different images different colors to contrast the colors in the images.

* The text I wanted to pop out a bit more I gave the color white.

* To help the user to navigate easier I gave hover functions to the Logo, Navigation bar, login button, all the anchor elements and the submit and reset button for the forms.

* The colors I gave for the different workouts in the Schedule was picked to make them pop out of the other content. A slightly darker tone was picked so it would be a contrast.

#### Fonts

* I early on picked the font **Quicksand** and I stuck with that font throughout the project because I liked it. For the backup I picked **Sans-serif**.

### Wireframes

* Below you can see the links to the respective wireframes

    * Full size, Desktop [Wireframe](https://github.com/Charlie9009/CI_MS1_MYGYM/blob/master/docs/wireframes/mygym_fullsize_desktop.pdf)
    * Tablet [Wireframe](https://github.com/Charlie9009/CI_MS1_MYGYM/blob/master/docs/wireframes/mygym_tablet.pdf)
    * Mobile [Wireframe](https://github.com/Charlie9009/CI_MS1_MYGYM/blob/master/docs/wireframes/mygym_mobile.pdf)

## Features

* **Navigation bar and Footer section**

    * The navigation bar and the footer are featured on all four pages and they are responsive. The navigation bar show links to the Logo, Home, Schedule, Videos, Contact and a Login button. When on smaller screen sizes the login button will dissapear to allow for a clean and user friendly site. The login button is a pop up modal, so when you click it there will be a pop up window in the middle of the screen.
    * The footer shows Contact info, Social media icons, an Athlean X link and MyGyms location. When on smaller screen sizes the footer will only show a link to the contact page and social media icons to make the footer easily navigated.
    <img src="docs/features/f_nav_bar.jpg">
    <img src="docs/features/f_login_modal.jpg">
    <img src="docs/features/f_footer.jpg">
### User stories covered by feature:
2. As a first time user I want to be able to find the location of the gym.
3. As a first time user I want to be able to find the schedule to see what kinds of group workouts are offered and when.
4. As a first time user I want to know where I can find workout videos online.
5. As a first time user I need to come in contact with a personal trainer.
6. As a first time user I want to find MyGyms social media accounts so I can see how often they update their content.
9. As a regular user I want to find the contact info to be able to speak to a personal trainer.
10. As a regular user I want to be able to ask MyGym questions.
11. As a regular user I want to find out more about Athlean X.
12. As a regular user and want to have easy access to MyGyms social media so I can see when they release a new video.
<hr>

### Home

* **Hero Section**

    * When you land on the site the first thing the user will see is the big carousel with three images rotating.
    * On the images there are headers with information depending on what the user might be looking for. There is a login button on every image which is fully responsive. On the first image there is info about the membership cost, on the second image there is info to get in touch with a personal trainer and a link and on the third image there is info about Athlean X and a link to that page. When on a small screen the headers disappear to keep the site clean.
    * There is also a header above the carousel to welcome the user.
    <img src="docs/features/f_top_heading_index.jpg">
    <img src="docs/features/f_carousel_1image.jpg">

### User stories covered by feature:
1. As a first time user I want to find out what the membership costs. 
    <hr>
    <img src="docs/features/f_carousel_2image.jpg">
### User stories covered by feature:
5. As a first time user I need to come in contact with a personal trainer. 
9. As a regular user I want to find the contact info to be able to speak to a personal trainer.
    <hr>
    <img src="docs/features/f_carousel_3image.jpg">
### User stories covered by feature:
11. As a regular user I want to find out more about Athlean X.
<hr>

* **Group Training section**

    * The group training section will give examples of what kind of group trainings are offered and tell the user MyGyms personal trainers are well educated.
    * This section has an image to encourage the user to work out together with a group.
    <img src="docs/features/f_group_training.jpg">

* **Online Training section**

    * The online training section will encourage the user to check out Athlean X and go to MyGyms video page if they want to workout online. To keep it user friendly links are provided to both pages in the text.
    * This section also has an image from Athlean X to give the user a face to Athlean X.
    <img src="docs/features/f_online_training.jpg">
### User stories covered by feature:
4. As a first time user I want to know where I can find workout videos online.
8. As a regular user I want to have easy access to workout videos when I am ready to workout.
11. As a regular user I want to find out more about Athlean X.
<hr>

### Schedule

* **Schedule section**

    * Beneath the navigation bar there is a heading to welcome the user to the page and to reasure them they are on the schedule page.
    * There is a form where the user can book their next training session.
    * Beneath the form there is a big schedule where you can see the weeks training sessions, there is information about what workout, which day and time, as well as the personal trainer leading the session.
    <img src="docs/features/f_schedule.jpg">
### User stories covered by feature:
3. As a first time user I want to be able to find the schedule to see what kinds of group workouts are offered and when.
7. As a regular user I want to be able to book group workouts.
<hr>

### Videos

* **Video section**

    * At the top of the page there is a heading encouraging the user for todays workout.
    * Beneath the heading there are a variate of workout videos with different muscel groups depending on what the user want to work on today.
    <img src="docs/features/f_videos.jpg">
### User stories covered by feature:
4. As a first time user I want to know where I can find workout videos online.
8. As a regular user I want to have easy access to workout videos when I am ready to workout.
11. As a regular user I want to find out more about Athlean X.
<hr>

### Contact

* **Contact section**

    * At the top of the page there is a heading to reasure the user they are on the contact page.
    * Beneath the header to the left there is a container with contact information and a price tag for the membership in MyGym.
    * To the right of contact information there is a container with a question form if a user has any questions.
        * When on smaller devices these two containers stack on top of eachother.
    <img src="docs/features/f_contact.jpg">
### User stories covered by feature:
1. As a first time user I want to find out what the membership costs. 
5. As a first time user I need to come in contact with a personal trainer. 
9. As a regular user I want to find the contact info to be able to speak to a personal trainer.
10. As a regular user I want to be able to ask MyGym questions.
<hr>

* **Location**

    * At the bottom of the page there is a map of the Gyms location and above it a header containing the address.
    <img src="docs/features/f_location.jpg">
### User stories covered by feature:
2. As a first time user I want to be able to find the location of the gym.
<hr>

### Features left to implement

* **Personal trainers**

    * A section with information about all of the personal trainers.

* **Group training**

    * A section with information about every single group workout offered at the gym and a layout of how every session could look like.

* **Login function**

    * To be able to log in to the page to ghet access to other videos and content.

## Technologies used

### Languages

* HTML5

* CSS3

## Libraries and programs

* To get the "Modal Log in pop up window" to work, Bootstrap 4.1.3, jQuery and Popper JS was used.

* Font Awesome icons where used for social media in the footer.

* The Gitpod terminal was used to commit and push to Github.

* Github is used to store the code.

* Balsamiq was used to create the projects wireframes.

* WC3 Validator, Jigsaw W3 Validator, Wave Validator, Lighthouse and ami.responsivedesign were all used to test the website.

## Testing

### Validator testing

#### HTML

* No errors were found on index.html when passing through WC3 Validator, [index.html](https://github.com/Charlie9009/CI_MS1_MYGYM/blob/master/docs/validation/html_index_validator.JPG)

* No errors were found on schedule.html when passing through WC3 Validator, [schedule.html](https://github.com/Charlie9009/CI_MS1_MYGYM/blob/master/docs/validation/html_schedule_validator.JPG)

* No errors were found on videos.html when passing through WC3 Validator, [videos.html](https://github.com/Charlie9009/CI_MS1_MYGYM/blob/master/docs/validation/html_videos_validator.JPG)

* No errors were found on contact.html when passing through WC3 Validator, [contact.html](https://github.com/Charlie9009/CI_MS1_MYGYM/blob/master/docs/validation/html_contact_validator.JPG)

#### CSS

* No errors were found on the CSS file when passing through Jigsaw W3 Validator, [CSS](https://github.com/Charlie9009/CI_MS1_MYGYM/blob/master/docs/validation/css_validator.JPG)

#### Accessibility

* No errors were found on the index.html when passing through Wave Web Accessibility Validator, [index.html](https://github.com/Charlie9009/CI_MS1_MYGYM/blob/master/docs/validation/wave_index_validator.JPG)

* No errors were found on the schedule.html when passing through Wave Web Accessibility Validator, [schedule.html](https://github.com/Charlie9009/CI_MS1_MYGYM/blob/master/docs/validation/wave_schedule_validator.JPG)

* No errors were found on the videos.html when passing through Wave Web Accessibility Validator, [videos.html](https://github.com/Charlie9009/CI_MS1_MYGYM/blob/master/docs/validation/wave_videos_validator.JPG)

* No errors were found on the contact.html when passing through Wave Web Accessibility Validator, [contact.html](https://github.com/Charlie9009/CI_MS1_MYGYM/blob/master/docs/validation/wave_contact_validator.JPG)

#### Performance 

* Lighthouse was used to test the performance and the speed of the site.

## Further testing

* The website has been inspected thru the device toolbar in chrome.

* I have tested the website thru phones like One Plus 8T and Iphone XR.

* Friends and family has been asked to review the site.

## Testing user stories

1. As a first time user I want to find out what the membership costs.

|                     Feature                           |              Action                  |                       Expected result                      |   Actual result   |
|                  :----------:                         |              :------------:          |                     :-----------------:                    | :---------------: |
| Find membership price on first image of the carousel  | Scroll down                          |   I will find the price on the first image in the carousel | Works as expected |
| Find membership price on contact page                 | Click contact in the navigation bar  |   I will find the price on contact page                    | Works as expected |
[Screenshot for user story](https://github.com/Charlie9009/CI_MS1_MYGYM/blob/master/docs/features/user_story_1.jpg)
<hr>

2. As a first time user I want to be able to find the location of the gym.

|                     Feature                           |              Action                                 |                       Expected result                         |   Actual result   |
|                  :----------:                         |              :------------:                         |                     :-----------------:                       | :---------------: |
| Find address in the footer                            |                None                                 | I will find the address in the right hand side of the footer  | Works as expected |
| Find address and map on the contact page              | Click contact in the navigation bar and scroll down |   I will find the location at the bottom of the page          | Works as expected |
[Screenshot for user story](https://github.com/Charlie9009/CI_MS1_MYGYM/blob/master/docs/features/user_story_2.jpg)
<hr>

3. As a first time user I want to be able to find the schedule to see what kinds of group workouts are offered and when.

|                     Feature                      |              Action                                   |                       Expected result                         |   Actual result   |
|                  :----------:                    |              :------------:                           |                     :-----------------:                       | :---------------: |
| Find schedule in the schedule page               | Click schedule in the navigation bar and scroll down  |   I will find the schedule as I scroll down                   | Works as expected |
[Screenshot for user story](https://github.com/Charlie9009/CI_MS1_MYGYM/blob/master/docs/features/user_story_3.jpg)
<hr>

4. As a first time user I want to know where I can find workout videos online.

|                     Feature                      |              Action                         |                       Expected result                                 |   Actual result   |
|                  :----------:                    |              :------------:                 |                     :-----------------:                               | :---------------: |
| Find videos in the video page                    | Click videos in the navigation bar          |   I will find the videos when I land on the video page                | Works as expected |
| Find link to videos in online training section   | Scroll down                                 |   I will find a video link in the text section *online training*      | Works as expected |
[Screenshot for user story](https://github.com/Charlie9009/CI_MS1_MYGYM/blob/master/docs/features/user_story_4_8.jpg)
<hr>

5. As a first time user I need to come in contact with a personal trainer.

|                     Feature                                               |          Action                |                       Expected result                            |   Actual result   |
|                  :----------:                                             |          :------------:        |                   :-----------------:                            | :---------------: |
| Find personal trainer info with contact link on second image of carousel  |  Scroll down and click contact | I will find the number for customer service on contact page      | Works as expected |
| Find contact info and link in footer                                      |  None                          | I will find customer service in the left hand side of the footer | Works as expected |
| Find contact link in navigation bar                                       | Click contact in the navigation bar |I will find the number for customer service on contact page | Works as expected |
[Screenshot for user story](https://github.com/Charlie9009/CI_MS1_MYGYM/blob/master/docs/features/user_story_5_9.jpg)
<hr>

6. As a first time user I want to find MyGyms social media accounts so I can see how often they update their content.

|                     Feature                      |              Action                                   |                       Expected result                            |   Actual result   |
|                  :----------:                    |              :------------:                           |                     :-----------------:                          | :---------------: |
| Find social media in the footer                  |                None                                   |   I will find social media links on the left side of the footer  | Works as expected |
[Screenshot for user story](https://github.com/Charlie9009/CI_MS1_MYGYM/blob/master/docs/features/user_story_6_12.jpg)
<hr>

7. As a regular user I want to be able to book group workouts.

|                     Feature                      |              Action                                   |                       Expected result                         |   Actual result   |
|                  :----------:                    |              :------------:                           |                     :-----------------:                       | :---------------: |
| Find booking form in the schedule page           | Click schedule in the navigation bar                  |   I will find the form above the schedule                     | Works as expected |
[Screenshot for user story](https://github.com/Charlie9009/CI_MS1_MYGYM/blob/master/docs/features/user_story_7.jpg)
<hr>

8. As a regular user I want to have easy access to workout videos when I am ready to workout.

|                     Feature                      |              Action                                 |                       Expected result                                |   Actual result   |
|                  :----------:                    |              :------------:                         |                     :-----------------:                              | :---------------: |
| Find videos in the videos page                   | Click videos in the navigation bar                  |   I will find more videos as I scroll down                           | Works as expected |
| Find link to videos in online training section   | Scroll down                                         |   I will find a video link in the text section *online training*     | Works as expected |
[Screenshot for user story](https://github.com/Charlie9009/CI_MS1_MYGYM/blob/master/docs/features/user_story_4_8.jpg)
<hr>

9. As a regular user I want to find the contact info to be able to speak to a personal trainer.

|                     Feature                                               |          Action                |                       Expected result                            |   Actual result   |
|                  :----------:                                             |          :------------:        |                   :-----------------:                            | :---------------: |
| Find personal trainer info with contact link on second image of carousel  |  Scroll down and click contact | I will find the number for customer service on contact page      | Works as expected |
| Find contact info and link in footer                                      |  None                          | I will find customer service in the left hand side of the footer | Works as expected |
| Find contact link in navigation bar                                       | Click contact in the navigation bar |I will find the number for customer service on contact page | Works as expected |
[Screenshot for user story](https://github.com/Charlie9009/CI_MS1_MYGYM/blob/master/docs/features/user_story_5_9.jpg)
<hr>

10. As a regular user I want to be able to ask MyGym questions.

|                     Feature                                 |          Action                     |                       Expected result                               |   Actual result   |
|                  :----------:                               |          :------------:             |                   :-----------------:                               | :---------------: |
| Find contact link on second image of carousel               |  Scroll down and click contact      | I will find a question form on the contact page                     | Works as expected |
| Find contact info and link in footer                        |  None                               | I will find customer service in the left hand side of the footer    | Works as expected |
| Find contact link in navigation bar                         | Click contact in the navigation bar | I will find a question form on the contact page                     | Works as expected |
[Screenshot for user story](https://github.com/Charlie9009/CI_MS1_MYGYM/blob/master/docs/features/user_story_10.jpg)
<hr>

11. As a regular user I want to find out more about Athlean X.

|                     Feature                                   | Action      |                       Expected result                                                                 |   Actual result   |
|                  :----------:                                 | :---------: |                     :-----------------:                                                               | :---------------: |
| Find info and link for *Athlean X* on third image of carousel | Scroll down | as I scroll down I will find the image and text and if I click the link I arrive at *Athlean X* site  | Works as expected |
| Find link to *Athlean X* in online training section           | Scroll down | I will find an *Athlean X* link in the text section *online training*                                 | Works as expected |
| Find *Athlean X* link in the footer                           | None        | I will find an *Athlean X* link on the right side in the footer                                       | Works as expected |
[Screenshot for user story](https://github.com/Charlie9009/CI_MS1_MYGYM/blob/master/docs/features/user_story_11.jpg)
<hr>

12. As a regular user and want to have easy access to MyGyms social media so I can see when they release a new video.

|                     Feature                      |              Action                                   |                       Expected result                            |   Actual result   |
|                  :----------:                    |              :------------:                           |                     :-----------------:                          | :---------------: |
| Find social media in the footer                  |                None                                   |   I will find social media links on the left side of the footer  | Works as expected |
[Screenshot for user story](https://github.com/Charlie9009/CI_MS1_MYGYM/blob/master/docs/features/user_story_6_12.jpg)
<hr>

## Bugs

* For a while I had problems with the bootstrap and Javascript overriding my own CSS rules. I fixed it by placing my CSS stylesheet beneath the other links to have more priority.

* The code for the carousel had an extra incomplete div tag which I removed.

* I used Iframes for the videos in this project and I had paragraphs within those Iframes "*Sorry, your browser does not support Iframes*". But text within the Iframes did not go thru the validator so I removed them.

* The navigation bar did not push the other content down when opening. I fixed it by setting the logo and the navigation bar height to % instead of pixels.

* I had issues with aria-labelledby for the login modal when running the validation. I fixed it by changing it to loginModal.

* The navigation bar did not center. I fixed it by using justify content and margins.

* Fixed better performance score by replacing jquery and bootstap for newer versions

* The online-training section and group-section pushed eachother down. I fixed it by changing the font size and margins in both full size and responsive rules.

* The contact form on the contact page had a bug where the textarea did not size properly in internet explorer. I fixed it by making the container for the question form bigger.

* In the video page Internet explorer cut the two bottom videos, It did not apply margins because of flexbox. I fixed it by adding a css rule *display flexbox* for html and *width 100%* for the body.

* 404 page did not work so I created a 404.md file. Image did not work on 404 page either and it wa fixed with the correct filepath.

### Known bugs

* Cant sign in to the page. This will be implemented in the future.

* In Internet explorer, on the schedule page there are borders on some of the workouts.

## Deployment

* *The site was deployed to github pages.*

    1. Log in to Github.
    2. In your repository find the settings button and click it.
    3. Scroll down to GitHub Pages, beneath it says "Pages settings now has its own dedicated tab! Check it out here!" Click on "Check it out here".
    4. Find source.
    5. From the drop-down menu select master from branch, click save, let it automatically update.
    6. You can now find a live version of the published site under Github pages https://charlie9009.github.io/CI_MS1_MYGYM/.

### Forking a repository

    1. Log in to Github.
    2. Find the repository.
    3. In the top right corner click the fork button.
    4. Now you will have a copy of the repository in your account.

### Cloning a repository

    1. Log in to Github.
    2. Find the repository.
    3. Above the file window locate the green code button and click it.
    4. To clone the repository using https copy the link.
    5. Open Git bash.
    6. Change the current directory to where you want the repository cloned.
    7. In your terminal type now type “Git clone” followed by the repository you copied.
    8. Press Enter.
    9. Done.

## Credit

* Code from Social Media Column Footer, with Font Awesome icons was copied and restyled from Code Institutes "Love Running" project. (https://charlie9009.github.io/love-running/)

* Code for the Modal Login button and the pop up window was used from [codehim](https://www.codehim.com/bootstrap/bootstrap-4-modal-popup-login-form/). Styling was added to a degree for the login button only.

* Code for the Carousel was used from [getbootstrap](https://getbootstrap.com/docs/4.0/components/carousel/). The Carousel used was the one with indicators and then added captions. It was restyled to a degree in CSS.

* Code for the Schedule was used from [bootdey](https://www.bootdey.com/snippets/view/time-table#html). It was restyled in CSS.

* Code for the hamburger navigation bar was used from [mdbootstrap](https://mdbootstrap.com/docs/b4/jquery/navigation/hamburger-menu/)

* Favicon icon was taken from [Favicon](https://favicon.io/emoji-favicons/flexed-biceps)

* All the code besides the code mentioned above was written by me.

## Media Credit

### Images were googled and added to the project. Image sources were the following.

* https://wyckoffymca.org/fitness/small-group-training/

* https://www.polar.com/blog/what-is-group-fitness-benefits/

* https://freemotionfitness.com/fusion-team-training/

* https://athleanx.com/

* https://4kwallpaper.wiki/fitness-desktop-wallpapers.html

### Videos were used from Athlean X

## Acknowledgement

* My Mentor Mo has been invaluable, he pushed me to challenge myself and he was able to provide consistent and helpful feedback throughout my project.

* A friend of mine in the business Will, has been able to provide me with help and tips.
