# Frontend Mentor - Four card feature section solution

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
- [Author](#author)

  

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot


![image](https://user-images.githubusercontent.com/76195521/119057414-4edda380-b981-11eb-8849-f953fe791414.png)
![image](https://user-images.githubusercontent.com/76195521/119057262-00c8a000-b981-11eb-9dd4-e4a976dba78c.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

1. Organize HTML to prep for a grid layout
2. Start with a mobile-first layout since it's more simple to make
3. Use Gird to set a template 
4. Flex-box to adjust the spacing inside the cards and small tweets
5. Media Query to grid to rearrange to to desktop view

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

grid-template-area to set elements 

```css
@media (min-width: 989px)
{
    .card_wrapper 
    {
        display: grid;
        grid-gap: 25px;
        padding: 30px;
        align-items: center;
        grid-template-columns: 1fr 1fr 1fr;
        /* border: solid 5px royalblue; */
        justify-items: center;
        grid-template-areas: 
                    "...    team    ..."
                    "super  team    calc"
                    "super  karma   calc"
                    "...    karma   ..."
        ;
    }

```


### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-areas) - Where I go for reference when I need to review CSS Grid
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) - Where I go for reference when I need to review CSS Flex-box

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@T4R0TARO](https://www.frontendmentor.io/profile/T4R0TARO)
- Twitter - [@taro_code](https://twitter.com/taro_code)

## Acknowledgments

After going through Wes Bos Course on Flex-box and CSS Grid it helped me better understand when and where to apply layout properties.
