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
* During this week we had a lot of free time to learn our tool so I decided that I want to find an animation that is more flashy. I looked through a lot of examples and I tinkered with some to make this code:
```CSS
#container {
  color:#999;
  text-transform: uppercase;
  font-size:36px;
  font-weight:bold;
  padding-top:200px;  
  position:fixed;
  width:100%;
  bottom:45%;
  display:block;
}

#flip {
  height:50px;
  overflow:hidden;
}

#flip > div > div {
  color:#fff;
  padding:4px 12px;
  height:45px;
  margin-bottom:45px;
  display:inline-block;
}

#flip div:first-child {
  animation: show 5s linear infinite;
}

#flip div div {
  background:#42c58a;
}
#flip div:first-child div {
  background:#4ec7f3;
}
#flip div:last-child div {
  background:#DC143C;
}

@keyframes show {
  0% {margin-top:-270px;}
  5% {margin-top:-180px;}
  33% {margin-top:-180px;}
  38% {margin-top:-90px;}
  66% {margin-top:-90px;}
  71% {margin-top:0px;}
  99.99% {margin-top:0px;}
  100% {margin-top:-270px;}
}
```
* This code would make one block of text in between two others rotate between 3 different words. For example if I wanted it to say "Are you feeling `happy` `sad` `mad` today?" It would keep the "Are you feeling" and "today?" parts while rotating the middle text between `happy` `sad` and `mad`. I found this code incredibly interesting so I continued to tinker with it and change some properties. Overall these codes and processes I showed and explained are the ways that ive learned my tool and how ive learned my tool.
## Skills
*Some skills I improved on or learned in this entry are **collaboration**,**a growth mindset**, and **planning**. Although I was mainly working alone on learning CSS Animate and tinkering, sometimes it would be confusing and I would ask those around me for help, for example, even though my friend Ramses is working on a different tool, he is very smart and reliable so I was able to ask him for his opinion on some of my tinkerings, he would point on things that I had done wrong or could improve on which really helped me out. In return I would check out his A-frame code and try to give him advice even if I did not know much about A-frame. Throughout the time of me learning my tool, instead of only using what I already knew, I made up my mind to be immersed in the videos I watched and try to learn some new things  

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
