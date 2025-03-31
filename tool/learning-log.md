# Tool Learning Log

## Tool: **Animate CSS**

---

### 3/8:
* I went to [Animate.css](https://animate.style/)
  * I looked through every aspect of Animate CSS and explored each of the examples
  * I picked some that I liked
* I went to edit on github and tried some out on my own
  * I took this code example below and started tinkering with it because I liked the rubber band animation
 ```CSS
   @keyframes rubberBand {
  from {
    -webkit-transform: scale3d(1, 1, 1);
    transform: scale3d(1, 1, 1);
  }
  30% {
    -webkit-transform: scale3d(1.25, 0.75, 1);
    transform: scale3d(1.25, 0.75, 1);
  }
  40% {
    -webkit-transform: scale3d(0.75, 1.25, 1);
    transform: scale3d(0.75, 1.25, 1);
  }
  50% {
    -webkit-transform: scale3d(1.15, 0.85, 1);
    transform: scale3d(1.15, 0.85, 1);
  }
  65% {
    -webkit-transform: scale3d(0.95, 1.05, 1);
    transform: scale3d(0.95, 1.05, 1);
  }
  75% {
    -webkit-transform: scale3d(1.05, 0.95, 1);
    transform: scale3d(1.05, 0.95, 1);
  }
  to {
    -webkit-transform: scale3d(1, 1, 1);
    transform: scale3d(1, 1, 1);
  }
}
.animate__rubberBand {
  -webkit-animation-name: rubberBand;
  animation-name: rubberBand;
```
* I went to [W3schools](https://www.w3schools.com/css/css3_animations.asp) CSS Animations
  * I tested out the code and created my own little ideas with them
* I went to [FCC](https://www.freecodecamp.org/learn/responsive-web-design/#applied-visual-design)
  * I completed the lessons on CSS Animations
* I made a lot of progress getting familiar with CSS Animation elements
* It is very tedious code so I had some challenges with keeping everything organized
* Are there any shortcuts to using CSS Animation that would make it easier and faster to use?

### 3/16:
* I didn't have much time to learn this week due to some personal things as well as sports, but I skimmed through [this video](https://www.youtube.com/watch?v=SgmNxE9lWcY) about basic CSS animations.
  *  I learned about how to make buttons move when hovered over.
* I also watched [this video](https://www.youtube.com/watch?v=z2LQYsZhsFw) about CSS animation properties.
  *  I learned about transformations and changing shapes by changing the border radius.
  * I tinkered a bit with CSS Animations once again so I wouldn't forget too much, but it was all minor tinkering and refreshing my memory, I did not do try too many new aspects of CSS animate this week.

### 3/23: 
* This week I wanted to see how others used CSS Animations to create projects.
* I saw this [video](https://www.youtube.com/watch?v=aOI0fpahGr8)
*   I noticed that some of the features are similar to bootstrap such as the collapse feature.
* I clicked on [this link](https://blog.hubspot.com/website/css-animation-examples) about more CSS Animation examples
*   This gave me some ideas and I tinkered a bit to test them.
*   I learned how useful CSS Animation can be and what uses it has to it.
* Overall, this week was mainly a research week rather than a tinker week, I wanted to just see other people's ideas and creations with CSS Animation so I can be inspired to make some of my own as well as find more uses for CSS Animation.

### 3/28:
* I continued going through [W3schools](https://www.w3schools.com/css/css3_animations.asp)
  * I made this code:
```CSS
@keyframes example {
  0% {rotate:72deg; background-color: red;}
  25% {rotate:144deg; background-color: yellow;}
  50% {rotate:216deg; background-color: blue;}
  75% {rotate:288deg; background-color: green;}
  100% {rotate:360deg; background-color:pink;}
}
div {
  width: 100px;
  height: 100px;
  background-color: red;
  animation-name: example;
  animation-duration: 0.5s;
  animation-iteration-count:infinite;
}
```
* I learned how to use opacity, left, and width to make animations like moving text, and text that fades in.
  * My tinkering for a div that comes into the center of the screen slowly as the word is coated with the color red
```CSS
    @keyframes example {
  0% {opacity:0%; left:0%;width:0px;}
  25% {opacity:10%; left:10%; width:100px;}
  50% {opacity:20%;left:20%; width:200px;}
  75% {opacity:30%; left:30%; width:300px;}
  100% {opacity:100%; left:45%; width:500px;}
}
div {
  font-size:100px;
  text-align:center;
  width: 100px;
  height: 100px;
  background-color: red;
  position:absolute;
  animation-name: example;
  animation-duration:1s;
  animation-fill-mode:both;
}
```
* I had a lot more time to tinker and create some fun test examples this week because of the extra days we had in class to work
* I still have some questions like how I can make my text fade in and fade out at certain points.
* I can now use opacity for my animations to slowly make an element visible or invisible
* I can keep certain properties of my animations like the beginning or the end using `animation-fill-mode`
* I have not yet figured out shortcuts to make CSS faster to use, for example if I wanted to use `opacity` to make something appear as slowly as possible, id have to make 100 different percentages from 0-100, that would take a lot of work.
* Next week I will look more for shortcuts on CSS rather than new codes to learn, I think overloading my brain with codes is not as effective as mastering the use of easier codes which I already have in my brain.
