# Frontend Mentor - NFT preview card component

![Design preview for the NFT preview card component coding challenge](./design/desktop-preview.jpg)

# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learn about the image hover, I had a idea how to excute but there were some issues. I went online for solutions.

To see how you can add code snippets, see below:

```html
<div class="card-head">
  <img src="./images/image-equilibrium.jpg" alt="">
  <div class="icon">
    <img src="./images/icon-view.svg" alt="">
  </div>
</div>
```
```css
.card-head>.icon {
    position: absolute;
    background-color: hsl(178, 100%, 50%, 60%);
    width: 100%;
    height: 300px;
    border-radius: 10px;
    top: 0%;
    opacity: 0;
    z-index: 1;
    transition: opacity .2s ease-in-out;
}

.card-head>.icon:hover {
    opacity: 1;
    cursor: pointer;
}

.card-head>.icon>img {
    position: absolute;
    top: 48%;
    left: 50%;
    width: 60px;
    transform: translate(-50%, -50%);
}

}
```

### Continued development

I will contiune my reasech on image hover and hsl with opactiy.

### Useful resources

- [WW3 Schools with image overlay](https://www.w3schools.com/howto/howto_css_image_overlay.asp) - This helped me with figuring out the image hover issue.

