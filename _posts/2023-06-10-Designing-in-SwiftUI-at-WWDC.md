---
title: 'Designing in SwiftUI at WWDC'
date: 2023-06-10 00:00:00
layout: post
---

WWDC is one of my favourite times of the year, and this year I'm enjoying the SwiftUI related sessions. 

I've previously linked to [Philip Davis](https://philipcdavis.com/writing/designing-in-swiftui?ref=heydesigner), and his excellent resources for [designing in SwiftUI](https://swiftui.design/guide), so I was excited to see that at this year's WWDC he has a session with [Will Danner](https://www.linkedin.com/in/willdanner/) on '[Design with SwiftUI](https://developer.apple.com/wwdc23/10115)'. 

I'll come back to this video in the future, so I thought I'd document some of favourite slides here. 

![](/images/posts/IMG_3507.jpeg)
<figcaption align = "center"><b>Designing in code helps you surface hidden states that are easy to miss in static design tools.</b></figcaption>

![](/images/posts/IMG_3508.jpeg)
<figcaption align = "center"><b>By designing in code you can test your app in the context where it will be used. The Maps team were able to test their app in the app's main context of walking and cycling. </b></figcaption>

![](/images/posts/IMG_3509.jpeg)
<figcaption align = "center"><b>The Maps team were able to dynamically test multiple variants of the Walking Radius feature in Maps for watchOS 10 by using a mini design tool which they created to visualise a different states the app can find itself in.</b></figcaption>

![](/images/posts/IMG_3510.jpeg)
<figcaption align = "center"><b>The Maps team follow a demo culture, where they shows interactive prototypes, rather than presentations.</b></figcaption>

![](/images/posts/IMG_3511.jpeg)
<figcaption align = "center"><b> In summary SwiftUI allows you to Quickly surface design decisions, Design how things feel, Test in realistic scenarios and Demo on device.</b></figcaption>


The design process that the Maps team follow today feels similar to the process which the original "Purple" team used to delivered the first iPhone. This is detailed in [Creative Selection](https://books.apple.com/ie/book/creative-selection/id1403408298) by [Ken Kocienda](https://www.linkedin.com/in/kenkocienda/).

Here are some quotes from the book which feel relevant to me:

> “He (Steve Jobs) used these **demo reviews** as his chief means of deciding how Apple software should look and feel and function.” ― Ken Kocienda, Creative Selection, p. 9
> 

> “**Software demos need to be convincing enough to explore an idea**, to communicate a step toward making a product, even though the demo is not the product itself.” ― Ken Kocienda, Creative Selection, p. 35
> 

> “I want my demo audience to think they’re looking at something real, even though they aren’t. I know the demo isn’t an actual product, and my audience knows it too, but **creating the illusion of an actual product is essential during the development process to maintain the vision of what we’re actually trying to achieve**, and so my colleagues can begin responding and giving feedback as if the demo was the product.” ― Ken Kocienda, Creative Selection, p. 36
> 

> “**Demos made us react**, and the reactions were essential.” ― Ken Kocienda, Creative Selection, p. 84
> 

> “Concrete and specific **demos were the handholds and footholds that helped boost us up from the bottom of the conceptual valley so we could scale the heights of worthwhile work.** Making a succession of demos was the core of the process of taking an idea from the intangible to the tangible.” ― Ken Kocienda, Creative Selection, p. 84
>  

> “Literally, **we had to demonstrate our idea. We couldn’t get away with telling.** We were required to show. We combined some inspiration, craft, taste, and decisiveness, and we shared our results. We had to work like this, because the team didn’t accept anything unless it was concrete and specific, a demo showing what we meant. Then we tried out each other’s demos, said what we liked and what we didn’t, and offered suggestions for improvements, which led to more demos and more feedback.” ― Ken Kocienda, Creative Selection, p. 134
> 

> "**Demo -> feedback -> next demo**: creative selection.“ ― Ken Kocienda, Creative Selection
> 

> “We listened to guidance from smart colleagues. We blended in variations. We honed our vision. We followed the initial demo with another and then another. **We improved our demos in incremental steps.** We evolved our work by slowly converging on better versions of the vision. Round after round of creative selection moved us step by step from the spark of an idea to a finished product.”― Ken Kocienda, Creative Selection, p. 186
> 

> “We created new demos that were concretely and specifically **targeted to be better than the previous one.**” ― Ken Kocienda, Creative Selection, p. 117
>  

The theme is that designing in code, with tools like SwiftUI, facilitates the creation of successful products. The improvements in Maps for watchOS 10 looks like a by-product of this process, and I'm looking forward to experiencing these changes later this year.  
