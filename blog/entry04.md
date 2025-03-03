# Entry 4
##### 3/2/25

## My tool
During the time between the last entry and this one, I was given many different coding tools to use. I originally chose Aframe because it seemed really cool to have 3d shapes that I could control to make models. After tinkering with that for a while I decided that it was too difficult for me so I chose my backup, Animate CSS. I tinkered with this tool on [W3Schools](https://www.w3schools.com/css/css3_animations.asp). At first I just read through the articles and clicked "try it yourself", this gave me an idea of how to use the tool. I then changed the code myself and created this little box that changes between colors as the animation begins and ends.
```HTML
<style> 
div {
  width: 100px;
  height: 100px;
  background-color: red;
  animation-name: example;
  animation-duration: 2s;
}

@keyframes example {
  0% {background-color: red;}
  25% {background-color: purple;}
  50% {background-color: yellow;}
  75% {background-color: blue;}
  100% {background-color: green;}
}
</style>
```
This was just the start of CSS animation though, I continued to look through the lessons and tried to do something with each of the new elements that were shown to me. One of my favorite elements were these ones:
```HTML
<style> 
div {
  width: 100px;
  height: 50px;
  background-color: red;
  font-weight: bold;
  position: relative;
  animation: mymove 5s;
  animation-fill-mode: forwards;
}

#div1 {animation-timing-function: linear;}
#div2 {animation-timing-function: ease;}
#div3 {animation-timing-function: ease-in;}
#div4 {animation-timing-function: ease-out;}
#div5 {animation-timing-function: ease-in-out;}

@keyframes mymove {
  from {left: 0px;}
  to {left: 300px;}
}
</style>
```
When I saw what the `animation-timing`function` elements could do, it gave me so many ideas on how I could use them, I really like how they move at different speeds, and you can even control the speed by using the `cubic-bezier(n,n,n,n)` element where you set 4 different movement speeds from the start to the end of the animation.
[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
