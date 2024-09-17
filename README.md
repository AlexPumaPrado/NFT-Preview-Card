# Make It Real - NFT Preview Card

This is a solution to the NFT Preview Card project of the Make It Real course.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to: Users will be able to view a NFT Preview Card.

- Version Mobile
- Version Desktop

### Screenshot

![FireShot Capture 005 - NFT Preview Card - ](https://github.com/user-attachments/assets/decedf50-0e5e-4c31-8c78-3d336e9636bc)

![FireShot Capture 006 - NFT Preview Card - Desktop](https://github.com/user-attachments/assets/de14bde8-724b-489b-a411-378f9723c1cb)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
 <div class="card-avatar">
      <img src="images/image-avatar.png" alt="avatar" class="card-avatar-img">
      <p class="card-name"> Creation of <a href="#">Alexander Puma</a></p>
```
```css
.card-img::after {
  content: url(../images/icon-view.svg);
  background: var(--Soft-blue);
  position: absolute;
  inset: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  opacity: 0;
  transition: all 0.25s ease;
}
```


### Continued development

For future projects, I will focus on image optimization to ensure fast loading times. I'll also explore more about implementing CSS to improve the user experience.

### Useful resources

- Markdown Guide

## Author

- Alexander Puma Prado
- Linkedin - [@AlexanderPuma](https://www.linkedin.com/in/alexander-puma-prado/)


## Acknowledgments

I am grateful to the teachers of the project and the authors of the visual and written internet resources.
