# result-summary-component-design

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

## Overview

Result summary component design using HTML5 CSS and Flexbox

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: (https://github.com/Nikkaburger/result-summary-component-design)
- Live Site URL: (https://bespoke-squirrel-736182.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learnt about hsl color codes, using flexbox to align contents in row and column using media query for responsive design 

```html

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" type="text/image" sizes="32x32" href="images/favicon-32x32.png">
    <link rel="stylesheet" href="css/style.css">
    <title>Frontend Mentor | Result Summary</title>
</head>
<body>
    <div class="container">
    <div class="container1">
    <h1>
        Your Result
    </h1>
    <div class="circle"> 
        <span class="top-text">76</span>
        <span class="bottom-text"> of 100</span>
    </div>
    <span class="msg">
        Great
    </span>
    <h2>You scored higher than 65% of the people who have taken these tests.</h2> 
    </div>
    <div class="container2">
        <h3>
            Summary
        </h3>
        <div class="box1">
            <img src="images/icon-reaction.svg" alt="icon-reaction" class="left-align"> 
            <span class="left-align">
               Reaction
            </span>
            <span class="right-align">
                80
            <span class="grey"> / 100</span>
            </span>
        </div>
        <div class="box2">
            <img src="images/icon-memory.svg" alt="icon-memory" class="left-align">
            <span class="left-align">
            Memory
            </span>
            <span class="right-align">
                92
            <span class="grey"> / 100</span>
            </span>
        </div>
        <div class="box3">
            <img src="images/icon-verbal.svg" alt="icon-verbal" class="left-align">
            <span class="left-align">
             Verbal
            </span>
            <span class="right-align">
                61 
            <span class="grey"> / 100</span>
            </span>
        </div>
        <div class="box4">
            <img src="images/icon-visual.svg" alt="icon-visual" class="left-align">
            <span class="left-align">
                Visual
            </span>
            <span class="right-align">
                72
            <span class="grey"> / 100</span>
            </span>
        </div>
        <button class="button">
            Continue
        </button>
    </div>
    </div>
</body>
</html>

```
```css

html,body {
        display: flex;
        align-items: center;
        background-color: hsl(0, 13%, 95%);
        justify-content: center;
        font-size: 18px;
        max-height: 900px;
        max-width: 100%;
        margin: 0px;
        font-family: 'Hanken Grotesk', sans-serif;
    }

    .container {
        display: flex;
        background-color: hsl(0, 0%, 100%);
        flex-direction: row;
        justify-content:center;
        margin: 100px;
        align-items: center;
        width: fit-content;
        height: 450px;
        border-radius: 25px;
    }


```

### Continued development

My focus is on mastering modern web design techniques through continuous learning, experimentation, and a willingness to adapt to the ever-changing web landscape. 
By focusing on responsive design using, HTML5, CSS3, JavaScript, and PHP, to be adequately equipped to create visually stunning and user-friendly websites. Embrace new technologies, stay curious, and push the boundaries of my creativity to unlock endless possibilities in the world of web development. 

### Useful resources

- [#CSSMediaQuery](https://courses.webdevsimplified.com) - This helped me to understand and fix media query for the mobile version of my design, the tutorial was direct and explanatory. I really liked this pattern and will use it going forward.
- [#HTMLFullCourseforBeginners](https://courses.davegray.codes/) - This is an amazing course which helped me finally understand the functionality of #HTML5 tags. I'd recommend it to anyone still learning this concept.
-[#CSSTutorialFullCourseforBeginners](https://courses.davegray.codes/) - This is an amazing course which helped me finally understand CSS tags, syntax and their functionalities. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Oluwaseun Akeju](https://www.fluxverge.com)
- Frontend Mentor - [@nikkaburger](https://www.frontendmentor.io/profile/nikkaburger)
- Twitter - [@fluxverge](https://www.twitter.com/fluxverge)

## Acknowledgments

Special thanks to Almighty God for the completion of this task, my profound gratitude to Dave Gray, Omolade Sunday, Akinola Akeem and Webdevsimplified for their immense contributions.
