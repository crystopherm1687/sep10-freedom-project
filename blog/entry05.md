# Entry 5
##### 4/11/2025

## Content

During my time of experiencing Aframe and learning some code I found that you can make many things within the software, whether it is a place or an object, anything and you can get creative with it. During a few weeks of tinkering I discovered all sorts of effects and designs that could be implemented onto your projects but there are other multiple forms of code that are available for everyone as long you watch a video online or search up content on the website. As I was using Aframe my topic of volleyball i knew wouldn't be easy to replicate because you need nets, balls, a court and background. While starting out the scene I was able to make a net and plan some spheres onto the scene.

<img src="../tool/volleyball.png">

Not only that but I found out that you could actually get color and images onto these which got me tinkering a bit more and adding animation was what I imagined for the balls to make it appear more of a realistic scene that would actually give off professional intent to promote something. There were other things I wanted to try but sometimes they needed work and it took much more time to figure them out so I only added required coding tips.

<img src="../tool/balls.jpg">

Some of my ideas that can be added were interesting which involved lighting effects and moveable objects by clicking the object then viewing a reaction. An example would be like this code. This type of code can used to move objects in the scene so now there are more chances that the balls can move using raycasting.
```
<a-entity camera raycaster="objects: .clickable" cursor="fuse: true; maxDistance: 20; fuseTimeout: 1500"> </a-entity>
  <a-light type="ambient" intensity="0.5"></a-light>
<a-light type="directional" intensity="0.8" position="1 3 1"></a-light>
```
Another idea that popped my interest were the color changing objects I mentioned earlier with this being an example of code being affected by the code.
```
<a-scene>
      <a-box position="0 1 -3" color="#4CC3D9"
             event-set__click="_event: click; color: #EF2D56">
      </a-box>
      <a-camera></a-camera>
    </a-scene>
```
As people start to be aware of topics that might seem worth their value they would want to see these ideas in action or prview which is where multiple screens sizes would come in and allow for people to see my invention clearly on their device.
```
<a-entity
geometry="primitive: box; width: 3; height: 3; depth: 3"
position="0 2 -5"
scale="1 1 1"
mobile-scale="1.5 1.5 1.5"
desktop-scale="1 1 1"
></a-entity>
```

## Sources

Some of the sources that I used for reference were these sites 
* <a href="https://www.youtube.com/@uwrealitylab">youtube channel</a>
* <a href="https://aframe.io/">Aframe website</a>
* <a href="https://glitch.com/">Glitch website</a>
## Skills
Some skills that I focused on during my Aframe learning was time management and planning my ideas into my topic so that i feel successful and present a life-changing product.

### Time management
I found myself on this skill a lot because i had many things to do before and after school which gives me less time to actually come up with better ideas than i already have since switching between an athlete and student can be difficult with a ton of homework so now instead of cramming everything last minute i plan to do things right after they were assigned meaning cutting back game time until i finished everything and sleeping early to help me the next day. 
### Planning
While working on this skill I found it useful to write down things that would work on developing my topic further because creativity can go a long way and saving those ideas can be important for when you want to actually do something that requires thinking or doing work. By inputting things into my notes it helps me remember these awesome ideas i had and are ready to test out for when i feel good. Also it saved me a lot of time on doing work and being able to play my games during my freetime as homework is already draining my mind and games help me get rid of stress.

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
