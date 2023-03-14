# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview
  This project showcases my own experimentation with HTML and CSS. I tried everything based on my own understanding of the codes with a little help from the internet.

  DISCLAIMER: I do not have enough knowledge of programming HTML and CSS, only those I know were applied in the product so sorry if you think that my codes are messed up.
              Also, I do not have enough understanding on how to make responsive page for mobile screen so I decided not to input it. 

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot/Screen%20Shot%202023-03-14%20at%2012.29.10%20PM.png)
![](./screenshot/Screen%20Shot%202023-03-14%20at%2012.29.40%20PM.png)
![](./screenshot/Screen%20Shot%202023-03-14%20at%2012.29.48%20PM.png)
![](./screenshot/Screen%20Shot%202023-03-14%20at%2012.29.55%20PM.png)
![](./screenshot/Screen%20Shot%202023-03-14%20at%2012.30.02%20PM.png)
![](./screenshot/Screen%20Shot%202023-03-14%20at%2012.30.09%20PM.png)
![](./screenshot/Screen%20Shot%202023-03-14%20at%2012.30.16%20PM.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

1. Analyzed the layout.
2. Start building codes based on my understanding.
3. Applied basic HTML and CSS.
4. Deployed with github.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Bootsrap 5


### What I learned

I learned that web development is not an easy task, it requires proper planning and understanding of the codes as well as the projected layout of the project.

CODES SNIPPETS:

```html
<div class="main-container shadow-lg p-3 mb-5 bg-body rounded-5 position-absolute top-50 start-50 translate-middle">
        <div class="box-container position-absolute top-0 start-0 rounded-5">
            <div class="title1">
              <h6>Your Result</h6>
            </div>
                <div class="rounded-circle ">
                  <div class="score">
                    <h1>76</h1>
                    <p>of 100</p>
                  </div>
                </div>

                <div class="achievement">
                    <p>Great</p>
                </div>

                <div class="paragraph">
                  <p>You scored higher than 65% of <br>the people who have taken <br>these tests.</p>
                </div>
          </div>
```
```css
@import url('https://fonts.googleapis.com/css2?family=Hanken+Grotesk:wght@500;700;800&display=swap');

.main-container {
    height: 400px;
    width: 550px;
    /* max-width: 1440px; */
    position: relative;
    margin: auto;
    display: flex;
}
```


## Author

- Website - [John Benedick M. Lat](https://jbenedicklat.my.canva.site/)
- Frontend Mentor - [@benedicklat](https://www.frontendmentor.io/profile/benedicklat)
- Twitter - [@benedick_lat](https://twitter.com/benedick_lat)




