Deployed project: [https://generategeorgina.github.io/fac-agency/](https://generategeorgina.github.io/fac-agency/)

## 1. Structure a site using semantic HTML to aid accessibility
Here I used `section`, `article` and `p` elements to strucutre the website to aid accessibility.

![semantic html screenshot](../images/markup/Screenshot%202023-06-11%20at%2011.48.05.png)
## 2. Ensure a web page is readable for screen readers
VoiceOver on Mac was used to stress-test the accessibility of the site for those who use screen readers.

## 3. Ensure our UI has sufficient colour contrast so that everyone can perceive it comfortably
The blue background contrasts with the orange buttons and white text.

![UI without relying on colour](../images/markup/Screenshot%202023-06-11%20at%2012.09.14.png)
## 4. Use various tools to check that our website meets accessibility criteria
Chrome Lighthouse was one of the dev tools used to check that the website met the accessibility criteria. We also manually checked with screen readers and keyboard-only navigation.

![Lighthouse score](../images/markup/Screenshot%202023-06-11%20at%2012.25.16.png)
## 5. Use CSS media queries to ensure our content is always presented effectively on screens of different sizes
I used media queries for desktop/laptop, tablet and mobile displays.

![media queries](../images/markup/Screenshot%202023-06-11%20at%2012.27.44.png)
## 6. Demonstrate a mobile-first approach to building a website
The website was designed for an optimised mobile experience. For example, the nav bar text is set to `display: none` for screens under 600px.

![mobile-first](../images/markup/Screenshot%202023-06-11%20at%2012.30.55.png)
## 7. Use CSS variables to apply repeated colours to HTML elements
CSS variables were used to store hex codes and were used to style HTML pages.

![CSS variables](../images/markup/Screenshot%202023-06-11%20at%2012.34.30.png)
## 8. Use CSS Flexbox to style children in a single-direction layout (ie a row or a column)
I used flexbox containers allow for a single-column layout to optimise the mobile experience.

![CSS Flexbox](../images/markup/Screenshot%202023-06-11%20at%2012.39.35.png)
## 9. Use CSS Grid to style children in two-direction layout
For my [beautiful calculator](https://github.com/generateGeorgina/beautiful-calculator) project, I used CSS grid to layout the calculator buttons, such as numbers and operators.
## 10. Ensure our Git commit history tells a coherent story
Git history shows the order the features were worked on and demonstrates how the project progressed.

![git commit history main branch](../images/markup/Screenshot%202023-06-11%20at%2012.46.13.png)
## 11. Use the appropriate input types in HTML forms for gathering different types of information
I used text input type for name. This section could have been improved by using `type="tel"` for telephone number.
![HTML forms input type](../images/markup/Screenshot%202023-06-11%20at%2012.48.14.png)