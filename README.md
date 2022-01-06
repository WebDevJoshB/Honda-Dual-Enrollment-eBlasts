# Honda Dual Enrollment eBlasts
_This repo and README is a work in progress, more details to come._

Template Links: [Week 1][src1] | [Week 2][src2] | [Week 3][src3] | [Week 4][src4] <br/>


**Table of Contents**
1. [Intro](#user-content-intro)
2. [Development Info](#user-content-development-info)
3. [Features](#user-content-features)
    - [Fonts](#user-content-fonts)
    - [Responsive Images](#user-content-responsive-images)
      - [Honda Logo](#user-content-honda-logo)
      - [Program Timeline](#user-content-program-timeline)
4. [Challenges and Solutions](#user-content-challenges-and-solutions)
5. [Responsive Layouts](#user-content-responsive-layouts)
    - [Screenshots](#user-content-1-screenshots)
    - [DevTools](#user-content-2-devtools)
    - [Browser Resizing](#user-content-3-browser-resizing)


## Intro
These weekly B2B emails were sent over the course of four weeks to participating Honda dealerships to entice dealers to enroll in both Honda Corporate's _Winter Season_ and the _Warranty Customer Retention_ program.

## Development Info
* Email content default width: 600px.
* Hard coded responsive break points of 320px and 480px (due to time constraits).
* More details to come.

## Features
More details to come that talk about features and techniques used in email production.

### Fonts
Font stack/family details. More details to come.

### Responsive Images
_This content is a work in progress_
* Same image is not used and resized for all layouts.
  - Improves user experience, pages load faster.
  - Images don't appear shrunk on smaller screens.

* Design control: Crop image at various sizes depending on user agent/device display size.
  * One image optimized for both landscape and portrait dimensions.

These HTML techniques will be seen in devices that support them without impacting those that don't. This approach is called [graceful degradation][ref1].

#### Honda Logo 

**Example 1:** <br/>
The logo (170 x 65px, 8kb) used for 600px display layout is shrunk down for mobile devices:

![](https://webdevjoshb.github.io/Honda/Dual-Enrollment-eBlasts/screenshots/honda-logo-ex-before.png)


**Example 2:** <br/>
Using this technique, I use a resized version of the same image (120 x 46px, 5kb) for mobile devices:

![](https://webdevjoshb.github.io/Honda/Dual-Enrollment-eBlasts/screenshots/honda-logo-ex-after.png)


More modern email browsers/apps that support this code will render the logo as seen in the second example, while all others default to example one.


#### Program Timeline
More details to come.

**Example 1:**<br/>
The program timeline graphic used for 600px display layout shrunk for mobile devices:

![](https://webdevjoshb.github.io/Honda/Dual-Enrollment-eBlasts/screenshots/timeline-ex-before.png)


**Example 2:** <br/>
Modified image to account for smaller screen display:

![](https://webdevjoshb.github.io/Honda/Dual-Enrollment-eBlasts/screenshots/timeline-ex-after.png)


## Challenges and Solutions
* Prevent dates from appearing as links in iOS.
* Non-breaking spaces (phone numbers don't appear on two separate lines).
* More details to come.

## Responsive Layouts 
To view responsive layouts, there are three options: 
1. View screenshots various screen widths.
2. Use web browser's DevTools to simulate different layouts.
3. Manually resize browser.

### 1. Screenshots 
The following are screenshots of each template at various screen widths.

<table>
<tr>
    <th>Week 1</th>
    <td><a href="https://webdevjoshb.github.io/Honda/Dual-Enrollment-eBlasts/screenshots/wk1/320px.png" target="_blank">320px</a></td>
    <td><a href="https://webdevjoshb.github.io/Honda/Dual-Enrollment-eBlasts/screenshots/wk1/480px.png" target="_blank">480px</a></td>
    <td><a href="https://webdevjoshb.github.io/Honda/Dual-Enrollment-eBlasts/screenshots/wk1/600px.png" target="_blank">600px</a></td>
    <td><a href="https://webdevjoshb.github.io/Honda/Dual-Enrollment-eBlasts/screenshots/wk1/768px.png" target="_blank">768px</a></td>
</tr>
<tr>
    <th>Week 2</th>
    <td><a href="https://webdevjoshb.github.io/Honda/Dual-Enrollment-eBlasts/screenshots/wk2/320px.png" target="_blank">320px</a></td>
    <td><a href="https://webdevjoshb.github.io/Honda/Dual-Enrollment-eBlasts/screenshots/wk2/480px.png" target="_blank">480px</a></td>
    <td><a href="https://webdevjoshb.github.io/Honda/Dual-Enrollment-eBlasts/screenshots/wk2/600px.png" target="_blank">600px</a></td>
    <td><a href="https://webdevjoshb.github.io/Honda/Dual-Enrollment-eBlasts/screenshots/wk2/768px.png" target="_blank">768px</a></td>
</tr>
<tr>
    <th>Week 3</th>
    <td><a href="https://webdevjoshb.github.io/Honda/Dual-Enrollment-eBlasts/screenshots/wk3/320px.png" target="_blank">320px</a></td>
    <td><a href="https://webdevjoshb.github.io/Honda/Dual-Enrollment-eBlasts/screenshots/wk3/480px.png" target="_blank">480px</a></td>
    <td><a href="https://webdevjoshb.github.io/Honda/Dual-Enrollment-eBlasts/screenshots/wk3/600px.png" target="_blank">600px</a></td>
    <td><a href="https://webdevjoshb.github.io/Honda/Dual-Enrollment-eBlasts/screenshots/wk3/768px.png" target="_blank">768px</a></td>
</tr>
<tr>
    <th>Week 4</th>
    <td><a href="https://webdevjoshb.github.io/Honda/Dual-Enrollment-eBlasts/screenshots/wk4/320px.png" target="_blank">320px</a></td>
    <td><a href="https://webdevjoshb.github.io/Honda/Dual-Enrollment-eBlasts/screenshots/wk4/480px.png" target="_blank">480px</a></td>
    <td><a href="https://webdevjoshb.github.io/Honda/Dual-Enrollment-eBlasts/screenshots/wk4/600px.png" target="_blank">600px</a></td>
    <td><a href="https://webdevjoshb.github.io/Honda/Dual-Enrollment-eBlasts/screenshots/wk4/768px.png" target="_blank">768px</a></td>
</tr>
</table>

### 2. DevTools 
To open the browser's DevTools, press `F12` or `Control`+`Shift`+`I` (Windows, Linux) or `⌘`+`Option`+`I` (macOS).

Note that simulations _only give an approximation_ of the mobile or device user experience while using a web browser. 

**How to use DevTool:** [Chrome][dev1] | [Firefox][dev2] | [Microsoft Edge][dev3] | [Safari][dev4]

### 3. Browser Resizing
Note that using a web browser only gives an approximation of the mobile or device user experience in a web browser. 


  [src1]: https://webdevjoshb.github.io/Honda/Dual-Enrollment-eBlasts/wk1.html
  [src2]: https://webdevjoshb.github.io/Honda/Dual-Enrollment-eBlasts/wk2.html
  [src3]: https://webdevjoshb.github.io/Honda/Dual-Enrollment-eBlasts/wk3.html
  [src4]: https://webdevjoshb.github.io/Honda/Dual-Enrollment-eBlasts/wk4.html

  [ref1]: https://developer.mozilla.org/en-US/docs/Glossary/Graceful_degradation

  [dev1]: https://developer.chrome.com/docs/devtools/device-mode/#viewport
  [dev2]: https://developer.mozilla.org/en-US/docs/Tools/Responsive_Design_Mode
  [dev3]: https://docs.microsoft.com/en-us/microsoft-edge/devtools-guide-chromium/device-mode/#simulate-a-mobile-viewport
  [dev4]: https://support.apple.com/guide/safari-developer/simulate-responsive-web-content-apple-devices-dev84bd42758/11.0/mac/10.13

