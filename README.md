# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview
Order summary card created with HTML and SASS

### Screenshot

Mobile 

![order-summary-card-mobile](https://user-images.githubusercontent.com/90436675/159144040-dec38240-3e48-445e-b148-7c8a40ab521b.png)


Desktop

![order-summary-card-desktop](https://user-images.githubusercontent.com/90436675/159144044-4c58d9e1-b822-4555-8889-41c1c9777d7a.png)


### Links

- Solution URL: https://github.com/Marvin-Erazo/order-summary-card/
- Live Site URL: https://order-summary-card-me.netlify.app/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flex
- Mobile-first workflow
- [SASS] (https://sass-lang.com) - For stylesheet


### What I learned

Is my fisrt time using mobile first workflow although the dimension of qr component is also small then this see good in mobile and dektop to responsive i only change the width of the qr div content for the margins

```SCSS

@media screen and (max-width: 375px) {

    .order-card{
        width: 90%;
        margin: auto;

        .order-description,
        .order-plan,
        .payment{
            margin: 0px 20px;
        }
    }
}
```
### Continued development

In the last challenge i didn't use html tags for the accesiblity, in others chanllege i will try insert this tags
thanks so much everybody


## Author

- Website - [Marvin Erazo](https://marvin-erazo.github.io/)
- Frontend Mentor - [@Marvin-Erazo](https://www.frontendmentor.io/profile/Marvin-Erazo)
- GitHub - [Marvin-Erazo](https://github.com/Marvin-Erazo)
