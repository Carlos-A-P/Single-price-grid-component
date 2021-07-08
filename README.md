# 3-column preview card component

- Live website -(https://carlospwd-single-price-grid-component.netlify.app/)

## Table of contents

- [The challenge](#the-challenge)
- [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

It was hard trying to get by second and third boxes to match the width of content perfectly and evenly. I had to do some math to get it to fit but I was wondering if there was a better way to do this oppose to calculating pixles. However I'm still happy by the way it looked in the end and how close I got to achieving the product. What I was most proud of was my implementation of grid which I found to be the easiest method for this project.

```css
.content {
	grid-template-areas:
		"first-card first-card"
		"second-card third-card";
	max-width: 700px;
}
```

I also got a better understanding to my html layout, I feel like it's very easy to follow my code now.

### Continued development

I'm starting to have a better hang of using grids in my projects. So far I've succesfully used grid in my projects

### Useful resources

- [Build a Responsive Grid CSS Website Layout From Scratch](https://www.youtube.com/watch?v=moBhzSC455o&ab_channel=TraversyMedia) - This helped me understand how to use grids and flexbox to organize my website. I also learned about some new vs code extentions such as prettier which helped make my code look neat and organised.

## Author

- Website - [Carlos Perez](https://www.site.com)
- Frontend Mentor - [@Carlos-A-P](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@WDCarlosP](https://www.twitter.com/WDCarlosP)
