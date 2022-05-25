# NFT Preview Card
- [Overview](#overview)
- [Screenshot](#screenshot)
- [Links](#links)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Continued development](#continued-development)
- [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)



## Overview
I used HTML and CSS to build the NFT Preview card from Frontend Mentors

### Screenshot
![nft-card](https://user-images.githubusercontent.com/69125833/170151439-ae93c93a-ab71-4cc6-8efc-11a3a767aecc.png)



### Links

- Live Site URL: (https://chic-lily-20147e.netlify.app/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

I put all the colors in root variables. I also tried using the BEM naming conventions in writing my CSS classes. Using this naming conventions for the first time. I can
say it made me less confused about which class names are for the elements. Looking forward to working with it more in my upcoming projects.

Code Snippet: Some of my CSS and HTML to show BEM

```
:root{
    /* primary colors */
    --softBlue:hsl(215, 51%, 70%);
    --cyan:hsl(178, 100%, 50%);
    /* neutral colors */
    /* main Background */
    --verydarkblue1: hsl(217, 54%, 11%); 
    /* card Background */
    --verydarkblue2: hsl(216, 50%, 16%);
    /* line */
    --verydarkblue3: hsl(215, 32%, 27%);
    --white: hsl(0, 0%, 100%);
}

<div class="card--footer-align">
            <img src="image-avatar.png" alt="avatar" class="card-footer-image">
            <label class="card-footertext-label">Creation of <span class="card-footertext-span">Jules Wyvern</span></label>
 </div>
```

### Continued development

I will focus on bulding projects from Frontend Mentor challenges and personal projects for personal development.

### Useful resources

- [Resource 1]([https://www.asmeurer.com/git-workflow/](https://cssguidelin.es/#bem-like-naming)) - This resource helped me with the BEM naming conventions.



## Author

- Website - [Nkwor Jane](https://chic-lily-20147e.netlify.app/).
- Frontend Mentor - [@Nkwor-Jane](https://www.frontendmentor.io/profile/@Nkwor-Jane).


## Acknowledgments
I would like to thank Frontend Mentor.
