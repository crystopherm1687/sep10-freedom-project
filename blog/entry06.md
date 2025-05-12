# Entry 6
##### 5/11/25

## Content
During this period of creating my website I encountered many challenges and breakthroughs in my code. Although i figured out most of my errors the few mistakes that bug me sometimes need help from the Internet or a question to a friend which can useful in some ways. By using bootstrap as my go to code I was able to make an accordion, and Nav bar in their respective positions. In this way i could use a good layout and have good steps for inputting text and images with the proper margins, padding and colors. Also the use of fonts helped guide me through a rough proccess. To make sure my site works well on all devices, I used media queries to adjust layouts and styles based on screen size. This ensures everything looks great, whether it’s on a phone, tablet, or desktop. When I want to take the experience further, I use A-Frame to add interactive 3D or VR elements right in the browser. Although my first big website may not look great it is a good learning experience for being innovative and doing new things. 

Even as I look back from previous challenges I don’t have to start from scratch every time as I can use pre-designed components like buttons, navbars, and modals, which are already optimized for responsiveness. Here this is a carousel from my website as I was trying to fix it's position. 
```
<div id="carouselExampleInterval" class="carousel slide imgcaro" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active" data-bs-interval="10000">
      <img src="prep/playing3.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item" data-bs-interval="2000">
      <img src="prep/playing5.jpg"class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="prep/playing6.jpg"class="d-block w-100" alt="...">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleInterval" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleInterval" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
```
While i did use other components they were easy fixes and my website is doing it's best to show information without troubling itself.
The accordion for my information was very useful in putting together lots of things i said about my topic so that i would not have to make space that i need. Considering all things aside this specific element allowed me to get a good Nav that shows you information without error.
```
 <nav>
  <div class="nav nav-tabs" id="nav-tab" role="tablist">
    <button class="nav-link active" id="nav-home-tab" data-bs-toggle="tab" data-bs-target="#nav-home" type="button" role="tab" aria-controls="nav-home" aria-selected="true" id="#intro"> Intro</button>
    <button class="nav-link" id="nav-profile-tab" data-bs-toggle="tab" data-bs-target="#nav-profile" type="button" role="tab" aria-controls="nav-profile" aria-selected="false" >Context</button>
   <button class="nav-link" id="nav-contact-tab" data-bs-toggle="tab" data-bs-target="#nav-contact" type="button" role="tab" aria-controls="nav-contact" aria-selected="false" >Overview</button>
  </div>
</nav>
<div class="tab-content" id="nav-tabContent">
  <div class="tab-pane fade show active" id="nav-home" role="tabpanel" aria-labelledby="nav-home-tab" tabindex="0"><p class="font">Volleyball is an exciting team sport where players use skill, strategy, and teamwork to score points by sending a ball over a net, and with the integration of technology, teams can now enhance performance, analyze gameplay, and engage fans in new, interactive ways.</p> </div>
  <div class="tab-pane fade" id="nav-profile" role="tabpanel" aria-labelledby="nav-profile-tab" tabindex="0"><p class="font">In the context of volleyball, technology has become a game-changer, providing advanced tools for player performance tracking, tactical analysis, and fan engagement, ultimately transforming how the sport is played, coached, and experienced.</p></div>
  <div class="tab-pane fade" id="nav-contact" role="tabpanel" aria-labelledby="nav-contact-tab" tabindex="0"> <p class="font">An overview of volleyball technology reveals how innovations like wearable devices, video analysis software, and real-time stats are revolutionizing training, strategy, and fan interactions, making the sport more data-driven and interactive than ever before.</p></div>
  <div class="tab-pane fade" id="nav-disabled" role="tabpanel" aria-labelledby="nav-disabled-tab" tabindex="0">...</div>
</div>
```

## EDP
Going through all the steps of the engineering design process has been hard even as I'm finishing up the website because thinking and revising my work has taken longer than expected to complete because of all the things i have to do for other classes and daily life. Aside from that aspect the end starts with identifying the problem or goal, what the website needs to do and who it's for. From there, I brainstorm and plan features, layouts, and functionality, often sketching wireframes or writing a basic outline. During development, I build a prototype by coding the initial version, testing it as I go, and refining each part based on how well it meets the original goals. Once i feel ready i'm pushing everything and looking for errors that i missed and now I have a mvp that can address my topic without problem.
## Sources
* <a href="https://glitch.com/~aframe">Glitch</a>
* <a href="https://getbootstrap.com/">Bootstrap website</a>
* <a href="https://aframe.io/">Aframe website</a>
<!--section-->
## Skills

### Time management
When I'm coding, time management is crucial to staying productive and avoiding burnout. I start by breaking down the project into smaller tasks and setting realistic deadlines for each one. I use a timer to focus during work sessions and take short breaks in between to stay sharp. Prioritizing bugs or features that need immediate attention helps me stay on track, and I make sure to review my progress at the end of each day to adjust my plan if needed. This routine keeps me organized and helps me write cleaner, more efficient code.

### patience 
As I code the website, patience is one of the most important skills I rely on. Sometimes things don’t work the way I expect, and it’s easy to get frustrated when a bug takes hours to fix. Instead of rushing, I remind myself to slow down, read error messages carefully, and try different solutions methodically. I’ve learned that taking a short break can help clear my mind and give me a fresh perspective. Staying patient not only helps me solve problems more effectively but also makes the whole coding process more enjoyable.
[Previous](entry05.md) | [Next](entry07.md)

[Home](../README.md)
