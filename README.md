# Horiseon Project: Code Refactor


## Table of Contents
- [Description](#description)
- [Link](#link)
- [Screenshot](#screenshot)

## Description
For the Horiseon website, they asked their code be refactored to meet accessibility standards and be more logically structured. This repository is my attempt to do such. My overall goal was to make the code more organized and meaningfully condensed. For the style.css, I renamed and grouped css selectors to better simplify and organize the content (ex:``` .header h1{...}``` replace with: ```h1{...}```). I also have css selectors organized according to when they appear in the HTML (body -> header content -> main content -> footer content). 

For index.html, I incorporated HTML elements inplace of the using all divs with classes (ex:``` <div class="footer">...</div>``` replace with: ```<footer>...</footer>```). For images, I included alt attributes for them so if the images won't load there is descriptive text provided in it's place.

## Link
[Click to view Horiseon GitHub Page](https://maggiemcc.github.io/Horiseon/)

## Screenshot
![](screenshot.png)