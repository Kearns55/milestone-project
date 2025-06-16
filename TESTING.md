# Testing

> [!NOTE]
> Return back to the [README.md](README.md) file.

## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Directory | File | URL | Screenshot | Notes |
| --- | --- | --- | --- | --- |
|  | [404.html](https://github.com/Kearns55/milestone-project/blob/main/404.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://kearns55.github.io/milestone-project/404.html) | ![screenshot](documentation/validation/html--404.PNG) ||
|  | [about-me.html](https://github.com/Kearns55/milestone-project/blob/main/about-me.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://kearns55.github.io/milestone-project/about-me.html) | ![screenshot](documentation/validation/html--about-me.PNG) |  Section Lacks Heading |
|  | [commissions.html](https://github.com/Kearns55/milestone-project/blob/main/commissions.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://kearns55.github.io/milestone-project/commissions.html) | ![screenshot](documentation/validation/html--commissions.png) |Section Lacks Heading |
|  | [index.html](https://github.com/Kearns55/milestone-project/blob/main/index.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://kearns55.github.io/milestone-project/index.html) | ![screenshot](documentation/validation/html--index.png) |  Section Lacks Heading|
|  | [success.html](https://github.com/Kearns55/milestone-project/blob/main/success.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://kearns55.github.io/milestone-project/success.html) | ![screenshot](documentation/validation/html--success.png) | Section Lacks Heading |


### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| Directory | File | URL | Screenshot |
| --- | --- | --- | --- |
| assets | [style.css](https://github.com/Kearns55/milestone-project/blob/main/assets/css/style.css) | [CSS Validator](https://jigsaw.w3.org/css-validator/validator?uri=https://kearns55.github.io/milestone-project) | ![screenshot](documentation/validation/css-assets-style.png) 


## Responsiveness

I've tested my deployed project to check for responsiveness issues.

| Page | Mobile | Tablet | Desktop | Notes |
| --- | --- | --- | --- | --- |
| Home | ![screenshot](documentation/responsiveness/mobile-home.png) | ![screenshot](documentation/responsiveness/tablet-home.png) | ![screenshot](documentation/responsiveness/desktop-home.png) | Works as expected |
| Commission | ![screenshot](documentation/responsiveness/mobile-commission.png) | ![screenshot](documentation/responsiveness/tablet-commission.png) | ![screenshot](documentation/responsiveness/desktop-commission.png) | Works as expected |
| Success | ![screenshot](documentation/responsiveness/mobile-success.png) | ![screenshot](documentation/responsiveness/tablet-success.png) | ![screenshot](documentation/responsiveness/desktop-success.png) | Works as expected |
| 404 | ![screenshot](documentation/responsiveness/mobile-404.png) | ![screenshot](documentation/responsiveness/tablet-404.png) | ![screenshot](documentation/responsiveness/desktop-404.png) | Works as expected |

## Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Page | Chrome | Brave | Safari | Notes |
| --- | --- | --- | --- | --- |
| Home | ![screenshot](documentation/browsers/chrome-home.png) | ![screenshot](documentation/browsers/brave-home.png) | ![screenshot](documentation/browsers/safari-home.png) | Works as expected |
| Commission | ![screenshot](documentation/browsers/chrome-commission.png) | ![screenshot](documentation/browsers/brave-commission.png) | ![screenshot](documentation/browsers/safari-commission.png) | Works as expected |
| Success | ![screenshot](documentation/browsers/chrome-success.png) | ![screenshot](documentation/browsers/brave-success.png) | ![screenshot](documentation/browsers/safari-success.png) | Works as expected |
| 404 | ![screenshot](documentation/browsers/chrome-404.png) | ![screenshot](documentation/browsers/brave-404.png) | ![screenshot](documentation/browsers/safari-404.png) | Works as expected |

## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues. Some warnings are outside of my control, and mobile results tend to be lower than desktop.

| Page | Mobile | Desktop |
| --- | --- | --- |
| Home | ![screenshot](documentation/lighthouse/mobile-home.png) | ![screenshot](documentation/lighthouse/desktop-home.png) |
| Commission | ![screenshot](documentation/lighthouse/mobile-commission.png) | ![screenshot](documentation/lighthouse/desktop-commission.png) |
| Success | ![screenshot](documentation/lighthouse/mobile-success.png) | ![screenshot](documentation/lighthouse/desktop-success.png) |
| 404 | ![screenshot](documentation/lighthouse/mobile-404.png) | ![screenshot](documentation/lighthouse/desktop-404.png) |

## Defensive Programming

Defensive programming was manually tested with the below user acceptance testing:

| Page | Expectation | Test | Result | Screenshot |
| --- | --- |  --- |  --- |  --- |
| Gallery | Feature is expected to showcase a gallery of my artwork. | Verified that the gallery contains clear images that aren't stretched, pixelated, and fully responsive. | Images are properly sized, and respond well to different device sizes. | ![screenshot](documentation/defensive/gallery.PNG) |
| Commission Form | Feature is expected to prevent submission of an empty form. | Attempted to submit the form without filling any fields. | Form submission was blocked, as expected. | ![screenshot](documentation/defensive/commission01.PNG) |
| | Feature is expected to enforce valid input types for each field. | Entered invalid data (e.g., random text in an email field, numbers in a name field, etc.). | Error messages were displayed appropriately, and submission was blocked. | ![screenshot](documentation/defensive/commission02.PNG) |
| Social Links | Feature is expected to include working links to the club’s social platforms (Instagram, Facebook, etc.). | Clicked each social link to verify redirection to the correct platform page. | All links redirected to the correct platform pages, opening in new browser tabs. | ![screenshot](documentation/defensive/socialmedia.PNG) |
| 404 Error Page | Feature is expected to display a 404 error page for non-existent pages. | Navigated to an invalid URL (e.g., `/test`) to test error handling. | A custom 404 error page was displayed as expected. | ![screenshot](documentation/defensive/404.PNG) |

## User Story Testing

| Target | Expectation | Outcome | Screenshot | 
| --- | --- | --- | --- | 
| As a user | I would like to see high quality images of the art. | so that I can descide if I want to commission my own piece. | ![screenshot](documentation/features/gallery.PNG) |
 As a user | I would like to learn more about the artist through an about me page | so that I can be more engaged. | ![screenshot](documentation/features/about-me.PNG) |
| As a collector | I would like to be able to request my own art work | so that I can support the artist. | ![screenshot](documentation/features/commission.PNG) |
| As a user | I would like to be able to find the artist on soclai media easily | so that I can keep up with their art| ![screenshot](documentation/features/footer.PNG) |
| As a user | I would like the website to be fully responsive | so that I can easily navigate and access information from my phone, tablet, or desktop. | ![screenshot](documentation/responsiveness/mobile-home.PNG) |
| As a user | I would like to see a 404 error page if I get lost | so that it's obvious that I've stumbled upon a page that doesn't exist. | ![screenshot](documentation/features/404.PNG) |

## Bugs

### Fixed Bugs

[![GitHub issue custom search](https://img.shields.io/github/issues-search?query=repo%3Akearns55%2Fmilestone-project%20label%3Abug&label=bugs)](https://www.github.com/kearns55/milestone-project/issues?q=is%3Aissue+is%3Aclosed+label%3Abug)

I've used [GitHub Issues](https://www.github.com/kearns55/milestone-project/issues) to track and manage bugs and issues during the development stages of my project.

All previously closed/fixed bugs can be tracked [here](https://www.github.com/kearns55/milestone-project/issues?q=is%3Aissue+is%3Aclosed+label%3Abug).

![screenshot](documentation/bugs/gh-issues-closed.PNG)

### Unfixed Bugs

[![GitHub issues](https://img.shields.io/github/issues/kearns55/milestone-project)](https://www.github.com/kearns55/milestone-project/issues)

Any remaining open issues can be tracked [here](https://www.github.com/kearns55/milestone-project/issues).

![screenshot](documentation/bugs/gh-issues-open.png)

### Known Issues

| Issue | Screenshot |
| --- | --- |
| On devices smaller than 240px, the page starts to have horizontal `overflow-x` scrolling. | ![screenshot](documentation/bugs/overflow.png) |
| When validating HTML with a semantic `<section>` element, the validator warns about lacking a header `h2-h6`. This is acceptable. | ![screenshot](documentation/bugs/section-header.png) |

> [!IMPORTANT]
> There are no remaining bugs that I am aware of, though, even after thorough testing, I cannot rule out the possibility.

