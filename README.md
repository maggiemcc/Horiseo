# Horiseon Project: Code Refactor


## Table of Contents
- [User Story](#user-story)
<!-- - [Acceptance Criteria](#acceptance-criteria) -->
- [Description](#description)
- [Link](#link)
- [Screenshot](#screenshot)


## User story
Aa a marketing agency
I want a codebase that follows accessibility standards
so that our own site is optimized for search engines

<!-- ## Acceptance criteria
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title -->

## Description
For the Horiseon website, they asked their code be refactored to meet accessibility standards and be more logically structured. This repository is my attempt to do such. My overall goal was to make the code more organized and meaningfully condensed. For the style.css, I renamed and grouped css selectors to better simplify and organize the content (ex:``` .header h1{...}``` replace with: ```h1{...}```). I also have css selectors organized according to when they appear in the HTML (body -> header content -> main content -> footer content). 

For index.html, I incorporated HTML elements inplace of the using all divs with classes (ex:``` <div class="footer">...</div>``` replace with: ```<footer>...</footer>```). For images, I included alt attributes for them so if the images won't load there is descriptive text provided in it's place.

## Link
[Click to view Horiseon GitHub Page](https://maggiemcc.github.io/Horiseon/)

## ScreenShot
![](screenshot.png)