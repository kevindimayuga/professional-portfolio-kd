# Module 2 Challenge - Advanced CSS Professional Portfolio

This repo is for module two's challenge assignment.

## Description

The challenge is an Job-seeking coding assessment or take-home assignment (no starter code is provided, we will build this web application by scratch). The goal is to create a portfolio from scratch that will showcase my work. It will showcase my skills and talents to employers looking to fill a part-time or full-time position. The portfolio will highlight my strongest work as well as the thought processes behind it. It will include several deployed projects that will be used for me to apply and receive an initial interview at companies. I will be applying the skills I've learned in HTML and CSS. In particular, it will showcase the advanced CSS skills we have learned such as flexbox, media queries and CSS variables. for a marketing agency that has hired me to make it more accessible.

The motivation behind this project is to create a web application from scratch as well as create a portfolio that we will maintain to help us after bootcamp graduation. I built this portfolio in order to hone my own skills in HTML, CSS (Advanced CSS as well) and Git to ensure that I begin to understand more about the developer mindset and process. The problem it solved is making the a portfolio from scratch will utilize what we have learned thus far in the bootcamp. After completing this project, I have been able build an application from scratch and understand the process.

## User Story

```
AS AN employer
I WANT to view a potential employee's deployed portfolio of work samples
SO THAT I can review samples of their work and assess whether they're a good candidate for an open position
```

## Acceptance Criteria

```
GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport
```

## Accessing the Repo or Webpage:

- GitHub Repo URL: https://github.com/kevindimayuga/module-one-challenge.git
- GitHub Pages WebPage Deployment URL: https://kevindimayuga.github.io/module-one-challenge/

## Webpage Screenshot

![module one challenge webpage screenshot](./assets/images/kevindimayuga.github.io_module-one-challenge_.png)

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

The following steps were taken to complete the project:
- Review the purpose of the project, the user story and acceptance criteria
- Review the ins and outs of refactoring code
- Review semantic HTML elements and structure
- Review CSS
- Review code accessibility standards
- Refactor HTML and CSS
- Create Professional README file
- Add website image to README file
- Deploy website to GitHub Pages
- Submit screenshot of webpage and URLs to webpage and GitHub Repo

HTML Updates
```
<!--comments were made as needed in the HTML file-->

<title> was updated to "Horiseon Social Solution Services, Inc." </title>

the first <div> tag was updated to a <header> tag

removed <span> element in <h1>

next <div> tag was updated to a <nav> tag since it has nav links

moved "meetingimg" to header section

next <div> tag was updated to <main> tag for main content and changed "content" to "main content"

added alt attributes to specify alternate text for all images on webpage

updated "search-engine-optimization" class to id

removed "online-reputation-management" class, kept id

removed "social-media-marketing" class, kept id

next <div> tag was updated to <aside> tag

updated "benefit-lead", "benefit-brand" and "benefit-cost" classes to ids

last <div> tag was updated to a <footer> tag

made spaces between sections for clarity and cleanliness

added indents where necessary for clarity and cleanliness

```

CSS Updates
```
/*comments were made as needed in the CSS file*/

moved "a" and "p" styles to global section at top of css file

removed ".header h1 .seo" rule

updated ".header div", ".header div ul" and ".header div ul li" to ".header nav", ".header nav ul" and ".header nav ul li" 

updated .hero to .meetingimg

updated .content to .maincontent

updated "online-reputation-management" and "social-media-marketing" class (.) to id (#)

merged #search-engine-optimization, #online-reputation-management, #social-media-marketing into one

merged #search-engine-optimization img, #online-reputation-management img, #social-media-marketing img into one

merged #search-engine-optimization h2, #online-reputation-management h2, #social-media-marketing h2 into one

updated "benefit-lead", "benefit-brand" and "benefit-cost" class (.) to id (#)

merged #benefit-lead, #benefit-brand, #benefit-cost into one

merged #benefit-lead h3, #benefit-brand h3, #benefit-cost h3 into one

merged #benefit-lead img, #benefit-brand img, #benefit-cost img into one

```

Additional Updates
```

```

## Usage

N/A

## Credits

I used the following resources to help guide me to complete the refactoring project:

- [CSS Tutorial](https://www.w3schools.com/css/)
- [A Beginner's Guide to HTML Accessibility](https://blog.hubspot.com/website/html-accessibility)
- [HTML: A good basis for accessibility](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/HTML)
- [HTML Comments: How to Use Them](https://blog.hubspot.com/website/comment-out-in-html#:~:text=To%20leave%20a%20comment%20in,with%20a%20team%20of%20developers.)
- [HTML <img> Tag](https://www.w3schools.com/tags/tag_nav.asp)
- [HTML Images Syntax](https://www.w3schools.com/html/html_images.asp)
- [HTML 'aside' Tag](https://www.w3schools.com/tags/tag_aside.asp)
- [div: The Content Division Element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/div)
- [span: The Content Span element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/span)
- [CSS Selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors)
- [CSS and JavaScript accessibility best practices](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/CSS_and_JavaScript)

## License

N/A

## Badges

N/A

## Features

N/A

## How to Contribute

N/A

## Tests

N/A