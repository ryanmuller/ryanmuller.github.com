---
layout: project
title: Learnstream
---

Learnstream is a series of several projects exploring learing on the web
with video, problem solving, and spaced repetition. 

## Rudinium

[Rudinium](http://rudinium.herokuapp.com) is intended as a "video dictionary" for the material we filmed for Harvey Mudd's Real Analysis course. Users can search for a definition or theorem in the course and then see
a description and video clip.

<img src="/assets/images/lsr2.png" class="project-inline">

Of course, we didn't stop there. We created quizzes for many of the items so
that they could all be studied on a spaced repetition schedule. (Check out the
extracted [Spaceable gem](https://github.com/cicatriz/spaceable) to
use spaced repetition on any Rails model.)

<img src="/assets/images/lsr3.png" class="project-inline">

We also supplied full video lectures with synchronized notes.

## Atomic

[Learnstream Atomic](http://learnstream.heroku.com) was created in the summer of 2011 for Harvey Mudd
College by four students. Our target audience was students entering Harvey Mudd that wanted to brush up on physics and calculus.

<img src="/assets/images/lsa4.png" class="project-inline">

Atomic again used the concept of spaced repetition, but we had a more
sophisticated user model that allowed solving a single problem to count as a
review for several knowledge components (called "concepts" in the interface).
We represented knowledge components as questions, which were answered in our
concept dictionary. Users can scrutinize the system's evaluation of their
strength for each component.

<img src="/assets/images/lsa3.png" class="project-inline">
<img src="/assets/images/lsa5.png" class="project-inline">

The material for physics was presented as lessons using video from [MIT OpenCourseWare](http://ocw.mit.edu) and [Khan Academy](http://khanacademy.org). The video lessons included
embedded questions. After viewing a lesson, relevant concepts were unlocked so
that they could be practiced and reviewed with the study interface.

<img src="/assets/images/lsa2.png" class="project-inline">
