# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Blog preview card final output image](https://github.com/IVSonlee/Blog-preview-card/blob/658e9d41d50261cd6f9d31e8b1bbe72e3bcc2e8a/images/Blog_preview_card_final_output.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/IVSonlee/Blog-preview-card.git)
- Live Site URL: [Add live site URL here](https://ivsonlee.github.io/Blog-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Responsive
- CSS hover
- CSS Alignment
- CSS Transition
- CSS Fonts

### What I learned

```css 
@font-face {
    font-family: Figtree_italic;//This is serve as a name of the font you will be using for font family 
    src: url(/assets/fonts/Figtree-Italic-VariableFont_wght.ttf); //This serves as the source of the font
}
@font-face {
    font-family: Figtree_variable;//This is serve as a name of the font you will be using for font family 
    src: url(/assets/fonts/Figtree-VariableFont_wght.ttf); //This serves as the source of the font
}

main
{
    box-sizing: border-box;
    box-shadow: 8px 8px hsl(0, 0%, 7%);
    border: 0.12em solid hsl(0, 0%, 7%);
    border-radius: 20px;
    background: rgb(255, 255, 255);
    height: 522px;
    transition: color 0.5s ease-in-out;
    transition: box-shadow 0.5s ease-in-out;
    width: 384px;
}
main:hover h2
{
    color: rgb(244, 208, 78);
}
main:hover
{
    box-shadow: 20px 20px hsl(0, 0%, 7%);
}

/*I have fun learning to use transition in color and box-shadow. For hover I am happy I used my skill that I learned how can I change the color that is being needed even my cursor is not in the text and 
for the background shadow I also used hover as well because of the transition that is needed to be applied.
also have a l*/
```

### Continued development

This project can be included or used to display in my personal portfolio to indicate some experience and skill using html and css.

### Useful resources

- [Figma](figma.com) - It helps to have a complete visualization of the design with exact information needed
- [Claude](claude.ai) - This helps me what code to use for specific purposes like how can I use the fonts in the folder that is already given then it recommend me to use 
@font-face indicating the font-family and its source.


### AI Collaboration

1) Claude - to serve me as guide when I had some questions regarding to what code or command I should use but I am not asking the exact output just the sample output 

## Author

- Frontend Mentor - [@IVSonlee](https://www.frontendmentor.io/profile/IVSonlee)
- Jobstreet - ph.jobstreet.com/profiles/iversonrichmond-lee-QkPdmlXNHv
- LinkedIn - www.linkedin.com/in/iverson-richmond-lee-332029405

## Acknowledgments

[Author] - IVSonlee
- Jobstreet Profile: https://ph.jobstreet.com/profiles/iversonrichmond-lee-QkPdmlXNHv 
- LinkedIn Profile: www.linkedin.com/in/iverson-richmond-lee-332029405 
- Github Profile: https://github.com/IVSonlee
