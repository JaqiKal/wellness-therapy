# Manus Herba - Herbal, Lymphatic drainage and Zone therapy website

[The website shown on a variety of screen sizes](documentation/doc-image/amiresponsive-wellness-therapy.png)
*add an image of the finished site her Use [amiresponsive](https://ui.dev/amiresponsive?url=https://jaqikal.github.io/wellness-therapy/).*

Visit the deployed site: [Manus Herba](https://jaqikal.github.io/wellness-therapy/) 

- - -

## CONTENTS

* [AUTOMATED TESTING](#automated-testing)
  * [W3C Validator](#w3c-validator)
  * [Lighthouse](#lighthouse)
* [MANUAL TESTING](#manual-testing)
  * [Testing User Stories](#testing-user-stories)
  * [Full Testing](#full-testing)

Testing was ongoing throughout the entire build. I utilised Chrome developer tools whilst building to pinpoint and troubleshoot any issues as I went along.

During development I made use of google developer tools to ensure everything was working correctly and to assist with troubleshooting when things were not working as expected.

I have gone through each page using google chrome developer tools & Firefox inspector tool to ensure that each page is responsive on a variety of different screen sizes and devices.

I also used the following websites to test responsiveness:
* [Responsinator](http://www.responsinator.com/?url=https%3A%2F%2Fjaqikal.github.io%2Fwellness-therapy%2F)
* [Am I Responsive](https://ui.dev/amiresponsive?url=https://jaqikal.github.io/wellness-therapy/)

- - -

## AUTOMATED TESTING

### W3C Validator

[W3C](https://validator.w3.org/) was used to validate the HTML on all pages of the website. It was also used to validate the CSS.

* [index.html](testing/w3/w3-index.png) - Passed.
* [game.html](testing/w3/w3-game.png) - No errors, 1 Warning. The warning is for an empty H2 tag. This is where the question is inserted using jQuery.
* [highscores.html](testing/w3/w3-highscores.png) - Passed.
* [404.html](testing/w3/w3-404.png) - Passed.
* [500.html](testing/w3/w3-500.png) - Passed.

* [style.css](testing/w3/w3-css.png) - Passed, no errors found.

- - -

### Lighthouse

I used Lighthouse within the Chrome Developer Tools to test the performance, accessibility, best practices and SEO of the website.

### Desktop Results

All pages of the site are achieving a score of 100 across the 4 categories.

![index.html](testing/lighthouse/lighthouse-desktop-index.webp)

![game.html](testing/lighthouse/lighthouse-desktop-game.webp)

![highscores.html](testing/lighthouse/lighthouse-desktop-highscores.webp)

![404.html](testing/lighthouse/lighthouse-desktop-404.webp)

![500.html](testing/lighthouse/lighthouse-desktop-500.png)

### Mobile Results

Each page is achieving a score of 100 for the last three categories. The performance category is achieving a score of 98 for the first three pages and a score of 99 on the 404 & 500 page.

![index.html](testing/lighthouse/lighthouse-mobile-index.webp)

![game.html](testing/lighthouse/lighthouse-mobile-game.webp)

![highscores.html](testing/lighthouse/lighthouse-mobile-highscores.webp)

![404.html](testing/lighthouse/lighthouse-mobile-404.webp)

![500.html](testing/lighthouse/lighthouse-mobile-500.png)

- - -

## MANUAL TESTING

### Testing User Stories

`First Time Visitors`

| Goals | How are they achieved? |
| :--- | :--- |
| I want to take part in a pub quiz online and improve my general knowledge. I want to be able to play at any time, anywhere. | The Quiz Arms pulls general knowledge quiz questions from a large variety of topics, much like a pub quiz would do. The site is available for use whenever is convenient to the user. |
| I want the site to be responsive to my device. | I have developed the site with responsiveness in mind. |
| I want the site to be easy to navigate. | Buttons are used throughout the site for navigation, much like a mobile app. As the site is like a mobile app - I decided that I didn't want to add a navigation bar or footer, as these would make the site look more like a traditional webpage. The page title also acts as a link to the home page.  |

`Returning Visitors`

|  Goals | How are they achieved? |
| :--- | :--- |
| I want to be able to choose a level of difficulty that I feel is appropriate for me, based on my experience from my first visit to the site. | Users are able to select their own level of difficulty before the game begins. Once they have played they are free to select a different level of difficulty for subsequent games. |

`Frequent Visitors`

| Goals | How are they achieved? |
| :--- | :--- |
| I want to be able to adjust the difficulty level to keep improving my knowledge. | Users are able to select their own level of difficulty before the game begins. Once they have played they are free to select a different level of difficulty for subsequent games. |
| I want to be able to log my high scores to see how I am performing. | Users of the site are able to log their high scores to the high scores page. The top ten results will be displayed. |

- - -

### Full Testing

Full testing was performed on the following devices:

* Laptop:
    * Lenovo Legion T7 - i9 | 32GB | 2TB 
* Screen:
   * Samsung Odyssey G3 / 27" / VA / 1920 x 1080 / 144 Hz / 1ms / 
   * Samsung Odyssey G3 / 27" / VA / 1920 x 1080 / 165 Hz / 1ms / 
* Mobile Devices:
    * Samsung Galaxy S20
    * iPhone 12 pro.


Each device tested the site using the following browsers:

* Google Chrome, version 121.0.6167.86 (Official Build) (64-bit)
* Firefox, version 122.0 (64-bit)

#### Landing Page (LAP)

| TestCase ID | Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| ---| --- | --- | --- | --- |--- |
| LAP-01 | Logo link | Link directs the user back to the home page | Clicked logo | Home page reloads | PASS |
| LAP-02 | Logo hover | Visibly scaling up when hovering over with pointer | Hover over with pointer | Visibly scaling up | PASS |
| LAP-03 | Menu link | Link to insite page (except Home item) - not opening separate tab | Clicked each menu item link, Home item to reload page | Menu item opened insite, except Home item, it reloaded page| PASS |
| LAP-04 | Menu hover | Menu items visibly scaling up when hovering over with pointer | Hover over with pointer | Visibly scaling up | PASS |
| LAP-05 | Book me button link |Link directs the user to the Contact page | Clicked | Contact page opened | PASS |
| LAP-06 | Book me button hover | Visibly scaling up and changing colour when hovering over with pointer | Hover over with pointer | Visibly scaling up and changing colour | PASS |
| LAP-07 | Give a Gift button link | Link directs the user to the Shop sub page | Clicked | Shop page opened | PASS |
| LAP-08 | Give a Gift button hover | Visibly scaling up and changing colour when hovering over with pointer | Hover over with pointer | Visibly scaling up and changing colour | PASS |
| LAP-09 | Herbal Therapy image link | Link directs the user to the Services page | Clicked | Services page opened | PASS |
| LAP-10 | Herbal Therapy image hover | Visibly scaling up when hovering over with pointer | Hover over with pointer | Visibly scaling up | PASS |
| LAP-11 | Lymphatic Drainage Therapy image link | Link directs the user to the Services page  | Clicked | Services page opened | PASS |
| LAP-12 | Lymphatic Drainage Therapy image hover | Visibly scaling up when hovering over with pointer | Hover over with pointer | Visibly scaling up | PASS |
| LAP-13 | Zone Therapy image link|Link directs the user to the Services page | Clicked | Services page opened | PASS |
| LAP-14 | Zone Therapy image hover | Visibly scaling up when hovering over with pointer | Hover over with pointer | Visibly scaling up | PASS |
| LAP-15 | footer fa-brands icon social media link | Upon click take one to social media site in separate tab | Clicked | Site opened in separate tab | PASS |
| LAP-16 | footer fa-brands icon social media hover | Visibly scaling up when hovering over with pointer | Hover over with pointer | Visibly scaling up | PASS |
| LAP-17 | Footer fa-brands icon payment link | Upon click take one to social media site in separate tab | Clicked | Site opened in separate tab | PASS |
| LAP-18 | Footer fa-brands icon payment hover | Visibly scaling up when hovering over with pointer | Hover over with pointer | Visibly scaling up | PASS |
| LAP-19 | Footer links| Upon click take one to insite sub page - not opening separate tab| Clicked | Site opened insite | PASS |
| LAP-20 | Footer links hover | Changeing colour when hovering over with pointer | Hover over with pointer | Visibly changing colout | PASS |

#### Services Page (SEP)

| TestCase ID | Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| ---| --- | --- | --- | --- |--- |
| SEP-01 | Logo link | Link directs the user back to the home page | Clicked logo | Links to landing page | PASS |
| SEP+02 | Logo hover | Visibly scaling up when hovering over with pointer | Hover over with pointer | Visibly scaling up | PASS |
| SEP-03 | Menu link | Link to insite page - not opening separate tab | Clicked each menu item link | Menu item opened insite | PASS |
| SEP-04 | Book me button links under each image | Link directs the user to the Contact page | Clicked | Contact page opened | PASS |
| SEP-05 | Give a gift button links under each image | Link directs the user to the Shop page | Clicked | Shop page opened | PASS following FAIL, detailed below|
| SEP-06 | Footer links behaving as in Landing page | Hovering and clicking on each icon/link | Hovered and Clicked | All opened in separate tab and transported to correct external page | PASS |

#### Pricing Page (PRP)

| TestCase ID| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| ---| --- | --- | --- | --- |--- |
| PRP-01 | Logo link | Link directs the user back to the home page | Clicked logo | Links to landing page | PASS |
| PRP-02 | Logo hover | Visibly scaling up when hovering over with pointer | Hover over with pointer | Visibly scaling up | PASS |
| PRP-03 | Menu link | Link to insite page - not opening separate tab | Clicked each menu item link | Menu item opened insite | PASS |
| PRP-04 | Book a session button link |Link directs the user to the Contact page | Clicked | Contact page opened | PASS |
| PRP-05 | Footer links behaving as in Landing page | Hovering and clicking on each icon/link | Hovered and Clicked | All opened in separate tab and transported to correct external page | PASS |

#### Contact Page (COP)

| TestCase ID| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| ---| --- | --- | --- | --- |--- |
| COP-01 | Logo link | Link directs the user back to the home page | Clicked logo | Links to landing page | PASS |
| COP-02 | Logo hover | Visibly scaling up when hovering over with pointer | Hover over with pointer | Visibly scaling up | PASS |
| COP-03 | Menu link | Link to insite page - not opening separate tab | Clicked each menu item link | Menu item opened insite | PASS |
| COP-04 | Form - text field input check | On Contact page, attempt to "Get in contact" without entering data| Leave field empty| User is prompted to enter a value. Form is not submitted. | PASS |
| COP-05 | Form - drop down menu check | Ensure every option in the dropdown menu is accessible | Selected each option | All options in the dropdown are individually selectable | PASS |
| COP-06 | Form - radio button check | Verify that each radio button in a form can be selected  | Clicked each button | Each button can be selected individually | PASS |
| COP-07 | Form - text message field check | Confirm that the text message field is functional | Typed in the field | Text can be entered and edited in the field | PASS |
| CO0-08 | "Get in Touch" Button Submission | Verify the button leads to a Thank-you page upon correctly completing the form | Completed the form | Redirected to Thank-you page successfully | PASS |
| COP-09 | Give a Gift button hover | Visibly scaling up and changing colour when hovering over with pointer | Hover over with pointer | Visibly scaling up and changing colour | PASS |
| COP-10 | Footer links behaving as in Landing page | Hovering and clicking on each icon/link | Hovered and Clicked | All opened in separate tab and transported to correct external page | PASS |

#### Shop Page (SPP)

| TestCase ID | Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| ---| --- | --- | --- | --- |--- |
| SPP-01 | Logo link | Link directs the user back to the home page | Clicked logo | Links to landing page | PASS |
| SPP-02 | Logo hover | Visibly scaling up when hovering over with pointer | Hover over with pointer | Visibly scaling up | PASS |
| SPP-03 | Menu link | Link to insite page - not opening separate tab | Clicked each menu item link | Menu item opened insite | PASS |
| SPP-04 | Click on Image |Link directs the user to the Thank-you page | Clicked | Thank-you page opened | PASS |
| SPP-05 | Footer links behaving as in Landing page | Hovering and clicking on each icon/link | Hovered and Clicked | All opened in separate tab and transported to correct external page | PASS |

#### Thank-You Page (TYP)

| TestCase ID | Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| ---| --- | --- | --- | --- |--- |
| TYP-01 | Logo link | Link directs the user back to the home page | Clicked logo | Links to landing page | PASS |
| TYP-02 | Logo hover | Visibly scaling up when hovering over with pointer | Hover over with pointer | Visibly scaling up | PASS |
| TYP-03 | Menu link | Link to insite page - not opening separate tab | Clicked each menu item link | Menu item opened insite | PASS |
| TYP-04| Footer links behaving as in Landing page | Hovering and clicking on each icon/link | Hovered and Clicked | All opened in separate tab and transported to correct external page | PASS |

#### 404 Page (404P)

| TestCase ID | Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| ---| --- | --- | --- | --- |--- |
| 404P-01| Logo link | Link directs the user back to the home page | Clicked logo | Links to landing page | PASS |
| 404P-02 | Logo hover | Visibly scaling up when hovering over with pointer | Hover over with pointer | Visibly scaling up | PASS |
| 404P-03 | Menu link | Link to insite page - not opening separate tab | Clicked each menu item link | Menu item opened insite | PASS |
| 404P-04 | Footer links behaving as in Landing page | Hovering and clicking on each icon/link | Hovered and Clicked | All opened in separate tab and transported to correct external page | PASS |

#### Privacy Policy Page (PPP)

| TestCase ID | Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| ---| --- | --- | --- | --- |--- |
| PPP-01 | Logo link | Link directs the user back to the home page | Clicked logo | Links to landing page | PASS |
| PPP-02 | Logo hover | Visibly scaling up when hovering over with pointer | Hover over with pointer | Visibly scaling up | PASS |
| PPP-03| Menu link | Link to insite page - not opening separate tab | Clicked each menu item link | Menu item opened insite | PASS |
| PPP-04 | Page internal links | Link to external page on new tab | Clicked each item linked externally on new tab | Each item linked externally on new tab| PASS |
| PPP-05 | Page internal links-'visiting website'| Links to Thank-you page insite | Clicked | Thank-you page opened| PASS |
| PPP-06 | Footer links behaving as in Landing page | Hovering and clicking on each icon/link | Hovered and Clicked | All opened in separate tab and transported to correct external page | PASS |

#### Cookies Page (CKP)

| TestCase ID | Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| ---| --- | --- | --- | --- |--- |
| CKP-01 | Logo link | Link directs the user back to the home page | Clicked logo | Links to landing page | PASS |
| CKP-02 | Logo hover | Visibly scaling up when hovering over with pointer | Hover over with pointer | Visibly scaling up | PASS |
| CKP-03 | Menu link | Link to insite page - not opening separate tab | Clicked each menu item link | Menu item opened insite | PASS |
| CKP-04 | Page internal links | Link to external page on new tab | Clicked item linked externally on new tab | Item linked externally on new tab| PASS |
| CKP-05 | Page internal links'GDPR'| Links to Thank-you page insite | Clicked | Thank-you page opened| PASS |
| CKP-06 | Footer links behaving as in Landing page | Hovering and clicking on each icon/link | Hovered and Clicked | All opened in separate tab and transported to correct external page | PASS |

#### GDPR Page (GDPR)

| TestCase ID | Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| ---| --- | --- | --- | --- |--- |
| GDPR-01 | Logo link | Link directs the user back to the home page | Clicked logo | Links to landing page | PASS |
| GDPR-02 | Logo hover | Visibly scaling up when hovering over with pointer | Hover over with pointer | Visibly scaling up | PASS |
| GDPR-03 | Menu link | Link to insite page - not opening separate tab | Clicked each menu item link | Menu item opened insite | PASS |
| GDPR-04 | Page internal link 'Cookies' | Link to Cookies page insite | Clicked item linked insite to Cookies page | Cookies page opened insite | PASS |
| GDPR-05 | Page internal links'contact us'| Links to Thank-you page insite | Clicked | Thank-you page opened| PASS |
| GDPR-06 | Footer links behaving as in Landing page | Hovering and clicking on each icon/link | Hovered and Clicked | All opened in separate tab and transported to correct external page | PASS |


### FAILED test cases  - now fixed
| TestCase ID| Feature | Expected Outcome | Result | Result after correction|
| ---| --- | --- | --- | --- |
| SeP-05 | Give a gift button links under each image | Same size on all media sizes | Button larger on screens > 768px | PASS

--------------------

1; I want to easily find information about the different therapies offered.

2; I need to clearly understand how to get in contact and or book an appointment.

3; I want to easily purchase gift cards, having already experienced the benefits of the therapies myself.

4; I want a simple way to provide feedback or suggestions.