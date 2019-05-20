# Developer Test

## Introduction

You're required to build a single webpage to display the latest photographs for a fictitious nature photographer. Designs for mobile, tablet & desktop have been supplied, along with page content & images which can all be found below.

The web page should be built with PHP, HTML & CSS and should follow industry best practices. It should work in Chrome, Firefox & Edge on desktop, and should work on both modern iOS & Android devices for mobile/tablet. 

## Rules

* Please do not spend more than 4 hours on the task
* Feel free to use the internet
* Do not share your submission publicly online

## Test Submission

Please send a `.zip` of your submission to kerry.pendlebery@indigotree.co.uk.

* * *

## Designs

You can find mobile, tablet & desktop designs inside the `/designs` folder of this repository. Currently these designs are only in `.png` format, so we therefore do not expect pixel perfect implementations. We would however like you to be as close as possible.

### Fonts

The fonts used are: `Open Sans`, with the following weights: 300, 400, 700. You're free to load these from [Google Fonts](https://fonts.google.com/).

The body font weight is 300, the font size is `18px`, and the line height is `1.75`.

### Colours

You should be able to use a colour picker to extract most colours from the design. The purple used is `#553C9A` and is 85% transparency.

### Images

All images can be found in the `images` folder of this repository. A copy of the logo (`logo.svg`) has also been supplied.

* * *

## Content

### Hero/Banner

The page hero should use `banner.jpg` background image, with the following text ontop: `Lorem ipsum dolor sit amet` and `sed do eiusmod tempor incididunt ut labore`.

### Body/Page Content

The main body content should have the following text:

```
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
```

### Photo Gallery

The content for the photo gallery must be pulled in dynamically from our JSON endpoint. This must be done with PHP on the server side. The URL is provided below.

```
https://indigotree-developer-test-1-api.netlify.com/photos.json
```

## Contact Form

Please create a contact form that will send emails to `dev-test@indigotree.co.uk`. It must contain the following fields:

- First Name
- Last Name
- E-Mail Address
- Message

For the purposes of this test, input validation is optional.
