# Manus Herba - Herbal, Lymphatic drainage and Zone therapy website

![The website shown on a variety of screen sizes](/documentation/doc-image/amiresponsive.png)

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
I have used google chrome developer tools & Firefox inspector tool to ensure that each page is responsive on a variety of different screen sizes and devices.

### Testing was performed on the following devices:
* Desktop:
    * Lenovo Legion T7
* Screen:
   * Samsung Odyssey G3 / 27" / 1920 x 1080 /
* Mobile Devices:
    * Samsung Galaxy S20

### Browser compability 
Each device tested the site using the following browsers:
* Google Chrome, version 121.0.6167.86 (Official Build) (64-bit)
* Firefox, version 122.0 (64-bit)

### Responsiveness
* Tested on Galaxy S20, 27" Samsung screen
* [Responsinator](http://www.responsinator.com/?url=https%3A%2F%2Fjaqikal.github.io%2Fwellness-therapy%2F)
* [Am I Responsive](https://ui.dev/amiresponsive?url=https://jaqikal.github.io/wellness-therapy/)

- - -

## AUTOMATED TESTING

### W3C Validator

[W3C](https://validator.w3.org/) was used to validate the HTML on all pages of the website. It was also used to validate the CSS.

* [404.htm](/documentation/doc-image/w3-404.png) - Passed
* [contact.html](/documentation/doc-image/w3-contact.png) - Passed
* [cookies.html](/documentation/doc-image/w3-css.png) - Passed
* [style.css](/documentation/doc-image/w3-css.png) - Passed
* [gdpr.html](/documentation/doc-image/w3-gdpr.png) - Passed
* [index.html](/documentation/doc-image/w3-index.png) - Passed
* [pricing.html](/documentation/doc-image/w3-pricing.png) - Passed
* [privacy-policy.html](/documentation/doc-image/w3-privacy-policy.png) - Passed
* [services.html](/documentation/doc-image/w3-services.png) - Passed
* [shop.html](/documentation/doc-image/w3-shop.png) - Passed
* [thank-you.html](/documentation/doc-image/w3-ty.png) - Passed

- - -

### Lighthouse

I used Lighthouse within the Chrome Developer Tools to test the performance, accessibility, best practices and SEO of the website.
This was done only on Desktop

All but one page is in the green, achieving a scores from 92  till 100. Main issues are related to lesser performance due to bad image handling.

`Those pages with scores of 92 and up:`
*  Form elements do not have associated labels causes accessibility issues.
*  Badly sized images.
*  Unused code.

`One with score 76 on performance is the page with all the image problems. This impacts all the other performace rates on the other pages.`
*  Image elements do not have explicit width and height.
*  Video: some third-party embeds can be lazy loaded. Consider replacing them with a facade until they are required.
*  LCP is to hig (or slow), LCP measures when the largest content element in the viewport is rendered to the screen.
*  Form elements do not have associated labels cause accessibility issues.

![404.htm](/documentation/doc-image/lighthouse-404.png)
![contact.html](/documentation/doc-image/lighthouse-contact.png)
![cookies.html](/documentation/doc-image/lighthouse-cookies.png)
![gdpr.html](/documentation/doc-image/lighthouse-gdpr.png)
![index.html](/documentation/doc-image/lighthouse-index.png)
![pricing.html](/documentation/doc-image/lighthouse-pricing.png)  
![privacy-policy.html](/documentation/doc-image/lighthouse-privacy.png)
![services.html](/documentation/doc-image/lighthouse-services.png)
![shop.html](/documentation/doc-image/lighthouse-shop.png)
![thank-you.html](/documentation/doc-image/lighthouse-ty.png)

## MANUAL TESTING

### Testing User Stories

`First Time Visitors`

| Goals | How are they achieved?|
| :--- | :--- |
| I want to easily find information about the different therapies offered. | The website have information snippets on landing page and links to Services page where the therapy forms are presented. Clear call to action button to mildly steer visitor towards either buying gift card or book an appointment. | I need to clearly understand how to get in contact and or book an appointment. | Call to action button on all pages. Though this is an area that definitely can be improved |

`Returning Visitors`

|  Goals | How are they achieved? |
| :--- | :--- |
| I want to easily purchase gift cards, having already experienced the benefits of the therapies myself. | Call to action button on  landing page is the first thin that meets a visitor. In future improvement I mention 'favourite' button, a way to bookmark what interest you on thre site. |

`Frequent Visitors`

| Goals | How are they achieved? |
| :--- | :--- |
| I want a simple way to provide feedback or suggestions.| In current version of the site our visitor can give their feedback on contact page. In coming versions of site a dedicated form and page will be created. |

- - -

### Full Testing

#### Landing Page (LAP)

| TestCase ID | Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| ---| --- | --- | --- | --- |--- |
| LAP-01 | Logo link | Link directs the user back to the home page | Clicked logo | Home page reloads | PASS |
| LAP-02 | Logo hover | Visibly scaling up when hovering over with pointer | Hover over with pointer | Visibly scaling up | PASS |
| LAP-03 | Menu link | Link to insite page (except Home item) - not opening separate tab | Clicked each menu item link, Home item to reload page | Menu item opened insite, except Home item, it reloaded page | PASS |
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
| SEP-05 | Give a gift button links under each image | Link directs the user to the Shop page | Clicked | Shop page opened | PASS following FAIL,|
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
| COP-08 | Form - text message field check | Preventing user from submitting only whitespace in the form | Typed in the field | space, tab etc can be entered. | FAIL, detailed below |
| CO0-09 | "Get in Touch" Button Submission | Verify the button leads to a Thank-you page upon correctly completing the form | Completed the form | Redirected to Thank-you page successfully | PASS |
| COP-10 | Give a Gift button hover | Visibly scaling up and changing colour when hovering over with pointer | Hover over with pointer | Visibly scaling up and changing colour | PASS |
| COP-11 | Footer links behaving as in Landing page | Hovering and clicking on each icon/link | Hovered and Clicked | All opened in separate tab and transported to correct external page | PASS |

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
| 404P-01 | Logo link | Link directs the user back to the home page | Clicked logo | Links to landing page | PASS |
| 404P-02 | Logo hover | Visibly scaling up when hovering over with pointer | Hover over with pointer | Visibly scaling up | PASS |
| 404P-03 | Menu link | Link to insite page - not opening separate tab | Clicked each menu item link | Menu item opened insite | PASS |
| 404P-04 | Footer links behaving as in Landing page | Hovering and clicking on each icon/link | Hovered and Clicked | All opened in separate tab and transported to correct external page | PASS |

#### Privacy Policy Page (PPP)

| TestCase ID | Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| ---| --- | --- | --- | --- |--- |
| PPP-01 | Logo link | Link directs the user back to the home page | Clicked logo | Links to landing page | PASS |
| PPP-02 | Logo hover | Visibly scaling up when hovering over with pointer | Hover over with pointer | Visibly scaling up | PASS |
| PPP-03 | Menu link | Link to insite page - not opening separate tab | Clicked each menu item link | Menu item opened insite | PASS |
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

### Failed  test cases  - now FIXED

| TestCase ID| Feature | Expected Outcome | Result | Result after correction|
| ---| --- | --- | --- | --- |
| SEP-05 | Give a gift button links under each image | Same size on all media sizes | Button larger on screens > 768px | PASS

### UNSOLVED Bugs

| TestCase ID| Feature | Expected Outcome | Result | Result after correction|
| ---| --- | --- | --- | --- |
| COP-08 | Form - text message field check | Preventing user from submitting only whitespace in the form | To address the issue I applied the pattern attribute to each relevant input field `<input type="text" name="fname" id="fname" class="text-input" required pattern="\S(.*\S)?" title="This field cannot be empty or contain only spaces">`. This doesn't handle the problem with white-space. Cannot find any answers on the net to why. Code is kept in my contact html file.| NOT SOLVED |
| Observation post test |  NAVBAR | Navbar and footer corners not hidden | In Chrome browser & MS Edge the bottom right corner of the navbar is hidden under the browser schrollbar. Not present in Firefox.| NOT SOLVED | 
| Observation post test| Bulleted list | Normal formatting | On 1920px wide screen bulleted list has strange formatting | NOT SOLVED |

--------------------