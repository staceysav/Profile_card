# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Profile card component solution](#frontend-mentor---profile-card-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
  - [Author](#author)


## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Github repository](https://github.com/staceysav/Profile_card)
- Live Site URL: [Github pages](https://staceysav.github.io/Profile_card/)

## My process
Difficulties:
when creating background, i couldn't position the circles inside the background div and make it partially "leave" the screen at the same time. - but that was not the problem itself... Оказалось, для того, чтобы двигать элементы относительно друг друга, необходимо добавить для родительсткого элемента position: relative, а для дочернего position:absolute.

Is it better to put images inside the background div or outside? to use   overflow: hidden; inside div is what i need?

id or class?

а нужно ли создавать отдельный div или можно прямо в body всё вписывать?

размер mobile version 375, получается судя по макету, ширина карточки примерно 360px.


как сделать так, чтобы картинка в карточке точно подходила по размерам??

добавление белой обводки фото кажется очевидным, но не для меня. оказывается, ружно просто добавить border к этой картике.

как организовать бэкграунд, чтобы при уменьшении размера экрана декоративные круги не сдвигались?

как выровнять results по вертикали?


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

### Continued development

First things first, I'd like to focus on CSS grid and mastering the layout (flexbox, arranging elements on the page).

### Useful resources

- [Flexboxfroggy](https://flexboxfroggy.com/) - This helped me to get acquainted with Flexbox in an interesting format.

## Author

- Website - [Anastasia Savinova](https://staceysav.github.io/)
- Frontend Mentor - [@staceysav](https://www.frontendmentor.io/profile/@staceysav)
- 