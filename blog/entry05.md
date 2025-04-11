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
## Skills
*

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
