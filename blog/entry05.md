# Entry 5
##### 4/11/25

## What I learned
* During the time since my last entry, I learned a lot more about CSS Animations. First I went through  [Animate.css](https://animate.style/) to check out some animations and pick ones that I would like. My favorite one was this:
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
I really liked it but it seemed like a lot of work to do it the way they did, so I tried to make one on my own using simpler and smaller code like this:
```CSS
@keyframes test {
  0% {
    transform: scale(0.1);
    opacity: 0;
    color:red;
  }
  60% {
    transform: scale(2);
    opacity: 1;
    color:blue;
  }
  100% {
    transform: scale(0.6);
    color:green;
  }
  }
  .bye {
    text-align:center;
    text-transform:uppercase;
    width:100%;
    height: 50px;
    font-size:50px;
    background-color: #FFE5B4;
    animation-name: test;
    animation-duration:10s;
    animation-iteration-count:infinite;
    position:fixed;
    top:70%;
  }
  ```
* I learned how to use CSS Animations on my own by watching certain videos like [this video]((https://www.youtube.com/watch?v=SgmNxE9lWcY) and [this one](https://www.youtube.com/watch?v=z2LQYsZhsFw). After watching these videos, I would try to replicate the results that they got with my knowledge of the code like I did in the example above, this helped me put my knowledge to use and also gave me opportunities to learn about new code if I could not figure out how to create what the example did.
* I changed up some of the codes from examples I studied to see what part would change and to improve my understanding of the element, for example when I used `left` `right` `top` `bottom`, they had percentages on them and I kept changing it to see the effects, at first I thought it was how far it moves towards the direction it corresponds with. I then learned that it is actually how far away it pushes from said direction. `left:50%:` would move the element 50% away from the left side of the screen.
* During this week we had a lot of free time to learn our tool
## Skills
*

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
