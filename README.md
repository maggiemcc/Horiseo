# Horiseon Project: Code Refactor


## Table of Contents
- [Description](#description)
- [Link](#link)
- [Screenshot](#screenshot)

## Description
For this Horiseon project, they asked their existing code to be refactored to meet accessibility standards and be more logically structured. This repository is my attempt to do such.

For index.html file, one of the key changes I made was incorporate more HTML elements inplace of using div elements with class names for everything (ex: ```<div class="footer">...</div>``` replaced with: ```<footer>...</footer>```). By making this change, it helped me better organize the css file too in terms of renaming and condensing selectors. Another change I made was for images, I included alt attributes. This way if the images don't load there is descriptive text provided in the images's place so user's know what should be shown.

For the style.css, I renamed css selectors to better simplify and make the names more logical for the content (ex:``` .header h1{...}``` replaced with: ```h1{...}```). I also have css selectors organized according to when they appear in the HTML (body -> header content -> main content -> footer content). By doing this it helps with finding content you wish to change faster and easier.

## Link
[Click to view Horiseon GitHub Page](https://maggiemcc.github.io/Horiseon/)

## Screenshot
![](screenshot.png)