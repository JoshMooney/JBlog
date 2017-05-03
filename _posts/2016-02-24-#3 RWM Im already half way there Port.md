---
layout: post
title: #3 RWM "I'm Already Half Way There" Port
color: light-blue
tags: WordpressPort #3
categories: Dev
date: 24-02-2016
---

Two weeks in and the Real World Modeling is going well we gained a new team member this time around as another team needed to be broken up, we scored Tienan a excellent programmer whom I'm delighted to work with. I know I may have mentioned it before in my most recent blog post, allow me to reiterate. This RWM project is based on the four aspects of the course, combining the subjects of the course into one super project. The subjects which have continuous assessment grading integrated with RWM are AI, Games Engineering and Online Gaming Technologies. This joint project is called Argo after each of the subjects involved. Regular classes are put on hold and we are expected to be in every day from 9 a.m. til 5 p.m. working on this project. IT Carlow is fortunate enough to have a sister college in Wicklow which whom we collaborate with there visual design students. This collaboration with these "Art" students involves explain our designs, game settings and they will come back to us with some concept designs; we then build on these designs until both sides are happy with the final product.

The requirements for each of the subjects and the CA percentages associated with them:
<h3>Game Engineering</h3>
<h4>Mandatory:</h4>
<ul>
	* Command Pattern
	* Bridge or Game Update Loop<
	* Observer Pattern
	* Appropriate Factory Pattern
</ul>
<h4>Pick Two:</h4>
<ul>
	* Flyweight Pattern
	* Momento
	* Custom Script Interpreter
	* Service Locator
	* Optimization Techniques(Must be agreed with lecture)
</ul>
<h3>Real World Modeling</h3>
<ul>
* Select and use appropriate techniques to produce finely tuned gameplay, and fluid physical interaction, that feels natural and has pleasing aesthetic (e.g. sync physics with the animation)
* Note: You can choose whether to use Box2D or to build the physics from scratch.  Carefully consider the tradeoff in terms of the result you can get and the time investment.
* Each LO has a ‘size’. The cumulative size of your LOs for RWM must exceed 50
* Also, note that the sizes can be negotiated with lecturers, depending on the complexity of your proposed feature.
</ul>
<h3>Online Gaming Technologies</h3>
<ul>
	* Add a networked multiplayer mode (select appropriate techniques)
</ul>
<h3>Artificial Intelligence</h3>
<ul>
	* Design and implement an automated test bot for a game.
	* Choose an appropriate AI algorithm for a game
	* Design, test and debug an AI algorithm (efficiency, documentation and customisation)
	* Demonstrate the influence of AI on playability/quality of a Game
</ul>
The Brief for the project can be found here[Hyper link here]. I'm aware these links may go dead over time or permissions may change. I will have local copies in the event of such a thing which will can be made available as soon as someone lets me know its no longer working.
<h3>Week 1</h3>
The week began quiet rough with the lectures sending us a list of instructions that where out dated and had missing even in some cases wrong information. It wasn't any easier when each group is assigned a lecture to "mentor" them but each lecture had a different understanding of the requirements and you can never catch more than one of them in the lab at a time. Our scrum master approached our mentor about these issues and from that moment on we agreed to follow the draft guidelines as best we could always keeping our mentor happy with updates and progress reports.

I managed to get all my tasks done this sprint which included setting up the github and base project, write the factory class for generating Entities which satisfy the ECM model. By the end of the first week we had the bones of the ECM implemented and the whole team began to wrap their heads around that and how to correctly implement it. On the visual side we had little to show but a few squares move around the screen and as a team we decided it would be good habit of using doxygen due to its nice layout and easy visual output.
<h3>Week 2</h3>
{% include player-youtube.html w=500 h=315 ylink="Szo6vuzmxfY" %}

This week started off good with a good chunk of the first day going into our scrum meeting. We found it easy to grasp what was needed to be done this sprint but found it a little more difficult to gauge the amount of time each task would take, AND! in steps planning poker. It is a form or brainstorming and talking out ideas using cards with values for difficultly. I found it a really interesting concept and was eager to try it, I found it did aid the development process greatly and made sure not only do everyone know what there doing they know what everyone else is doing and who they might need to consult with when approaching there task. We got a chance to meet with the Art students who took a bus from Wicklow to the IT just to discuss the assignment and we negotiated possible titles and themes for the project. We all seemed to like the Nordic/Viking meets Game of Thrones feel.

This sprint I was tasked with implementing the path with a component and creating a system to manage this. I also got the opportunity to work on the movement system to add functionality for the movement of the box2d bodies. Our sprint 2 ended with all of our tasks getting complete and having a demo branch with everything implemented and working together nicely below you can seen a short snibbit of the game I captured to show off to you guys.

For further interest please refer to the following documentation:
<ul>
  [Joint Project Brief](https://docs.google.com/document/d/1lqRmIL6bp91AtFxsfwRqVjBnoCCEoEWbQ93dcJvSZug/edit)
  [Games Engineering Rubic](https://onedrive.live.com/view.aspx?resid=5E66DFE2F20FD7ED!211291&ithint=file%2cdocx&app=Word&authkey=!AA1M-45IgvYPzqw)
  [RWM Guide](https://docs.google.com/document/d/1GeLqzSDPes32euJjTozxEG7Esz5nWrAs6JCw_HZRAec/edit#heading=h.7d01gdyqa7c6)
</ul>